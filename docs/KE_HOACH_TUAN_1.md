# Kế hoạch thực hành Tuần 1 — Project 1

**Đề tài:** Xây dựng ứng dụng Web quản lý tủ sách cá nhân  
**Công nghệ:** HTML5 và CSS3 (chưa dùng JavaScript)  
**Thời lượng gợi ý:** 12–15 giờ trong 7 ngày

## Kết quả có sẵn trong bộ mã nguồn

- `index.html`: trang chủ, thư viện 9 sách minh họa, thanh công cụ tĩnh và thống kê mẫu.
- `add-book.html`: biểu mẫu nhập thông tin sách (giao diện tĩnh).
- `style.css`: style cơ bản, Flexbox, Grid, responsive, hover/focus.
- `assets/`: logo và ảnh bìa sách tạo riêng cho bản demo.
- `README.md`: giới thiệu và hướng dẫn chạy.

## Từng ngày cần đọc và tự thực hành lại

### Ngày 1 — HTML cơ bản

- [ ] Đọc cấu trúc `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.
- [ ] Xem vai trò của `meta viewport`, `title`, `link stylesheet`.
- [ ] Tự tạo trang chỉ có tiêu đề, một đoạn giới thiệu, 3 ảnh bìa sách.
- **Mã nguồn xem:** đầu file `index.html`.

### Ngày 2 — HTML ngữ nghĩa và form

- [ ] Nhận biết `header`, `nav`, `main`, `section`, `article`, `footer`.
- [ ] Hiểu `label for`, `input id`, `select`, `textarea`, `fieldset`, `button`.
- [ ] Thử thêm một trường “Năm xuất bản” vào `add-book.html`.
- **Mã nguồn xem:** `add-book.html`.

### Ngày 3 — CSS và Box Model

- [ ] Nắm `class`, selector, `margin`, `padding`, `border`, `box-sizing`.
- [ ] Thử thay đổi màu chính `--blue` trong `style.css`.
- [ ] Tự chỉnh thẻ sách: cỡ ảnh, bo góc, font, màu nền.
- **Mã nguồn xem:** các khối `:root`, `.book-card`, `.book-cover`, `.book-copy`.

### Ngày 4 — Flexbox và Grid

- [ ] Tìm các phần dùng `display:flex` (`.topbar`, `.side-nav`, `.book-footer`).
- [ ] Tìm các phần dùng `display:grid` (`.stats-grid`, `.books-grid`).
- [ ] Thử đổi desktop từ 3 cột sang 4 cột rồi về 3 cột.
- **Mã nguồn xem:** `style.css`.

### Ngày 5 — Form và hiệu ứng

- [ ] Tìm pseudo-class `:hover`, `:focus-visible`, `:checked`.
- [ ] Chỉnh form sao cho các input có chiều cao nhất quán.
- [ ] Quan sát hiệu ứng khi đưa chuột lên nút và thẻ sách.
- **Mã nguồn xem:** `.book-form`, `.form-field`, `.radio-pill`.

### Ngày 6 — Responsive Design

- [ ] Dùng DevTools thử màn hình 1440px, 768px, 390px.
- [ ] Hiểu các breakpoint `1290px`, `1050px`, `760px`, `530px` trong CSS.
- [ ] Đảm bảo 3 cột trên desktop, 2 cột tablet, 1 cột mobile.
- [ ] Kiểm tra không tràn ngang và form vẫn dễ đọc.

### Ngày 7 — Git/GitHub và tự kiểm tra

- [ ] Chạy checklist trong `docs/KIEM_THU_TUAN_1.md`.
- [ ] Viết tên mình vào README.
- [ ] Khởi tạo Git và tạo commit đầu tiên.
- [ ] Tạo repository và push lên GitHub bằng hướng dẫn `docs/HUONG_DAN_GITHUB.md`.
- [ ] Đọc lại HTML/CSS và tự giải thích những thành phần chính.

## Bài tập bổ sung để tránh chỉ sao chép code

1. Tự tạo thêm một thẻ sách thứ 10, đổi tên và ảnh minh họa.
2. Sửa giao diện trang chủ thành tông màu xanh lá bằng CSS variables.
3. Thêm một tùy chọn “Tạm dừng” ở form trạng thái đọc.
4. Tạo một trang `about.html` có mô tả tác giả và mục tiêu dự án.

## Tiêu chí kết thúc tuần 1

Có thể **tự giải thích** cấu trúc HTML, CSS cơ bản, Flexbox, Grid, media query, vai trò của form và cách chạy project. Chưa cần có Backend, Database, React hay thao tác lưu sách.
