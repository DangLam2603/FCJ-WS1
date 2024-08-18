---
title : "Modify Connection String and Inbound Rule"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 4.1 </b> "
---

For our Database instances to be able to work in the AWS cloud environment, we will need to update the Connection String and create a inbound rule to connect to our local MSSQL server.

#### Update Connection String

1. Go to project folder and look for ```appsetting.json```
  + In the Connection String, look for **DefaultConnection**
  + Modify the **Server, uid, pwd** match with the database settings in Elastic Beanstalk.
 
  ![cnstr](/images/4-config-rds/(1)-cntr.jpg?width=80pc)


2. Navigate to AWS RDS Database in  AWS Console UI
   + Select the database to modify
![database](/images/4-config-rds/(2)-modify.jpg?width=60pc)
   + Add the following Inbound rule
![inbound](/images/4-config-rds/(3)-inbound-rule.jpg?width=60pc) 
 

Next, we will proceed to migration an test our database to local MSSQL Server. 