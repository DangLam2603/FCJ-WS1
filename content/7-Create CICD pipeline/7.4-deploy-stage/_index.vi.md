---
title : "Tạo Giai Đoạn Triển Khai"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 7.4 </b> "
---

#### Tổng Quan
Trong giai đoạn triển khai của AWS CodePipeline, bạn thiết lập quy trình để triển khai ứng dụng đã được xây dựng đến môi trường đã chỉ định. Trong workshop này, chúng ta sẽ tích hợp với việc triển khai lên AWS Elastic Beanstalk.

1. Chọn nguồn cho **Nhà Cung Cấp Triển Khai**
   ![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(1).jpg?width=60pc)
2. **Chỉnh sửa** các thông tin sau:
   + *Khu Vực*: khu vực cụ thể của vùng triển khai của bạn
   + Chọn **Tên Ứng Dụng** của Elastic Beanstalk
   + Chọn **Tên Môi Trường** của Elastic Beanstalk
   ![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(2).jpg?width=60pc)
3. **Xem lại** các bước sau và chọn **Tạo Pipeline**
   ![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(3).jpg?width=60pc)
