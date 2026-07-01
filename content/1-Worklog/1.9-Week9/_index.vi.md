---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Triển khai website tĩnh trên Amazon S3.
* Hiểu cách kiểm soát public access, object permission và website routing.
* Tối ưu truy cập với Amazon CloudFront.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu static website hosting trên S3<br>- Hiểu public access block và ACL | 11/08/2025 | 11/08/2025 | Tài liệu AWS S3 |
| 3 | - Tạo bucket S3 cho static website<br>- Upload file website<br>- Bật website endpoint | 12/08/2025 | 12/08/2025 | AWS S3 console |
| 4 | - Cấu hình public access và bucket policy cẩn trọng<br>- Kiểm tra website endpoint | 13/08/2025 | 13/08/2025 | AWS security best practices |
| 5 | - Tạo CloudFront distribution<br>- Đặt bucket S3 làm origin<br>- Cấu hình cache behavior và root object | 14/08/2025 | 15/08/2025 | Hướng dẫn AWS CloudFront |
| 6 | - Bật versioning cho bucket<br>- Cấu hình replication đa region<br>- Ghi chú cleanup | 15/08/2025 | 15/08/2025 | Tài liệu AWS S3 replication |

### Kết quả đạt được tuần 9:

* Triển khai thành công website tĩnh trên S3.
* Phân biệt rõ giữa public access block và permission cấp object.
* Tăng tốc truy cập bằng CloudFront kết hợp S3 origin.
* Bật versioning và cấu hình replication để tăng độ bền dữ liệu.
* Ghi nhận các bước dọn dẹp bucket và distribution.
* ...