---
title: "Nhật ký công việc Tuần 3"
date: 2026-01-19
weight: 3
chapter: false
pre: "<b>1.3.</b> "
---

### Mục tiêu tuần:
- Hiểu các kiến thức nền tảng về mạng trong AWS, bao gồm VPC, subnet, route table và gateway.
- Tìm hiểu cách thiết kế ranh giới bảo mật mạng bằng Security Group và Network ACL.
- Thực hành cấu hình truy cập internet cho public subnet và private subnet.
- Xây dựng một kiến trúc nhiều tầng đơn giản trên AWS.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Tìm hiểu các khái niệm của VPC, bao gồm CIDR block, subnet và route table<br>- Hiểu kiến trúc VPC và các thành phần chính của nó | 20/01/2026 | 20/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Tạo một VPC tùy chỉnh<br>- Cấu hình public subnet và private subnet<br>- Thiết lập route table để quản lý luồng mạng giữa các subnet | 21/01/2026 | 21/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Tìm hiểu Security Group và Network ACL<br>- Hiểu sự khác nhau giữa cơ chế lọc stateful và stateless<br>- Cấu hình rule inbound và outbound, đồng thời kiểm tra hành vi lọc lưu lượng | 22/01/2026 | 22/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Thực hành:**<br>&emsp;+ Tạo và gắn Internet Gateway (IGW)<br>&emsp;+ Thiết lập NAT Gateway để private subnet có thể truy cập outbound<br>&emsp;+ Xây dựng kiến trúc nhiều tầng đơn giản gồm web, application và database | 23/01/2026 | 23/01/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần:
- Có được hiểu biết khá vững về các kiến thức mạng cơ bản trong AWS, đặc biệt là cấu trúc và vai trò của Amazon VPC trong kiến trúc cloud.
- Nắm được các khái niệm quan trọng của VPC như CIDR block, public subnet, private subnet, route table và mối liên hệ giữa các thành phần mạng.
- Tạo và cấu hình thành công một môi trường VPC tùy chỉnh, qua đó củng cố hiểu biết thực tế về phân chia mạng trong AWS.
- Hiểu rõ hơn cách route table điều hướng lưu lượng mạng giữa các subnet và ra bên ngoài hệ thống.
- Tìm hiểu Security Group và Network ACL, đồng thời phân biệt được sự khác nhau giữa cơ chế lọc lưu lượng stateful và stateless.
- Thực hành cấu hình các rule inbound và outbound, từ đó hiểu rõ hơn cách kiểm soát và giới hạn lưu lượng ở các lớp khác nhau trong hệ thống mạng.
- Nắm được vai trò của Internet Gateway và NAT Gateway trong việc cung cấp kết nối internet cho tài nguyên ở public subnet và private subnet.
- Xây dựng một kiến trúc nhiều tầng đơn giản với các lớp web, application và database tách biệt, qua đó có thêm kinh nghiệm thực tế trong việc tổ chức tài nguyên cloud theo yêu cầu bảo mật và truy cập.
- Củng cố hiểu biết tổng thể về nguyên tắc thiết kế mạng trên AWS, đặc biệt là trong các khía cạnh phân tách mạng, kiểm soát truy cập và xây dựng kiến trúc cloud an toàn.