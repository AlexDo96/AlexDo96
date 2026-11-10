<div align="center">

# Đỗ Hoàng Tuấn Anh (Alex)
**Principal Test Engineer tại Rakus Vietnam · ISTQB® Certified · TP. Hồ Chí Minh**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-do--hoang--tuan--anh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/do-hoang-tuan-anh/)
[![Email](https://img.shields.io/badge/Email-anh.dht3772%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anh.dht3772@gmail.com)
[![Certifications](https://img.shields.io/badge/Certifications-ISTQB%C2%AE_%7C_Claude_API-374151?style=flat-square)](https://www.linkedin.com/in/do-hoang-tuan-anh/details/certifications/)

[English](./README.md) | **Tiếng Việt**

</div>

---

Mình có **hơn 8 năm kinh nghiệm trong mảng Software QA & Test Automation** (bắt đầu từ **LogiGear** và **TMA Solutions** năm 2018, và làm việc tại **Rakus Vietnam** từ năm 2021 đến nay).

Công việc chính của mình là thiết kế và duy trì các bộ E2E Automation Framework (**Playwright**, **Cypress**, **Selenide**, **Appium**), kiểm thử bảo mật (**VEX testing**) cho các hệ thống B2B SaaS tải lớn tại thị trường Nhật Bản, và đưa các công cụ **AI** (**Claude API**, **Claude Code**, **Antigravity**, **Cursor**) vào giải quyết các bài toán thực tế trong quy trình kiểm thử.

<div align="center">

| **8+ Năm Kinh Nghiệm** | **-30% Thời Gian Regression** | **+25% Tốc Độ Bàn Giao E2E** | **Mentor ~10 Kỹ Sư QA** |
| :---: | :---: | :---: | :---: |
| Thực chiến qua Web, Mobile, API & B2B SaaS | Nhờ thay thế các bước test lặp lại bằng Automation Framework | Nâng cao độ ổn định của bản build và tốc độ release giữa các squad | Hướng dẫn Manual QA làm chủ TypeScript & Prompt (+40% hiệu suất cả đội) |

</div>

---

## Dự Án & Mã Nguồn Tiêu Biểu Trên GitHub

| Dự án | Bài toán thực tế & Cách giải quyết | Công nghệ |
| :--- | :--- | :--- |
| **[agentic-workstation-optimizer](https://github.com/AlexDo96/agentic-workstation-optimizer)**<br/>*Windows/Network Toolkit & AI Agent Skill* | Khi chạy song song nhiều luồng E2E (Playwright/Appium) cùng với các công cụ AI CLI trên máy Windows công ty (có VPN/Proxy), máy rất hay bị cạn cổng TCP tạm thời (ephemeral ports), lỗi SSL và mạng WSL2 bị chậm.<br/>→ Mình viết bộ script PowerShell (tích hợp sẵn AI Agent Skill) để tinh chỉnh cấu hình OS/mạng an toàn, có tự động backup và khôi phục (rollback) bằng 1 lệnh (`-Mode Work` / `-Mode All`). | `PowerShell`<br/>`Windows Internals`<br/>`WSL2` · `Ollama`<br/>`Claude Code` |
| **[Playwright_E2E](https://github.com/AlexDo96/Playwright_E2E)** & **[Playwright_QA](https://github.com/AlexDo96/Playwright_QA)**<br/>*Web E2E Test Architecture* | Giữ cho bộ UI test dễ đọc, dễ sửa khi sản phẩm mở rộng.<br/>→ Tổ chức code theo Page Object Model (`BasePage`, tách riêng phần xử lý Modal, và cấu hình `global-setup`), hỗ trợ chạy đa trình duyệt (Chromium, Firefox, WebKit). | `TypeScript`<br/>`Playwright`<br/>`Node.js` |
| **[Appium_E-Commerce](https://github.com/AlexDo96/Appium_E-Commerce)**<br/>*Mobile Automation Suite* | Tự động hóa luồng mua sắm trên ứng dụng di động Android.<br/>→ Bao phủ luồng người dùng đầu-cuối, chuyển đổi ngữ cảnh Native/Hybrid, xử lý thao tác vuốt/chạm (gestures) và quản lý driver tập trung. | `Java`<br/>`Appium`<br/>`Maven` |
| **[API_Testing_QA](https://github.com/AlexDo96/API_Testing_QA)**<br/>*API Contract & Workflow Tests* | Kiểm tra logic hệ thống qua API trước khi ghép nối giao diện.<br/>→ Bộ test Postman áp dụng kỹ thuật nối chuỗi request (request chaining), biến môi trường động, kiểm tra JSON schema và các kịch bản lỗi/biên. | `Postman`<br/>`JavaScript`<br/>`REST API` |

---

## Công Cụ & Kỹ Năng Chuyên Môn

- **Test Automation (Web & Mobile)**: Playwright, Cypress, Selenide, Selenium, Appium, Puppeteer, Mocha & Chai
- **API, Performance & Security**: Postman, Apache JMeter (chạy tải bằng CLI / Non-GUI), VEX Security Testing, Concurrency & Risk-Based Testing
- **Ngôn ngữ lập trình**: TypeScript, JavaScript, Java, C# (.NET), PowerShell, Python, Google Apps Script
- **Ứng dụng AI trong QA**: Claude API, Claude Code, Antigravity, Cursor, Local LLMs (`Ollama`), phương pháp kiểm thử ISTQB CT-AI (hỗ trợ sinh test case, tự động sửa locator, phân tích log lỗi)
- **CI/CD & Môi trường**: GitHub Actions, Jenkins, Docker, WSL2, Git, Maven, Windows 10/11

---

## Tóm Tắt Quá Trình Làm Việc

| Giai đoạn | Vị trí & Công ty | Sản phẩm & Công việc chính |
| :--- | :--- | :--- |
| **2021 – Hiện tại**<br/>*(Hơn 5 năm)* | **Principal Test Engineer** *(2025–Nay)*<br/>**Senior / Middle QA Engineer** *(2021–2025)*<br/>**Rakus Vietnam Co., Ltd** | • Định hình kiến trúc test với **Playwright & Cypress (TypeScript)** và nghiên cứu ứng dụng AI vào quy trình test cho các squad.<br/>• **R-Denshihozon & R-Meisai** *(Lưu trữ chứng từ & Hóa đơn điện tử)*: Viết E2E bằng TypeScript/Cypress, test tải đồng thời (concurrency) và kiểm thử bảo mật VEX.<br/>• **Mail Dealer** *(Email doanh nghiệp)*: Mở rộng bộ regression test với Java + Selenide.<br/>• **Chat Dealer** *(Web Chatbot)*: Viết E2E bằng JS/Puppeteer/Mocha & tự động hóa đối chiếu DB bằng Google Apps Script. |
| **2018 – 2021**<br/>*(2 năm 9 tháng)* | **Middle Software QA Engineer**<br/>**TMA Solutions** | • Dẫn dắt nhóm 4 QA cho các hệ thống Quản trị rủi ro & Sự cố vận hành (**Control of Work / Sphera**, **Pink Squad**, **IMPACT**).<br/>• Viết kịch bản UI/API automation bằng **C# / .NET**, thực hiện test hiệu năng và kiểm thử triển khai (deployment). |
| **2018**<br/>*(6 tháng)* | **Fresher QA Engineer**<br/>**LogiGear Corporation** | • Kiểm thử chức năng và tự động hóa regression test cho dự án **Halliburton**. |

> *Chi tiết từng dự án có thể xem đầy đủ trên [trang LinkedIn của mình](https://www.linkedin.com/in/do-hoang-tuan-anh/).*

---

## Chứng Chỉ & Học Vấn

- **ISTQB® Certified Tester** — Foundation Level Agile Tester (CTFL-AT)
- **Certified Tester** — Mobile Automation Testing
- **Building with the Claude API** — Anthropic
- **Python (Basic) & Problem Solving (Basic)** — HackerRank
- **Kỹ sư Kỹ thuật Phần mềm (B.E. in Computer Software Engineering)** — Đại học Hoa Sen *(2014 – 2018)*
