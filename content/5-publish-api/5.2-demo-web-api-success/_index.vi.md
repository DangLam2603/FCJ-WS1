---
title : "Demo Và Kiểm Tra APIs"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 5.2 </b> "
---

{{% notice info %}}
Để xác thực việc triển khai các API của chúng ta, hãy bắt đầu bằng cách lấy URL liên kết với miền Elastic Beanstalk của chúng ta. API sử dụng Swagger UI cho tài liệu và tương tác với các điểm cuối. Để truy cập danh sách đầy đủ các endpoint có sẵn, hãy thêm ```../swagger/index.html``` vào URL cơ bản của miền.
{{% /notice %}}

1. Sao chép và dán URL miền ```ebs-player-apis-dev.ap-southeast-1.elasticbeanstalk.com/swagger/index.html```
![link](/images/3-deploy-ebs-application/3.9-demo-api/demo%20(1).jpg?width=60pc)
1. Triển khai thành công và kiểm tra các API hoạt động với cơ sở dữ liệu RDS đã được lưu trữ.
![link](/images/3-deploy-ebs-application/3.9-demo-api/demo%20(2).jpg?width=60pc)

> API của bạn hiện đã được lưu trữ trên đám mây AWS sử dụng môi trường Elastic Beanstalk, với cơ sở dữ liệu RDS được tích hợp đầy đủ. Bạn có thể truy cập API và phát triển một ứng dụng web hoàn chỉnh cho backend của bạn, tất cả được triển khai liền mạch trên đám mây AWS với hỗ trợ cơ sở dữ liệu mạnh mẽ từ Amazon RDS.
