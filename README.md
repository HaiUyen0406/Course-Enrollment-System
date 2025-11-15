### 📘Course Enrollment System
Dự án cơ sở dữ liệu quản lý đăng ký học phần cho sinh viên. Bao gồm tạo bảng, thiết lập ràng buộc, thêm dữ liệu mẫu và thực hiện các truy vấn thống kê – phân tích dữ liệu phục vụ quản lý học vụ.

### 🚀Mục tiêu dự án
- Xây dựng cơ sở dữ liệu mô phỏng hệ thống đăng ký môn học của trường đại học.
- Thực hành thiết kế bảng, khóa chính – khóa ngoại, ràng buộc dữ liệu.
- Thực hiện các truy vấn thống kê, phân tích dữ liệu theo nhiều tiêu chí.
- Rèn luyện kỹ năng SQL thực tế như JOIN, GROUP BY, HAVING, AGGREGATION, UPDATE theo bảng khác.
  
### 📌Nội dung chính của dự án 
1. Các bảng chính
- DEPARTMENTS – Thông tin Khoa  
- STUDENTS – Thông tin Sinh viên  
- COURSES – Thông tin Môn học  
- ENROLLMENTS – Đăng ký học phần   
2. Thiết lập ràng buộc: 
- PRIMARY KEY: đảm bảo mỗi bản ghi là duy nhất
- FOREIGN KEY: liên kết giữa bảng Sinh viên, Môn học và Khoa
- CHECK: ràng buộc logic (ví dụ: tín chỉ > 0)
- UNIQUE: email sinh viên không trùng 
3. Các truy vấn thống kê:
- Thống kê số lượng học phần theo khoa  
- Thống kê sinh viên đăng ký nhiều học phần  
- Thống kê số lượng đăng ký theo môn  
- Truy vấn theo học kỳ, năm học, tín chỉ,…  

### 📂Tất cả mã SQL ở trong Course_enrollment.sql gồm:
+ Lệnh tạo database
+ Lệnh tạo bảng
+ Lệnh thêm dữ liệu
+ Lệnh cập nhật

### 📥Cách chạy dự án
- Mở SQL Server Management Studio (SSMS)
- Chạy toàn bộ nội dung file Course_enrollment.sql
- Kiểm tra các bảng đã được tạo
- Chạy các truy vấn phân tích ở cuối file

### 👤Tác giả: 
Nguyễn Cửu Hải Uyên  
Dự án thực hành học phần Cơ sở dữ liệu.
