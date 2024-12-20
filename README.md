# Hệ Thống Luyện Tập Trắc Nghiệm Trực Tuyến

Mô tả dự án: Đây là một hệ thống hỗ trợ người dùng luyện tập các bài tập trắc nghiệm trực tuyến một cách hiệu quả. Dự án được xây dựng như một bài tập thực hành cá nhân nhằm nâng cao kỹ năng lập trình và quản lý dự án.

## Các tính năng chính:
- **Quản lý tài khoản người dùng**:
  - Đăng ký, đăng nhập tài khoản.
  - Khôi phục mật khẩu qua email với kiểm tra email hợp lệ.
  - Luyện tập trắc nghiệm.

- **Hiển thị danh sách bài tập**:
  - Theo danh mục.
  - Trả lời các câu hỏi trắc nghiệm và xem kết quả.
  - CRUD dữ liệu (dành cho Admin).

- **Quản lý danh mục trắc nghiệm, câu hỏi và thông tin người dùng**:
  - Các chức năng thêm, sửa, xóa dữ liệu.
  - Giao diện tối ưu, responsive.

- **Thân thiện với người dùng**:
  - Hỗ trợ tốt trên nhiều loại thiết bị.
  - Thông báo qua email.

- **Gửi email xác nhận thay đổi thông tin tài khoản.**

## Công nghệ sử dụng:
- **Back-end**: Java (JDBC, JPA, MVC).
- **Front-end**: HTML, CSS, JSP.
- **Cơ sở dữ liệu**: SQL Server.

## Môi trường phát triển:
- **IDE**: NetBeans.
- **Server**: Apache Tomcat.
- **Cơ sở dữ liệu**: SQL Server.

## Hướng dẫn cài đặt và chạy dự án:
1. Clone dự án:
   ```bash
   git clone https://github.com/DinhHoangQuocVuong/43ulsa.git
2.Mở dự án bằng NetBeans hoặc IDE tương thích.
3.Cấu hình kết nối cơ sở dữ liệu:
Import file cấu hình cơ sở dữ liệu (nếu có).
4.Triển khai trên Server Apache Tomcat.
5.Mở trình duyệt và truy cập địa chỉ:
http://localhost:8080/[project-name]
