---
title : "Create Load Balancer and Auto Scaling Group"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 3.4 </b> "
---

#### Overview 

{{% notice warning %}}
To further enhance the scalability, availability, and fault tolerance of the application, integrating an Auto Scaling Group (ASG) and a Load Balancer can be **considered**. These components are particularly beneficial for applications that **require high availability** and the ability to handle **varying levels of traffic**.
{{% /notice %}}

1. Choose **Default** Security Group for your EC2
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(1)-ec2-sg.jpg?width=60pc)
2. Setting **Capacity** for **Auto Scaling Group**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(2)-asg.jpg?width=60pc)
3. Select **Load Balancer Network Settings**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(3)-lb-networking.jpg?width=60pc)
4. Select **Load Balancer Type**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(4)-alb-type.jpg?width=60pc)
5. Select **Instance Type**
   ![SecutityGroup](/images/3-deploy-ebs-application/3.4-create-alb-asg/(5)-next.jpg?width=60pc)