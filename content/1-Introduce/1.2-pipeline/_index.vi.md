---
title : "CI/CD sử dụng AWS CodePipeline và AWS CodeBuild"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 1.2 </b> "
---
## Tổng quan về CI/CD

**CI/CD** là viết tắt của Continuous Integration (Tích hợp liên tục) và Continuous Delivery (Phân phối liên tục) hoặc Continuous Deployment (Triển khai liên tục), một tập hợp các phương pháp được sử dụng trong phát triển phần mềm hiện đại để tự động hóa và tối ưu hóa quá trình xây dựng, kiểm thử và triển khai ứng dụng.

- *Continuous Integration* (CI): Liên quan đến việc tự động tích hợp các thay đổi mã từ nhiều người đóng góp vào một kho lưu trữ chung nhiều lần trong ngày. Mỗi lần tích hợp được xác minh bằng các bản dựng và kiểm thử tự động, cho phép các nhóm phát hiện vấn đề sớm.

- *Continuous Delivery* (CD): Mở rộng CI bằng cách tự động triển khai ứng dụng lên môi trường staging hoặc production sau khi bản dựng và kiểm thử thành công. Điều này đảm bảo phần mềm luôn ở trạng thái có thể triển khai.

**AWS CodePipeline** là dịch vụ tích hợp liên tục và phân phối liên tục hoàn toàn được quản lý, tự động hóa các bước cần thiết để phát hành phần mềm của bạn. Với CodePipeline, bạn có thể định nghĩa một loạt các giai đoạn như nguồn, xây dựng, kiểm thử và triển khai, được kích hoạt tự động khi phát hiện thay đổi trong kho mã nguồn.

**Các tính năng chính:**
- *Luồng công việc tự động*: Tự động hóa toàn bộ quá trình phát hành từ thay đổi mã nguồn đến triển khai.
- *Tích hợp với dịch vụ AWS*: Tích hợp liền mạch với các dịch vụ khác của AWS như CodeBuild, ECS, Lambda, và S3.
- *Đường ống tùy chỉnh*: Cho phép bạn tùy chỉnh từng giai đoạn của đường ống, bao gồm sử dụng công cụ của bên thứ ba hoặc script tùy chỉnh.
- *Thực thi song song*: Hỗ trợ thực thi song song các hành động để tăng tốc quá trình phát hành.
- *Bảo mật tích hợp*: Cung cấp mã hóa và tích hợp với AWS Identity and Access Management (IAM) để kiểm soát truy cập an toàn.

**AWS CodeBuild** là dịch vụ xây dựng hoàn toàn được quản lý, biên dịch mã nguồn, chạy kiểm thử, và tạo ra các gói phần mềm sẵn sàng để triển khai. Nó loại bỏ nhu cầu thiết lập và quản lý máy chủ xây dựng riêng.

**Các tính năng chính:**
- *Khả năng mở rộng*: Tự động mở rộng để xử lý nhiều bản dựng cùng lúc, đảm bảo thời gian xây dựng nhanh chóng và đáng tin cậy.
- *Môi trường xây dựng tùy chỉnh*: Cho phép bạn định nghĩa môi trường xây dựng riêng sử dụng các hình ảnh Docker, làm cho nó linh hoạt với các ngôn ngữ lập trình và công cụ khác nhau.
- *Tích hợp với đường ống CI/CD*: Dễ dàng tích hợp với AWS CodePipeline và các công cụ CI/CD khác để tự động hóa quá trình xây dựng như một phần của đường ống triển khai.
- *Giá cả theo sử dụng*: Chỉ tính phí cho tài nguyên tính toán bạn sử dụng trong quá trình xây dựng, giúp tiết kiệm chi phí.
