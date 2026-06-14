# Hướng dẫn tích hợp CAPTCHA - Nhóm 02 (Đã sẵn sàng cho Vercel)

Tài liệu này hướng dẫn cách chạy thử dự án ở môi trường Local và cách Deploy lên Server (đặc biệt là Vercel).
Dự án đã được cấu trúc lại chuẩn Serverless: Frontend tĩnh được phục vụ ở thư mục gốc, và Backend API (Python) nằm trong thư mục `api/`.

## 1. Khởi chạy hệ thống để kiểm thử (Local)

Chỉ cần chạy **1 lệnh Python duy nhất** là có thể chạy cả giao diện web lẫn API.

### Bước 1: Cài đặt thư viện
1. Mở Terminal (CMD/PowerShell) tại thư mục gốc của dự án.
2. Cài đặt các thư viện bắt buộc bằng lệnh:
   ```bash
   pip install -r requirements.txt
   ```

### Bước 2: Chạy Server
1. Di chuyển vào thư mục `api`:
   ```bash
   cd api
   ```
2. Khởi chạy hệ thống:
   ```bash
   python index.py
   ```
3. Mở trình duyệt web và truy cập vào: **http://127.0.0.1:5000**
   -> Trang Đăng Nhập Demo có nhúng Captcha sẽ xuất hiện.

---
