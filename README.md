# 🤖 Gemini CLI Configuration & Skills

Dự án này chứa cấu hình cá nhân, các Agents chuyên biệt và hệ thống Skills đồ sộ dành cho **Gemini CLI** (một công cụ hỗ trợ lập trình Agentic).

## 🚀 Cấu trúc dự án

- **`agents/`**: Danh mục các Sub-Agents chuyên biệt (Reviewer, Docs, Security, Test Generator).
- **`extensions/`**: Các bộ mở rộng quy trình làm việc:
    - `oh-my-product`: Quy trình phát triển sản phẩm toàn diện.
    - `conductor`: Quản lý các tracks và kế hoạch thực thi.
    - `caveman`: Chế độ giao tiếp siêu nén tiết kiệm token.
- **`skills/`**: Thư viện hàng ngàn kỹ năng chuyên sâu (Web Dev, Mobile, Security, AI/ML, DevOps...).
    - *Nguồn gốc:* [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills)
- **`GEMINI.md`**: File chỉ dẫn cốt lõi, quy định phong cách coding và quy tắc vận hành của Agent.

## 🛠 Cài đặt & Sử dụng

### 1. Cấu hình môi trường
Đảm bảo bạn đã cài đặt Gemini CLI và trỏ thư mục cấu hình về đây.

### 2. Sử dụng Skills
Các skills được nạp động (Dynamic Loading) để tối ưu hóa context. Sử dụng lệnh trong chat:
```
activate_skill <tên_skill>
```

### 3. Chế độ Caveman
Để tiết kiệm token (lên đến 75%), hãy kích hoạt:
```
/caveman full
```

### 4. MCP Servers (Nâng cao)
Dự án tích hợp các máy chủ MCP để tăng cường khả năng hiểu code:

- **CodeGraphContext (cgc)**: Phân tích đồ thị phụ thuộc sâu.
    - Cài đặt: `pip install codegraphcontext`
    - Index project: `cgc index`
- **memvid**: Bộ nhớ ngữ cảnh dài hạn và đa phương tiện.
    - Cài đặt: `npx @google/memvid-mcp` (hoặc cấu hình trong `settings.json`)

## 🛡 Bảo mật & Quy tắc
- Các file nhạy cảm (`.env`, keys, tokens) đã được đưa vào `.gitignore`.
- Tuân thủ nghiêm ngặt các quy tắc trong `GEMINI.md`.

## ✍️ Tác giả
- **Trần Dũng** - [GitHub](https://github.com/trduxng)

---
*Ghi chú: Đây là workspace cấu hình cá nhân được tối ưu cho hiệu suất và an toàn.*
