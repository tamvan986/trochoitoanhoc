# Thư viện trò chơi — Học Toán Cùng Thầy Tâm

Trang thư viện các trò chơi học tập môn Toán (24 mục), chỉ gồm nội dung trò chơi học tập.

## Cách đưa lên GitHub Pages

1. Vào GitHub, tạo repository mới (ví dụ tên `tro-choi-hoc-tap`), để ở chế độ Public.
2. Tải toàn bộ file trong thư mục này lên repository (kéo thả cả thư mục hoặc từng file lên trang GitHub).
   - `index.html` là trang thư viện (trang chủ của web).
   - Các file `.html` còn lại là từng trò chơi, công cụ và trang chủ cũ (`trang-chu.html`).
   - Giữ nguyên tên file và giữ tất cả file cùng một thư mục thì các liên kết mới mở được.
3. Vào **Settings → Pages**, mục **Build and deployment → Source** chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, rồi bấm **Save**.
4. Chờ khoảng 1 phút, mở địa chỉ dạng `https://<tên-tài-khoản>.github.io/<tên-repo>/` là xem được trang thư viện.

## Ghi chú

- Toàn bộ trò chơi chạy bằng file HTML tĩnh, không cần máy chủ riêng.
- Thêm trò mới: chép file `.html` của trò vào cùng thư mục rồi thêm một thẻ (card) mới trong `index.html`, trỏ liên kết tới file đó.
