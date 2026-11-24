# Personal Library — Ứng dụng Web quản lý tủ sách cá nhân

> **Project 1 | Dự án học tập Full-stack**  
> **Trạng thái:** Đang xây dựng — Giai đoạn 1: giao diện HTML/CSS.

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

