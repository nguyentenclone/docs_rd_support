**3. Quy trình triển khai** 

Thứ tự các bước triển khai:  
  
Bước 1: Đăng ký tạo tài khoản quản trị giao dịch với Bizfly Billing

Bước 2: Tiến hành tích hợp theo tài liệu hướng dẫn 

Bizfly Billing hiện hỗ trợ thanh toán qua một số cổng thanh toán: ATM / VISA (WEPAY), MOMO, TRUEMONEY, VNPAY, VIETTELPAY . Chọn và kí kết hợp đồng kinh doanh với các cổng thanh toán đó -> thông báo cho Billing biết các cổng thanh toán đã chọn

Bước 3: Đơn vị tiến hành kiểm thử phần mềm, tham khảo các testcase của Billing cung cấp để kiểm tra các lỗi phổ biến trong quá trình thanh toán.

Bước 4: Sau khi đơn vị kinh doanh hoàn thành tích hợp và kiểm thử, Billing sẽ xác thực dịch vụ của bạn trên môi trường test trước khi lên production

Bước 5: Triển khai dịch vụ thanh toán cho khách hàng.

