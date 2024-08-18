---
title : "Tạo Môi Trường Elastic Beanstalk Mới"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 3.1 </b> "
---

#### Tổng quan
Trước khi tiến hành thiết lập **AWS Elastic Beanstalk**, điều quan trọng là phải cấu hình một môi trường mới để đảm bảo quá trình triển khai diễn ra suôn sẻ.

1. Truy cập vào **AWS Console UI** và tìm kiếm **Elastic Beanstalk**
   ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(1)-ebs.jpg?width=60pc)
2. Chọn **New Environment**
    ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(2)-create-new-ebs.jpg?width=60pc)
3. Trong phần **Environment Information**, điền **Environment name** bạn muốn
{{% notice note %}}
Bạn có thể chọn **Domain Name** bạn muốn, tuy nhiên nó là *tùy chọn*. Đảm bảo rằng bạn kiểm tra **tính khả dụng** của tên miền.
{{% /notice %}} 
![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(3)-config-ebs-env-name.jpg?width=60pc)
4. Sau đó, chọn **platform, platform version và branch** bạn muốn triển khai, trong hướng dẫn này sẽ sử dụng **.NET 6 trên Linux**
 ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(4)-ebs-platform.jpg?width=60pc)
5. Trong phần Presets, chọn **High availability**. 
![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(5)-ebs-preset.jpg?width=60pc)

{{% notice info %}}
Bước này cho phép người dùng thiết lập môi trường của họ một cách hiệu quả dựa trên nhu cầu cụ thể, cho dù lựa chọn một cấu hình **đơn giản với một instance duy nhất** (có thể đủ điều kiện cho tầng miễn phí) hay một cấu hình **khả dụng cao** mạnh mẽ hơn. Trong phần **Application Code**, bạn có thể chọn sử dụng **mã mẫu** để triển khai cơ bản hoặc **tải mã của bạn từ S3** Bucket.
{{% /notice %}}
