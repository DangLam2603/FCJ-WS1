---
title : "Triển khai ứng dụng web API với Elastic Beanstalk và thiết lập CI/CD sử dụng CodePipeline"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
---
# Triển khai ứng dụng web API với Elastic Beanstalk và thiết lập CI/CD sử dụng CodePipeline

### Tổng quan
 Trong bài thực hành này, chúng ta sẽ triển khai một ứng dụng API hoạt động (ASP.NET 6, Swagger UI) sử dụng AWS Elastic Beanstalk, tương tác với AWS RDS và sau đó thiết lập một pipeline cho quá trình tích hợp liên tục và phân phối/triển khai liên tục với Github và AWS CodePipeline.

![Pipeline CICD](/images/architechture/CICD.png?width=60pc) 
![ElasticBeanstalk](/images/architechture/Elastic%20Beanstalk.png?width=60pc)