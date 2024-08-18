---
title : "Create CodeBuild Project"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 6.2 </b> "
---

#### Overview
**AWS CodeBuild** is a managed service that automates code compilation, testing, and artifact creation. It scales automatically and integrates with other AWS services, using a ```buildspec.yml``` file to configure build commands and settings.

1. Navigate to the **CodeBuild** section on the **AWS console UI**
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(1)%20code-build.jpg?width=60pc)
2. Choose **Create Project**
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(2)-create-new.jpg?width=60pc)
3. In the **Project Configuration**, enter **Project Name** you want
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(3)-name-prj.jpg?width=60pc)
4. In the **Source section**, select **Source provider**
   + **Connect** to your Github account
   + **Choose the repository** from your Github repo
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(4)-source%20.jpg?width=60pc)
5. Config the environment
  + In the **Operating Sytems** section, choose your OS 
  + Leave the **Runtime(s)** as default : **Standard Runtime**
  ![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(1)-config-env.jpg?width=60pc)
  + In the **Image** section, select the **latest runtime**
  + Select **new service role**
  + Enter **role name**
![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(2)-config-env.jpg?width=60pc)
   + Select **Buildspec** option to use the provided ```buildspec.yml``` file
![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(3)-build-spec.jpg?width=60pc)
6. Enter **Create New Project**
![codebuild](/images/5-creating-codebuild-project/4%20result/(1)-create-build-prj.jpg?width=60pc)
7. Result
![codebuild](/images/5-creating-codebuild-project/4%20result/(2)-successfully-create.jpg?width=60pc)
  