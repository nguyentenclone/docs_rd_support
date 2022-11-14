**2.8.1. Tạo mới phiếu kiểm**

**Bước 1**: Đăng nhập hệ thống quản lý bán hàng => Chọn  'Kiểm kho'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/29/huyenvt/img_1jpg1661757658.jpg)

**Bước 2**: Click button 'Tạo phiếu kiểm'. Nhập thông tin cần thiết:  kho kiểm, sản phẩm, số lượng... và click button 'Lưu lại'
- Kho kiểm: danh sách kho 
- Danh sách sản phẩm: Có thể tìm kiếm theo tên hoặc chọn button 'Danh sách' để tìm kiếm

	- Tồn kho = Chờ xuất + Khả dụng + SL lỗi
	- Hiện có: tổng số sản phẩm có trong kho
	- Lệch : chênh lệch số lượng Hiện có so với Tồn kho hệ thống ghi nhận
		+ Đủ: Hiện có = Tồn kho trên hệ thống
		+ Thừa: Hiện có > Tồn kho trên hệ thống
		+ Thiếu: Hiện có < Tồn kho trên hệ thống
	- Click icon "..." để thêm ghi chú, lý do lệch từng sản phẩm hoặc xóa sản phẩm khỏi danh sách kiểm
- Chi phí: các chi phí phát sinh trong quá trình kiểm kho


![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/29/huyenvt/img_2jpg1661758329.jpg)



**2.8.2. Cân bằng kho**

Sau khi tạo thành công phiếu ở trạng thái Phiếu mới:

**Bước 1:**  Người dùng vào xem chi tiết phiếu


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/06/phuongmeu/img_1ajpg1665043188.jpg)


**Bước 2:** Người dùng có thể Hủy phiếu, Chỉnh sửa, xuất excel danh sách sản phẩm hoặc Cân bằng kho

- Click button Hủy phiếu -> Hiển thị popup chọn lý do hủy. Chọn lý do và click button 'Hủy phiếu'. Phiếu kiểm chuyển trạng thái thành Đã hủy

	Người dùng có thể cấu hình lý do hủy phiếu kiểm tại [6.2. Cấu hình phiếu xuất/nhập. ](https://chat.bizfly.vn/guides/#/eshop/cauhinhxuatnhap)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/09/29/huyenvt/img_1jpg1664436620.jpg)
	
	
	
Người dùng chỉ được phép Hủy phiếu kiểm mới - phiếu chưa tạo phiếu xuất/nhập cân bằng 
- Người dùng chỉnh sửa thông tin phiếu kiểm -> Click button 'Lưu lại' để lưu thông tin phiếu kiểm
- Cân bằng kho phiếu kiểm

	**Trường hợp 1:** Tất cả sản phẩm đủ (lệch = 0)
	- Click button 'Cân bằng kho' -> Hiển thị popup xác nhận kho đã cân bằng, người dùng muốn hoàn thành phiếu kiểm. Người dùng click button 'Xác nhận'. Phiếu kiểm chuyển sang trạng thái Đã cân bằng

	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/29/huyenvt/img_4jpg1661759185.jpg)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/29/huyenvt/img_5jpg1661759258.jpg)


**Trường hợp 2:** Phiếu kiểm có sản phẩm kiểm lệch

 ***Cân bằng thủ công*:** Người dùng tự tạo phiếu xuất/nhập cân bằng với số lượng tùy chỉnh

+)  Lệch = "Thừa": Hiện có nhiều hơn Tồn kho

**Bước 1:** Người dùng click vào checkbox các sản phẩm lệch "Thừa" muốn cân bằng và click button 'Xử lý nhập(n)' (n = số sản phẩm đã chọn)

![enter image description here](https://chatbizfly.mediacdn.vn/2022/09/29/huyenvt/img_2jpg1664436745.jpg)

**Bước 2:** Người dùng chọn/thêm địa chỉ nhập từ, nhập số lượng muốn cân bằng, có thể thêm ghi chú hoặc xóa sản phẩm chưa muốn cân bằng khỏi phiếu -> Click button 'Cân bằng' để tạo phiếu

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k1png1664963377.png)



Phiếu nhập cân bằng kho (thủ công) vừa tạo ở trạng thái "Đã nhập kho"

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k2png1664963416.png)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k3png1664963451.png)

Phiếu kiểm cập nhật lại số lượng Tồn kho, lệch sau khi tạo phiếu nhập cân bằng (thủ công)



![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k4png1664963508.png)

+)  Lệch = "Thiếu": Hiện có ít hơn Tồn kho

**Bước 1:** Người dùng click vào checkbox các sản phẩm lệch "Thiếu" muốn cân bằng và click button 'Xử lý xuất(n)' (n = số sản phẩm đã chọn)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k5png1664963589.png)

**Bước 2:** Người dùng chọn/thêm địa chỉ Xuất đến, nhập số lượng muốn cân bằng, có thể thêm ghi chú hoặc xóa sản phẩm chưa muốn cân bằng khỏi phiếu -> Click button 'Cân bằng' để tạo phiếu


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k6png1664963629.png)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k7png1664963675.png)

Phiếu xuất cân bằng kho (thủ công) vừa tạo ở trạng thái "Đã xuất kho"

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k8png1664963718.png)



![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k9png1664963753.png)

Phiếu kiểm cập nhật lại số lượng Tồn kho, lệch sau khi tạo phiếu xuất cân bằng (thủ công)

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k10png1664963805.png)


**Note:** 
 - Phiếu kiểm ở trạng thái Phiếu mới (mới tạo/đang cân bằng): người dùng được phép chỉnh sửa Mục đích kiểm kho, Nhân viên tham gia, Thêm lý do lệch hoặc Xóa sản phẩm lệch chưa tạo phiếu xuất/nhập cân bằng, Thêm Chi phí, Ghi chú 
-  Người dùng có thể xem danh sách phiếu xuất/nhập cân bằng (thủ công) đã tạo bằng cách: Click button "Cân bằng kho" -> Click vào phiếu xuất nhập muốn xem

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k11png1664963840.png)


 ***Cân bằng tự động*:** Hệ thống tự động tạo phiếu xuất/nhập cân bằng tương ứng với sô lượng lệch 
 
**Bước 1:**  Người dùng vào chi tiết phiếu kiểm ở trạng thái phiếu mới (mới tạo/đang cân bằng) có sản phẩm lệch = "Thừa" hoặc "Thiếu". 
 
![https://prnt.sc/HddVzRWri5lm](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k12png1664964251.png)

**Bước 2:** Click button 'Cân bằng kho', hệ thống hiển thị popup Xác nhận gồm:
Danh sách cân bằng thủ công: Sản phẩm và phiếu xuất/nhập cân bằng (thủ công) tương ứng
Danh sách cân bằng tự động: sản phẩm với số lượng Tồn kho, Hiện có, Lệch

![https://prnt.sc/ShAK7foPnd_Z](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k14png1664964494.png)

**Bước 3:** Người dùng click vào button 'Xác nhận' -> Hệ thống tự động tạo phiếu xuất/nhập cân bằng (tự động) tương ứng với số lượng Lệch. Phiếu xuất/nhập cân bằng kho (tự động) vừa tạo ở trạng thái Đã xuất/nhập kho. Phiếu kiểm chuyển trạng thái từ 'Phiếu mới' sang 'Đã cân bằng'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k15png1664964533.png)


![enter image description here](https://chatbizfly.mediacdn.vn/2022/10/05/huyenvt/img_k16png1664964561.png)

Người dùng có thể in phiếu xuất/nhập cân bằng tự động hoặc link tới phiếu kiểm từ chi tiết phiếu xuất/nhập tự động*

**Note:** Nếu số lượng Hiện có < Khả dụng 

-> Hệ thống cân bằng kho bằng cách trừ lần lượt số lượng Khả dụng, Chờ xuất và SL lỗi