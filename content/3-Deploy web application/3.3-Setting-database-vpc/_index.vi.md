---
title : "Cấu Hình VPC và Cơ Sở Dữ Liệu"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 3.3 </b> "
---

#### Tổng quan 
Tiếp theo, chúng ta sẽ cấu hình VPC và tạo cơ sở dữ liệu RDS mới để lưu trữ SQL Server trên đám mây.

1. Chọn **Virtual Private Cloud (VPC)** hiện có hoặc Tạo mới. Trong bản demo này, tôi sẽ chọn **default VPC**.
   ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(1)-ebs-vpc.jpg?width=60pc)
2. Chọn **Availability Zone** mà bạn muốn chạy ứng dụng của mình.
    ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(2)-ebs-instance-setting.jpg?width=60pc)
3. Chọn **database subnets** của bạn và ```enable database```
    ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(3)-ebs-database.jpg?width=60pc)
4. Chỉnh sửa các thông số sau:
   - *Engine*: động cơ của cơ sở dữ liệu (trong workshop này, tôi sẽ sử dụng SQL Server)
   - *Engine Version*: phiên bản của cơ sở dữ liệu
   - *Instance class*: loại instance của cơ sở dữ liệu 
   - *Storage*: dung lượng lưu trữ của cơ sở dữ liệu
   - *Username*: tên người dùng của cơ sở dữ liệu (khóa để kết nối đến cơ sở dữ liệu)
   - *Password*: mật khẩu của cơ sở dữ liệu (khóa để kết nối đến cơ sở dữ liệu)
  ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(4)-ebs-database-settings.jpg?width=60pc)

5. Nhấn **Next**
   ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(5)-next.jpg?width=60pc)
