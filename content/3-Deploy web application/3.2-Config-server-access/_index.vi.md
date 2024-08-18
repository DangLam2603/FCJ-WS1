---
title : "Cấu Hình Quyền Truy Cập Máy Chủ"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 3.2 </b> "
---

#### Tổng quan 
Trong phần này, chúng ta sẽ sử dụng IAM role đã chỉnh sửa cho EC2 mà chúng ta đã tạo trong phần điều kiện tiên quyết ```ebs-ec2-webtier-role``` để cho phép Elastic Beanstalk truy cập.

1. Chọn Tạo và Sử dụng role dịch vụ
2. Nhập tên role dịch vụ mới
3. Chọn ```ebs-ec2-webtier-role```
   ![service-role](/images/3-deploy-ebs-application/3.2-configure-service-access/(1)-ebs-service-access.jpg?width=60pc)
