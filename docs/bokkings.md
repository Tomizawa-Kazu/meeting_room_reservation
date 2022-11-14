## bookings

### カラム情報
| No. | 物理名 | データ型 | Not NULL | デフォルト | Index | 備考 |  
| --- | --- | --- | --- | --- | --- | --- |
| 1 | booking_id | Integer | Yes(PK) | | True | ユニーク
| 2 | user_id | Integer | Yes | | True | ユニーク
| 3 | room_id | Integer | Yes | | True | ユニーク
| 4 | booked_num | Integer | | |  | 
| 5 | start_datetime | Datetime | Yes | |  | 
| 6 | end_datetime | Datetime | Yes | |  | 