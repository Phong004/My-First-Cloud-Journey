---
title: "Worklog Tuần 6"
date: 2026-02-15
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Thực hành cấu hình luồng định tuyến cơ bản với Amazon API Gateway.
* Rà quét lỗ hổng bảo mật trên môi trường container và tổng hợp báo cáo đánh giá hệ thống cũ.
* Chốt sổ công việc cá nhân, rà soát và dọn dẹp tài nguyên AWS để tối ưu chi phí trước kỳ nghỉ Tết Nguyên đán.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Thực hành tạo và cấu hình các endpoint thử nghiệm (Mock API) trên Amazon API Gateway.<br> - Kiểm tra luồng request/response cơ bản để chuẩn bị tích hợp với backend Golang. | 09/02/2026 | 09/02/2026 | [Hiện đại hóa ứng dụng](https://cloudjourney.awsstudygroup.com/4-modernize/) |
| 3 | - Ứng dụng công cụ Trivy để rà quét lỗ hổng bảo mật (Vulnerability Scanning) trên các Docker image của hệ thống Monolith đang chạy local.<br> - Ghi nhận các gói thư viện lỗi thời cần cập nhật. | 10/02/2026 | 10/02/2026 | [Trivy Documentation](https://aquasecurity.github.io/trivy/) |
| 4 | - Lập báo cáo đánh giá bảo mật tổng quan cho hệ thống cũ.<br> - Xây dựng Security Checklist cho kiến trúc Microservices mới (tập trung vào xác thực JWT, chống XSS và CSRF). | 11/02/2026 | 11/02/2026 | Tài liệu dự án |
| 5 | - Tổng hợp và đẩy (push) các báo cáo, tài liệu bảo mật lên kho lưu trữ chung của dự án.<br> - Tự rà soát và lên kế hoạch các task kiểm thử (Pentest) cá nhân cần thực hiện ngay sau kỳ nghỉ lễ. | 12/02/2026 | 12/02/2026 | Kho lưu trữ nội bộ |
| 6 | - Kiểm tra dashboard AWS Billing.<br> - Rà soát và tắt (stop/terminate) các EC2 instance cùng những tài nguyên không thiết yếu để ngăn chặn phát sinh chi phí trong thời gian nghỉ Tết dài ngày. | 13/02/2026 | 13/02/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/1-explore/) |

### Kết quả đạt được tuần 6:

* Nắm được thao tác cấu hình thực tế trên Amazon API Gateway.
* Hoàn thành rà quét bảo mật container bằng Trivy, thiết lập tiêu chuẩn an toàn (Security Checklist) cho chặng đường code Microservices sắp tới.
* Hoàn thiện hệ thống tài liệu bảo mật và lên kế hoạch công việc cá nhân sẵn sàng cho giai đoạn sau Tết.
* Quản lý tốt chi phí Cloud, đảm bảo môi trường AWS an toàn và không phát sinh rủi ro tài chính trong kỳ nghỉ lễ.