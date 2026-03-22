---
title: "Worklog Tuần 8"
date: 2026-03-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Nâng cao kỹ năng dò quét (Fuzzing) thư mục và tham số ẩn trên ứng dụng Web.
* Phân tích mã nguồn client-side và thực hành khai thác lỗ hổng Cross-Site Scripting (XSS) theo lộ trình chuyên sâu.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Bám sát lộ trình HTB, hoàn thành module **Web Fuzzing**.<br> - Sử dụng ffuf/gobuster để brute-force thư mục ẩn, tham số (parameters) và vhost nhằm mở rộng attack surface. | 02/03/2026 | 02/03/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 3 | - Hoàn thành module **JavaScript Deobfuscation**.<br> - Phân tích, đảo ngược mã JS bị làm rối (obfuscated) phía client để tìm kiếm endpoint ẩn và thông tin nhạy cảm. | 03/03/2026 | 03/03/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 4 | - Hoàn thành module **Cross-Site Scripting (XSS)**.<br> - Khai thác thành công các kịch bản Reflected, Stored và DOM-based XSS, kèm kỹ thuật bypass filter cơ bản. | 04/03/2026 | 04/03/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 5 | - Đọc trước tài liệu lý thuyết chuẩn bị cho các module tiếp theo trong Job Path (**SQL Injection Fundamentals** và **SQLMap Essentials**) để sẵn sàng cho tuần học mới. | 05/03/2026 | 05/03/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 6 | - Dựa trên kiến thức HTB, lập kịch bản kiểm thử (Test cases) chi tiết kết hợp Recon, Fuzzing và XSS sẵn sàng áp dụng vào hệ thống Microservices sắp ra mắt của team. | 06/03/2026 | 06/03/2026 | Kế hoạch cá nhân |

### Kết quả đạt được tuần 8:

* Mở khóa và hoàn thành xuất sắc 3 modules kỹ thuật tấn công chuyên sâu trên HTB Academy.
* Thành thạo quy trình Web Fuzzing, nâng cấp kỹ năng phân tích mã nguồn client-side (JS Deobfuscation) và khai thác XSS.
* Xây dựng xong chiến lược kiểm thử bảo mật toàn diện chuẩn bị cho đợt deploy Microservices chính thức của dự án sự kiện.