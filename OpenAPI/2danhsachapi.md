**2. Danh sách api**

1. Lấy danh sách khách hàng:

Lấy danh sách toàn bộ khách hàng hoặc thông tin một khách hàng

```cURL-g
https://chat.bizfly.vn/api/crm/get-list-customer
```

**METHOD: POST**

| Trường      | Kiểu dữ liệu           | Mô tả   |
|----------------|----------------|---------------|
| table             | String        | table = data_customer |
| limit        | Number         | Số lượng bản ghi cần lấy |      
| skip        | Number         | Skip số lượng bản ghi |      
| query        | Array         | Một mảng, trong đó key "id" là một mảng chứa các giá trị id của bản ghi muốn lấy |      
| select        | Array         | Mảng gồm các trường muốn lấy |      
| output        | String         | Đầu ra của dữ liệu tuỳ theo nhu cầu |      

!> Thông tin chi tiết về các trường dữ liệu có thể xem tại [đây](https://crm.bizfly.vn/apidoc/doc/#api-BaseTable-itemDetail).

_Ví dụ:_ 

Dữ liệu đầu vào sẽ theo cấu trúc sau:
```json
{
    "skip" : 0,
    "select": ["name", "created_at"],
    "table" : "data_customer",
    "limit" : 10,
    "output": "by-key",
    "project_token": "973324a3-fe7e-44f4-bc16-6523961de02e",
    "access_token":"4zQNvesxgezlhmykZJnqDQZybekPOLxo",
    "signature": "0ca6ea6b0846ca9503aff41f7a6430b96bcebde15beab2c07c532127cd4f4378"
}
```

Dữ liệu trả về sẽ theo theo cấu trúc sau:

```json
{
    "status": true,
    "data": [
        {
            "id": "5f7ae1028385bd495663d444",
            "name": {
                "value": "Đỗ Phương"
            },
            "created_at": "2020-10-05T09:01:54.233Z",
            "payload": [
                {
                    "id": "5f7ae1028385bd495663d444",
                    "table": "data_customer",
                    "field": "_id"
                }
            ]
        },
        {
            "id": "5f7ae175399a464999d05d23",
            "name": {
                "value": "Hậu Mít"
            },
            "created_at": "2020-10-05T09:03:49.016Z",
            "payload": [
                {
                    "id": "5f7ae175399a464999d05d23",
                    "table": "data_customer",
                    "field": "_id"
                }
            ]
        }
    ]
}
```

