# Checklist kiểm thử giao diện — Tuần 1

> Chỉ kiểm thử **HTML/CSS**. Các nút tìm kiếm, lọc và lưu sách chưa có logic — đây là phạm vi có chủ đích của tuần 1.

## Kiểm thử chức năng giao diện

- [ ] Mở `index.html` không lỗi.
- [ ] Thanh điều hướng dẫn đúng tới trang chủ, danh sách sách và trang thêm sách.
- [ ] Có ít nhất 6 thẻ sách (bản demo có 9).
- [ ] Các ảnh bìa tải thành công kể cả khi không có Internet.
- [ ] Mỗi thẻ sách hiển thị tên, tác giả, thể loại và trạng thái.
- [ ] Có ô tìm kiếm và bộ lọc làm UI mẫu; hiển thị chú thích chưa hoạt động.
- [ ] Nút **Thêm sách** dẫn đến `add-book.html`.
- [ ] Biểu mẫu có tên sách, tác giả, thể loại, số trang, trạng thái và ghi chú.
- [ ] Biểu mẫu không giả vờ lưu sách; nút Lưu bị vô hiệu hóa.
- [ ] Nhấn **Quay lại tủ sách** hoạt động.

## Kiểm thử responsive

- [ ] Desktop 1440px: danh sách sách 3 cột, thống kê 4 cột.
- [ ] Tablet 768px: danh sách sách 2 cột.
- [ ] Mobile 390px: danh sách sách 1 cột.
- [ ] Không có cuộn ngang bất thường trên mọi trang.
- [ ] Form hiển thị đầy đủ, các trường không che lấp nhau.

## Accessibility cơ bản

- [ ] Có `lang="vi"` và `meta viewport`.
- [ ] Các thẻ `img` có nội dung `alt` phù hợp.
- [ ] Các trường form có `label` tương ứng.
- [ ] Có thể dùng bàn phím để truy cập các liên kết / trường form.
- [ ] Có trạng thái `:focus-visible` rõ ràng.

## Giới hạn hiện tại

Tuần 1 **không cần**: đăng nhập, CRUD thật, lưu localStorage, tìm kiếm có kết quả, REST API, kết nối PostgreSQL. Các mục này thực hiện ở tuần 2 và các tuần tiếp theo.
