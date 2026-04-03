---
title: "Worklog Tuần 2"
date: 2026-01-18
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Nâng cao kiến thức về hạ tầng mạng (Networking) trên AWS làm tiền đề cho việc triển khai các ứng dụng thực tế.
* Bắt tay vào thực hành dự án FCAJ-Serverless-Workshop, làm quen với môi trường Node.js và cách xử lý các sự cố về dependencies.
* Khởi động dự án FPT Event Management: Lên ý tưởng, chốt công nghệ và thiết kế kiến trúc hệ thống sơ bộ.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Nghiên cứu chuyên sâu về AWS Networking (VPC): <br>&emsp; + Kiến trúc Subnet (Public/Private).<br>&emsp; + Cấu hình Route Table và Internet Gateway (IGW). | 12/01/2026 | 12/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 3 | - Bắt đầu tiếp cận dự án **FCAJ-Serverless-Workshop**.<br> - Clone source code, tìm hiểu luồng hoạt động của mã nguồn và các thành phần Serverless cốt lõi. | 13/01/2026 | 13/01/2026 | [Hiện đại hóa ứng dụng](https://cloudjourney.awsstudygroup.com/vi/4-modernize/) |
| 4 | - **Xử lý sự cố:** Gặp lỗi xung đột phiên bản thư viện (dependency conflict) khi cài đặt môi trường cho dự án bằng `npm`.<br> - Tự tra cứu và khắc phục thành công bằng cách sử dụng cờ `npm install --legacy-peer-deps`.<br> - Tìm hiểu thêm về mục đích của lệnh `yarn` và quy trình build project. | 14/01/2026 | 14/01/2026 | StackOverflow & Docs |
| 5 | - Khởi động dự án **FPT Event Management**.<br> - Phân tích yêu cầu bài toán quản lý vé và sự kiện.<br> - Chốt công nghệ (Tech stack): Backend Java Web App, Frontend React, Database SQL Server và Supabase để lưu trữ file. | 15/01/2026 | 15/01/2026 | Nội bộ nhóm |
| 6 | - Phác thảo sơ đồ kiến trúc hệ thống cho FPT Event Management.<br> - Tìm hiểu sơ bộ về các phương án deploy hệ thống này lên AWS để chuẩn bị cho các tuần tiếp theo. | 16/01/2026 | 16/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) & Draw.io |

### Kết quả đạt được tuần 2:

* Nắm vững cách luồng dữ liệu di chuyển trong AWS VPC và cách phân lập mạng bằng Public/Private Subnet.
* Cài đặt thành công môi trường cho dự án FCAJ-Serverless-Workshop. 
* Thể hiện được kỹ năng problem-solving thực tế khi tự rà soát và khắc phục triệt để lỗi xung đột peer dependencies của Node.js.
* Phân tích và thiết kế thành công kiến trúc tổng thể cho hệ thống FPT Event Management, xác định rõ vai trò của từng công nghệ trong dự án.