---
title : "Create Buildspect and Procfile"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 6.1 </b> "
---

#### Overview
Creating a **buildspec.yml** file and a **Procfile.txt** is essential for automating and managing the build, deployment, and runtime configuration of your application. Each serves a distinct purpose in the software development lifecycle, particularly when using AWS services like CodeBuild and Elastic Beanstalk

1. ```buildspec.yml```: This file defines the **build process** for AWS CodeBuild. It includes phases for **installing dependencies**, **compiling code**, **running tests**, and **packaging the application**. Customize it by specifying build commands, environment variables, and artifact locations to match your project’s needs.
![buildspect](/images/5-creating-codebuild-project/1.%20add-buildspec-and-procfile/buildspec.jpg?width=60pc)
2. ```Procfile```: Used primarily in platforms like AWS Elastic Beanstalk, the Procfile s**pecifies the commands to start various application processes**, such as web servers or worker processes. **Define the types of processes** and their corresponding startup commands to ensure the application runs correctly.
![buildspect](/images/5-creating-codebuild-project/1.%20add-buildspec-and-procfile/Profile.jpg?width=60pc)

3. After that commit your code to your own repository on Github and let's get started with CodeBuild

{{% notice info %}}
In the source code folder, two deployment files have been included to facilitate the deployment process. These files are essential for automating the build and deployment of the application. However, you may choose to create and modify these files according to specific requirements or preferences
{{% /notice %}}