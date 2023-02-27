**Hướng dẫn sử dụng các form kịch bản của Zalo**

Hiện tại, bot zalo hỗ trợ 6 form tạo kịch bản như hình dưới đây:

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/24/chatbot/img_90jpg1677212944.jpg)

**1. Form text**

Hiển thị đoạn text không quá 640 kí tự, có thể sử dụng emoji trong nội dung kịch bản

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762536_screenshot-20.jpg)

**2. Form ảnh**

Form ảnh hỗ trợ tải lên ảnh hoặc file upload( .doc, .docx, .pdf). Hiện tại zalo chưa hỗ trợ hiển thị kịch bản có chứa video.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762545_screenshot-21.jpg)

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762546_screenshot-22.jpg)

**3. Form card**

Form card của zalo hỗ trợ hiển thị 1 slide hình ảnh và 4 nút kèm ảnh. 

Bước 1. Chọn form Card zalo 

Bước 2. Điền thông tin cho phần slide bao gồm: ảnh, tiêu đề, URL và mô tả

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762563_screenshot-23.jpg)

Bước 3: Thêm nút cho form card, có thể thêm 1 hoặc nhiều nút(tối đa là 4 nút)

Ở phần nút này, bạn có thể thêm ảnh cho nút và chọn hành động gắn vào nút đó

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762575_screenshot-24.jpg)

Giao diện hiển thị trên zalo:

![enter image description here](https://static8.muarecdn.com/zoom,80/360_360/muare/images/2020/10/20/5762593_photo-2020-10-20-15-24-18.jpg)

**4. Form Dynamic**

Bước 1: Trong phần kịch bản => chọn form Dynamic

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/24/chatbot/img_88jpg1677212728.jpg)

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762600_screenshot-26.jpg)

Bước 2: Gắn link API muốn hiển thị thông tin 

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/24/chatbot/img_89jpg1677212870.jpg)

- Chọn kiểu hiển thị: Menu hoặc Gallery

- Nhập vào link API

- Chọn phương thức: GET hoặc POST

- Nhập dữ liệu thêm vào ở đâu, ví dụ: {{dulieu}}

Bước 3: Chọn thông tin hiển thị từ API

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762608_screenshot-28.jpg)

Kết quả hiển thị:

![enter image description here](https://static8.muarecdn.com/zoriginal/muare/images/2020/10/20/5762636_photo-2020-10-20-15-49-53.jpg)

**5. Form hỏi đáp**

Nhập vào câu hỏi và trường tùy chỉnh lưu đáp án của khách hàng.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762695_screenshot-29.jpg)

**6. Form List**

Form cho phép nhập nội dung text kèm theo 5 button 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762704_screenshot-30.jpg)

**7. Form Google Sheet**

Chức năng cho phép người dùng thu thập thông tin có sẵn của khách hàng và hiển thị trên form Google Sheet

**Cách tạo form Google Sheet**

**Bước 1**: Click vào form Google Sheet

**Bước 2**: Thiết lập form Google Sheet theo các thông tin dưới đây:

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/14/chatbot/img_Screenshot4png1665736468.png)

-   Chọn tài khoản google: người dùng mới cần kết nối tài khoản google với form google sheet.
    
-   Chọn Googlesheet: những trường hợp sử dụng lần đầu, chưa có sheet nào được tạo trước đó, nên sẽ không có danh sách google sheet.
    
-   Chọn trường hiển thị: trường hợp chọn sheet có sẵn thì trường hiển thị mặc định là các trường đã có sẵn trong sheet đó.
    
**Bước 3**: Click Lưu và Áp dụng. Sheet đã tạo không được sửa, thêm mới, xoá trường hiển thị.

**Sử dụng form Google Sheet**

Sau khi hoàn thành form Google Sheet, người dùng có thể thông qua form Hỏi đáp, Webform (tuỳ mục đích sử dụng) để thu thập thông tin khách hàng. Khi khách hàng tương tác với những kịch bản có chứa form Google sheet vừa được tạo, các thông tin tương ứng của khách hàng sẽ tự động được fill vào sheet đó.

-   VD sử dụng Google Sheet qua form Hỏi đáp

**Bước 1**: Thiết lập form Hỏi đáp, lưu câu trả lời của khách hàng vào trường tuỳ chỉnh

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/15/chatbot/img_Screenshot16png1665805524.png)

**Bước 2**: Thiết lập form google sheet, các trường hiển thị là trường tuỳ chỉnh đã lưu câu trả lời khách hàng.

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/17/chatbot/img_Screenshot18png1665973263.png)

-   VD sử dụng Google Sheet qua Webform

**Bước 1**: Thiết lập Webform, lưu câu trả lời của khách hàng vào trường tuỳ chỉnh

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/17/chatbot/img_Screenshot19png1665973564.png)

**Bước 2**: Thiết lập form google sheet sao cho form google sheet được gọi sau khi khách hàng đã hoàn thành webform

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/15/chatbot/img_Screenshot14png1665805185.png)

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/15/chatbot/img_Screenshot15png1665805238.png)

-   VD sử dụng Google Sheet để thu thập thông tin có sẵn của khách hàng

**Bước 1**: Người dùng thu thập những thông tin của khách hàng được ghi nhận thông qua livechat như tên khách hàng, sđt, email, ...

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/17/chatbot/img_Screenshot20png1665981240.png)

**Bước 2**: Thiết lập google sheet sao cho khách hàng tương tác với kịch bản có chứa form Google sheet vừa được tạo

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/17/chatbot/img_Screenshot21png1665981366.png)

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/17/chatbot/img_Screenshot22png1665981489.png)

Sau khi khách hàng tương tác những kịch bản có chứa form Google sheet vừa được tạo, các thông tin tương ứng của khách hàng sẽ tự động được fill vào Sheet đó

**Kết quả của thiết lập**

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/15/chatbot/img_Screenshot17png1665805878.png)

**8. Form Action**

**Thêm action vào kịch bản:**

Bước 1: Tạo 1 kịch bản

Bước 2. Chọn  **form Action**  trong phần  **Công cụ tạo kịch bản**

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/13/chatbot/img_77jpg1665651213.jpg)

Bước 3: Chọn hành động muốn gắn vào kịch bản

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/13/chatbot/img_78jpg1665651372.jpg)

Bước 4: Bấm  **Lưu**

Bước 5: Bấm  **Áp dụng**

_Lưu ý: Bỏ nhúng kịch bản chỉ áp dụng đối với những kịch bản có thời gian chờ gửi lớn. Đối với những kịch bản đã nhúng và cài đặt thời gian gửi là Gửi ngay lập tức hoặc gửi sau 1-2p sẽ không bỏ được._

**9. Chèn mã code vào kịch bản**

Bước 1: Tạo kho mã code bằng cách click vào menu Danh sách quà tặng

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762725_screenshot-31.jpg)

Bước 2. Chọn kho code muốn phát và gắn vào kịch bản

Bấm vài icon hình gói quà trong form kịch bản:

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/10/20/5762727_screenshot-32.jpg)















