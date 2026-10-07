# BÁO CÁO KIỂM THỬ API BẰNG POSTMAN
## Thông tin 
Họ và tên: Lữ Trung Anh
MSSV: 23010339


## 1. Giới thiệu

Đây là bài thực hành tìm hiểu và kiểm thử API bằng công cụ Postman.

Mục đích của bài thực hành là làm quen với việc gửi các Request đến API và kiểm tra Response trả về.

## 2. Công cụ sử dụng

- Postman
- GitHub
- JSONPlaceholder API

## 3. Thực hiện kiểm thử API

### 3.1. Kiểm thử GET Users

**Phương thức:** GET

**Endpoint:**

https://jsonplaceholder.typicode.com/users

**Mục đích:** Lấy danh sách người dùng từ API.

**Kết quả:**

API trả về danh sách người dùng dưới dạng JSON.

[GET Result](GET.png)

---

### 3.2. Kiểm thử POST User

**Phương thức:** POST

**Endpoint:**

https://jsonplaceholder.typicode.com/users

**Mục đích:** Tạo một người dùng mới.

**Kết quả:**

Request được gửi thành công và API trả về thông tin người dùng đã gửi.

[POST Result](POST.png)

---

### 3.3. Kiểm thử PUT User

**Phương thức:** PUT

**Endpoint:**

https://jsonplaceholder.typicode.com/users/1

**Mục đích:** Cập nhật thông tin của người dùng có ID là 1.

**Kết quả:**

Request được gửi thành công và API trả về thông tin người dùng sau khi cập nhật.

[PUT Result](PUT.png)

---

### 3.4. Kiểm thử DELETE User

**Phương thức:** DELETE

**Endpoint:**

https://jsonplaceholder.typicode.com/users/1

**Mục đích:** Xóa người dùng có ID là 1.

**Kết quả:**

Request được gửi thành công và API trả về kết quả xử lý.

[DELETE Result](DELETE.png)

---

## 4. Kết quả kiểm thử

Các API đã được kiểm thử bằng công cụ Postman.

Các nội dung kiểm thử bao gồm:

- Kiểm tra mã trạng thái HTTP (Status Code).
- Kiểm tra dữ liệu Response trả về.
- Kiểm tra thông tin người dùng.
- Kiểm tra tên người dùng.
- Kiểm tra email người dùng.

Kết quả kiểm thử cho thấy các Request GET, POST, PUT và DELETE đều được thực hiện thành công.

---

## 5. Kết luận

Thông qua bài thực hành, em đã hiểu được cách sử dụng Postman để gửi Request đến API và kiểm tra Response trả về.

Em đã thực hiện và kiểm thử được các phương thức HTTP cơ bản gồm GET, POST, PUT và DELETE.

Ngoài ra, em cũng hiểu được cách kiểm tra Status Code và dữ liệu trả về từ API.

Qua bài thực hành, em có thêm kiến thức cơ bản về kiểm thử API và cách sử dụng Postman trong quá trình kiểm thử phần mềm.
