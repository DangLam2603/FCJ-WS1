---
title : "Demo And Test APIs"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 5.2 </b> "
---

{{% notice info %}}
To validate the deployment of our APIs, initiate by obtaining the URL associated with our Elastic Beanstalk domain. The API utilizes Swagger UI for the documentation and interaction with endpoints. To access the comprehensive list of available endpoints, append ```../swagger/index.html``` to the base URL of the domain.
{{% /notice %}}

1. Copy and paste the domain URL ```ebs-player-apis-dev.ap-southeast-1.elasticbeanstalk.com/swagger/index.html```
![link](/images/3-deploy-ebs-application/3.9-demo-api/demo%20(1).jpg?width=60pc)
2. Deploy sucessfully and test the APIs working with the hosted RDS database.
![link](/images/3-deploy-ebs-application/3.9-demo-api/demo%20(2).jpg?width=60pc)

> Your API is now hosted on the AWS Cloud utilizing the Elastic Beanstalk environment, with a fully integrated RDS database. You can access the API and develop a fully functional web application for your backend, all seamlessly deployed on the AWS Cloud with robust database support from Amazon RDS.
