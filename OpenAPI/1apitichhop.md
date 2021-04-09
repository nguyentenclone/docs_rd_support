**1. Thông số cấu hình chung**

Khi gọi api để lấy dữ liệu, ngoài các tham số của từng api, cần truyền thêm hai tham số sau:

Trường | Kiểu dữ liệu | Mô tả 
--- | --- | --- 
project_token | String | Project Token của dự án đang muốn truy vấn
access_token | String | Access Token do Chat Bizfly cung cấp
signature | String | Chuỗi chữ ký đảm bảo toàn vẹn dữ liệu

**Quy tắc mã hóa để tạo chữ ký:**

- Đầu vào là gồm mảng các tham số của từng api, project_token và access_token.
- Mảng được sắp xếp theo alphabet của key.
- Mã hóa json_encode với mảng trên để tạo chuỗi.
- Sử dụng hàm mã hóa HMAC-SHA256 (chuỗi, secret_token). Secret Token do Chat Bizfly cung cấp.

