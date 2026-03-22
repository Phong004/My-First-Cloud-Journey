---
title: "Worklog Tuần 4"
date: 2026-02-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Nghiên cứu các dịch vụ bảo mật cốt lõi của AWS và thực hành quản trị phân quyền tài khoản.
* Phối hợp cùng hai thành viên còn lại (bạn Web Dev và bạn DevOps) đánh giá hệ thống, chuẩn bị môi trường và kiến trúc để chuyển đổi sang Microservices với Golang.
* Nâng cao kỹ năng kiểm thử bảo mật ứng dụng Web (Penetration Testing) phục vụ cho định hướng chuyên sâu.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Tìm hiểu các dịch vụ bảo mật của AWS như WAF và Cognito.<br> - Đánh giá khả năng tích hợp Cognito cho quản lý người dùng. | 26/01/2026 | 26/01/2026 | [Hiện đại hóa ứng dụng](https://cloudjourney.awsstudygroup.com/vi/4-modernize/) |
| 3 | - Thực hành quản trị quyền truy cập AWS IAM.<br> - Tự tạo các tài khoản IAM user, mò mẫm cấu hình gán Roles và Policies trên môi trường lab cá nhân để nắm vững cơ chế. | 27/01/2026 | 27/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 4 | - Cùng hai thành viên trong nhóm (Web Dev và DevOps) review và chạy thử hệ thống quản lý sự kiện hiện tại.<br> - Thảo luận chiến lược và phương án chuyển đổi kiến trúc sang Microservices để tối ưu hóa việc deploy lên AWS. | 28/01/2026 | 28/01/2026 | Nội bộ nhóm |
| 5 | - Hỗ trợ bạn Web Dev tìm hiểu cách triển khai Microservices.<br> - Tiến hành cài đặt môi trường chạy Golang và tìm hiểu cấu trúc code cơ bản, luồng hoạt động của ngôn ngữ này. | 29/01/2026 | 29/01/2026 | [Go Documentation](https://go.dev/doc/) |
| 6 | - Tự học và trau dồi kỹ năng Penetration Testing.<br> - Nghiên cứu và hoàn thành một số bài học, lab thực hành về lỗ hổng SSRF (Server-Side Request Forgery). | 30/01/2026 | 30/01/2026 | [PortSwigger: SSRF](https://portswigger.net/web-security/ssrf) |

### Kết quả đạt được tuần 4:

* Hiểu rõ Use-case của AWS WAF và Cognito trong kiến trúc bảo mật ứng dụng.
* Nắm được cách khởi tạo IAM User và gán Role thông qua việc tự thực hành trên AWS Console.
* Hoàn tất cài đặt môi trường Golang và chốt được định hướng chuyển đổi sang Microservices cùng hai thành viên trong nhóm.
* Nắm vững cơ chế khai thác cũng như cách phòng chống lỗ hổng bảo mật SSRF thông qua nền tảng PortSwigger.