# Đưa dự án tuần 1 lên GitHub

Phần này cần được thực hiện trên máy và tài khoản GitHub của bạn; bộ mã nguồn không tự xuất bản lên GitHub.

## 1. Mở terminal trong thư mục dự án

Trong VS Code chọn **Terminal → New Terminal**, đảm bảo bạn đang đứng tại thư mục có `index.html`.

## 2. Khởi tạo Git và tạo commit

```bash
git init
git add .
git commit -m "feat: build personal library static UI for week 1"
```

Nếu Git yêu cầu cấu hình tên/email, chạy lệnh sau với thông tin **của bạn** rồi commit lại:

```bash
git config --global user.name "Ten Cua Ban"
git config --global user.email "email-cua-ban@example.com"
```

## 3. Tạo repository mới trên GitHub

1. Đăng nhập vào https://github.com/.
2. Chọn **New repository**.
3. Đặt tên `personal-library` (hoặc tên bạn muốn).
4. Chọn Public hoặc Private tùy nhu cầu của bạn.
5. **Không tích** khởi tạo README / .gitignore / License vì thư mục đã có README và .gitignore.
6. Chọn **Create repository**.

## 4. Push mã nguồn lên repository

Thay `<USERNAME>` bằng tên tài khoản GitHub của bạn:

```bash
git branch -M main
git remote add origin https://github.com/<USERNAME>/personal-library.git
git push -u origin main
```

GitHub có thể yêu cầu đăng nhập thông qua trình duyệt hoặc phương thức xác thực được hỗ trợ. **Không chia sẻ mật khẩu hoặc token trong README hoặc commit.**

## 5. Kiểm tra

- Repo có `index.html`, `add-book.html`, `style.css` và `assets/`.
- README hiển thị trên trang chính của repo.
- Các commit được liệt kê tại trang **Commits**.

### Tùy chọn: chạy demo trên GitHub Pages

Bạn có thể vào **Settings → Pages → Build and deployment**, chọn **Deploy from a branch** và nhánh `main` / thư mục `/ (root)` nếu tài khoản và repository hỗ trợ. Với dự án HTML/CSS tĩnh, đây là một cách chia sẻ demo thuận tiện; không bắt buộc cho tuần 1.
