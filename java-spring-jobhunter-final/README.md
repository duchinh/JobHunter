## JobHunter - Java Spring Boot Project

JobHunter là một hệ thống quản lý và tìm kiếm việc làm được xây dựng bằng Spring Boot, cung cấp API backend cho ứng dụng web tìm việc.

### Tính năng chính
- Quản lý tài khoản người dùng (đăng ký, đăng nhập, phân quyền)
- Quản lý công ty, tin tuyển dụng, hồ sơ ứng viên
- Tìm kiếm và lọc việc làm theo nhiều tiêu chí
- Quản lý và duyệt hồ sơ ứng viên
- Tích hợp với frontend React Vite

### Công nghệ sử dụng
- Java 17, Spring Boot 3
- Spring Data JPA, Hibernate
- MySQL/PostgreSQL
- RESTful API
- Docker (tuỳ chọn)

### Cấu trúc thư mục
- `src/main/java`: Mã nguồn backend
- `src/main/resources`: Cấu hình, template, static files
- `build.gradle.kts`: File cấu hình Gradle

### Hướng dẫn chạy dự án
1. Cài đặt Java 17 và MySQL/PostgreSQL
2. Cấu hình database trong `src/main/resources/application.properties`
3. Chạy lệnh sau để build và khởi động server:
	```powershell
	./gradlew bootRun
	```
4. Truy cập API tại `http://localhost:8080`

### Tác giả
- Duchinh

---
Frontend: [react-vite-jobhunter](../react-vite-jobhunter)


