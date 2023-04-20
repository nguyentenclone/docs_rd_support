**3. Cài đặt loyalty**

**3.1 Thiết lập**

Thông tin loyalty đã được tạo có thể chỉnh sửa thông tin: 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/06/22/5641549_screenshot-1.png)

Giao diện thay đổi thông tin Loyalty thành công

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l6jpg1676620532.jpg)

**Kết nối với Bot nhà hàng Bizfly để tích điểm khi đặt bàn và order món ăn thành công**

Note:

-   Trong cùng 1 dự án, nhiều nhà hàng có thể kết nối cùng 1 loyalty
    
-   Bên loyalty bật kết nối => lưu thay đổi thành công thì bên nhà hàng mới lưu giao dịch được ở màn giao dịch tích điểm bên loyalty
    
Vd: Bên nhà hàng order món ăn thành công sẽ đổ giao dịch sang bên loyalty

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/25/5609890_screenshot-70.png)

**Kết nối với Bot Bán hàng Bizfly để tích điểm khi đặt hàng và order mua hàng thành công**

Note:

-   Một Bot bán hàng chỉ kết nối với 1 loyalty
    
-   Bên loyalty bật kết nối => lưu thay đổi thành công thì bên bán hàng mới lưu giao dịch được ở màn giao dịch tích điểm bên loyalty
    
Vd: Bên bán hàng order đơn hàng thành công sẽ đổ giao dịch sang bên loyalty

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/06/23/5642540_screenshot-2.png)

**Định danh khách hàng có: số điện thoại (mặc định), số cmnd và email**

Note: Phần định danh có thể bật thêm Số cmnd và emal => Tiêu chí nào bật sẽ bắt buộc phải điền khi thêm mới thành viên

**Cài đặt cảnh báo**

Cảnh báo giao dịch vượt quá n lần/ngày để theo dõi hoạt động của khách hàng trong 1 ngày tại sao lại có nhiều giao dịch có thể bị nhầm hoặc trùng khi có nhân viên đã tích điểm rồi

Vd: lớn hơn n*số ngày lọc mới hiện cảnh báo phần trang chủ

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l7jpg1676620586.jpg)

Cảnh báo số tiền giao dịch vượt quá n vnđ sẽ có thông báo

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/16/5600926_photo-2020-05-16-11-34-40.jpg)

**Cài đặt thông báo**

Chưa kích hoạt dịch vụ Bizfly Mail=>click vào để kích hoạt.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/16/5600951_4.png)

Kích hoạt thành công bật dịch vụ muốn gửi thông báo=>lưu thay đổi

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610655_screenshot-78.png)

Tại đây có thể chỉnh sửa mẫu thông báo:

**Note: Chỉnh sửa nội dung thông báo không cần click 'Lưu thay đổi' nữa **

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/25/5609541_screenshot-56.png)

VD: Chỉnh sửa mẫu chào mừng thành viên mới Sms=> click vào Sms nhập nội dung mới => Click lưu nội dung

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/25/5609605_screenshot-57.png)

Giao diện lưu nội dụng thành công

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l8jpg1676620634.jpg)

**Ẩn loyalty**

Chủ dự án có thể ẩn loyalty, toàn bộ nhân viên trong dự án không xem được loyalty bị ẩn nữa cho đến lúc kích hoạt lại

**Note**: Khi ẩn loyalty có kết nối với Bot nhà hàng đặt bàn và order món ăn thành công sẽ không đổ giao dịch sang bên loyalty nữa

Bước 1: Click ẩn loyalty

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610616_screenshot-71.png)

Bước 2: Thông báo xác nhận ẩn loyalty => Click Ẩn loyalty

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610617_screenshot-72.png)

Giao diện ẩn loaylty thành công

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610626_screenshot-73.png)

Nhân viên truy cập vào loyalty sẽ có thông báo

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610637_screenshot-75.png)

Muốn kích hoạt lại loyalty đã ẩn chủ dự án truy cập lại loyalty => click Kích hoạt lại

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610644_screenshot-76.png)

Kích hoạt thành công giao diện lại mặc định về trang chủ

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/26/5610648_screenshot-77.png)

**3.2 Thông báo**

Thông báo gồm các giao dịch tích điểm đã thành công

Hiện thị màn hình danh sách thông báo là bản to của thông báo nhanh hình chuông

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/16/5600981_7.png)

**3.3 Nhân viên**

Thêm nhân viên và phân quyền sử dụng cho từng nhân viên

Bước 1: Click vào thêm email mới.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/16/5600987_9.png)

Bước 2: Điền thông tin nhân viên=>click Thêm.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/16/5600996_11.png)

Giao diện thêm nhân viên thành công tại đây có thể phân quyền cho nhân viên đó bằng cách click bật các chức năng

![enter image description here](https://static8.muarecdn.com/original/muare/images/2020/05/25/5609642_screenshot-59.png)

**3.4. Tạo bản sao**

Tạo bản sao loyalty sẽ sao chép ra 1 loyalty mới: phân hạng thành viên sẽ giống loyalty vừa sao chép ban đầu

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l5jpg1676620302.jpg)

**3.5. Nền tảng SMS & E-mail**

Cho phép người dùng cấu hình gửi sms từ các nền tảng đã có sản. Để có được thông tin cấu hình người dùng cần đăng ký tài khoản với các bên dịch vụ cung cấp gửi sms trước. Hiện tại hệ thống có thể kết nối được với 2 hệ thống cổng Bipbip của Vccloud và VMG của GAPIT.

Cấu hình Vccloud:

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_loyalty1jpg1676619230.jpg)

Bước 1: Nhập tên cấu hình 

Bước 2: Nhập tên tài khoản được cấp bởi hệ    thống Bipbip 

Bước 3: Nhập mật khẩu được cấp bởi hệ thống Bipbip 

Bước4: Nhập domain đăng ký và ấn enter 

Bước 5: Bấm Lưu lại để hoàn thành thao tác

Cấu hình VMG:

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_loyalty2jpg1676619316.jpg)

Bước 1: Nhập tên cấu hình

Bước 2: Nhập Api key được cấp bởi hệ thống VMG

Bước 3: Nhập Api secrect được cấp bởi hệ thống VMG

Bước 4: Bấm Thêm cấu hình để hoàn thành thao tác

**3.6. Mã QR**

Cho phép người dùng cấu hình mã QR hoặc link để Khách hàng có thể đăng ký thành viên thân thiết, đồng thời nhận được SMS chào mừng (sử dụng dịch vụ gửi sms đã cấu hình ở mục 3.5). 

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l3jpg1676619647.jpg)

Để tạo được QR người dùng thao tác theo các bước sau đây:

Bước 1: Chọn nền tảng gửi sms là Vccloud hoặc VMG 

Bước 2:  Chọn brand name: chính là tên miền đã đăng ký 

Bước 3: Tích ẩn/hiện logo nếu muốn 

QR và link được tạo thành công và hiển thị như sau:

![enter image description here](https://chatbizfly.mediacdn.vn/2023/02/17/chatbot/img_l4jpg1676620235.jpg)


