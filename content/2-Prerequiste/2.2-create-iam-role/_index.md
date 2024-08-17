---
title : "Create IAM Role"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2.2 </b> "
---

## Create IAM Role For Elastic Beanstalk
1. Navigate to AWS Console and search for IAM 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(1)-iam.jpg?width=60pc)

2. Select **Role** from left side bar and choose **Create role** 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(2)-create-role.jpg?width=60pc)

3. Choose **Trusted Service**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(3)-iam-service.jpg?width=60pc)

4. Select **EC2**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(3)-iam-ec2.jpg?width=60pc)

5. Add the following permision  **AWSElasticBeanstalkWebTier** 
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(4)-add-permission.jpg?width=60pc)

6. Enter **Role name**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(5)-role-name.jpg?width=60pc) 

7. Choose **Create Role**
![IAM](/images/2-prerequisite/2.3-setup-iam-roles/(6)-create-new-role.jpg?width=60pc)