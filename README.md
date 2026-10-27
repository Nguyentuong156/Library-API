# FastAPI Library Management API

Dự án xây dựng một Web API quản lý thư viện sử dụng **FastAPI**, **Pydantic v2**, và In-memory Data Store, được thiết kế để thực hiện đầy đủ các thao tác CRUD và kiểm thử tự động.

---

## 🚀 Các Tính Năng Chính
- **Quản lý Sách (Books CRUD):**
  - Lấy danh sách toàn bộ sách (hỗ trợ phân trang `skip`, `limit` và bộ lọc theo `author`, `year`).
  - Xem chi tiết thông tin sách theo `id`.
  - Thêm mới sách (`POST /books`) với kiểm tra trùng lặp mã `isbn`.
  - Cập nhật toàn bộ thông tin sách (`PUT /books/{id}`).
  - Cập nhật một phần thông tin sách (`PATCH /books/{id}`).
  - Xóa sách theo `id` (`DELETE /books/{id}`).
- **Kiểm tra trạng thái hệ thống:** Endpoint `/health` kiểm tra tình trạng hoạt động của ứng dụng.

---

## 🛠️ Công Nghệ Sử Dụng
- **Python 3.10+ / FastAPI**
- **Uvicorn** (ASGI Server)
- **Pydantic** (Validation dữ liệu)
- **Thunder Client / Postman** (Kiểm thử API)

---

## ⚙️ Hướng Dẫn Cài Đặt và Chạy Ứng Dụng

1. **Clone repository và di chuyển vào thư mục dự án:**
   ```bash
   git clone [https://github.com/Nguyentuong156/Library-API.git](https://github.com/Nguyentuong156/Library-API.git)
   cd Library-API
