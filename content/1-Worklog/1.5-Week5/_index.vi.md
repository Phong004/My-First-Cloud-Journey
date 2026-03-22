---
title: "Worklog Tuần 5"
date: 2026-02-08
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Nghiên cứu Amazon API Gateway để kiểm soát luồng giao tiếp và bảo mật các endpoint.
* Phối hợp review mã nguồn, hỗ trợ dựng môi trường container để chạy thử hệ thống nguyên khối (Monolith) trên local.
* Tiếp tục trau dồi kỹ năng Penetration Testing với các lỗ hổng Web phổ biến (XSS, CSRF).

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Tìm hiểu dịch vụ Amazon API Gateway.<br> - Đánh giá cơ chế hoạt động, định tuyến và khả năng tích hợp bảo mật cho các endpoint của kiến trúc Microservices sau này. | 02/02/2026 | 02/02/2026 | [Hiện đại hóa ứng dụng](https://cloudjourney.awsstudygroup.com/4-modernize/) |
| 3 | - Cùng nhóm review mã nguồn hệ thống quản lý sự kiện hiện tại.<br> - Phân tích luồng xử lý logic của bản Monolith để chuẩn bị cho bước bóc tách service. | 03/02/2026 | 03/02/2026 | Phân tích mã nguồn nội bộ |
| 4 | - Chạy thử hệ thống trên môi trường local.<br> - Hỗ trợ bạn DevOps dựng các containers (Docker) để đóng gói và test trực tiếp bản Monolith. | 04/02/2026 | 04/02/2026 | [Docker Documentation](https://docs.docker.com/) |
| 5 | - Tự học chuyên sâu về kiểm thử bảo mật Web.<br> - Nghiên cứu cơ chế khai thác, các biến thể và cách phòng chống lỗ hổng XSS (Cross-Site Scripting). | 05/02/2026 | 05/02/2026 | [PortSwigger: XSS](https://portswigger.net/web-security/cross-site-scripting) |
| 6 | - Tiếp tục hoàn thành các bài học và lab thực hành về lỗ hổng CSRF (Cross-Site Request Forgery) để củng cố kỹ năng. | 06/02/2026 | 06/02/2026 | [PortSwigger: CSRF](https://portswigger.net/web-security/csrf) |

### Kết quả đạt được tuần 5:

* Nắm rõ vai trò và Use-case của Amazon API Gateway trong việc quản lý và bảo vệ API.
* Hoàn tất khâu đánh giá mã nguồn cũ, hỗ trợ team đóng gói thành công hệ thống Monolith vào container để test trên local.
* Hiểu sâu về bản chất kỹ thuật và hoàn thành các bài lab mô phỏng khai thác lỗ hổng XSS và CSRF qua nền tảng PortSwigger.