
Vào thư mục server trong DoAn, mở thư mục bằng Visual Studio Code và chạy lệnh "npm install"

Vào trong file DoAn/server/models/index.js sẽ có đoạn ConnectionString như sau:
  "mssql://sa:2@localhost/Bakery?TrustServerCertificate=true&encrypt=false&Trusted_Connection=true"
        [taikhoangsqlserver:password@localhost]
            
- Đổi tên tk thành sa và password của mình

- Sau khi chạy hoàn tất thì chạy lệnh "npm start" và vào đường dẫn   --->       localhost:3000 (yêu cầu có cơ sở dữ liệu)

--------- Thành viên nhóm --------
Trương Quang Đạt
Lê Ngọc Hân
Dương Bảo Minh
Nguyễn Hoàng Minh
Đinh Hoàng Thùy Linh
