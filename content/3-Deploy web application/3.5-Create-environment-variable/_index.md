---
title : "Add Environment Variable"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 3.5 </b> "
---

## Overview 

The following step allow us to add environment variabale inside Elastic Beanstalk for security purpose

1. Enabling CloudWatch Logs for Elastic Beanstalk is an essential step for monitoring and troubleshooting your application 
   ![cloudwatch](/images/3-deploy-ebs-application/3.5-create-enviroment-variable/(1)-next.jpg?width=60pc)
2. Set the following environment variables that configure the logging behavior.
    - ``ASPNETCORE_ENVIRONMENT = Development`` (specific the dev enviroment on NET Core)
    - ``ConnectionString__DefaultConnection = "Your Connection String"`` (add a connection to your RDS database)
   ![variable](/images/3-deploy-ebs-application/3.5-create-enviroment-variable/(2)-copy.jpg?width=60pc)