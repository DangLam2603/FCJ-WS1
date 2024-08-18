---
title : "Tạo Buildspect và Procfile"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 6.1 </b> "
---

#### Tổng Quan
Việc tạo **buildspec.yml** và **Procfile.txt** là rất quan trọng để tự động hóa và quản lý quá trình xây dựng, triển khai, và cấu hình runtime của ứng dụng của bạn. Mỗi tệp này phục vụ một mục đích riêng trong vòng đời phát triển phần mềm, đặc biệt khi sử dụng các dịch vụ AWS như CodeBuild và Elastic Beanstalk.

1. ```buildspec.yml```: Tệp này định nghĩa **quá trình xây dựng** cho AWS CodeBuild. Nó bao gồm các giai đoạn như **cài đặt phụ thuộc**, **biên dịch mã nguồn**, **chạy kiểm tra**, và **đóng gói ứng dụng**. Tùy chỉnh nó bằng cách chỉ định các lệnh xây dựng, biến môi trường và vị trí artifact để phù hợp với nhu cầu dự án của bạn.
![buildspect](/images/5-creating-codebuild-project/1.%20add-buildspec-and-procfile/buildspec.jpg?width=60pc)

2. ```Procfile```: Chủ yếu được sử dụng trên các nền tảng như AWS Elastic Beanstalk, Procfile **xác định các lệnh để khởi động các quy trình ứng dụng khác nhau**, chẳng hạn như máy chủ web hoặc quy trình worker. **Định nghĩa các loại quy trình** và các lệnh khởi động tương ứng của chúng để đảm bảo ứng dụng hoạt động chính xác.
![buildspect](/images/5-creating-codebuild-project/1.%20add-buildspec-and-procfile/Profile.jpg?width=60pc)

3. Sau đó, hãy commit mã nguồn của bạn vào kho lưu trữ trên Github và bắt đầu với CodeBuild.

{{% notice info %}}
Trong thư mục mã nguồn, hai tệp triển khai đã được bao gồm để hỗ trợ quá trình triển khai. Những tệp này rất quan trọng để tự động hóa quá trình xây dựng và triển khai ứng dụng. Tuy nhiên, bạn có thể chọn tạo và chỉnh sửa các tệp này theo yêu cầu hoặc sở thích cụ thể.
{{% /notice %}}
