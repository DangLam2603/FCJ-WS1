---
title : "Create Deploy Stage"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 7.4 </b> "
---

#### Overview
In the deploy stage of AWS CodePipeline, you set up the process to deploy your built application to a specified environment.In this workshop, we'll involves integrating with deployment AWS Elastic Beanstalk

1. Choose the source for **Deploy Provider**
![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(1).jpg?width=60pc)
2. **Modify** the following:
  + *Region*: specific areas of your deployment zone
  + Select the **Application Name** of your Elastic Beanstalk
  + Select the **Environment Name** of your Elastic Beanstalk
![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(2).jpg?width=60pc)
3. **Review** the following steps and enter **Create Pipline**
 ![buildspect](/images/6-set-up-pipeline/4-add-deploy-stage/deploy%20(3).jpg?width=60pc)