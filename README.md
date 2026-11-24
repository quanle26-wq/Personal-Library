<<<<<<< HEAD
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
=======
# Personal Library — Ứng dụng Web quản lý tủ sách cá nhân

> **Project 1 | Dự án học tập Full-stack**  
> **Trạng thái:** Đang xây dựng

## 1. Giới thiệu

**Personal Library** là ứng dụng Web giúp người dùng tổ chức và quản lý tủ sách cá nhân. Người dùng có thể lưu thông tin sách, phân loại, tìm kiếm và theo dõi quá trình đọc. Trong các giai đoạn sau, ứng dụng sẽ hỗ trợ tài khoản riêng, thống kê thói quen đọc và nhật ký đọc sách.

Dự án được thực hiện nhằm thực hành quy trình phát triển Web từ **Frontend → Backend → Cơ sở dữ liệu → Triển khai**, với mục tiêu xây dựng một sản phẩm có thể sử dụng thực tế.

## 2. Mục tiêu

- Thiết kế giao diện đơn giản, dễ sử dụng và tương thích với máy tính, điện thoại.
- Nắm vững HTML, CSS, JavaScript và React.
- Xây dựng REST API với Java Spring Boot.
- Thiết kế và quản lý dữ liệu bằng PostgreSQL.
- Tích hợp Frontend với Backend, kiểm thử và triển khai ứng dụng.

## 3. Chức năng dự kiến

### Chức năng cốt lõi (MVP)

- Hiển thị danh sách sách trong tủ sách cá nhân.
- Thêm, xem chi tiết, chỉnh sửa và xóa sách (CRUD).
- Tìm kiếm sách theo tên hoặc tác giả.
- Lọc sách theo thể loại và trạng thái đọc.
- Quản lý trạng thái: **Muốn đọc**, **Đang đọc**, **Đã đọc**, **Tạm dừng**.
- Theo dõi tổng số trang và số trang đã đọc.

### Chức năng mở rộng

- Đăng ký, đăng nhập và quản lý dữ liệu theo tài khoản.
- Nhật ký đọc sách và ghi chú.
- Đặt mục tiêu đọc sách theo tháng hoặc năm.
- Thống kê sách đã đọc, tiến độ và hoạt động đọc.
- Đánh giá sách; gợi ý sách phù hợp (nếu đủ dữ liệu).

## 4. Công nghệ sử dụng

| Thành phần | Công nghệ | Giai đoạn |
| --- | --- | --- |
| Giao diện cơ bản | HTML5, CSS3 | Tuần 1 |
| Xử lý tương tác | JavaScript | Tuần 2 |
| Frontend | React | Từ tuần 3 |
| Backend | Java, Spring Boot | Từ tuần 4 |
| Cơ sở dữ liệu | PostgreSQL | Từ tuần 5 |
| API | REST, JSON | Từ tuần 4 |
| Quản lý mã nguồn | Git, GitHub | Xuyên suốt |

## 5. Cấu trúc thư mục giai đoạn 1

```text
personal-library/
├── index.html           # Trang chính
├── style.css            # Giao diện và responsive
├── assets/
│   └── images/          # Hình ảnh/ảnh bìa sách mẫu
└── README.md            # Tài liệu dự án
```

Khi phát triển lên Full-stack, dự án dự kiến tách thành hai thư mục `frontend/` (React) và `backend/` (Spring Boot).

## 6. Định hướng kiến trúc Full-stack

```text
Người dùng / Trình duyệt
          |
          v
    React Frontend
          |
       REST API
          |
          v
 Java Spring Boot Backend
          |
   Spring Data JPA
          |
          v
      PostgreSQL
```

Ở giai đoạn đầu, giao diện HTML/CSS hoạt động độc lập; các tầng Backend và Database sẽ được bổ sung theo lộ trình.

>>>>>>> fabfff485d65be6dc36cf313dce027795d45da52
