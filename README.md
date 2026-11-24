# Folio — Personal Library 📚

**Project 1 | Ứng dụng Web quản lý tủ sách cá nhân**  
**Phiên bản hiện tại:** Giao diện tĩnh tuần 1 (HTML5 + CSS3)  
**Tác giả:** [Điền tên của bạn] · **Trường:** [Điền thông tin nếu cần]

## Giới thiệu

Folio là bản giao diện mẫu cho hệ thống quản lý tủ sách cá nhân. Khi hoàn thiện, người dùng sẽ có thể lưu trữ thông tin sách, phân loại, tìm kiếm, cập nhật trạng thái và theo dõi quá trình đọc.

> **Quan trọng:** Phiên bản tuần 1 chỉ có HTML/CSS. Tìm kiếm, lọc sách và lưu biểu mẫu **chưa hoạt động**; các chức năng này sẽ được lập trình bằng JavaScript trong tuần 2. Dữ liệu và thống kê trên trang là **dữ liệu minh họa**, không phải dữ liệu từ cơ sở dữ liệu.

## Những gì đã xây dựng trong tuần 1

- [x] Trang chủ `index.html` với header, điều hướng, banner giới thiệu.
- [x] Danh sách **9 cuốn sách mẫu**; mỗi thẻ có bìa minh họa, tên, tác giả, thể loại và trạng thái đọc.
- [x] Các thẻ thống kê mẫu: **9** sách, **3** đã đọc, **2** đang đọc, **4** muốn đọc.
- [x] Ô tìm kiếm và bộ lọc dưới dạng **giao diện**.
- [x] Trang `add-book.html` chứa biểu mẫu thêm sách dưới dạng **giao diện**.
- [x] CSS với Flexbox, Grid, `:hover`, `:focus-visible` và responsive.
- [x] Ảnh bìa tự tạo ở định dạng SVG — chạy offline, không cần tải ảnh trên Internet.
- [x] README, hướng dẫn Git/GitHub và checklist học tập.
- [ ] **Đăng dự án lên GitHub của bạn** (cần thực hiện từ máy/tài khoản GitHub của bạn).

## Cách chạy ứng dụng

Cách 1 — Không cần cài đặt:

1. Giải nén thư mục dự án.
2. Mở `index.html` bằng trình duyệt Chrome / Edge / Firefox.
3. Nhấn **Thêm sách** để tới trang biểu mẫu.

Cách 2 — Dùng VS Code (khuyến nghị):

1. Mở thư mục bằng **File → Open Folder**.
2. Cài extension **Live Server** trong VS Code.
3. Nhấn chuột phải vào `index.html` → **Open with Live Server**.
4. Xem giao diện ở màn hình rộng và chế độ Responsive (F12 → Toggle Device Toolbar).

**Yêu cầu:** Trình duyệt hiện đại. **Không cần** Node.js, React, Java hoặc PostgreSQL ở tuần 1.

## Cấu trúc thư mục

```text
personal-library-tuan-1/
├── index.html                 # Trang tổng quan, danh sách sách
├── add-book.html              # Biểu mẫu thêm sách (giao diện tĩnh)
├── style.css                  # Màu sắc, bố cục, responsive
├── assets/
│   ├── logo.svg               # Logo mẫu
│   └── covers/                # 9 ảnh bìa minh họa tự tạo
├── docs/
│   ├── KE_HOACH_TUAN_1.md     # Học gì và làm gì trong 7 ngày
│   ├── HUONG_DAN_GITHUB.md    # Đưa dự án lên GitHub
│   └── KIEM_THU_TUAN_1.md     # Danh sách kiểm thử giao diện
├── screenshots/               # Ảnh chụp giao diện sau khi kiểm tra
├── .gitignore
└── README.md
```

## Các trang

| Trang | Nội dung | Trạng thái |
|---|---|---|
| `index.html` | Tổng quan, thống kê mẫu, thẻ sách, tìm kiếm và lọc tĩnh | Giao diện hoàn thành |
| `add-book.html` | Các trường nhập sách, trạng thái đọc, ghi chú | Giao diện hoàn thành; không lưu dữ liệu |

## Các chức năng dự kiến cho ứng dụng hoàn chỉnh

1. Thêm / sửa / xóa / xem chi tiết sách (CRUD).
2. Tìm kiếm theo tên hoặc tác giả; lọc theo thể loại và trạng thái.
3. Theo dõi sách muốn đọc, đang đọc, đã đọc, tạm dừng.
4. Cập nhật số trang, ghi chú, nhật ký đọc và mục tiêu đọc.
5. Tài khoản cá nhân, quản lý quyền truy cập dữ liệu.
6. Thống kê thói quen đọc; gợi ý sách là chức năng mở rộng nếu còn thời gian.

**Các mục trên đều là kế hoạch, không phải những tính năng đã chạy ở tuần 1.**

## Công nghệ và lộ trình

| Tuần | Nội dung |
|---|---|
| 1 | HTML, CSS, Flexbox, Grid, responsive (bản này) |
| 2 | JavaScript: CRUD, tìm kiếm/lọc, localStorage |
| 3 | React: Component, Props, State, form |
| 4 | Java Spring Boot: REST API |
| 5 | PostgreSQL + Spring Data JPA |
| 6 | Kết nối React với Spring Boot |
| 7 | Hoàn thiện CRUD và theo dõi đọc |
| 8 | Đăng nhập, xác thực, phân quyền |
| 9 | Kiểm thử, thống kê, cải thiện UX |
| 10 | Deploy, hoàn thiện báo cáo/demo |

## Tài liệu học

- [MDN — Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn_web_development)
- [HTML](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content)
- [CSS](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics)
- [Flexbox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox)
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Grids)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)

## Ghi chú

- Các ảnh bìa SVG là **thiết kế minh họa tự tạo**, không phải ảnh bìa chính thức của nhà xuất bản.
- Số sách, tiêu đề, thể loại và trạng thái trong trang chủ là dữ liệu mẫu cố định viết trực tiếp trong HTML.
- Để luyện tập thực chất, hãy thử tự chỉnh CSS, thêm một thẻ sách và đọc từng phần mã nguồn, thay vì chỉ nộp sản phẩm có sẵn.
