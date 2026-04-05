---
title: "Cloud Mastery 2026: #2 IaC, K8s & DevOps"
date: 2026-04-04
weight: 3
chapter: false
pre: " <b> 3.3. </b> "
---

### Mục Đích Của Sự Kiện

- Chuyển đổi tư duy quản trị hạ tầng từ thủ công (ClickOps) sang tự động hóa hoàn toàn bằng mã nguồn (Infrastructure as Code - IaC).
- Cung cấp cái nhìn toàn cảnh về kiến trúc Cloud Native thông qua nền tảng điều phối container hàng đầu là Kubernetes (K8s).
- Giới thiệu ngôn ngữ lập trình Elixir và máy ảo BEAM, giải pháp tối ưu cho các hệ thống DevOps đòi hỏi tính đồng thời (Concurrency) và khả năng chịu lỗi (Fault-Tolerance) cao.

### Danh Sách Diễn Giả

- **Anh Nguyễn Thịnh** - FCAJ Cloud Engineer Trainee.
- **Anh Huỳnh Bảo** - Junior Cloud Native Developer tại Endava Vietnam / Founder ITea Lab.
- **AnhNguyễn Tạ Minh Triết** - R&D Member tại ITea Lab / SAP Developer Intern.

### Nội Dung Nổi Bật

#### Infrastructure as Code (IaC) với Terraform
- **Từ ClickOps đến Code:** Phân tích những hạn chế của việc cấu hình thủ công như tốc độ chậm, dễ sai sót do con người và khó cộng tác.
- **Quy trình làm việc với Terraform:** Hướng dẫn các lệnh cơ bản (`init`, `plan`, `apply`, `destroy`) và cách quản lý trạng thái tài nguyên qua file `terraform.tfstate`.
- **Thực hành mô phỏng:** Sử dụng LocalStack để giả lập môi trường AWS ngay trên máy local và demo cấu trúc thư mục Terraform nâng cao chia theo module và môi trường (dev/prod).

#### Kiến trúc Cloud Native với Kubernetes (K8s)
- **Kiến trúc K8s:** Đi sâu vào Control Plane và Worker Nodes, giải thích cơ chế vận hành của kube-apiserver, etcd và kubelet.
- **Quản lý Kubernetes Objects:** Làm rõ chức năng của Pods, Deployments, Services, ConfigMaps và đặc biệt là cách K8s xử lý Secrets.
- **Hệ sinh thái công cụ:** Giới thiệu Helm để đóng gói ứng dụng (Charts) và K9s để giám sát cluster trực tiếp qua terminal.

#### Elixir và Triết lý "Let It Crash" trong DevOps
- **Sức mạnh của BEAM VM:** Giải thích cách Elixir chạy trên máy ảo BEAM giúp hệ thống xử lý hàng triệu tiến trình nhẹ mà không tốn nhiều tài nguyên.
- **Khả năng chịu lỗi (Fault-Tolerance):** Tìm hiểu cơ chế Supervisor để theo dõi và tự động khởi động lại tiến trình khi có lỗi, giúp hệ thống luôn trong trạng thái sẵn sàng cao.

### Những Gì Học Được

#### Tư Duy Kỹ Thuật
- Nắm vững quy trình triển khai hạ tầng tự động hóa, giúp loại bỏ các rủi ro cấu hình sai lệch giữa các môi trường.
- Hiểu rõ cách thức container orchestration vận hành để quản lý các hệ thống Microservices quy mô lớn.

#### Nhận thức về Bảo mật
- **Rủi ro lộ lọt thông tin nhạy cảm:** Nhận diện nguy cơ từ file `terraform.tfstate` nếu không được bảo vệ kỹ lưỡng có thể chứa secrets ở dạng plaintext.
- **Lỗ hổng cấu hình K8s:** Nhận ra rằng K8s Secrets mặc định chỉ mã hóa Base64 chứ không được mã hóa bảo mật, đòi hỏi phải có các giải pháp quản lý secret chuyên dụng như HashiCorp Vault.

### Ứng Dụng Vào Công Việc

- **Tối ưu Pentest Workflow:** Ứng dụng tư duy IaC để xây dựng các kịch bản Lab tấn công/phòng thủ nhanh chóng và nhất quán cho đồ án *FPT Event Management System*.
- **Kiểm thử môi trường Container:** Kiến thức về K8s giúp tôi xây dựng các test cases mới nhắm vào cấu hình RBAC (Role-Based Access Control) và kiểm tra khả năng thoát khỏi vùng chứa (Container Escape) trong môi trường Cloud Native.
- **Nâng cấp tư duy Red Team:** Việc thấu hiểu triết lý "Let It Crash" của Elixir giúp tôi nhận thức được các bề mặt tấn công mới vào logic chịu lỗi của hệ thống, từ đó thiết kế các kịch bản mô phỏng tấn công sâu hơn vào tầng ứng dụng thay vì chỉ dừng lại ở tầng mạng.

### Trải nghiệm trong sự kiện

Sự kiện diễn ra tại Tầng 26 tháp Bitexco mang lại một không gian thảo luận công nghệ sôi nổi và đậm chất kỹ thuật.

#### Cầu nối giữa Lý thuyết và Thực tiễn
- Các buổi live demo về LocalStack và Terraform giúp tôi chuyển hóa lý thuyết thành các bài học thực tiễn, dễ dàng hình dung cách các dịch vụ AWS tương tác với nhau bên dưới hạ tầng.

#### Bài học đọng lại
- Để trở thành một Pentester xuất sắc trên Cloud, việc nắm rõ cách các Builder xây dựng hạ tầng bằng mã nguồn (IaC) và điều phối hệ thống (K8s) là điều kiện bắt buộc. Hiểu được "mã nguồn của hạ tầng" chính là hiểu được con đường ngắn nhất dẫn đến điểm yếu của hệ thống.

#### Minh chứng tham gia sự kiện

![Cloud Mastery 2026 #2](/images/3-EventParticipated/event-image-3.3.jpg)

> Tổng kết lại, sự kiện "Cloud Mastery #2" không chỉ cung cấp nền tảng kiến thức vững chắc về kiến trúc Cloud Native mà còn giúp tôi nhìn nhận các rủi ro bảo mật mới trong việc quản lý hạ tầng, hỗ trợ trực tiếp cho định hướng theo đuổi ngành An toàn thông tin.