# 🧱 Project Architecture

> Tổng quan cấu trúc thư mục của codebase dự án `web-v5`

---

## 📂 Root Structure

web-v5/
 ├── public/ # Assets tĩnh (images, favicon, etc.)
 ├── src/
 │ ├── assets/ # Hình ảnh, font, icon
 │ ├── components/ # UI Components chính
 │ │ ├── artist/ # Trang nghệ sĩ & thông tin chi tiết
 │ │ ├── basic/ # Thành phần cơ bản: Image, Card, Icon, etc.
 │ │ └── Authentication/ # Thành phần liên quan đến login, auth
 │ ├── constants/ # Biến tĩnh: TEXT, ENUM, ID,...
 │ ├── config/ # Config app: env, localStorage, API key,...
 │ ├── helpers/ # Hàm tiện ích (utils, xử lý logic)
 │ ├── hooks/ # Custom hooks (nếu có)
 │ ├── seo/ # Thành phần và xử lý SEO
 │ └── pages/ # Trang ứng dụng (nếu dùng Next.js hoặc SPA)
 ├── .cursor/ # Cấu hình cho Cursor AI (docs.json)
 ├── custom-elements.json # Output từ CEM, mô tả Web Components
 └── README.md