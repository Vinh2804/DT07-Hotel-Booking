
# QUY ĐỊNH LÀM VIỆC NHÓM

## 1. Quy định về Branch

Không làm việc trực tiếp trên nhánh main.

Mỗi thành viên sử dụng một nhánh riêng:

- feature/business-analysis
- feature/database-sql
- feature/backend
- feature/testing
- feature/redis-cache

## 2. Quy định về Commit

Commit message cần ngắn gọn, thể hiện rõ nội dung thay đổi.

- docs: add business requirements
- database: create hotel tables
- backend: add booking controller
- test: add booking test cases
- cache: implement Redis caching

## 3. Quy trình làm việc

1. Pull code mới nhất từ main.
2. Chuyển sang branch cá nhân.
3. Thực hiện công việc được giao.
4. Commit thay đổi.
5. Push branch lên GitHub.
6. Tạo Pull Request.
7. Trưởng nhóm kiểm tra và merge.

## 4. Quy định bảo mật

- Không đưa mật khẩu vào source code.
- Không commit file .env thật.
- Không đưa thông tin cá nhân của khách hàng thật lên Repository.
- Không tự ý xóa hoặc sửa dữ liệu của thành viên khác.
