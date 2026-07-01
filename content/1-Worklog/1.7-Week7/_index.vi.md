---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Hiểu vai trò của IAM role cho EC2 và lý do nó an toàn hơn access key.
* Thực hành gắn instance profile và sử dụng temporary credentials.
* Truy cập tài nguyên AWS từ EC2 mà không dùng credential cố định.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Xem lại rủi ro của access key dài hạn<br>- So sánh IAM user access key với instance role | 11/08/2025 | 11/08/2025 | Tài liệu AWS IAM |
| 3 | - Tạo IAM role cho EC2<br>- Gắn quyền truy cập S3<br>- Xem lại trust policy | 12/08/2025 | 12/08/2025 | AWS IAM console |
| 4 | - Gắn role vào EC2<br>- Kiểm tra temporary credentials qua metadata | 13/08/2025 | 13/08/2025 | EC2 instance metadata |
| 5 | - Truy cập S3 từ EC2 bằng role<br>- Test thao tác đọc/ghi<br>- Kiểm tra không còn key cố định trong code | 14/08/2025 | 15/08/2025 | AWS SDK examples |
| 6 | - Ghi chú cleanup cho role và instance profile<br>- Tổng hợp best practices | 15/08/2025 | 15/08/2025 | AWS IAM best practices |

### Kết quả đạt được tuần 7:

* Hiểu rõ tại sao nên dùng IAM role thay vì access key dài hạn.
* Tạo và gắn IAM role vào EC2 thành công.
* Truy cập tài nguyên AWS từ EC2 mà không dùng credential hardcode.
* Kiểm tra hành vi temporary credential qua instance metadata.
* Ghi nhận best practices khi dùng role cho EC2.
* ...