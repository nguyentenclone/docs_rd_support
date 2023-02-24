# I. Hướng dẫn tạo bot Zalo và kết nối với OA


Bài viết này sẽ hướng dẫn cụ thể từng bước để kết nối 1 OA Zalo với nền tảng zalo bot Bizfly. Sau khi kết nối bạn có thể chăm sóc khách hàng, trả lời tự động theo từ khóa,...như tương tác trên OA.

**1. Tạo bot kiểu Zalo**

Sau khi đã tạo được tài khoản vào dự án từ trang https://my.bizfly.vn hoặc https://chat.bizfly.vn, bạn chọn nền tảng hoạt động của bot là Zalo.

**Bước 1**: Bấm vào bot kiểu Zalo

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/09/5723037_screenshot-1.jpg)

**Bước 2**: Đặt tên cho bot => bấm vào nút Tạo Bot Zalo

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/09/5723038_screenshot-2.jpg)


**2. Kết nối OA Zalo với zalo bot**

**Bước 1**: Lấy ID ứng dụng liên kết với zalo bot

 - Truy cập vào đường dẫn: [https://developers.zalo.me/](https://developers.zalo.me/) và đăng nhập bằng tài khoản zalo của bạn

 - Chọn ứng dụng đã kết nối với OA zalo 
 
 - Lấy ID ứng dụng từ mục Cài đặt

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/09/5723063_screenshot-3.jpg)

**Bước 2**: Nhập ID ứng dụng vào mục Duyệt OA Zalo

- Sau khi tạo bot zalo thành công, màn hình ứng dụng sẽ chuyển sang phần Cài đặt. Tại đây, bạn click sang phần Duyệt OA Zalo

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724620_screenshot-4.jpg)

- Sau đó nhập ID ứng dụng đã lấy được từ bước 1 và bấm Liên kết Zalo

**Bước 3**: Chọn OA để kết nối

 - Sau khi bấm vào Liên kết Zalo, màn hình sẽ chuyển sang trang chọn OA để kết nối
 
![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724625_screenshot-5.jpg)

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724629_screenshot-6.jpg)

*Lưu ý: Trong bước này bạn cần chọn đúng OA đang được kết nối với app ID của zalo developer*

 - Nếu bạn chưa đăng nhập, zalo sẽ yêu cầu bạn đăng nhập để thực hiện kết nối
 - Sau khi cho phép kết nối thành công, màn hình sẽ quay trở lại trang cài đặt của zalo bot

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724630_screenshot-7.jpg)

**Bước 4**: Chỉnh sửa kịch bản và sử dụng bot zalo

- Hiện tại, bot zalo đang có 5 form tạo kịch bản bao gồm: Form Text/menu, form Ảnh, form Card, form Dynamic và form Hỏi đáp

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724731_screenshot-8.jpg)

- Gắn tag, bỏ tag khi khách hàng tương tác với 1 nút trong kịch bản hoặc khi chat vào 1 từ khóa

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724732_screenshot-9.jpg)
- Cách sử dụng các form tương tự các form của FB, tuy nhiên trên giao diện zalo sẽ có 1 số form có hiển thị khác.

**Bước 5**: Kiểm tra tin nhắn đổ về Live chat 

- Khi khách hàng bấm vào Quan tâm tới OA => kịch bản tự động của OA sẽ hiển thị để khách hàng tương tác.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724737_img-3660.jpg)

- Sau khi kết nối thành công, các tin nhắn của khách hàng chat với OA sẽ được đổ về Live chat.

- Tại đây, bạn có thể quản lý tập trung các OA( mỗi OA kết nối với 1 bot) và cả những fanpage FB trong cùng 1 dự án.







