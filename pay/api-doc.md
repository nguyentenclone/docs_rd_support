## API Danh Sách Phòng


Để có thể thiết lập kịch bản đặt phòng, trước hết bạn phải cung cấp cho chúng tôi link API trả về danh sách phòng theo mẫu sau


```cURL-g
https://you_domain/your_action
```

**METHOD: GET**

| Attribute      | Type           | Description   |
|----------------|----------------|---------------|
| id             | Integer        | Mã địa điểm ( bắt buộc )|
| checkin        | String         | Ngày Checkin ( bắt buộc )|      

!> Hai param ID và checkin là bắt buộc phải chính xác

Ví dụ: 
```cURL-g
https://vinpearl.todo.vn/api/room/list_from_place?id=4&checkin=30/12/2019
```

Dữ liệu trả về là danh sách phòng buộc phải theo cấu trúc sau:

```json
{
  "code": 0,  
  "message": "Success", 
  "data": [
  		{
  		  "id" : 19,
  		  "name": "Phòng Deluxe hướng vườn",
  		  "hotel_desc": "Không gian Á Đông miền nhiệt đới",
  		  "link_popup": "https://vinpearl.todo.vn/popup/payment/info?checkin=30%2F08%2F2019&checkout=01%2F09%2F2019&search_room=1&search_adult=2&search_child=0&combo=146&parent_combo=2&item_id=19",
  		  "img": "https://upload.zamba.vn/thumb_wm/1170/vinpearl/upload/room/phong-deluxe-huong-vuon-1558173428.jpg"
  		},
  		{
  		  "id" : 20,
  		  "name": "Phòng Senior Suite Hướng biển",
  		  "hotel_desc": "KHÔNG GIAN XANH, NGẬP TRÀN SỨC SỐNG",
  		  "link_popup": "https://vinpearl.todo.vn/popup/payment/info?checkin=30%2F08%2F2019&checkout=01%2F09%2F2019&search_room=1&search_adult=2&search_child=0&combo=146&parent_combo=2&item_id=19",
  		  "img": "https://upload.zamba.vn/thumb_wm/1170/vinpearl/upload/room/phong-deluxe-huong-vuon-1558173428.jpg"
  		},
  		{
  		  "id" : 21,
  		  "name": "Phòng Standard",
  		  "hotel_desc": "Đắm mình trong hoàng hôn đảo ngọc",
  		  "link_popup": "https://vinpearl.todo.vn/popup/payment/info?checkin=30%2F08%2F2019&checkout=01%2F09%2F2019&search_room=1&search_adult=2&search_child=0&combo=146&parent_combo=2&item_id=19",
  		  "img": "https://upload.zamba.vn/thumb_wm/1170/vinpearl/upload/room/phong-deluxe-huong-vuon-1558173428.jpg"
  		},
  		
  	]

}
```
