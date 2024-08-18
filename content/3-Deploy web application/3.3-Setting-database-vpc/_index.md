---
title : "Setting VPC and Database"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 3.3 </b> "
---

#### Overview 
Next, we'll configure VPC and create new RDS database to host our SQL Server to cloud.

1. Select the exiting or Create new **Vitural Private Cloud (VPC)**. In this demo, i'll choose the **default VPC**.
   ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(1)-ebs-vpc.jpg?width=60pc)
2. Choose the **Avalibility Zone** you want to run your application.
    ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(2)-ebs-instance-setting.jpg?width=60pc)
3. Select your **database subnets** and ```enable database```
    ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(3)-ebs-database.jpg?width=60pc)
4. Modify the following:
   - *Engine* : the engine of your database (in this workshop i'll use SQL Server)
   - *Engine Version* : version of database
   - *Instance class* : instance type of database 
   - *Storage* : database storage
   - *Username* : the username of database (key to connect to database)
   - *Password* : the password of database (key to connect to database)
  ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(4)-ebs-database-settings.jpg?width=60pc)

5. Enter **Next**
   ![database](/images/3-deploy-ebs-application/3.3-setting%20database,%20vpc/(5)-next.jpg?width=60pc)