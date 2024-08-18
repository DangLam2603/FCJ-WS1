---
title : "Chỉnh sửa Inbound Rule"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 2.4 </b> "
---

## Tổng quan

1. Truy cập vào **AWS Console**, tìm kiếm dịch vụ **EC2** và chọn **Security Group**.
   ![security group](/images/2-prerequisite/2.5-edit-inbound-rule/(1)-security-group.jpg?width=60pc)
2. Chọn và chỉnh sửa **Security Group của bạn**. 
   ![Modify security group](/images/2-prerequisite/2.5-edit-inbound-rule/(2)-crreate-sg.jpg?width=60pc)
3. Chọn **Edit Inbound Rule**
   ![Edit security group](/images/2-prerequisite/2.5-edit-inbound-rule/(3)-edit-sg.jpg?width=60pc)
4. Thêm Rule => Chọn loại **MSSQL** => Lưu Rule
   ![Edit security group](/images/2-prerequisite/2.5-edit-inbound-rule/(5)-add-sg.jpg?width=60pc)
{{% notice info %}}
Trong workshop này, chúng ta sẽ sử dụng MSSQL triển khai lên RDS Database. Bạn có thể chọn loại cơ sở dữ liệu khác bằng cách chỉnh sửa phạm vi cổng để phù hợp với cổng của cơ sở dữ liệu.
{{% /notice %}}
