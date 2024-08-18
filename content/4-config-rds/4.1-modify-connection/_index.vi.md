---
title : "Sửa Đổi Chuỗi Kết Nối và Inbound Rule"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 4.1 </b> "
---

Để các phiên bản cơ sở dữ liệu của chúng ta hoạt động trong môi trường đám mây AWS, chúng ta cần cập nhật Chuỗi Kết Nối và tạo một inbound rule để kết nối với máy chủ MSSQL cục bộ của chúng ta.

#### Cập Nhật Chuỗi Kết Nối

1. Vào thư mục dự án và tìm tệp `appsetting.json`
   + Trong Chuỗi Kết Nối, tìm **DefaultConnection**
   + Sửa đổi các giá trị **Server, uid, pwd** sao cho phù hợp với cài đặt cơ sở dữ liệu trong Elastic Beanstalk.

   ![cnstr](/images/4-config-rds/(1)-cntr.jpg?width=80pc)

2. Điều hướng đến Cơ sở Dữ Liệu AWS RDS trong Giao Diện AWS Console
   + Chọn cơ sở dữ liệu để sửa đổi
   ![database](/images/4-config-rds/(2)-modify.jpg?width=60pc)
   + Thêm quy tắc inbound sau
   ![inbound](/images/4-config-rds/(3)-inbound-rule.jpg?width=60pc)

Tiếp theo, chúng ta sẽ tiến hành di chuyển và kiểm tra cơ sở dữ liệu của chúng ta đến máy chủ MSSQL cục bộ.
