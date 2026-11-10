<div align="center">

# Đỗ Hoàng Tuấn Anh (Alex)
**Principal Test Engineer tại Rakus Vietnam · ISTQB® Certified · TP. Hồ Chí Minh**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-do--hoang--tuan--anh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/do-hoang-tuan-anh/)
[![Email](https://img.shields.io/badge/Email-anh.dht3772%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anh.dht3772@gmail.com)
[![Certifications](https://img.shields.io/badge/Certifications-ISTQB%C2%AE_%7C_Claude_API-374151?style=flat-square)](https://www.linkedin.com/in/do-hoang-tuan-anh/details/certifications/)

[English](./README.md) | **Tiếng Việt**

</div>

---

Mình có **hơn 8 năm kinh nghiệm trong mảng Software QA & Test Automation** — bắt đầu từ **LogiGear** và **TMA Solutions** năm 2018, và gắn bó với **Rakus Vietnam** từ năm 2021 đến nay.

Công việc hàng ngày của mình tập trung vào việc xây dựng các bộ E2E Automation Framework dễ bảo trì (**Playwright**, **Cypress**, **Selenide**, **Appium**), kiểm thử lỗ hổng bảo mật (**VEX testing**) cho các hệ thống B2B SaaS tải lớn tại thị trường Nhật Bản, và đưa các công cụ **AI** (**Claude API**, **Claude Code**, **Antigravity**, **Cursor**) vào giải quyết các bài toán thực tế trong quy trình test.

<div align="center">

| **8+ Năm Kinh Nghiệm** | **-30% Thời Gian Regression** | **+25% Tốc Độ Bàn Giao E2E** | **Mentor ~10 Kỹ Sư QA** |
| :---: | :---: | :---: | :---: |
| Thực chiến qua Web, Mobile, API & B2B SaaS | Nhờ thay thế các bước test lặp lại bằng Automation Framework | Nâng cao độ ổn định của bản build và tốc độ release giữa các squad | Hướng dẫn Manual QA làm chủ TypeScript & Prompt (+40% hiệu suất cả đội) |

</div>

---

## Dự Án & Mã Nguồn Tiêu Biểu Trên GitHub

| Repository & Công nghệ | Bài toán thực tế & Giải pháp mình xây dựng |
| :--- | :--- |
| **[agentic-workstation-optimizer](https://github.com/AlexDo96/agentic-workstation-optimizer)**<br/><br/>`PowerShell` · `WSL2`<br/>`TCP/IP` · `Ollama`<br/>`Claude-Code` · `Antigravity` | **Bộ công cụ tối ưu Windows/Network & AI Agent Skill**<br/>Khi chạy song song nhiều luồng Playwright/Appium cùng lúc với các công cụ AI CLI trên máy Windows công ty (có VPN/Proxy), máy rất hay gặp lỗi `EADDRINUSE` do cạn cổng TCP tạm thời, nghẽn SSL/VPN và mạng WSL2 bị chậm.<br/><br/>Mình viết bộ script này (kèm AI Agent Skill) để mở rộng dải cổng TCP động từ `16.384` lên `55.535` cổng, giảm `TcpTimedWaitDelay` từ `120s` xuống `30s`, cấu hình WSL2 Mirrored Networking và tối ưu VRAM cho `Ollama` — tích hợp sẵn cơ chế tự động backup Registry/hệ thống và khôi phục (rollback) về nguyên trạng chỉ bằng 1 lệnh (`-Mode Work` / `-Mode All`). |
| **[Playwright_E2E](https://github.com/AlexDo96/Playwright_E2E)** &<br/>**[Playwright_QA](https://github.com/AlexDo96/Playwright_QA)**<br/><br/>`TypeScript`<br/>`Playwright` · `Node.js` | **Kiến trúc Web E2E Test Automation**<br/>Bài take-home dùng Playwright test trang e-commerce Demoblaze. Mỗi màn hình có một Page Object, các modal (About, Contact, Place Order) tách thành class riêng, 8 file spec bao phủ đăng ký, đăng nhập, giỏ hàng và đặt hàng. Chạy trên Chromium, Firefox, WebKit, có HTML report và trace khi retry. |
| **[Appium_E-Commerce](https://github.com/AlexDo96/Appium_E-Commerce)**<br/><br/>`Java` · `Appium` · `TestNG`<br/>`Selenium Grid` · `Allure` | **Android Automation chạy song song**<br/>Project Appium cho app demo của WebdriverIO. `DriverFactory` có thể tự bật Appium server local trên cổng trống, hoặc kết nối tới Selenium Grid hub với 2 Appium node để chạy song song trên nhiều thiết bị. Dữ liệu test đăng nhập đọc từ file JSON qua GSON, có hàm swipe để cuộn cho tới khi tìm thấy element. |
| **[API_Testing_QA](https://github.com/AlexDo96/API_Testing_QA)**<br/><br/>`Postman` · `JavaScript` | **Kiểm thử API với Postman (15 Days of Postman)**<br/>Bài làm của mình trong chương trình "15 Days of Postman for Testers": 15 collection gồm các luồng authorization, collection variables và script, assertion `pm.test`, điều hướng workflow bằng `setNextRequest`, kiểm tra JSON schema và mock server. |

---

## Công Cụ Sử Dụng & Hướng Nghiên Cứu Hiện Tại

- **Web & Mobile Automation**: Playwright, Cypress, Selenide, Selenium, Appium, Puppeteer, Mocha & Chai
- **API, Load & Security Testing**: Postman, Apache JMeter (chạy tải bằng CLI Non-GUI & phân tích Percentile), VEX Security Testing, Concurrency & Risk-Based Testing
- **Ngôn ngữ lập trình**: TypeScript, JavaScript, Java, C# (.NET), PowerShell, Python, Google Apps Script
- **AI trong QA & Agent Tooling**: Claude API, Claude Code, Antigravity, Cursor, Local LLMs (`Ollama`), tự động hóa sinh test case, tự phục hồi locator (self-healing) và phân tích defect
- **CI/CD & Hạ tầng**: GitHub Actions, Jenkins, Docker, WSL2, Git, Maven, Windows 10/11 Internals
- **Đang đào sâu nghiên cứu**: Phương pháp kiểm thử hệ thống AI theo chuẩn **ISTQB® CT-AI** (Metamorphic Testing, Red Teaming cho LLM, Drift Testing) và **Harness Engineering** (thiết kế `AGENTS.md` & cơ chế tự kiểm chứng thực thi cho Coding Agents).

---

## Tóm Tắt Quá Trình Làm Việc

| Giai đoạn | Vị trí & Công ty | Sản phẩm & Phạm vi công việc |
| :--- | :--- | :--- |
| **11/2025 – Hiện tại** | **Principal Test Engineer**<br/>**Rakus Vietnam Co., Ltd** | Dẫn dắt việc hiện đại hóa kiến trúc test với **Playwright & Cypress (TypeScript)** giữa các squad; R&D giải pháp ứng dụng AI hỗ trợ viết test case và self-healing; trực tiếp hướng dẫn kỹ thuật cho ~10 thành viên QA. |
| **04/2021 – 11/2025**<br/>*(4 năm 7 tháng)* | **Senior / Middle QA Engineer**<br/>**Rakus Vietnam Co., Ltd** | • **R-Denshihozon & R-Meisai** *(Lưu trữ chứng từ & Hóa đơn điện tử)*: Xây dựng E2E test bằng TypeScript + Cypress, kiểm thử tải đồng thời (concurrency) và bảo mật VEX.<br/><br/>• **Mail Dealer** *(Email doanh nghiệp — Team 11 người)*: Duy trì và mở rộng bộ regression test bằng Java + Selenide.<br/><br/>• **Chat Dealer** *(Web Chatbot)*: Phụ trách toàn diện khâu test, viết automation bằng JS/Puppeteer/Mocha và viết công cụ Google Apps Script tự động đối chiếu dữ liệu DB. |
| **07/2018 – 03/2021**<br/>*(2 năm 9 tháng)* | **Middle Software QA Engineer**<br/>**TMA Solutions** | Dẫn dắt nhóm 4 QA cho các hệ thống Quản trị rủi ro & Sự cố vận hành quốc tế (**Control of Work / Sphera**, **Pink Squad**, **IMPACT**). Viết kịch bản UI/API automation bằng **C# / .NET**, thực hiện test hiệu năng và kiểm thử triển khai (deployment). |
| **01/2018 – 06/2018**<br/>*(6 tháng)* | **Fresher QA Engineer**<br/>**LogiGear Corporation** | Kiểm thử chức năng và tự động hóa regression test cho dự án **Halliburton**. |

> *Chi tiết từng dự án có thể xem đầy đủ trên [trang LinkedIn của mình](https://www.linkedin.com/in/do-hoang-tuan-anh/).*

---

## Chứng Chỉ & Học Vấn

- **ISTQB® Certified Tester** — Foundation Level Agile Tester (CTFL-AT)
- **Certified Tester** — Mobile Automation Testing
- **Building with the Claude API** — Anthropic
- **Python (Basic) & Problem Solving (Basic)** — HackerRank
- **Kỹ sư Kỹ thuật Phần mềm (B.E. in Computer Software Engineering)** — Đại học Hoa Sen *(2014 – 2018)*
