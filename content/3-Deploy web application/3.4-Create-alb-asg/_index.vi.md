---
title : "Tạo Cân Bằng Tải và Nhóm Tự Động Mở Rộng"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 3.4 </b> "
---

#### Tổng quan 

{{% notice warning %}}
Để tăng cường khả năng mở rộng, tính sẵn sàng và khả năng chịu lỗi của ứng dụng, bạn có thể **xem xét** việc tích hợp Nhóm Tự Động Mở Rộng (ASG) và Cân Bằng Tải. Những thành phần này đặc biệt có lợi cho các ứng dụng yêu cầu **tính sẵn sàng cao** và khả năng xử lý **mức độ lưu lượng khác nhau**.
{{% /notice %}}

1. Chọn Nhóm Bảo Mật **Mặc Định** cho EC2 của bạn
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(1)-ec2-sg.jpg?width=60pc)
2. Cài đặt **Dung Lượng** cho **Nhóm Tự Động Mở Rộng**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(2)-asg.jpg?width=60pc)
3. Chọn **Cài Đặt Mạng Cân Bằng Tải**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(3)-lb-networking.jpg?width=60pc)
4. Chọn **Loại Cân Bằng Tải**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(4)-alb-type.jpg?width=60pc)
5. Chọn **Loại Instance**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(5)-next.jpg?width=60pc)
