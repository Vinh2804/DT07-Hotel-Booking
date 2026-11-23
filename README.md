# DT07 – HỆ THỐNG QUẢN LÝ KHÁCH SẠN VÀ ĐẶT PHÒNG

## 1. Giới thiệu đề tài

Đồ án DT07 tập trung phân tích, thiết kế và xây dựng hệ thống quản lý khách sạn và đặt phòng. Hệ thống hỗ trợ quản lý thông tin khách sạn, phòng, khách hàng, giao dịch đặt phòng và các nghiệp vụ liên quan.

## 2. Mục tiêu

- Quản lý thông tin khách sạn, loại phòng và phòng.
- Tìm kiếm phòng trống theo thời gian lưu trú.
- Hỗ trợ đặt phòng, hủy phòng và thay đổi đặt phòng.
- Quản lý thanh toán, nhận phòng và trả phòng.
- Ngăn chặn tình trạng đặt trùng phòng.
- Tối ưu tìm kiếm phòng trống bằng Redis Cache.

## 3. Công nghệ sử dụng

| Thành phần | Công nghệ |
|---|---|
| Cơ sở dữ liệu | PostgreSQL |
| Cache | Redis |
| Ngôn ngữ | Java |
| Backend | Spring Boot |
| ORM | JPA/Hibernate |
| Database Migration | Flyway |

## 4. Thành viên nhóm

| STT | Họ và tên | Vai trò |
|---|---|---|
| 1 | Nguyễn Quang Vinh | Trưởng nhóm |
| 2 | Nguyễn Tố Uyên | Thiết kế CSDL |
| 3 | Bùi Phúc Vương | Lập trình CSDL |
| 4 | Nguyễn Văn Vinh | Backend Java |
| 5 | Vũ Xuân Trường | Dữ liệu và kiểm thử |
| 6 | Phạm Quang Vinh | Cache và hiệu năng |

## 5. Cấu trúc dự án

- `documents/`: Tài liệu phân tích và báo cáo.
- `database/`: Cấu trúc CSDL và câu lệnh SQL.
- `backend/`: Mã nguồn Java Spring Boot.
- `scripts/`: Các script hỗ trợ.
- `test/`: Tài liệu và mã kiểm thử.
- `docs/`: Hướng dẫn triển khai.

## 6. Tiến độ thực hiện

- Tuần 1–2: Khởi động và phân tích nghiệp vụ.
- Tuần 3–5: Thiết kế và xây dựng cơ sở dữ liệu.
- Tuần 6–7: Lập trình cơ sở dữ liệu.
- Tuần 8–10: Phát triển ứng dụng Java và kiểm thử.
- Tuần 11–12: Hoàn thiện báo cáo và sản phẩm.
- Tuần 13: Bảo vệ đồ án.

## 7. Quản lý mã nguồn

Mã nguồn và tài liệu được quản lý tập trung trên GitHub. Các thành viên có trách nhiệm cập nhật tiến độ và lưu sản phẩm theo đúng cấu trúc thư mục chung.
