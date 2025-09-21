
## JobHunter Frontend - React Vite

Đây là giao diện web cho hệ thống JobHunter, xây dựng bằng React và Vite, kết nối với backend Spring Boot.

### Tính năng chính
- Đăng ký, đăng nhập, phân quyền người dùng
- Quản lý công ty, tin tuyển dụng, hồ sơ ứng viên
- Tìm kiếm, lọc và ứng tuyển việc làm
- Giao diện quản trị cho admin
- Responsive, tối ưu trải nghiệm người dùng

### Công nghệ sử dụng
- React, TypeScript
- Vite
- Redux Toolkit
- SCSS Modules
- Axios

### Cấu trúc thư mục
- `src/components`: Các component chia theo chức năng (admin, client, share)
- `src/pages`: Các trang chính (home, auth, admin)
- `src/config`: Cấu hình API, axios
- `src/redux`: Store, slice
- `src/styles`: SCSS

### Hướng dẫn chạy dự án
1. Cài đặt Node.js >= 18
2. Cài đặt package:
	```powershell
	npm install
	```
3. Chạy dự án:
	```powershell
	npm run dev
	```
4. Truy cập giao diện tại `http://localhost:5173`

### Tác giả
- Duchinh

---


Các bước cài đặt: (chế độ development)
1. clone code
2. cài đặt thư viện: npm i
3. Update file .env.development (nếu cần thiết)
4. Chạy dự án: npm run dev

===

Cách chạy tại chế độ production:
1. clone code
2. cài đặt thư viện: npm i
3. Update file .env.production (nếu cần thiết)
4. Build dự án: npm run build
5. Chạy dự án: npm run preview