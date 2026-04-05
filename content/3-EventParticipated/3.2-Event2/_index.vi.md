---
title: "Cloud Mastery 2026: #1 AI From Scratch"
date: 2026-03-14
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---

### Mục Đích Của Sự Kiện

- Trang bị kiến thức nền tảng và nâng cao về Kỹ thuật Lời nhắc (Prompt Engineering) nhằm tối ưu hóa chi phí token và giảm thiểu hiện tượng ảo giác khi làm việc với AI.
- Tìm hiểu cách thức xây dựng Tác nhân AI (AI Agents), cụ thể là Strands Agents, với khả năng tự lập kế hoạch và tương tác với các công cụ bên ngoài.
- Khám phá các mô hình ứng dụng AI kết hợp IoT (AIoT) thông qua các dự án thực tế triển khai trên nền tảng đám mây AWS.

### Danh Sách Diễn Giả

- **Anh Lê Hoàng Đinh** - AI Engineer.
- **Anh Bành Cầm Vĩnh** - Data Engineer.
- **Anh Nguyễn Tuấn Thịnh** - DevOps Engineer.

### Nội Dung Nổi Bật

#### Kỹ thuật Gợi ý Tự động (Automated Prompt Engineering)
- **Token Economics:** Phân tích chi phí thực tế khi sử dụng LLM. Ví dụ, chi phí đầu ra của Claude Opus đắt gấp 5 lần chi phí đầu vào ($25.00 so với $5.00 trên 1 triệu tokens). Việc viết prompt chung chung sẽ gây lãng phí tài nguyên lớn.
- **7 Nguyên tắc cốt lõi:** Cần sử dụng dấu phân cách (Delimiters), tập trung vào các việc CẦN làm (DOs), và cho phép mô hình trả lời "Tôi không biết" để tránh ảo giác (Hallucination).

#### Xây dựng Tác nhân AI (Strands Agent)
- Giới thiệu khái niệm AI Agent với khả năng suy luận đa bước và giao thức Agent-as-tools giúp các Agent hợp tác với nhau.
- Tìm hiểu vòng lặp Agentic Loop để gọi công cụ (APIs, Database) và tích hợp Knowledge Base.

#### Hệ sinh thái AIoT trên AWS Cloud
- **Dự án Locker Management:** Trình diễn hệ thống quản lý tủ đồ tự động sử dụng thiết bị biên (Arduino, Raspberry Pi) giao tiếp qua MQTT Broker.
- Kiến trúc tích hợp AWS IoT Core với AWS Rekognition để nhận diện khuôn mặt và AWS Lambda xử lý logic tự động.

### Những Gì Học Được

#### Tư Duy Kỹ Thuật
- Nắm vững cấu trúc của một Prompt chuẩn bao gồm 7 thành phần: Role, Instruction, Context, Input Data, Output Format, Examples, và Constraints.
- Hiểu được sự dịch chuyển từ AI tương tác thuần túy sang AI tự chủ (Agents) có khả năng thao tác với thế giới vật lý qua API.

#### Nhận thức về Bảo mật
- Quá trình AI Agent gọi API hệ thống và lấy dữ liệu thời gian thực tiềm ẩn rủi ro lớn về bảo mật. Nếu không kiểm soát phân quyền (IAM) chặt chẽ, hacker có thể tiêm nhiễm lời nhắc (Prompt Injection) để đánh lừa Agent thực thi mã độc.

### Ứng Dụng Vào Công Việc

- **Tối ưu Pentest Workflow:** Áp dụng các kỹ thuật nâng cao như Chain-of-Thought (CoT) để dùng LLM hỗ trợ viết kịch bản khai thác lỗ hổng và tổng hợp tự động "Báo cáo Kiểm thử Bảo mật" cho đồ án FPT Event Management System.
- **Bảo mật IoT & Cloud:** Kiến thức từ dự án Locker Management giúp tôi hiểu rõ luồng giao tiếp giữa thiết bị IoT và AWS Cloud, từ đó xây dựng các test cases đánh giá cấu hình mạng nội bộ và API Gateway.
- **Mở rộng Red Teaming:** Nghiên cứu sâu hơn về Strands Agents để phục vụ việc lập trình các tác nhân tự động thu thập thông tin mục tiêu (Reconnaissance) trong các chiến dịch tấn công mô phỏng sau này.

### Trải nghiệm trong sự kiện

Sự kiện diễn ra tại Tầng 26 tháp Bitexco mang lại cảm hứng học tập và làm việc trong không gian văn phòng. 

#### Đào sâu vào kỷ luật lập trình
- Việc hiểu về chi phí đầu ra/đầu vào (Token Economics) nhắc nhở tôi rằng: Trong môi trường Cloud, một dòng lệnh lỏng lẻo không chỉ gây lỗi logic mà còn gây thiệt hại trực tiếp về tài chính.

#### Minh chứng tham gia sự kiện

![Cloud Mastery 2026](/images/3-EventParticipated/0S0A0016.jpg)

> Tổng kết lại, sự kiện "Cloud Mastery 2026" không chỉ cung cấp nền tảng kiến thức vững chắc về GenAI mà còn giúp tôi nhìn nhận các rủi ro bảo mật mới trong kỷ nguyên AI tự chủ, hỗ trợ trực tiếp cho định hướng theo đuổi ngành An toàn thông tin.