# Shadow Race — GitHub Pages website

Website landing page chủ đề Minecraft Legendary Weapon, responsive cho điện thoại, có hiệu ứng 3D/parallax, reveal khi cuộn, gallery từ ảnh bạn gửi và form đăng ký/đăng nhập demo.

## Chạy thử
Mở `index.html` trong trình duyệt. Nếu trình duyệt hạn chế file cục bộ, dùng VS Code Live Server hoặc chạy một static server.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub.
2. Upload toàn bộ file và thư mục `assets/` trong ZIP này lên repo (giải nén trước).
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**, chọn `main` và thư mục `/(root)`, nhấn Save.
5. Chờ GitHub build rồi mở URL Pages được hiển thị.

## Lưu ý xác thực
Form hiện tại là **demo giao diện**: tài khoản được lưu trong `localStorage` của chính trình duyệt, không đồng bộ giữa thiết bị và không an toàn cho website thật. Không nhập mật khẩu thật. Muốn đăng nhập/đăng ký thật cần backend hoặc dịch vụ xác thực (ví dụ Supabase/Firebase) và chính sách bảo mật phù hợp.
