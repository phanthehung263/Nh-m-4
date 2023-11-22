Nhóm 4 Cơ sở dữ liệu:
1. Nội dung: 
-  Blog Review là trang web uy tín chuyên đánh giá, nhận xét sản phẩm tốt, chất lượng cùng giá rẻ nhằm đem đến cho cộng đồng người dùng những thông tin hữu ích. Từ đó họ có thể dễ dàng tìm kiếm được sản phẩm phù hợp với nhu cầu của mình.
2. Ngôn ngữ:
- HTML, CSS, JavaScript
- PHP, SQL.
3. Phân tích thiết kế database

1) Bảng admin

- id: int(100) -> Khóa chính tự tăng

- name: varchar(20)

- password: varchar(50)

2) Bảng user

- id: int(100) -> Khóa chính tự tăng

- name: varchar(20)

- email: varchar(50)

- password: varchar(50)

3) Bảng posts

- id: int(100) -> Khóa chính tự tăng

- admin_id: int(100)

- name: varchar(100)

- title: varchar(100)

- content: varchar(100000)

- cartegory: varchar(50)

- image: varchar(100)

- date: date

- status: varchar(10)

4) Bảng comment

- id: int(100) -> Khóa chính tự tăng

- post_id: int(100)

- admin_id: int(100)

- user_id: int(100)

- user_name: varchar(50)

- comment: varchar(100)

- date: date

5) Bảng like

- id: int(100) -> Khóa chính tự tăng

- admin_id: int(100)

- user_id: int(100)

- post_id: int(100)

- date: date
