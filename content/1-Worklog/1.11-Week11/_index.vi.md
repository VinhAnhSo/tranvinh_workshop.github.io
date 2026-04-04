---
title: "Nhật ký công việc Tuần 11"
date: 2026-04-06
weight: 11
chapter: false
pre: "<b>1.11.</b> "
---

### Mục tiêu tuần:
- Hiểu AWS WAF và Shield để bảo vệ ứng dụng.
- Tìm hiểu cách quản lý thông tin nhạy cảm bằng AWS Secrets Manager.
- Khám phá AWS Certificate Manager để quản lý chứng chỉ SSL/TLS.
- Xây dựng môi trường production an toàn bằng các dịch vụ bảo mật của AWS.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Tìm hiểu AWS WAF<br>- Hiểu các rule bảo vệ web application<br>- Khám phá các kịch bản lọc truy cập phổ biến | 07/04/2026 | 07/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Nghiên cứu AWS Shield<br>- Tìm hiểu khái niệm bảo vệ DDoS<br>- Hiểu cách Shield hỗ trợ tính sẵn sàng và khả năng chống chịu của ứng dụng | 08/04/2026 | 08/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Tìm hiểu AWS Secrets Manager<br>- Thực hành lưu trữ và truy xuất secrets an toàn<br>- Hiểu cơ chế xoay vòng secrets và bảo vệ thông tin xác thực | 09/04/2026 | 09/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Thực hành:**<br>&emsp;+ Cấu hình rule bảo vệ với AWS WAF<br>&emsp;+ Quản lý secrets bằng Secrets Manager<br>&emsp;+ Cấp phát chứng chỉ bằng AWS Certificate Manager | 10/04/2026 | 10/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần:
- Có được hiểu biết tốt hơn về các dịch vụ bảo mật nâng cao trong AWS và cách chúng góp phần bảo vệ môi trường production khỏi các mối đe dọa bên ngoài cũng như sai sót cấu hình nội bộ.
- Hiểu chức năng cốt lõi của AWS WAF và cách các rule truy cập web có thể được dùng để lọc lưu lượng độc hại, hạn chế request không mong muốn và tăng cường bảo mật ở tầng ứng dụng.
- Tìm hiểu AWS Shield và nắm được các khái niệm bảo vệ DDoS, bao gồm cách AWS hỗ trợ duy trì tính sẵn sàng của dịch vụ trước các tình huống tấn công quy mô lớn.
- Hiểu rõ hơn mối quan hệ giữa AWS WAF và Shield trong bối cảnh triển khai mô hình bảo mật nhiều lớp cho ứng dụng public-facing.
- Tìm hiểu AWS Secrets Manager và hiểu cách các thông tin nhạy cảm như API key, mật khẩu hay chuỗi kết nối có thể được lưu trữ và quản lý an toàn thay vì hardcode trong ứng dụng.
- Củng cố nhận thức về các best practices trong xử lý secrets, bao gồm kiểm soát truy cập, lưu trữ tập trung và xoay vòng định kỳ.
- Khám phá AWS Certificate Manager và hiểu cách chứng chỉ SSL/TLS được cấp phát, quản lý và áp dụng để hỗ trợ kết nối được mã hóa trong môi trường cloud.
- Xây dựng được môi trường production an toàn ở mức cơ bản, kết hợp bảo vệ ứng dụng, quản lý thông tin nhạy cảm và hỗ trợ mã hóa đường truyền.