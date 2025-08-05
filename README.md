ỨNG DỤNG KẾT NỐI HAI ỨNG DỤNG WEB FLASK QUA MẠNG LAN ĐỂ QUẢN LÝ SINH VIÊN
Giới thiệu
Đây là một mô hình ứng dụng web gồm 2 ứng dụng Flask độc lập chạy trên 2 máy tính khác nhau trong cùng mạng LAN. Ứng dụng mô phỏng cách giao tiếp giữa các hệ thống qua HTTP API, cụ thể:

App1: Chạy ở máy A, đóng vai trò là máy chủ API, quản lý cơ sở dữ liệu sinh viên (lưu trữ, cung cấp API).

App2: Chạy ở máy B, gọi API từ App1 để tra cứu thông tin sinh viên theo mã sinh viên.

Công nghệ sử dụng
Backend API :	Python Flask
Giao diện người dùng : HTML + Bootstrap
Cơ sở dữ liệu	: SQL Server (kết nối bằng pyodbc)
Giao tiếp	: RESTful API (Flask → Flask)
Giao tiếp liên máy : HTTP qua IP + Port
