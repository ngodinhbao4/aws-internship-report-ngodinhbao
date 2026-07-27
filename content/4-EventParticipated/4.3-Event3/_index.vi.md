---
title: "Event3: FCAJ x Agentic AI Build Week"
date: 2026-07-25
weight: 4
chapter: false
pre: " <b> 4.3. </b> "
---

{{% notice info %}}
💡 **Tổng quan:** Cuộc thi Hackathon FCAJ x Agentic AI Build Week tháng 7/2026 — đồng tổ chức cùng quỹ đầu tư JI Fund — đã đóng vai trò là một trung tâm đổi mới sáng tạo và kết nối mạnh mẽ. Sự kiện quy tụ các builder, sinh viên và chuyên gia tư vấn nhằm biến những ý tưởng AI táo bạo thành các giải pháp điện toán đám mây sẵn sàng đưa vào vận hành. Các phiên chia sẻ đã làm nổi bật những ứng dụng thực tế của AI Agent, kiến trúc Serverless toàn diện trên AWS, mô hình Multi-Agent, cùng các bài học thực chiến về triển khai kỹ thuật và thuyết trình sản phẩm (pitching).
{{% /notice %}}

# Báo cáo Sự kiện: “FCAJ x Agentic AI Build Week: Show Up. Build. Pitch. WIN!”

### Mục tiêu Sự kiện

- **Tiếp cận Tư duy Agentic (Agentic Mental Model):** Khuyến khích các kỹ sư trẻ thách thức quy trình phát hành truyền thống (chuyển dịch từ việc triển khai theo quý/mỗi 2 tuần sang tự động hóa liên tục do các AI Agent đảm nhiệm).
- **Thực hành Xây dựng Sản phẩm Thực tế:** Tạo ra môi trường Hackathon 24 giờ nơi người tham gia bắt tay vào làm thật, phát triển các dự án MVP/POC thực tế và giải quyết những bài toán kinh doanh cụ thể.
- **Làm chủ Kiến trúc Đám mây trên AWS:** Demo cách xây dựng các hệ thống Multi-Agent hoạt động ổn định, tối ưu chi phí và độ độ trễ thấp bằng cách sử dụng Amazon Bedrock, các dịch vụ Serverless và các công cụ AI hiện đại.
- **Hợp tác Liên ngành:** Kết nối kỹ thuật chuyên sâu (Cloud, AI/ML, DevOps) với chiến lược kinh doanh, thiết kế sản phẩm và kỹ năng thuyết trình gọi vốn.

### Diễn giả & Khách mời Đặc biệt

- **Mr. Joseph Marazzotta** - Head of Technology, Asia tại AWS.
- **Mr. Nguyễn Gia Hưng** - Head of Solutions Architecture tại AWS Vietnam.
- **One Team (Giải Nhất Track AWS)** - Nhóm phát triển AI Agent đặt hàng tự động qua đoạn chat.
- **Signal Scout / Dream AI (Giải Nhì Track AWS)** - Nhóm phát triển Hệ thống Trí tuệ Doanh nghiệp Multi-Agent.
- **Team Plan V** - Nhóm phát triển Ứng dụng Thiết kế Kiến trúc AI-Native dành cho SA.
- **Team 3Ka / Shepherd** - Nhóm phát triển Nền tảng Computer Vision & Điều phối Đám đông Thời gian thực.
- **Team Six Pillars** - Nhóm phát triển Động cơ Workflow Linh hoạt cho Phòng chống Rửa tiền (AML).

---

### Nội dung Nổi bật tại Các Phiên Chia sẻ

#### 1. Keynote: Định hình lại Sự Đổi mới trong Kỷ nguyên Agentic AI (Diễn giả: Joseph Marazzotta)
- **Sự Tiến hóa của Mô hình Tư duy (Mental Model):** Đặt sự đối lập giữa tư duy IT truyền thống (ưu tiên duy trì sự ổn định của hệ thống Mainframe với càng ít thay đổi càng tốt) và tư duy AI-Native ngày nay, nơi các AI Agent có thể hỗ trợ thực hiện phát hành liên tục.
- **Thách thức Trạng thái Hiện tại (Status Quo):** Khuyên các lập trình viên trẻ không nên bị e ngại bởi kinh nghiệm của những người đi trước. Lớp kỹ sư mới sở hữu tư duy tươi trẻ, không bị vướng bận bởi các khoản nợ kỹ thuật (technical debt) suốt 20 năm, từ đó có cơ hội dẫn dắt sự chuyển dịch trong các ngành bán lẻ, dịch vụ tài chính và tự động hóa.
- **Con người trong Vòng lặp AI (Human-in-the-Loop):** Nhấn mạnh việc Amazon triển khai hơn 1 triệu robot vận hành — khẳng định phần cứng hay các mô hình AI sẽ vô dụng nếu không có các kỹ sư con người định hướng, đánh giá và tối ưu hóa workflow của agent.

#### 2. Đặt hàng Tự nhiên qua AI Agent Đa kênh (Diễn giả: One Team)
- **Giải quyết Ma sát khi Chuyển đổi Ứng dụng (App Switch):** Khách hàng dễ mất ý định mua hàng khi bị bắt buộc phải tải app riêng hoặc đăng ký tài khoản chỉ để đặt một món ăn.
- **Khắc phục Hiện tượng Ảo giác của AI (Hallucination):** Rút kinh nghiệm từ thất bại của các doanh nghiệp lớn trước đây (ví dụ: AI Drive-thru đặt nhầm hàng trăm miếng gà rán) và ứng dụng **Bedrock Guardrails** cùng các bước xác nhận lại đơn hàng trước khi chốt giỏ hàng.
- **Kiến trúc Kỹ thuật & Hiệu quả Chi phí:** 
  - Tích hợp **Zalo** và **WhatsApp** thông qua các Channel Adapter gọn nhẹ kết nối với **Bedrock Agent Core** có khả năng ghi nhớ ngữ cảnh lịch sử.
  - Sử dụng **TinyFish** để cào dữ liệu menu động trực tiếp trên website mà không cần API gốc từ cửa hàng.
  - **Hiệu năng Chi phí:** Đạt mức chi phí hạ tầng cực thấp chỉ **$0.006/đơn hàng** (tiết kiệm 75% chi phí hạ tầng backend Bedrock, tổng cộng ~$88/tháng cho 500 đơn/ngày) với độ trễ phản hồi chỉ 3–5 giây.

#### 3. Phân tích Đối thủ & Trí tuệ Doanh nghiệp bằng Multi-Agent (Diễn giả: Signal Scout)
- **Tín hiệu Thị trường Rời rạc:** Các chuyên viên chiến lược doanh nghiệp mất hàng trăm giờ thu thập thông tin đối thủ nằm rải rác trên các báo cáo cổ đông, báo cáo tài chính và thông cáo báo chí.
- **Khung Mô hình Value Creation & Delivery Canvas:** Xây dựng hệ thống Multi-Agent dùng **TinyFish** và **Apify** để cào dữ liệu (vượt rào đăng nhập đối với dữ liệu công khai) và **LangFuse** để theo dõi hoạt động của Agent.
- **Dấu ấn Serverless trên AWS:** Host UI bằng **AWS Amplify**, bảo mật qua **AWS WAF** và **Amazon Cognito**, lưu trữ thông tin doanh nghiệp đã xác thực trên **Amazon S3** và **DynamoDB**.
- **Tối ưu Chi phí Chuẩn AWS Native:** Tái thiết kế loại bỏ các phụ thuộc vào công cụ bên thứ ba, chuyển sang dùng các công cụ Browser/Web Native của AWS giúp cắt giảm chi phí vận hành từ $94/tháng xuống còn ~$35/tháng mà vẫn đảm bảo tuân thủ về lưu trữ dữ liệu.

#### 4. Tự động hóa Vẽ Kiến trúc & Sinh Mã IaC (Diễn giả: Plan B)
- **Điểm nghẽn công việc của Solution Architect (SA):** Các SA thường xuyên gặp các yêu cầu gấp từ khách hàng đòi hỏi phải có sơ đồ kiến trúc, bảng ước tính chi phí và tệp mẫu Infrastructure-as-Code (IaC) trong thời gian rất ngắn.
- **Chuyển đổi Ngôn ngữ Tự nhiên thành Hạ tầng:** Phát triển trợ lý AI tiếp nhận câu lệnh tự nhiên hoặc tài liệu policy doanh nghiệp, phân tích luồng nghiệp vụ, vẽ sơ đồ **Draw.io** tương tác, tính toán chi phí AWS và tự động xuất mã **Terraform / CloudFormation** có thể tái sử dụng.
- **Kiểm soát Đầu ra Chặt chẽ (Strict Typing):** Áp dụng các script kiểm tra quy chuẩn và danh sách chặn service nội bộ để ngăn Agent tự ý đưa vào các dịch vụ AWS không được cấp phép hoặc tạo liên kết lỗi.

#### 5. Computer Vision & Hệ thống Quản trị Rủi ro Tài chính (Diễn giả: 3K & Six Pillars)
- **3K (Shepherd - Điều phối Đám đông):** Thu nhận luồng video trực tiếp qua **Amazon Kinesis Video Streams**, xử lý khung nhận diện và ID theo dõi bằng **YOLO v26 (Small)** + **ByteTrack** chạy trên **AWS Fargate**, kết hợp với **Amazon Bedrock Agent** để tự động điều phối nhân viên đến các khu vực sân bay/siêu thị đang bị ùn tắc.
- **Six Pillars (AML - Phòng chống Rửa tiền):** Giải quyết tỷ lệ cảnh báo sai (False Positive) lên tới 90–95% trong giao dịch ngân hàng ($158 tỷ USD lừa đảo crypto). Kết hợp **Kinesis Data Streams**, **Amazon OpenSearch Vector Engine**, **Step Functions** và mô hình Bedrock Agent kép giúp giảm thời gian điều tra từ 3 giờ xuống còn vài phút, đồng thời xuất ra các hồ sơ bằng chứng sẵn sàng cho việc kiểm toán.

---

### Bài học Quan trọng (Key Takeaways)

#### Chiến lược Kinh doanh & Kiến trúc Hệ thống
- **Giải quyết Nỗi đau (Pain Point), Không chỉ Khoe Công nghệ:** Một mô hình kỹ thuật phức tạp sẽ không có giá trị nếu không giải quyết được bài toán thực tế của khách hàng. Giám khảo và nhà đầu tư đánh giá cao một đề xuất giá trị rõ ràng (như tiết kiệm thời gian điều tra hay giảm ma sát khi thanh toán) hơn là những đoạn code rườm rà.
- **Kiểm soát Phạm vi Dự án (Scope Control) dưới Áp lực Thời gian:** Các dự án Hackathon và Production thành công đều cần xác định rõ sản phẩm khả dụng tối thiểu (MVP). Việc tự ý mở rộng tính năng giữa chừng sẽ dẫn đến code thiếu ổn định, trễ deadline và thất bại khi demo live.

#### Kỹ thuật Kỹ sư & Hạ tầng Cloud
- **Agent Core & Bộ nhớ Ngữ cảnh (Session Memory):** Việc sử dụng các Agent Core chuyên dụng có tích hợp quản lý bộ nhớ giúp hệ thống AI ghi nhớ sở thích người dùng qua nhiều lượt hội thoại mà không cần gửi lại toàn bộ prompt ngữ cảnh khổng lồ.
- **Khả năng Giám sát (Observability) & Kiểm soát (Guardrails):** Các AI Agent hoạt động trong môi trường doanh nghiệp bắt buộc phải có bước kiểm tra đầu ra nghiêm ngặt (**Bedrock Guardrails**, **LangFuse**) để hạn chế ảo giác, đảm bảo tuân thủ pháp lý và duy trì cơ chế can thiệp của con người (Human-in-the-loop).

---

### Ứng dụng Thực tế trong Công việc

- **Triển khai Micro-Adapter cho Đầu vào Đa kênh:** Thiết kế API Backend theo mô hình Decoupled Adapter để khi thêm các nền tảng tin nhắn mới (Zalo, Telegram, Slack) hay các công cụ cào dữ liệu mới thì không cần phải viết lại logic lõi của Agent.
- **Tối ưu Chi phí Hạ tầng AI:** Thường xuyên kiểm tra và thay thế các công cụ Agent của bên thứ ba bằng dịch vụ Serverless gốc của AWS. Việc chuyển các lệnh gọi API nặng sang kiến trúc Event-Driven (Lambda, DynamoDB, Bedrock) giúp giảm mạnh chi phí cho mỗi giao dịch.
- **Tự động hóa Vận hành & Chẩn đoán Hệ thống:** Xây dựng các workflow dạng Agentic cho các tác vụ nội bộ thường nhật — như phân tích log tự động, kiểm tra tuân thủ và tạo bản thiết kế hạ tầng — giải phóng thời gian cho các kỹ sư senior tập trung vào kiến trúc cốt lõi.
- **Xây dựng Văn hóa Rèn luyện Tốc độ (Rapid Prototyping):** Tích cực tham gia các kỳ Hackathon và Build-Week để rèn luyện kỹ năng phối hợp nhóm dưới áp lực, thực hành pitching sản phẩm thực tế và luôn đi trước đón đầu trong kỷ nguyên GenAI biến đổi nhanh chóng.

---

### Trải nghiệm Sự kiện

#### Bầu Không khí Hackathon Bùng nổ Energy
- Sự kiện đã thể hiện trọn vẹn sự quyết liệt và hào hứng của đổi mới công nghệ — từ những đêm thức trắng cùng code, những cuộc tranh luận kiến trúc bùng nổ trên bảng trắng, những phiên sửa lỗi cấp tốc bên ly cà phê, cho đến niềm vui vỡ òa khi trình bày sản phẩm thành công.

#### Màn Pitching Đa chiều & Gay cấn
- Các đội thi đã trải qua vòng phản biện gắt gao từ hội đồng giám khảo đa dạng chuyên môn. Màn trình bày không chỉ dừng lại ở sơ đồ kiến trúc kỹ thuật mà còn đi sâu vào mô hình tài chính, dự báo ROI, tuân thủ bảo mật và chạy demo phần mềm thực tế.

#### Sự Kết nối & Mentorship Tận tâm
- Các mentor và dàn lãnh đạo AWS đã đồng hành sát sao cùng các đội thi trong suốt sự kiện — đưa ra những góp ý kiến trúc kịp thời, hỗ trợ sửa lỗi triển khai và định hướng cho các thí sinh cách phát triển dự án POC từ Hackathon thành cơ hội nghề nghiệp thực sự.

#### Một số hình ảnh khi tham gia sự kiện
![FCAJ x Agentic AI Build Week](/images/4-Event/event3/event3-1.png)
![FCAJ x Agentic AI Build Week](/images/4-Event/event3/event3-2.png)

> **Tóm tắt:** FCAJ x Agentic AI Build Week đã chứng minh rằng tương lai của ngành kỹ thuật đám mây nằm ở sự kết hợp giữa kiến trúc nền tảng vững chắc và các AI Agent tự chủ. Bằng cách làm chủ hạ tầng Serverless của AWS, kiểm soát tốt phạm vi sản phẩm và liên tục tập trung vào giải quyết nỗi đau của người dùng, các builder hoàn toàn có thể biến những ý tưởng điên rồ nhất thành giải pháp doanh nghiệp thành công.
