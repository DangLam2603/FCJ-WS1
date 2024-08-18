---
title : "Tạo Dự Án CodeBuild"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 6.2 </b> "
---

#### Tổng Quan
**AWS CodeBuild** là một dịch vụ quản lý tự động hóa việc biên dịch mã nguồn, kiểm tra và tạo artifact. Nó tự động mở rộng và tích hợp với các dịch vụ AWS khác, sử dụng tệp ```buildspec.yml``` để cấu hình các lệnh xây dựng và cài đặt.

1. Truy cập vào phần **CodeBuild** trên **Giao diện AWS Console**
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(1)%20code-build.jpg?width=60pc)
2. Chọn **Create Project**
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(2)-create-new.jpg?width=60pc)
3. Trong **Project Configuration**, nhập **Project Name** bạn muốn
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(3)-name-prj.jpg?width=60pc)
4. Trong phần **Source section**, chọn **Source provider**
   + **Connect** với tài khoản Github của bạn
   + **Choose the repository** từ repo Github của bạn
![codebuild](/images/5-creating-codebuild-project/2.%20create-codebuild-project/(4)-source%20.jpg?width=60pc)
5. Cấu hình môi trường
  + Trong phần **Operating Sytems**, chọn hệ điều hành của bạn 
  + Để **Runtime(s)** mặc định là: **Standard Runtime**
  ![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(1)-config-env.jpg?width=60pc)
  + Trong phần **Image**, chọn **latest runtime**
  + Chọn **new service role**
  + Nhập **role name**
![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(2)-config-env.jpg?width=60pc)
   + Chọn tùy chọn **Buildspec** để sử dụng tệp ```buildspec.yml``` đã cung cấp
![codebuild](/images/5-creating-codebuild-project/3.%20config-enviroment/(3)-build-spec.jpg?width=60pc)
6. Nhập **Buildspec**
![codebuild](/images/5-creating-codebuild-project/4%20result/(1)-create-build-prj.jpg?width=60pc)
7. Kết quả
![codebuild](/images/5-creating-codebuild-project/4%20result/(2)-successfully-create.jpg?width=60pc)
