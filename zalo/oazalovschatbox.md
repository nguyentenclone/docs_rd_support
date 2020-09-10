# Hướng dẫn kết nối Zalo Official Account và webhook Bizfly

**1. Tạo Official Account**

Để thực hiện cấu hình cho OA bạn phải là admin của OA đó. Nếu bạn chưa có OA, bạn cần phải đăng ký tạo OA mới . Lưu ý chọn loại OA cửa hàng để sử dụng cho mục đích bán hàng nhé.

**Bước 1: Click vào Cửa hàng**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496633_1.png)

**Bước 2: Ấn Chọn và tìm loại dịch vụ bạn muốn kinh doanh**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496634_2.png)
Sau đó bấm Tiếp tục
![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496636_3.png)

**Bước 3: Nhập thông tin kênh của bạn và ấn Tiếp tục**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496641_4.png)

**Bước 4: Cập nhật ảnh cho OA của bạn và ấn Tiếp tục**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496656_5.png)

**Bước 5: Cập nhật địa chỉ và hoàn tất quá trình đăng kí**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496657_6.png)

*Chú ý: Sau khi bấm Hoàn tất, OA của bạn sẽ mất 1 khoảng thời gian để được Zalo kích hoạt.*

**2. Tạo một ứng dụng để liên kết với Official Account**

Truy cập vào đường dẫn: [https://developers.zalo.me/](https://developers.zalo.me/) và đăng nhập bằng tài khoản zalo của bạn.

**Bước 1: Truy cập vào tài khoản và thêm ứng dụng**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496664_7.png)

**Bước 2: Nhập tên (ID) ứng dụng của bạn**

Đặt tên cho ứng dụng và click Tạo ID ứng dụng

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496666_8.png)

**Bước 3: Kích hoạt ứng dụng của bạn**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496669_9.png)

**Bước 4: Liên kết tài khoản OA với ứng dụng của bạn để xin cấp quyền**

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496675_10.png)

**Bước 5: Xin quyền sử dụng các dịch vụ cho OA của mình**

Tích vào từng mục và bấm Nộp xét duyệt, quá trình sẽ mất 1 khoảng thời gian để Zalo có thể chấp nhận xét duyệt yêu cầu cho bạn.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496677_11.png)

**Bước 6: Gắn callback URL từ zalobot vào ứng dụng**

Trong phần Cài đặt của zalobot, bạn click Sao chép link để lấy link callback URL

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/09/10/5724620_screenshot-4.jpg)

Sau đó gắn link vào mục Official Account Callback Url và bấm Lưu lại.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496679_13.png)
![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496680_14.png)

**Bước 7: Gắn webhook của chatbot Bizfly để nhận các thay đổi từ OA của zalo như: message từ khách hàng, message từ OA gửi cho khách hàng, tag...**

_Lưu ý: URL webhook sẽ được bộ phận kỹ thuật của zalobot Bizfly cung cấp_

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496682_15.png)
![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496683_16.png)

Bật các sự kiện bạn muốn webhook có thể nghe:

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/03/18/5496685_17.png)

