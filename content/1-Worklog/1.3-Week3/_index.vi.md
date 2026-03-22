---
title: "Worklog Tuần 3"
date: 2026-01-25
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Nghiên cứu chuyên sâu dịch vụ lưu trữ, database AWS (S3, RDS, Aurora) và quản trị phân quyền (IAM, Policy Statement).
* Đánh giá kiến trúc web hiện tại (Monolith) và lên kế hoạch chuyển đổi sang Microservices.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Nghiên cứu AWS S3 (Storage Classes, versioning).<br> - Tìm hiểu và so sánh ưu/nhược điểm của RDS và Aurora. | 19/01/2026 | 19/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 3 | - Nghiên cứu sâu quyền truy cập AWS IAM.<br> - Phân tích cấu trúc Policy Statement (Effect, Action, Resource, Condition) để áp dụng Least Privilege. | 20/01/2026 | 20/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 4 | - Review hệ thống quản lý sự kiện hiện tại (Monolith).<br> - Đánh giá các điểm nghẽn và hạn chế về mở rộng (scalability). | 21/01/2026 | 21/01/2026 | Phân tích mã nguồn nội bộ |
| 5 | - Thảo luận phương án chuyển đổi kiến trúc từ Monolith sang Microservices.<br> - Chốt dùng Golang viết lại backend services để tối ưu hiệu năng và xử lý đồng thời (concurrency). | 22/01/2026 | 22/01/2026 | [Hiện đại hóa ứng dụng](https://cloudjourney.awsstudygroup.com/vi/4-modernize/) |
| 6 | - Phác thảo tài liệu kiến trúc mới.<br> - Lên danh sách các service cần tách và định tuyến luồng giao tiếp. | 23/01/2026 | 23/01/2026 | Draw.io & Docs |

### Kết quả đạt được tuần 3:

* Nắm vững cơ chế và Use-case của S3, RDS, Aurora.
* Biết cách đọc/viết IAM Policy Statement để phân quyền AWS bảo mật.
* Hoàn tất đánh giá hệ thống cũ, chốt phương án chuyển đổi sang Microservices.
* Thống nhất đưa Golang vào backend để giải quyết bài toán hiệu năng.