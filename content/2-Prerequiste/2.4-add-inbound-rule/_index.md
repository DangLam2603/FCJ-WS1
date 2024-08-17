---
title : "Modify Inbound Rule"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2.4 </b> "
---

## Overview

1. Locate to **AWS Console**, look for **EC2** Service and select **Security Group**.
   ![security group](/images/2-prerequisite/2.5-edit-inbound-rule/(1)-security-group.jpg?width=60pc)
2. Select and modify **Your Security Group**. 
   ![Modify security group](/images/2-prerequisite/2.5-edit-inbound-rule/(2)-crreate-sg.jpg?width=60pc)
3. Select **Edit Inbound Rule**
   ![Edit security group](/images/2-prerequisite/2.5-edit-inbound-rule/(3)-edit-sg.jpg?width=60pc)
4. Add Rule => Select **MSSQL** type => Save Rule
   ![Edit security group](/images/2-prerequisite/2.5-edit-inbound-rule/(5)-add-sg.jpg?width=60pc)
{{% notice info %}}
In this workshop we will use MSSQL deploy to RDS Database, you can choose different database type by modify the port range to match with Database's Port
{{% /notice %}}