---
title: "Nhật ký công việc Tuần 2"
date: 2026-01-12
weight: 2
chapter: false
pre: "<b>1.2.</b> "
---

### Mục tiêu tuần:
- Hiểu các dịch vụ lưu trữ và cơ sở dữ liệu của AWS, bao gồm S3, EBS và RDS.
- Tìm hiểu về lifecycle policy và snapshot để quản lý dữ liệu.
- Xây dựng một ứng dụng đám mây đơn giản tích hợp EC2, S3 và RDS.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Tìm hiểu Amazon S3 là dịch vụ lưu trữ đối tượng có độ bền dữ liệu rất cao (99.999999999%)<br>- Tìm hiểu về bucket, object và các yêu cầu kiểm soát truy cập trong S3<br>- Nghiên cứu S3 Lifecycle Policy để tự động quản lý dữ liệu | 13/01/2026 | 13/01/2026 | <https://000057.awsstudygroup.com> |
| 3 | - Tìm hiểu cách host static website bằng Amazon S3<br>- Khám phá các giải pháp hiện đại hơn như AWS Amplify Hosting<br>- Nghiên cứu đặc điểm của EBS volume, bao gồm thay đổi kích thước và chuyển đổi loại volume | 14/01/2026 | 14/01/2026 | <https://000057.awsstudygroup.com> |
| 4 | - Tìm hiểu EBS snapshot như một dạng sao lưu tại một thời điểm được lưu trữ trên S3<br>- Nghiên cứu cách snapshot hoạt động với mã hóa và khôi phục dữ liệu<br>- Tìm hiểu kiến trúc Amazon RDS, các hệ quản trị cơ sở dữ liệu được hỗ trợ và lợi ích của dịch vụ được quản lý | 15/01/2026 | 15/01/2026 | <https://000005.awsstudygroup.com/> |
| 5 | - **Thực hành:**<br>&emsp;+ Xây dựng một hệ thống tải tệp đơn giản<br>&emsp;+ Sử dụng EC2 cho phần xử lý ứng dụng<br>&emsp;+ Sử dụng S3 để lưu trữ tệp và RDS để lưu metadata | 16/01/2026 | 16/01/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần:
- Có được hiểu biết khá vững về các dịch vụ lưu trữ và cơ sở dữ liệu trên AWS, đặc biệt là vai trò của Amazon S3, EBS và RDS trong thiết kế ứng dụng đám mây.
- Hiểu được Amazon S3 là dịch vụ lưu trữ đối tượng có độ bền rất cao, đồng thời nắm được các khái niệm cơ bản như bucket, object và kiểm soát truy cập.
- Tìm hiểu S3 Lifecycle Policy và hiểu cách dữ liệu có thể được tự động chuyển lớp lưu trữ hoặc xóa đi để tối ưu quản lý lưu trữ.
- Khám phá khả năng host static website bằng Amazon S3 và biết thêm về các lựa chọn hiện đại hơn như AWS Amplify Hosting cho những nhu cầu triển khai nâng cao.
- Nắm được các đặc điểm của Amazon EBS volume, bao gồm mối liên hệ với Availability Zone, khả năng thay đổi kích thước và chuyển đổi loại volume một cách linh hoạt.
- Hiểu cách EBS snapshot hoạt động như bản sao lưu tại một thời điểm, cũng như vai trò của snapshot trong sao lưu, phục hồi, mã hóa và bảo vệ dữ liệu.
- Tìm hiểu kiến trúc của Amazon RDS và hiểu được lợi ích của dịch vụ cơ sở dữ liệu quan hệ được quản lý, bao gồm tự động bảo trì, vá lỗi và hỗ trợ nhiều database engine khác nhau.
- Cải thiện hiểu biết về kiến trúc cloud an toàn khi tìm hiểu cách RDS thường được đặt trong private subnet nhưng vẫn cho phép ứng dụng truy cập một cách phù hợp.
- Xây dựng thành công một hệ thống tải tệp đơn giản tích hợp EC2, S3 và RDS, qua đó củng cố hiểu biết thực tế về cách nhiều dịch vụ AWS có thể phối hợp với nhau trong một ứng dụng hoàn chỉnh.