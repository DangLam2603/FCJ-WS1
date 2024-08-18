---
title : "Tạo IAM Role"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2.2 </b> "
---

#### Tạo IAM Role cho Elastic Beanstalk
1. Điều hướng đến AWS Console và tìm kiếm IAM 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(1)-iam.jpg?width=60pc)

2. Chọn **Role** từ thanh bên trái và chọn **Create role** 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(2)-create-role.jpg?width=60pc)

3. Chọn **Trusted Service**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(3)-iam-service.jpg?width=60pc)

4. Chọn **EC2**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(3)-iam-ec2.jpg?width=60pc)

5. Thêm quyền sau **AWSElasticBeanstalkWebTier** 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(4)-add-permission.jpg?width=60pc)

6. Nhập **Tên Role**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(5)-role-name.jpg?width=60pc) 

7. Chọn **Create Role**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(6)-create-new-role.jpg?width=60pc)
