---
title: "Worklog Tuần 7"
date: 2026-03-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

*(Ghi chú: Bao gồm cả khối lượng công việc tự học trong kỳ nghỉ Tết Nguyên đán từ 16/02 - 20/02/2026)*

### Mục tiêu tuần 7:

* Đánh giá tiến độ dự án sau Tết và thống nhất mốc thời gian kiểm thử (Pentest) cho hệ thống.
* Hoàn thiện kiến thức nền tảng Web Application, kỹ năng đánh chặn (intercept) HTTP traffic và thu thập thông tin mục tiêu theo lộ trình HackTheBox (HTB).

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Họp nhóm đầu năm đánh giá tiến độ.<br> - Review phiên bản "Distributed Monolith" do Web Dev hoàn thiện trong Tết.<br> - Thống nhất hoãn quy trình Pentest cho đến khi hệ thống chuyển sang Microservices hoàn chỉnh. | 23/02/2026 | 23/02/2026 | Biên bản họp nhóm |
| 3 | - Tổng hợp kiến thức tự học từ các module **Web Requests** và **Introduction to Web Applications**.<br> - Nắm vững cấu trúc HTTP/HTTPS, các method cơ bản và vòng đời của một ứng dụng Web. | 24/02/2026 | 24/02/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 4 | - Hoàn thành module **Using Web Proxies**.<br> - Cấu hình và sử dụng thành thạo proxy (Burp Suite, OWASP ZAP) để đánh chặn và can thiệp luồng request/response. | 25/02/2026 | 25/02/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 5 | - Hoàn thành module **Information Gathering - Web Edition**.<br> - Thực hành kỹ thuật passive/active recon, dò quét subdomain và phát hiện công nghệ lõi của mục tiêu. | 26/02/2026 | 26/02/2026 | [HTB Academy](https://academy.hackthebox.com/) |
| 6 | - Vận dụng kỹ năng Proxies và Recon để thu thập thông tin (mapping) các endpoint trên bản Distributed Monolith đang chạy local mà chưa thực hiện tấn công sâu. | 27/02/2026 | 27/02/2026 | Local Environment |

### Kết quả đạt được tuần 7:

* Chốt chiến lược Pentest hợp lý, tránh lãng phí effort vào kiến trúc tạm thời.
* Nắm vững nền tảng Web Application và làm chủ kỹ năng thao tác với Web Proxies.
* Hoàn thành xuất sắc quy trình Information Gathering, tạo tiền đề vững chắc cho việc tìm kiếm lỗ hổng ở các giai đoạn sau.