# Về Bizfly Chat - Booking

Bizfly Chat - Booking là giải pháp đặt phòng cho các đơn vị kinh doanh du lịch, khách sạn như một bước trung gian sử dụng nền tảng Messenger của Facebook để giúp người dùng thao tác thuận tiện, nhanh chóng hơn: Chọn
địa điểm, ngày Checkin, tình trạng phòng,....

Các đối tác đang sử dụng Bizfly Chat - Booking là giải pháp đặt phòng khách sạn: Wow Holiday,...
## Tên miền

| Environment      | Development           | Production   |
|----------------|----------------|---------------|
| My Bizfly      | https://mybizfly.todo.vn   | https://my.bizfly.vn|
| Chat Bizfly     | https://chat.todo.vn   | https://chat.bizfly.vn|

## Quy trình tích hợp
Các bước cơ bản để tích hợp với Bizfly Chat - Booking:

- Đăng ký tạo tài khoản với https://my.bizfly.vn

- Đăng nhập và tạo dự án của bạn

- Thiết lập kịch bản trên https://chat.bizfly.vn

- Tiến hành tích hợp theo [Tài Liệu API Tích Hợp](chat/vi/api-doc.md)

- Đơn vị tiến hành kiểm thử phần mềm, tham khảo các testcase của chúng tôi cung cấp để kiểm tra các lỗi phổ biến trong quá trình đặt phòng.

- Sau khi đơn vị kinh doanh hoàn thành tích hợp và kiểm thử, Bizfly Chat - Booking sẽ xác thực dịch vụ của bạn trên môi trường test trước khi lên production

- Triển khai dịch vụ thanh toán cho khách hàng.
