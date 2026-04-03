---
title: "Worklog Tuần 12"
date: 2026-04-05
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Tiến hành kiểm thử lại (Re-test) các lỗ hổng đã được báo cáo trên môi trường Local để nghiệm thu quá trình vá lỗi (Patching) của đội phát triển.
* Đóng gói toàn bộ tài liệu, viết báo cáo tổng kết kỳ thực tập và đề xuất hướng phát triển bảo mật tiếp theo khi hệ thống Go-Live.

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Tiến hành Re-test các lỗ hổng nghiêm trọng (INF-01, BE-01).<br> - Xác nhận team Dev đã cấu hình lại mật khẩu Database và áp dụng JWT cho các luồng giao tiếp nội bộ thay vì dùng Header tĩnh. | 30/03/2026 | 30/03/2026 | Môi trường Local |
| 3 | - Re-test các lỗi phía Frontend (FE-01) và Backend (BE-02, BE-03, BE-04).<br> - Ghi nhận trạng thái xử lý (Closed) cho các lỗi đã vá và thống nhất các rủi ro chấp nhận được (Accepted Risks) trong giai đoạn hiện tại. | 31/03/2026 | 31/03/2026 | Công cụ Burp Suite, ZAP |
| 4 | - Hoàn thiện Báo cáo thực tập cá nhân.<br> - Tổng hợp kinh nghiệm xử lý sự cố và bổ sung mục "Hạn chế & Hướng phát triển" (đề xuất kế hoạch Pentest toàn diện sau khi hạ tầng AWS hoàn thiện). | 01/04/2026 | 01/04/2026 | Tài liệu cá nhân |
| 5 | - Tổ chức họp nhóm tổng kết (Retrospective) chặng đường 3 tháng thực tập.<br> - Bàn giao lại toàn bộ bộ test-case và tài liệu bảo mật cho team lưu trữ. | 02/04/2026 | 02/04/2026 | Kho lưu trữ nội bộ |
| 6 | - Rà soát lại toàn bộ Worklog, kiểm tra format báo cáo theo đúng chuẩn của chương trình.<br> - Hoàn tất thủ tục, nộp hồ sơ đánh giá thực tập cho First Cloud Journey. | 03/04/2026 | 03/04/2026 | [Quy định FCAJ](https://rules.fcjuni.com/) |

### Kết quả đạt được tuần 12:

* Hoàn thành quy trình đóng vòng đời lỗ hổng (Closed-loop) bằng việc Re-test và nghiệm thu thành công các bản vá bảo mật trên môi trường Local.
* Xây dựng rõ ràng lộ trình bảo mật tiếp theo cho dự án khi triển khai lên Cloud.
* Hoàn tất trọn vẹn 100% khối lượng công việc và hồ sơ của kỳ thực tập kéo dài 3 tháng tại FCAJ.