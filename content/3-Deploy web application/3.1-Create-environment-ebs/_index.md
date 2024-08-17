---
title : "Create New Elastic Beanstalk Environment"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 3.1 </b> "
---

## Overview
Before proceeding with the setup of **AWS Elastic Beanstalk**, it's essential to first configure a new environment to ensure that the deployment process runs smoothly.

1. Navigate to **AWS Console UI** and search **Elastic Beanstalk**
   ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(1)-ebs.jpg?width=60pc)
2. Choose **New Environment**
    ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(2)-create-new-ebs.jpg?width=60pc)
3. In the **Environment Information**, fill in **Environment name** you want
{{% notice note %}}
You can choose the **Domain Name** you want, though it is *optional*. Ensure that you check **the availability** of the domain name.
{{% /notice %}} 
![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(3)-config-ebs-env-name.jpg?width=60pc)
1. After that, select the **platform, platform version and branch** you want to deploy, in this tutorial  will use **.NET 6 on Linux**
 ![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(4)-ebs-platform.jpg?width=60pc)
1. In the Presets, choose **High avalibility**. 
![ElasticBeanstalk](/images/3-deploy-ebs-application/3.1-create%20environment%20for%20ebs/(5)-ebs-preset.jpg?width=60pc)

{{% notice info %}}
This step allows users to efficiently set up their environment based on their specific needs, whether opting for a **simple single-instance setup** (potentially eligible for the free tier) or a more **robust high-availability** configuration. In the **Application Code** section, you can choose either to use the **sample code** for a basic deployment or to **upload your own code from an S3** Bucket.
{{% /notice %}}
  
  