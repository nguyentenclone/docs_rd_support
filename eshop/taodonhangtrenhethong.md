



**3.1.1	Tạo đơn hàng trên hệ thống bán hàng**

**3.1.1.1 Tạo đơn mới**

**Bước 1**: Đăng nhập vào hệ thống quản lý bán hàng => Chọn menu 'Tạo đơn hàng'

**Bước 2**: Nhập đầy đủ thông tin đơn hàng, bao gồm :

 - Danh sách sản phẩm: Thêm sản phẩm/ Bộ sản phẩm bằng cách tìm kiếm theo text hoặc tìm theo danh sách (chọn theo thương hiệu, danh mục hoặc tags, nhãn)
 
 - Khách hàng: Tìm kiếm hoặc tạo mới khách hàng
 
  - Thông tin thanh toán: Hình thức, trạng thái thanh toán
  

![enter image description here](https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_121png1679992283.png)

 - Người dùng có thể sửa trực tiếp giá sản phẩm trong đơn hàng: 
 Click vào textbox Giá bán và sửa giá sản phẩm -> giao diện hiển thị giá bán sau khi sửa
 
 ![enter image description here](https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_120png1679992638.png)
 
 - Người dùng có thể bổ sung thêm chiết khấu trực tiếp, chọn chương trình khuyến mãi cho đơn hàng, áp dụng mã voucher giảm giá, thêm phí ship và thuế: 
 
- Chiết khấu trực tiếp: giảm theo vnd/% 

![](https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_122png1679992370.png)


- Chương trình khuyến mãi: 

Để hiển thị các chương trình khuyến mãi, người dùng làm theo hướng dẫn sau: [5.1.2 Tạo mới chiến dịch có điều kiện](https://chat.bizfly.vn/guides/#/eshop/taochiendichcodieukien).
Khi mua hàng, đơn hàng đủ điều kiện áp dụng khuyến mại sẽ hiển thị các chương trình trong phần chiết khấu để chọn. Người dùng có thể chọn nhiều chương trình khuyến mãi

![enter image description here](https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_123png1679992466.png)

**Lưu ý:** Sau khi áp dụng chương trình khuyến mãi:
* Giá bán ban đầu sản phẩm bị gạch ngang và hiển thị bên dưới, giá sản phẩm sau khi áp dụng khuyến mãi hiển thị ở trên
* Chương trình giảm giá có điều kiện gồm 3 loại: đồng giá, giảm giá, tặng sản phẩm
	* Khi sử dụng đồng thời nhiều chương trình đồng giá: hệ thống ưu tiên chọn chương trình đồng giá có lợi cho khách hàng nhất
	* Khi sử dụng nhiều chương trình giảm giá: hệ thống tính giá trị giảm của các chương trình theo giá bán ban đầu của sản phẩm 
	*  Khi sử dụng nhiều chương trình tặng sản phẩm: khách hàng được hưởng tất cả số lượng tặng của các chương trình 
	*  Các chương trình khuyến mãi áp dụng được ưu tiên theo thứ tự sau: chương trình đồng giá > chương trình giảm giá

Ví dụ: Đơn hàng  gồm: **Sản phẩm X có giá bán = 250.000 VNĐ**. 
Sản phẩm đủ điều kiện và được  áp dụng các chương trình sau:
1. Đồng giá 200.000 VNĐ
2. Đồng giá 150.000 VNĐ
3. Giảm giá 10%
4. Giảm gái 20.000 VNĐ
5. Tặng 1 sản phẩm Y
6. Tặng 2 sản phẩm Y và 1 sản phẩm Z

Hệ thống sẽ áp dụng khuyến mãi theo rule sau:

- Chương trình đồng giá: Lấy chương trình đồng giá 150.000 VNĐ
- Chương trình giảm giá:
	
	- Giảm 10% = giảm 10% của 250.000 = 25.000 VNĐ
	- Giảm 20.000 VNĐ
	-> Tổng giảm giá = 45.000 VNĐ
	
- Chương trình tặng quà: Tổng số quà tặng của 2 chương trình = 3 sản phẩm Y + 1 sản phẩm Z

=> Sau khi áp dụng 6 chương trình trên:  Sản phẩm X có giá bán = 150.000 - 45.000 = 105.000 VNĐ. Đơn hàng được tặng thêm 3 sản phẩm Y + 1 sản phẩm Z


**Bước 3**: Sau khi chọn chiết khấu và áp dụng các chương trình khuyến mãi. Người dùng click button 'Thêm mới'
 -> Hệ thống thông báo tạo đơn hàng thành công
    
![https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_130png1679994987.png](https://chatbizfly.mediacdn.vn/2023/03/28/phuongmeu/img_130png1679994987.png)

 - Lưu ý: Chỉ chỉnh sửa được thông tin đơn hàng khi đơn ở trạng thái "Đơn mới".
 
**3.1.1.2 Xử lý đơn hàng**

**Bước 1**: Đơn mới tạo thành công sẽ hiển thị màn chi tiết đơn mới để xử lý đơn hàng. Tại màn này có thể chỉnh sửa thông tin đơn hàng và lên lịch xử lý cho đơn hàng: 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5877883_8.png)

- Lên lịch xử lý nhằm mục đích đến thời gian đã lên lịch, mới có thể thao tác xử lý được đơn hàng tiếp. 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5877936_9.png)

Đồng thời ngoài danh sách sẽ đánh dấu đơn đã lên lịch xử lý 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/17/5882887_40.png)

- Đồng thời ngoài danh sách đơn sẽ hiển thị tại mục 'Đơn mới'

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/09/5874590_3.png)

- Sau khi đã xác thực lại đơn hàng với khách qua Số điện thoại, có thể xử lý hàng loạt đơn hàng cùng 1 lúc  hoặc xử lý từng đơn hàng

**- Xử lý từng đơn hàng**

**Bước 2**: Đơn sau khi đã xử lý thành công ở Bước 1 sẽ hiển thị màn chi tiết đơn 'Đang xử lý'. 

Đồng thời ngoài danh sách sẽ hiển thị tại mục 'Đang xử lý'

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/10/5875067_4.png)

**Tại bước này chúng ta có thể xử lý đơn hàng theo 2 cách:**

**Cách 1:** Xử lý đơn không dùng đến kho

Tại danh sách đơn, click vào dấu 3 chấm để chọn trạng thái đơn để xử lý đơn hàng 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5877393_6.png)

Note: Đơn xử lý theo cách này khi chuyển sang trạng thái đơn 'Đang đóng gói' và 'Đang giao hàng' cũng sẽ xử lý bằng cách chuyển trạng thái đơn hàng. Còn đơn trạng thái 'Đơn hoàn thành' và 'Đơn hủy' sẽ không chuyển được trạng thái nữa.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5877399_7.png)

**Cách 2:** Xử lý đơn liên quan đến kho

Sẽ thực hiện yêu cầu xuất kho sản phẩm.

Tại đơn trạng thái 'Đang xử lý'  Click vào button 'Yêu cầu xuất kho' để thực hiện chọn kho xuất cho sản phẩm 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908039_screenshot-64.png)

**Bước 3**: Sau khi click vào button Yêu cầu xuất kho, popup chọn kho hiện lên như ảnh dưới bao gồm các kho kèm với số lượng tồn kho của   sản phẩm. Bạn muốn chọn kho nào để xuất thì tích chọn kho đó.

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/10/5875071_5.png)

Khi đã hoàn thành xong việc chọn kho, bạn click button 'Tạo phiếu xuất' để tiến hành yêu cầu nhân viên kho xuất phiếu cho đơn hàng của bạn

- Có thể click 'Chi tiết đơn hàng' để xem chi tiết đơn hàng, lên lịch xử lý cho đơn hàng (hướng dẫn Bước 1) hoặc Tách đơn


Tách đơn phục vụ cho nhu cầu của khách hàng, hoặc đơn hàng có sản phẩm ở nhiều kho khác nhau, hiện xử lý theo kho là 1 đơn -1 kho

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908107_screenshot-69.png)

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908113_screenshot-70.png)

Tách thành công đơn sẽ hiển thị trong trạng thái 'Đang xử lý'

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908115_screenshot-71.png)


**Note:** Mỗi giá trị trong đơn tách : chiết khấu, phí ship, thuế có thể  chênh lệch n đồng trên mỗi đơn con (n là số đơn con được tách)

**Bước 4**: Tạo phiếu xuất thành công Đơn hàng của bạn sẽ nằm ở tab 'Đang đóng gói'. 

 Click vào 'Xem phiếu xuất' sẽ chuyển sang màn hình phiếu xuất kho để xem phiếu đã  xuất trạng thái 'Phiếu mới'

 ![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5878097_10.png)

**Bước 5**: Tại bước này, nhân viên phụ trách kho sẽ thực hiện xử lý phiếu yêu cầu.

Tiếp nhận phiếu xuất click 'Xuất kho' để gửi yêu cầu xuất kho
xuất kho

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5878099_11.png)




**Bước 6**: Sau khi tiếp nhận xử lý ở Bước 5, phiếu xuất sẽ chuyển sang màn chi tiết phiếu 'Chờ xuất kho'

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5878161_12.png)

Đồng thời ngoài danh sách phiếu xuất, phiếu sẽ nằm ở trạng thái 'Chờ xuất kho' và  số lượng sản phẩm trong kho sẽ bị giảm

Khi hàng đã được xuất ra khỏi kho click 'Đã xuất kho' để hoàn thành phiếu


![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/03/12/5878162_13.png)


**- Xử lý hàng loạt đơn hàng**

**Bước 1:** Tại danh sách đơn hàng, chọn đơn hàng muốn xử lý hàng loạt, click button 'Xử lý hàng loạt'

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908217_screenshot-72.png)

**Bước 2:**  Xử lý đơn thành công sẽ hiện thị màn để chọn kho để xuất hàng loạt click 'Tạo phiếu xuất đơn hàng'


![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908241_screenshot-77.png)


Tạo phiếu xuất thành công, số lượng sản phẩm trong kho đã bị trừ, đồng thời đơn hàng sẽ ở trạng thái 'Đang đóng gói' và phiếu xuất trạng thái 'Chờ xuất kho' 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908242_screenshot-78.png)

**Bước 3:**  Chọn phiếu muốn xử lý để hoàn tất việc xử lý  hoặc hủy hàng loạt
 ![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908243_screenshot-79.png)
 
 + click 'Đánh dấu đã xuất kho hàng loạt' để hoàn tất quá trình xử lý và có thể in đơn hàng loạt 
 
 ![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908245_screenshot-80.png)

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908247_screenshot-81.png) 

**Note:** 

- Đơn đổ về từ website hoặc facebook bên mylan in đơn hàng loạt sẽ có số km và mẫu in sẽ tự setup trong cài đặt sẽ hiển thị

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/09/5909106_screenshot-142.png)

- Chi tiết phiếu xuất xử lý hàng loạt sẽ có thông tin km 

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/09/5909107_screenshot-143.png)

- Đơn xử lý hàng loạt sẽ về trạng thái 'Đang giao hàng'

+ click 'Hủy hàng loạt' để hủy hàng loạt đơn hàng. Hủy hàng loạt về danh sách phiếu trạng thái 'Đã hủy' và số lượng sẽ cộng lại vào kho

![enter image description here](https://static8.muarecdn.com/original/muare/images/2021/04/08/5908248_screenshot-82.png)



















