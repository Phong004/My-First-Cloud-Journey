---
title: "Worklog Tuần 1"
date: 2026-01-11
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:
* Kết nối và làm quen với quy trình làm việc của dự án First Cloud Journey.
* Xây dựng nền tảng cơ bản về môi trường Cloud, nắm vững cách quản trị AWS qua cả giao diện web (Console) và dòng lệnh (AWS CLI).
* Áp dụng các nguyên tắc bảo mật cơ bản ngay từ bước tạo tài khoản (quản lý IAM, thiết lập Billing/Budget để kiểm soát chi phí).

### Các công việc đã triển khai trong tuần:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | - Làm quen với các thành viên FCAJ và môi trường làm việc.<br> - Đọc hiểu các nội quy, quy định và hướng dẫn triển khai dự án tại đơn vị thực tập. | 05/01/2026 | 05/01/2026 | [Nội quy - Hướng dẫn FCAJ](https://rules.fcjuni.com/) |
| 3 | - Lên thư viện nghiên cứu tài liệu và AWS Whitepaper.<br> - Tìm hiểu các khái niệm nền tảng về Cloud Computing và các mô hình triển khai (IaaS, PaaS, SaaS).<br> - Tự tra cứu trên Internet về các thành phần thiết yếu cấu thành hạ tầng Cloud (Compute, Network, Storage, Database). | 06/01/2026 | 06/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 4 | - Khởi tạo tài khoản AWS Free Tier an toàn.<br> - Cài đặt và cấu hình AWS CLI trên môi trường local.<br> - **Thực hành:** Thiết lập Access Key/Secret Key an toàn, cấu hình Region mặc định và test các lệnh CLI cơ bản để truy xuất thông tin. | 07/01/2026 | 07/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 5 | - Nghiên cứu sâu về dịch vụ EC2: <br>&emsp; + Phân biệt các Instance types và AMI. <br>&emsp; + Cơ chế lưu trữ với EBS. <br>&emsp; + Cấu hình Security Group cơ bản.<br> - Tìm hiểu các giao thức remote an toàn (SSH) vào EC2. | 08/01/2026 | 09/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |
| 6 | - **Thực hành:** <br>&emsp; + Khởi tạo một EC2 instance chạy Linux qua Console.<br>&emsp; + Tạo Key Pair và thiết lập kết nối SSH thành công từ terminal local.<br>&emsp; + Gắn và định dạng (format) thêm một EBS volume vào instance đang chạy. | 09/01/2026 | 09/01/2026 | [Khám phá dịch vụ AWS](https://cloudjourney.awsstudygroup.com/vi/1-explore/) |

### Kết quả đạt được tuần 1:

* Đã có cái nhìn tổng quan về hệ sinh thái AWS và hiểu rõ vai trò của các nhóm dịch vụ cơ bản thông qua việc tự nghiên cứu tài liệu.
* Khởi tạo thành công tài khoản AWS Free Tier và nắm được tư duy kiểm soát chi phí ban đầu.
* Cấu hình thành công AWS CLI với các tiêu chuẩn an toàn (Region, Access/Secret Key) để sẵn sàng cho các thao tác tự động hóa.
* Sử dụng thành thạo AWS CLI để thực thi các tác vụ quản trị cốt lõi:
  * Kiểm tra cấu hình và định danh tài khoản (`aws sts get-caller-identity`).
  * Truy vấn danh sách region và các dịch vụ đang hoạt động.
  * Quản lý vòng đời của Key Pair.
* Hoàn thành lab thực hành: Khởi tạo EC2 Linux, cấu hình rule SSH an toàn trong Security Group, kết nối thành công qua terminal và thao tác mount EBS volume vào hệ điều hành.