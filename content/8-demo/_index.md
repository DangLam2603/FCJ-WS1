---
title : "Demo CI/CD flow"
date :  "`r Sys.Date()`" 
weight : 8 
chapter : false
pre : " <b> 8. </b> "
---

#### Overview
Now, let's demostration the continuous integration and continuous delivery workflow automates the process from code commit to deployment. When a developer commits code to a GitHub repository, AWS CodePipeline detects the change and triggers the pipeline.

1. Commit new change to Github Repository ![commit](/images/7-demo/1-commit-new-change/commitcode.jpg?width=60pc)
2. CodePipeline automatically detects the latest changes ![commit](/images/7-demo/2-cicd-working/cicd%20(1).jpg?width=60pc) 
![commit](/images/7-demo/2-cicd-working/cicd%20(2).jpg?width=60pc)
3. New API endpoint deploy sucessfull
 ![commit](/images/7-demo/3-result/final-result.jpg?width=60pc)