# HQTCSDL_DTAP
## Thông tin sinh viên:
+ **Họ và tên:** Dương Thị Anh Phương
+ **Mã sinh viên:** K235480106056
+ **Lớp:** K235480106056
+ **Trường:** Đại học Kỹ thuật Công nghiệp Thái Nguyên
---
### 1. Cài đặt SQL Server
* Add current user
<img width="1920" height="1080" alt="hihi" src="https://github.com/user-attachments/assets/82adbb29-1f70-4b21-8ad1-a57a48aec69e" />

### 2. Các server đang chạy 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d0111ea6-87ba-40e9-a0d9-f2be8e3109d5" />

+ Enable TCP/IP
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c55d095-256c-4089-bbd9-b734bfa26ac7" />

+ Cấu hình chi tiết TCP/IP
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ce2ed396-6c06-4005-9a9d-0095d4751332" />

 + Listen ALL = YES
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/18f567d6-35b6-4367-a3fd-097370c8fd9f" />

+ IP Adress
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/664a474c-d082-4f36-85eb-dfebaf2d2104" />

+ Restart server SQL
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ff1bf1c4-404b-4c21-924e-6e99e7e5dcde" /> 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8160fe7-0682-43f0-bb66-2bb66da72602" />

### 3. kiểm tra cổng `36056` đang mở bằng lệnh `netstat -ano | findstr LISTENING`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/730e9c35-75e3-45bf-91c0-a18750ff4c87" />

### 4. Cài đặt _SQL Server Management Studio_
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/55a6b76d-1559-4e6b-aae6-210ce1034efe" />

### 5. Chạy phần mềm SQL Management Studio 22 bằng 2 kiểu: _Windows Authentication_ và _SQL Server Authentication_
+ Đăng nhập bằng Window Authentication
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/54a180d4-bd1c-4788-9f5d-199795e41475" />

+ Đăng nhập bằng username và password
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/84d2053e-5d33-4686-b44c-fe40da84769e" />

### 6. Tạo mới cở sở dữ liệu
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/e18eebeb-b371-408d-9db3-4a4abce81ef3" />

+ Kiểm tra path
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5715aaf0-363d-42a6-8097-43bb847be8ce" />

### 7. Tạo database `DuongPhuong` có trường `masv` là Khóa chính (Primary key)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c42c7d49-5781-4999-b453-27d940d2b03d" />

### 8. Import file dữ liệu `svtnut.csv`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2a5d7d9a-5e62-4acc-8b68-2e9fac5c7fa3" />

### 9. Gõ lệnh kiểm tra số dòng của bảng dữ liệu sau khi import
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e4b479c7-1a2c-4449-861a-047bd8870dc5" />

### 10. Thêm 1 row vào bảng với dữ liệu là thông tin của sinh viên đang làm bài 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3cfbd132-c596-40a8-b329-8eb78e2890da" />

### 11. Update trường `noisinh` thành `Sao Hỏa` cho những dòng có `noisinh` đều là `NULL`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e507e214-c48e-41ce-8a57-49338cf0f700" />

### 12. Tạo bảng `SaoHoa` sử dụng câu lệnh `SELECT + INTO`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/601d9157-72da-412e-acd2-365182f5a8e1" />

### 13. Xóa những sinh viên họ `Dương` có trong bảng `SaoHoa`
<img width="1920" height="1078" alt="image" src="https://github.com/user-attachments/assets/2d8beee8-c00b-4986-be3e-f2ca2ae16ed8" />

### 14. Xuất toàn bộ kết quả của các bước 6,7,8,9,10,11,12,13 ra file `dulieu.sql`, keyword sử dụng tính năng GEN SCRIPT `struct + data` cho database
<img width="1920" height="1075" alt="image" src="https://github.com/user-attachments/assets/e930ffae-e864-4778-a5b8-df36ac1c56a1" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/11905e5b-46c2-4f7a-9623-49d4fcaba47d" />
  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3f00f96a-98ea-4b41-bd51-8269d4e3fff9" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/224ee5c4-6ab9-4f9d-9b21-fcf94d65d24e" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d7884a95-0064-40cf-ba66-a57364974e8b" />

### 15. Xóa cơ sở dữ liệu đã tạo và kiểm tra lại file 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9e86d79b-9b3a-40eb-8ae7-05a0b0ed7c33" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/530109f3-7d7d-4594-9b1d-986e81bb2487" />

### 16. chạy toàn bộ các lệnh trong file dulieu.sql
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a8d557e-f231-4a3a-8378-bcd2c63d0a37" />

### 17. Upload file dulieu.sql lên github repository 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b1447165-9474-4734-b204-0722ccee0e96" />
