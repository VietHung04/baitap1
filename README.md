<div align="center"><b>ỨNG DỤNG KẾT NỐI HAI ỨNG DỤNG WEB FLASK QUA MẠNG LAN ĐỂ QUẢN LÝ SINH VIÊN</b></div>  <br>

Đây là một mô hình ứng dụng web gồm 2 ứng dụng Flask độc lập chạy trên 2 máy tính khác nhau trong cùng mạng LAN. Ứng dụng mô phỏng cách giao tiếp giữa các hệ thống qua HTTP API, cụ thể:
- App1: Chạy ở máy A, đóng vai trò là máy chủ API, quản lý cơ sở dữ liệu sinh viên (lưu trữ, cung cấp API).
- App2: Chạy ở máy B, gọi API từ App1 để tra cứu thông tin sinh viên theo mã sinh viên.

**Công nghệ sử dụng** 
- Backend API :	Python Flask  
- Giao diện người dùng : HTML + Bootstrap  
- Cơ sở dữ liệu	: SQL Server (kết nối bằng pyodbc)  
- Giao tiếp	: RESTful API (Flask → Flask)  
- Giao tiếp liên máy : HTTP qua IP + Port

**Giao diện minh họa**

**Nhập thông tin sinh viên**  

<img width="1439" height="792" alt="image" src="https://github.com/user-attachments/assets/574e2c5e-127d-4a14-979e-cd5b7d78a456" />

**Tra cứu sinh viên**  

<img width="1433" height="610" alt="image" src="https://github.com/user-attachments/assets/f245acca-1a12-4141-ad6b-bef47e95e21d" />

