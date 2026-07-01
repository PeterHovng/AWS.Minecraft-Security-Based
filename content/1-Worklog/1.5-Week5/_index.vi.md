---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Xây dựng môi trường VPC hoàn chỉnh trên AWS.
* Học subnetting, route table, IGW, NAT Gateway, Security Group và NACL.
* Thực hành kiểm tra kết nối và giám sát mạng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu VPC, subnet, route table, IGW, NAT<br>- Học Security Group và NACL | 11/08/2025 | 11/08/2025 | Tài liệu AWS VPC |
| 3 | - Tạo VPC<br>- Tạo public và private subnet<br>- Gắn Internet Gateway | 12/08/2025 | 12/08/2025 | AWS VPC console |
| 4 | - Cấu hình route table cho public và private<br>- Tạo và kiểm tra NAT Gateway | 13/08/2025 | 13/08/2025 | AWS networking guides |
| 5 | - Tạo Security Group và NACL<br>- Bật VPC Flow Logs<br>- Chạy Reachability Analyzer | 14/08/2025 | 15/08/2025 | AWS VPC security docs |
| 6 | - Launch EC2 trong VPC<br>- Kết nối bằng Session Manager<br>- Xem CloudWatch metrics và alarms | 15/08/2025 | 15/08/2025 | AWS Systems Manager |

### Kết quả đạt được tuần 5:

* Xây dựng được VPC có public subnet và private subnet.
* Cấu hình đúng routing, NAT, SG và NACL.
* Kiểm tra đường đi mạng bằng Reachability Analyzer.
* Kết nối EC2 không cần SSH bằng Session Manager.
* Cấu hình CloudWatch giám sát cơ bản cho mạng.
* ...