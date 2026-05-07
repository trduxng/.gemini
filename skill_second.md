# 🗺️ Secondary Skills Map (High-Level)

AI sử dụng file này để xác định nhóm kỹ năng. Nếu cần tìm skill cụ thể, AI thực hiện tìm kiếm trực tiếp trên ổ đĩa.

## 📂 Các Domain chính trong `skills_second/`
- **Backend & Core:** .NET, C#, Dapper, EF Core, Java, Spring, Laravel, Django, FastAPI.
- **AI & Automation:** Agent frameworks (CrewAI, LangGraph), LLM Tools, Web Scrapers (Apify), n8n.
- **Frontend & Mobile:** Angular, React, Vue, Svelte, Flutter, React Native, SwiftUI.
- **Bảo mật & Pentest:** Web hacking, Network audit, Malware analysis, Reverse engineering.
- **Tools & SaaS:** Stripe, Twilio, Telegram, Slack, Google Workspace, Firebase.

## 🔍 Hướng dẫn AI Tìm kiếm (Discovery Logic)
Khi cần một công cụ không có trong `skills/`:
1. Sử dụng `grep_search` với pattern từ khóa trong `C:\Users\Tran Dung\.gemini\skills_second\*\SKILL.md`.
2. Hoặc sử dụng `list_directory` trên `skills_second/` để quét tên thư mục.
3. Kích hoạt bằng đường dẫn tuyệt đối.
