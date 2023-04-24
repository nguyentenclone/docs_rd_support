


**3.3 Danh sách đơn hàng**

* Hiển thị đầy đủ đơn hàng đặt từ hệ thống và đơn đổ về từ các nguồn khác nhau: website, facebook,...
    
 *  Danh sách đơn hiển thị đầy đủ các trạng thái của đơn:
    
    -   Đơn mới: Đơn đặt hàng đang chờ xử lý
        
    -   Đang xử lý: Đã tiếp nhận đơn hàng, đang xác nhận đơn
        
    -   Đang đóng gói: Đơn đã xử lý và đang yêu cầu xuất kho
        
    -   Đang giao hàng: Đơn đã xuất kho và hàng đang được giao
        
    -   Đơn hoàn thành: Đơn đã giao hàng thành công
        
    -   Đơn hủy: Đơn đã hủy, hàng sẽ hoàn lại nếu đã được xuất.
    
![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/17/huyenvt/img_1png1660711527.png)

 * Tại danh sách đơn có thể tìm kiếm theo các điều kiện hoặc kết hợp nhiều điều kiện khác nhau (Nhãn, Nguồn đặt, Ngày đặt...). Ví dụ tìm kiếm đơn của các khách hàng tại Hồ Chí MInh
 
  ![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/17/huyenvt/img_12png1660711624.png)

* Người dùng có thể xuất excel danh sách đơn hàng: Chọn checkbox những đơn hàng cần xuất excel hoặc chọn tất cả đơn hàng  và click button Xuất ra file excel.

![enter image description here](https://chatbizfly.mediacdn.vn/2022/08/17/huyenvt/img_2png1660712353.png)

* Có thể thực hiện tiếp nhận hàng loạt, Tạo phiếu xuất hàng loạt, Hủy hàng loạt đơn hàng: 

+) Tiếp nhận hàng loạt:

 Tại màn Đơn mới, chọn những đơn cần xử lý (tối đa 50 đơn) -> Click 'Xử lý đơn hàng loạt' chọn 'Tiếp nhận'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/20/huyenvt/img_tnjpg1653017236.jpg)

Hệ thống hiển thị danh sách các đơn hàng được tiếp nhận gồm 2 trạng thái thành công hoặc thất bại. Nếu tiếp nhận thành công đơn hàng chuyển sang trạng thái 'Đang xử lý', nếu tiếp nhận thất bại đơn hàng vẫn ở trạng thái 'Đơn mới'


![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/20/huyenvt/img_kqjpg1653017650.jpg)
				               

+) Tạo phiếu xuất hàng loạt:

Tại màn Đơn mới hoặc Đang xử lý , chọn những đơn cần xử lý (tối đa 50 đơn) -> Click 'Xử lý đơn hàng loạt' chọn 'Tạo phiếu xuất'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/20/huyenvt/img_1jpg1653040056.jpg)

Người dùng chọn kho xuất -> CLick Tạo phiếu xuất cho n đơn hàng (n là số đơn đã chọn)

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_123jpg1653277441.jpg)

Hệ thống thông báo tạo thành công. Phiếu xuất được tạo ở trạng thái  Phiếu mới

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_1234jpg1653277506.jpg)	

+) Hủy đơn hàng loạt:

Tại màn Đơn mới hoặc Đang xử lý , chọn những đơn cần xử lý (tối đa 50 đơn) -> Click 'Xử lý đơn hàng loạt' chọn 'Hủy đơn'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_12jpg1653277838.jpg)

Chọn lý do -> Click 'Hủy đơn hàng'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_12jpg1653278038.jpg)

 Hệ thống hiển thị danh sách các đơn hàng  bị hủy  gồm 2 trạng thái thành công hoặc thất bại. Nếu hủy thành công đơn hàng chuyển sang trạng thái 'Đơn hủy', nếu thất bại đơn hàng vẫn giữ nguyên trạng thái

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_123jpg1653278060.jpg)

* **Note:**

	* Đơn có thể hủy ở các trạng thái: Đơn mới, Đang xử lý, Đang đóng gói, Đang giao hàng
	*   Lý do hủy đơn có thế cấu hình xem tại  [6.8.3 Lý do hủy hóa đơn](https://chat.bizfly.vn/guides/#/eshop/cauhinhlydohuydon)
	*  Lý do hủy đơn mặc định sẽ có Lý do khác (nếu chưa cấu hình)
	* Khi hủy đơn ở trạng thái 'Đang đóng gói' thì phiếu xuất cũng hủy theo và cộng lại số lượng sản phẩm vào kho
	* Đơn hàng ở trạng thái 'Đang giao hàng' (phiếu xuất cho đơn hàng đã xuất kho) nếu hủy đơn thì phiếu xuất không bị hủy, cần nhập lại kho với phiếu nhập có mục đích nhập '"Nhập từ đơn hủy" -> Số lượng sản phẩm được cộng lại vào kho


* Người dùng có thể lên lịch xử lý với những đơn hàng ở trạng thái 'Đơn mới' hoặc 'Đang xử lý'
	
	Tại tab 'Đơn mới' hoặc 'Đang xử lý' click xem chi tiết 1 đơn hàng
	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_1jpg1658290607.jpg)
			
	 Tại giao diện chi tiết đơn hàng -> Click 'Lên lịch xử lý'
	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_2jpg1658290637.jpg)

    Chọn thời gian và lý do lên lịch -> Click 'lên lịch'
	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_3jpg1658290660.jpg)

	 Thông báo thành công. Tại danh sách đơn hàng hiển thị Đơn đã lên lịch. Người dùng có quyền xử lý đơn hàng  từ ngày đã lên lịch
	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_4jpg1658290698.jpg)

	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_6jpg1658290726.jpg)

	Note: Có thể sửa hoặc xóa lịch xử lý đơn

	![enter image description here](https://chatbizfly.mediacdn.vn/2022/07/20/huyenvt/img_5jpg1658290864.jpg)
	
* Tại tab 'Đơn hủy' có thể tạo lại đơn với đơn hủy bất kì hoặc nhập lại kho với những đơn hủy có phiếu xuất đã xuất kho 

	+) Tạo lại đơn:
	
	Chọn đơn muốn tạo lại -> CLick 'Tạo lại đơn'
	
	![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_1jpg1653292302.jpg)
	
	Hiển thị chi tiết đơn hàng, có thể chỉnh sửa thông tin đơn -> Click 'Thêm mới'
	
	
![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_2jpg1653292330.jpg)

Thông báo thêm mới thành công, hiển thị chi tiết đơn hàng

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_3jpg1653292350.jpg)

+) Nhập lại kho (Điều kiện: đơn hàng có phiếu xuất đã xuất kho):

Người dùng có thể sử dụng bộ lọc Trạng thái hủy để tìm những đơn hàng 'Đã xuất kho'
		 
![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_4jpg1653292380.jpg)

Chọn đơn hàng muốn nhập lại kho -> Click 'Nhập lại kho'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_5jpg1653292409.jpg)

Giao diện chi tiết phiếu nhập hiển thị với mục đích "Nhập từ đơn hủy", phiếu nhập ở trạng thái Phiếu mới. 

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_6jpg1653292432.jpg)

Tại tab danh sách 'Đơn hủy' hiển thị button 'Xem phiếu nhập'. Click 'Xem phiếu nhập' hiển thị chi tiết phiếu.


![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_7jpg1653292464.jpg)

	
Tại chi tiết phiếu nhập, người dùng click 'Nhập kho' phiếu nhập chuyển sang  trạng thái 'Đã nhập kho', số lượng sản phẩm trong kho tăng. Tại tab 'Đơn hủy' hiển thị button 'Đã nhập kho'


![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_8jpg1653292490.jpg)


* In đơn hàng ở các trạng thái: Đang xử lý, Đang đóng gói, Đang giao hàng, Đơn hoàn thành, Đơn hủy 

Có thể cấu chỉnh sửa cấu hình mẫu in tại  [6.3 Cấu hình mẫu in](https://chat.bizfly.vn/guides/#/eshop/cauhinhmauin)

Vào chi tiết đơn hàng=> Click 'In hóa đơn'

	 
![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_9jpg1653292521.jpg)

Chọn khổ in và mẫu in -> Click 'Đồng ý'

![enter image description here](https://chatbizfly.mediacdn.vn/2022/05/23/huyenvt/img_10jpg1653292544.jpg)