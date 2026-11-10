<div align="center">

# Đỗ Hoàng Tuấn Anh (Alex)
**Principal Test Engineer tại Rakus Vietnam · ISTQB® Certified · TP. Hồ Chí Minh**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-do--hoang--tuan--anh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/do-hoang-tuan-anh/)
[![Email](https://img.shields.io/badge/Email-anh.dht3772%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anh.dht3772@gmail.com)
[![Certifications](https://img.shields.io/badge/Certifications-ISTQB%C2%AE_%7C_Claude_API-4B5563?style=flat-square)](https://www.linkedin.com/in/do-hoang-tuan-anh/details/certifications/)

[English](./README.md) | **Tiếng Việt**

</div>

---

## Giới thiệu ngắn

Mình làm QA/Testing từ đầu năm 2018 (bắt đầu từ **LogiGear**, qua **TMA Solutions** và gắn bó hơn 5 năm nay tại **Rakus Vietnam**).

Công việc hàng ngày của mình xoay quanh việc xây dựng và giữ cho các bộ test automation chạy ổn định (hiện tại chủ yếu dùng **Playwright** và **Cypress** với TypeScript; trước đó là **Java/Selenide**, **Puppeteer** và **C#/.NET**), kiểm thử bảo mật (**VEX testing**) cho các hệ thống B2B SaaS tại thị trường Nhật Bản, và hướng dẫn các bạn Manual QA trong team chuyển dần sang viết code automation.

Thời gian gần đây mình tập trung nhiều vào việc đưa các công cụ AI (**Claude Code**, **Claude API**, **Antigravity**, **Cursor**, **Ollama**) vào quy trình test thực tế — từ việc tự động hóa viết test case, giảm thời gian sửa test khi UI thay đổi, cho đến tinh chỉnh lại hệ điều hành/mạng trên Windows để chạy E2E song song mà không bị nghẽn port hay đụng độ với VPN công ty.

### Một vài kết quả thực tế trong công việc:
- **Giảm ~30% thời gian chạy Regression Test** nhờ việc chuẩn hóa và đưa các kịch bản lặp đi lặp lại vào Automation Framework.
- **Tăng ~25% tốc độ bàn giao ở các dự án E2E**, giữ chất lượng bản phát hành ổn định cho khách hàng doanh nghiệp Nhật.
- **Trực tiếp kèm cặp (mentor) ~10 bạn Manual QA** làm quen với TypeScript và cách dùng prompt/AI trong công việc, giúp hiệu suất chung của cả đội tăng khoảng **40%**.

---

## Công cụ & Ngôn ngữ sử dụng

| Mảng công việc | Công cụ & Ngôn ngữ |
| :--- | :--- |
| **Web & Mobile Automation** | Playwright, Cypress, Selenide, Selenium, Appium, Puppeteer, Mocha & Chai |
| **API, Load & Security** | Postman, Apache JMeter (CLI / Non-GUI), VEX Security Testing, Risk-Based Testing |
| **Ngôn ngữ lập trình** | TypeScript, JavaScript, Java, C# (.NET), PowerShell, Python, Google Apps Script |
| **AI & Agent Tooling** | Claude API, Claude Code, Antigravity, Cursor, Ollama, phương pháp kiểm thử ISTQB CT-AI |
| **CI/CD & Môi trường** | GitHub Actions, Jenkins, Docker, WSL2, Git, Maven, Windows 10/11 |

---

## Quá trình làm việc

### **Rakus Vietnam Co., Ltd** *(04/2021 – Hiện tại)*
- **Principal Test Engineer** *(11/2025 – Hiện tại)*
  - Chuyển đổi các bộ test cũ sang **Playwright** và **Cypress** (TypeScript), thống nhất chuẩn viết code test giữa các squad.
  - Thử nghiệm và áp dụng AI vào việc sinh test case, tự động sửa locator (self-healing) và phân tích log lỗi.
  - Hướng dẫn kỹ thuật cho các thành viên QA trong công ty.
- **Senior Software QA Engineer** *(05/2022 – 11/2025)*
  - **R-Denshihozon & R-Meisai** *(Hệ thống lưu trữ chứng từ & Hóa đơn điện tử)*: Xây dựng E2E test bằng TypeScript + Cypress; phụ trách test tải đồng thời (concurrency), update và kiểm thử lỗ hổng bảo mật (VEX).
  - **Mail Dealer** *(Hệ thống Email doanh nghiệp — Team 11 người)*: Duy trì và mở rộng bộ regression test bằng Java + Selenide.
  - **Chat Dealer** *(Ứng dụng Web Chatbot)*: Viết automation test bằng JavaScript, Mocha, Chai, Puppeteer; viết thêm công cụ bằng Google Apps Script để tự động đối chiếu dữ liệu dưới Database.
- **Middle Software QA Engineer** *(04/2021 – 04/2022)*
  - Phụ trách toàn bộ khâu test (module, integration, cross-browser, VEX security) và làm automation cho dự án **Chat Dealer**.

### **TMA Solutions** *(07/2018 – 03/2021)*
- **Middle Software QA Engineer**
  - Tham gia các dự án phần mềm Quản trị rủi ro & Sự cố vận hành (**Control of Work / Sphera**, **Pink Squad**, **IMPACT**).
  - Dẫn dắt nhóm 4 QA, làm việc trực tiếp với QA Account Manager phía khách hàng, và viết kịch bản UI/API automation bằng C# / .NET.

### **LogiGear Corporation** *(01/2018 – 06/2018)*
- **Fresher QA Engineer**
  - Thực hiện kiểm thử chức năng và regression automation cho dự án **Halliburton**.

---

## Một số Repo cá nhân trên GitHub

- **[agentic-workstation-optimizer](https://github.com/AlexDo96/agentic-workstation-optimizer)** *(PowerShell)*  
  Khi vừa chạy nhiều luồng Playwright/Appium vừa dùng các công cụ AI CLI trên máy Windows công ty (có VPN/Proxy), máy rất hay bị hết cổng TCP tạm thời (ephemeral ports), lỗi SSL hoặc mạng WSL2 bị chậm. Mình viết bộ script này để tự động tinh chỉnh lại cấu hình mạng/phần cứng Windows, có sẵn chế độ tự động backup và khôi phục (rollback) về nguyên trạng chỉ bằng 1 câu lệnh.

- **[Playwright_E2E](https://github.com/AlexDo96/Playwright_E2E) & [Playwright_QA](https://github.com/AlexDo96/Playwright_QA)** *(TypeScript)*  
  Project mẫu thể hiện cách mình tổ chức một bộ test Playwright theo Page Object Model (`BasePage`, tách riêng phần xử lý Modal, và cấu hình `global-setup`).

- **[Appium_E-Commerce](https://github.com/AlexDo96/Appium_E-Commerce)** *(Java / Maven)*  
  Project tự động hóa kiểm thử ứng dụng Android cho luồng mua sắm E-Commerce.

- **[API_Testing_QA](https://github.com/AlexDo96/API_Testing_QA)** *(Postman)*  
  Bộ test API sử dụng biến môi trường động, truyền dữ liệu nối tiếp giữa các request (chaining) và kiểm tra cấu trúc JSON trả về.

---

## Chứng chỉ & Học vấn

- **ISTQB® Certified Tester** — Foundation Level Agile Tester (CTFL-AT)
- **Certified Tester** — Mobile Automation Testing
- **Building with the Claude API** — Anthropic
- **Python (Basic) & Problem Solving (Basic)** — HackerRank
- **Kỹ sư Kỹ thuật Phần mềm (B.E. in Computer Software Engineering)** — Đại học Hoa Sen *(2014 – 2018)*
