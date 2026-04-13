---
title: "Nhật ký công việc Tuần 6"
date: 2026-03-02
weight: 6
chapter: false
pre: "<b>1.6.</b> "
---

### Mục tiêu tuần:
- Hiểu cơ chế nhắn tin của SQS và SNS trong AWS.
- Tìm hiểu cách sử dụng EventBridge để định tuyến sự kiện.
- Khám phá Step Functions để điều phối workflow của ứng dụng.
- Xây dựng kiến trúc hướng sự kiện bằng các dịch vụ tích hợp của AWS.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Tìm hiểu kiến thức cơ bản về SQS<br>- Hiểu SNS và mô hình pub/sub<br>- So sánh các trường hợp sử dụng của SQS và SNS | 03/03/2026 | 03/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Nghiên cứu kiến thức cơ bản về EventBridge<br>- Tìm hiểu cách định tuyến sự kiện<br>- Thực hành tạo rule và target | 04/03/2026 | 04/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Tìm hiểu Step Functions<br>- Hiểu state machine và cơ chế điều phối task<br>- Thực hành thiết kế workflow đơn giản | 05/03/2026 | 05/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Thực hành:**<br>&emsp;+ Tạo thành phần messaging bằng SQS và SNS<br>&emsp;+ Cấu hình EventBridge rules<br>&emsp;+ Điều phối workflow với Step Functions | 06/03/2026 | 06/03/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần:
- Có được hiểu biết khá vững về AWS SQS và SNS, bao gồm cách giao tiếp bằng hàng đợi và mô hình publish/subscribe trong hệ thống phân tán.
- Phân biệt được SQS và SNS, đồng thời xác định được các trường hợp sử dụng phù hợp của từng dịch vụ trong tích hợp bất đồng bộ.
- Tìm hiểu EventBridge và hiểu cách dịch vụ này được dùng để định tuyến sự kiện giữa các dịch vụ AWS và các thành phần ứng dụng tùy chỉnh một cách linh hoạt và có khả năng mở rộng.
- Nắm được kiến thức cơ bản về Step Functions, bao gồm cách workflow được mô hình hóa bằng state machine để điều phối nhiều bước xử lý.
- Thực hành thiết kế các workflow và mô hình định tuyến sự kiện đơn giản, qua đó cải thiện hiểu biết về orchestration và giao tiếp giữa các dịch vụ.
- Tích hợp SQS, SNS, EventBridge và Step Functions trong một kiến trúc hướng sự kiện cơ bản để quan sát cách các dịch vụ này phối hợp trong thực tế.
- Củng cố kỹ năng xây dựng hệ thống loosely coupled, nơi các thành phần giao tiếp với nhau thông qua message và event thay vì gọi trực tiếp đồng bộ.
- Nâng cao hiểu biết tổng thể về các mẫu tích hợp ứng dụng trên AWS, đặc biệt trong các khía cạnh xử lý bất đồng bộ, tự động hóa workflow và thiết kế hệ thống hướng sự kiện.