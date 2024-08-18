---
title : "Demo Quy Trình CI/CD"
date : "`r Sys.Date()`" 
weight : 8 
chapter : false
pre : " <b> 8. </b> "
---

#### Tổng Quan
Bây giờ, hãy cùng demo quy trình tích hợp liên tục và giao hàng liên tục, tự động hóa quy trình từ việc cam kết mã nguồn đến triển khai. Khi một nhà phát triển cam kết mã nguồn vào kho GitHub, AWS CodePipeline phát hiện sự thay đổi và kích hoạt pipeline.

1. Cam kết thay đổi mới vào Kho Github ![commit](/images/7-demo/1-commit-new-change/commitcode.jpg?width=60pc)
2. CodePipeline tự động phát hiện các thay đổi mới nhất ![commit](/images/7-demo/2-cicd-working/cicd%20(1).jpg?width=60pc) 
![commit](/images/7-demo/2-cicd-working/cicd%20(2).jpg?width=60pc)
3. Triển khai điểm cuối API mới thành công
 ![commit](/images/7-demo/3-result/final-result.jpg?width=60pc)
