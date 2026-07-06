---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Triển khai cơ chế sao lưu dữ liệu cho Minecraft Server bằng AWS Backup.
* Thiết lập Network Load Balancer nhằm tăng tính ổn định cho hệ thống.
* Kiểm thử khả năng khôi phục dữ liệu và tính sẵn sàng của hệ thống.
* Tham gia cuộc thi **The First Cloud Journey – AWS Việt Nam Knowledge Competition**.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tạo AWS Backup Vault<br>- Tìm hiểu cơ chế Backup Vault và Recovery Point<br>- Thiết lập mã hóa cho Backup Vault | 15/06/2026 | 15/06/2026 | https://www.youtube.com/@AWSStudyGroup https://cloudjourney.awsstudygroup.com/ |
| 3 | - Tạo Backup Plan cho Amazon EC2<br>- Cấu hình lịch sao lưu định kỳ và thời gian lưu trữ<br>- Gán EC2 Minecraft Server vào Backup Plan | 16/06/2026 | 16/06/2026 | https://www.youtube.com/@AWSStudyGroup https://cloudjourney.awsstudygroup.com/ |
| 4 | - Kiểm tra Recovery Point được tạo tự động<br>- Thực hành quy trình khôi phục dữ liệu từ AWS Backup<br>- Đánh giá khả năng phục hồi sau sự cố | 17/06/2026 | 17/06/2026 | [Report Minecraft Security Based on AWS](https://docs.google.com/document/d/1gLwVqTCD2lwx72q6pu60ZA4vUM945DOM860uvY6uNTI/edit?tab=t.0#heading=h.ceilhw2z2uk6) |
| 5 | - Tạo Target Group và Network Load Balancer<br>- Cấu hình TCP Listener cho Minecraft Server<br>- Kiểm thử lưu lượng qua NLB | 18/06/2026 | 18/06/2026 | [Report Minecraft Security Based on AWS](https://docs.google.com/document/d/1gLwVqTCD2lwx72q6pu60ZA4vUM945DOM860uvY6uNTI/edit?tab=t.0#heading=h.ceilhw2z2uk6) |
| 6 | - Tối ưu cấu hình Network Load Balancer<br>- Kiểm tra trạng thái Health Check và Target Group<br>- Hoàn thiện tài liệu triển khai | 19/06/2026 | 19/06/2026 | [Report Minecraft Security Based on AWS](https://docs.google.com/document/d/1gLwVqTCD2lwx72q6pu60ZA4vUM945DOM860uvY6uNTI/edit?tab=t.0#heading=h.ceilhw2z2uk6) |
| 7 | - Tham gia cuộc thi **The First Cloud Journey – AWS Việt Nam Knowledge Competition**<br>- Giao lưu với các thành viên chương trình và mở rộng kiến thức về AWS Cloud<br>- Tổng hợp những kiến thức và kinh nghiệm thu nhận được sau cuộc thi | 20/06/2026 | 20/06/2026 | The First Cloud Journey – AWS Việt Nam Knowledge Competition |
| CN | - Cập nhật tài liệu project và sơ đồ kiến trúc<br>- Chuẩn bị triển khai AWS Global Accelerator và hoàn thiện hệ thống trong tuần tiếp theo | 21/06/2026 | 21/06/2026 | Personal Notes, Udemy, Cousrera, Oreilly Learning |

### Kết quả đạt được tuần 9:

* Triển khai thành công AWS Backup để sao lưu dữ liệu định kỳ cho Minecraft Server.
* Thiết lập Backup Plan và kiểm tra khả năng khôi phục dữ liệu từ Recovery Point.
* Hoàn thành triển khai Network Load Balancer cho Minecraft Server và xác minh hoạt động của Health Check.
* Tham gia **The First Cloud Journey – AWS Việt Nam Knowledge Competition**, tích lũy thêm kiến thức và kinh nghiệm thực tế về nền tảng AWS.
* Hoàn thiện các thành phần về khả năng phục hồi và tính sẵn sàng của hệ thống, sẵn sàng triển khai AWS Global Accelerator trong tuần tiếp theo.