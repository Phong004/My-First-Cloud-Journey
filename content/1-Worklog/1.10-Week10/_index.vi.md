---
title: "Worklog Tuần 10"
date: 2026-03-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Áp dụng tư duy Shift-Left Security, tiến hành kiểm thử bảo mật (Pentest) toàn diện trên bản Microservices vừa được deploy ở môi trường Local Docker.
* Nhận diện, khai thác và lập báo cáo các lỗ hổng theo chuẩn OWASP Top 10 để team khắc phục trước khi đưa lên AWS.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Tiến hành rà quét (Recon) mục tiêu `fptevent.local`. Phát hiện lỗi bộc lộ port hạ tầng (8081-8086) và Database (3306).<br> - Khai thác lỗi truy cập MySQL, dùng Hashcat bẻ khóa ngoại tuyến (Offline Cracking) chứng minh lỗi băm mật khẩu yếu. | 16/03/2026 | 16/03/2026 | Môi trường Local / Công cụ Nmap, Hashcat |
| 3 | - Dùng Burp Suite kiểm thử API: Bypass xác thực nội bộ qua header `x-internal-call` và phát hiện lỗi thiếu Rate Limiting ở tính năng Quên mật khẩu.<br> - Dùng OWASP ZAP đánh giá Frontend: Khai thác lỗi lộ lọt Source Code và leo thang đặc quyền Client-side qua LocalStorage. | 17/03/2026 | 17/03/2026 | Công cụ Burp Suite, OWASP ZAP |
| 4 | - Tổng hợp các bằng chứng (PoC) và đánh giá mức độ rủi ro.<br> - Hoàn thiện "Báo cáo Kiểm thử Bảo mật" chi tiết, đưa ra khuyến nghị sửa lỗi (mã hóa đường truyền, quản lý biến môi trường, bảo mật Token). | 18/03/2026 | 18/03/2026 | Tài liệu dự án |
| 5 | - Trực tiếp bàn giao Báo cáo Kiểm thử cho đội ngũ phát triển. Theo dõi, đôn đốc tiến độ phân tích nguyên nhân (Root Cause) và lên phương án vá lỗi (Patching) thông qua các kênh trao đổi nội bộ của nhóm. | 19/03/2026 | 19/03/2026 | Báo cáo Pentest |
| 6 | - Hỗ trợ team rà soát lại các bản vá bảo mật vừa được cập nhật.<br> - Cùng DevOps lên kế hoạch thiết lập Security Group và AWS WAF chuẩn bị cho giai đoạn đưa hệ thống lên Production. | 20/03/2026 | 20/03/2026 | Nội bộ nhóm |

### Kết quả đạt được tuần 10:

* Thực hiện thành công đợt Pentest thực chiến (Black-box/Grey-box) trên kiến trúc Microservices của dự án.
* Phát hiện và khai thác (PoC) thành công 4 nhóm lỗ hổng nghiêm trọng từ Hạ tầng, Backend đến Frontend theo chuẩn OWASP.
* Hoàn thiện Báo cáo Kiểm thử Bảo mật chuyên nghiệp, cung cấp giải pháp vá lỗi kịp thời.
* Đảm bảo hệ thống đạt tiêu chuẩn an toàn cơ bản trước khi chính thức đưa lên môi trường AWS Cloud.