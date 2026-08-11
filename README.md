# React Training Project 🚀

Dự án nghiên cứu và thực hành ReactJS, được xây dựng với mục tiêu rèn luyện kỹ năng và áp dụng các công nghệ hiện đại vào phát triển Web Frontend.

## ✨ Tính năng chính

- **🚀 Migration & Upgrade**: Đã chuyển đổi (migrate) thành công từ Create React App (CRA) cũ sang **Vite** để tăng tốc độ build/phát triển, đồng thời nâng cấp hệ thống lên **Node.js LTS** mới nhất.
- **🔐 Xác thực người dùng (Authentication)**: Đăng nhập/Đăng ký an toàn sử dụng Supabase Auth.
- **📝 TodoList**: Ứng dụng quản lý công việc (CRUD) với giao diện thân thiện, hỗ trợ kéo thả (Drag & Drop) và Form Validation.
- **🔮 Tarot AR**: Trải nghiệm bói bài Tarot 3D sống động ngay trên trình duyệt sử dụng Three.js & Tween.js.

## 🛠 Công nghệ sử dụng

- **Core**: React 18, TypeScript 5
- **Build Tool**: Vite
- **Routing**: React Router DOM (v5)
- **State Management**: Redux Toolkit
- **Backend as a Service (BaaS)**: Supabase (Auth & Database)
- **3D Engine**: Three.js, Tween.js
- **Styling**: SCSS, Ant Design (UI Framework)
- **Form Handling**: React Hook Form, Zod (Validation)
- **Others**: Axios, Day.js, SortableJS

## 🚀 Cài đặt & Chạy dự án

Dự án sử dụng **Yarn** làm Package Manager.

1. **Clone repository:**
   ```bash
   git clone https://github.com/DucCuong159/Reactjs_learning.git
   cd react_tranning
   ```

2. **Cài đặt dependencies:**
   ```bash
   yarn install
   ```

3. **Cấu hình biến môi trường:**
   Tạo file `.env` ở thư mục gốc và cung cấp các key của Supabase:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Chạy server development:**
   ```bash
   yarn dev
   ```

## 📜 Các lệnh cơ bản khác

- `yarn build`: Kiểm tra lỗi TypeScript và đóng gói ứng dụng cho Production.
- `yarn preview`: Xem trước bản build Production tại local.

---

> **Lưu ý:** Dự án đã được chuyển đổi sang sử dụng **Vite** để tăng tốc độ build. Luôn sử dụng **Yarn** để cài đặt và quản lý package.
