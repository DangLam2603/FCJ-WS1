---
title : "Tạo Giai Đoạn Xây Dựng"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 7.3 </b> "
---

#### Tổng Quan
Trong **build stage** của AWS CodePipeline, bạn sẽ cấu hình quy trình **compiles your source code, runs tests, and packages the application**. Giai đoạn này thường liên quan đến việc tích hợp với AWS CodeBuild hoặc một dịch vụ xây dựng khác.

1. Cài đặt Build Provider sử dụng dự án CodeBuild hiện có.
   ![buildspect](/images/6-set-up-pipeline/3-add-build-stage/build%20(1).jpg?width=60pc)
2. Chọn Dự án CodeBuild hoặc bạn có thể tạo một dự án mới.
   ![buildspect](/images/6-set-up-pipeline/3-add-build-stage/build%20(2).jpg?width=60pc)
