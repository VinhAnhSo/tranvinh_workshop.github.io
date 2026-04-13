---
title: "Nhật ký công việc Tuần 8"
date: 2026-03-16
weight: 8
chapter: false
pre: "<b>1.8.</b> "
---

### Mục tiêu tuần:
- Hiểu AWS CloudWatch metrics và alarms để giám sát hiệu năng hệ thống.
- Tìm hiểu cách CloudTrail hỗ trợ audit logging và theo dõi hoạt động trong AWS.
- Khám phá AWS X-Ray để theo dõi distributed tracing và độ trễ giữa các service.
- Xây dựng một hệ thống giám sát tổng thể cho ứng dụng cloud.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Tìm hiểu kiến thức cơ bản về CloudWatch<br>- Hiểu metrics, logs và alarms<br>- Thực hành theo dõi hiệu năng tài nguyên | 17/03/2026 | 17/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Nghiên cứu CloudTrail<br>- Tìm hiểu cơ chế audit logging trong AWS<br>- Khám phá event history và theo dõi hoạt động tài khoản | 18/03/2026 | 18/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Tìm hiểu AWS X-Ray<br>- Hiểu các khái niệm distributed tracing<br>- Thực hành theo dõi request qua nhiều thành phần ứng dụng | 19/03/2026 | 19/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Thực hành:**<br>&emsp;+ Cấu hình CloudWatch metrics và alarms<br>&emsp;+ Xem CloudTrail logs cho hoạt động tài khoản<br>&emsp;+ Sử dụng X-Ray để trace request của ứng dụng | 20/03/2026 | 20/03/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần:
- Có được hiểu biết khá rõ về các dịch vụ giám sát và quan sát trong AWS, đặc biệt là vai trò khác nhau của CloudWatch, CloudTrail và X-Ray trong việc tăng khả năng hiển thị hệ thống.
- Hiểu cách CloudWatch metrics và alarms được sử dụng để theo dõi tài nguyên, giám sát sức khỏe ứng dụng và cảnh báo khi xuất hiện hành vi bất thường hoặc vượt ngưỡng.
- Thực hành làm việc với dữ liệu giám sát từ CloudWatch, qua đó cải thiện khả năng quan sát xu hướng hiệu năng và phản ứng với vấn đề vận hành hiệu quả hơn.
- Tìm hiểu CloudTrail và hiểu tầm quan trọng của dịch vụ này trong audit logging, theo dõi hoạt động tài khoản và rà soát các hành động diễn ra trong môi trường AWS.
- Nắm được vai trò của CloudTrail trong governance, security monitoring và accountability thông qua việc ghi nhận các sự kiện quản trị và hoạt động dịch vụ.
- Tìm hiểu AWS X-Ray và hiểu cách distributed tracing được dùng để phân tích luồng request, đo độ trễ service và xác định bottleneck giữa nhiều thành phần ứng dụng.
- Hiểu rõ hơn cách monitoring, logging và tracing phối hợp với nhau để cung cấp một bức tranh vận hành toàn diện hơn cho hệ thống cloud.
- Xây dựng được một hệ thống giám sát tổng thể cơ bản kết hợp metrics, alarms, audit logs và tracing nhằm tăng khả năng ổn định và xử lý sự cố cho ứng dụng.

### Dự án:
#### 3. API Todo Serverless
- Kiến trúc: Lambda + API Gateway + DynamoDB
- Chi phí dự kiến: khoảng \$15/tháng

#### 4. Kiến trúc Microservices
- Kiến trúc: ECS + ALB + RDS
- Chi phí dự kiến: khoảng \$35/tháng