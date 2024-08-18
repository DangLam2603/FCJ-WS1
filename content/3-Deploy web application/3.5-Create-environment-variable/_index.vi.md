---
title : "Thêm Biến Môi Trường"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 3.5 </b> "
---

#### Tổng quan 

Các bước dưới đây cho phép bạn thêm biến môi trường vào Elastic Beanstalk để đảm bảo bảo mật.

1. Kích hoạt CloudWatch Logs cho Elastic Beanstalk là một bước thiết yếu để giám sát và khắc phục sự cố ứng dụng của bạn.
   ![cloudwatch](/images/3-deploy-ebs-application/3.5-create-enviroment-variable/(1)-next.jpg?width=60pc)
2. Đặt các biến môi trường sau để cấu hình hành vi ghi log.
    - ``ASPNETCORE_ENVIRONMENT = Development`` (chỉ định môi trường phát triển trên .NET Core)
    - ``ConnectionString__DefaultConnection = "Your Connection String"`` (thêm kết nối tới cơ sở dữ liệu RDS của bạn)
   ![variable](/images/3-deploy-ebs-application/3.5-create-enviroment-variable/(2)-copy.jpg?width=60pc)
