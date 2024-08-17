---
title : "CI/CD using AWS CodePipeline and AWS CodeBuild"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 1.2 </b> "
---
## Overview of CI/CD

**CI/CD** stands for Continuous Integration and Continuous Delivery (or Continuous Deployment), a set of practices used in modern software development to automate and streamline the process of building, testing, and deploying applications.

- *Continuous Integration* (CI): Involves automatically integrating code changes from multiple contributors into a shared repository several times a day. Each integration is verified by automated builds and tests, allowing teams to detect problems early.

- *Continuous Delivery* (CD): Extends CI by automatically deploying the application to a staging or production environment after successful builds and tests. This ensures that the software is always in a deployable state.

**AWS CodePipeline** is a fully managed continuous integration and continuous delivery service that automates the steps required to release your software. With CodePipeline, you can define a series of stages, such as source, build, test, and deploy, which are triggered automatically when changes are detected in the source code repository.

**Key Features:**
- *Automated Workflows*: Automates the entire release process from code changes to deployment.
- *Integration with AWS Services*: Seamlessly integrates with other AWS services like CodeBuild, ECS, Lambda, and S3.
- *Customizable Pipelines*: Allows you to customize each stage of your pipeline, including using third-party tools or custom scripts.
- *Parallel Execution*: Supports parallel execution of actions to speed up the release process.
- *Built-In Security*: Offers encryption and integration with AWS Identity and Access Management (IAM) for secure access control.


**AWS CodeBuild** is a fully managed build service that compiles source code, runs tests, and produces software packages ready for deployment. It eliminates the need to set up and manage your own build servers.

**Key Features:**
- *Scalability*: Automatically scales to handle multiple builds simultaneously, ensuring fast and reliable build times.
- *Customizable Build Environment*: Allows you to define your own build environments using Docker images, making it flexible for different programming languages and tools.
- *Integration with CI/CD Pipelines*: Easily integrates with AWS CodePipeline and other CI/CD tools to automate the build process as part of your deployment pipeline.
- *Pay-As-You-Go Pricing*: Charges only for the compute resources you use during the build process, making it cost-effective.
