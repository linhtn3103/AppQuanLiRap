# AppQuanLiRap </br>
### File config </br>
- Thiết lập lại cấu hình database tại hàm load, file database.java
### Cấu trúc thư mục </br>
- Entity: Chứa class tạo đối tượng, làm cầu nối truyền data  </br>
- Controller: Nhiệm vụ duy nhất là load hàm từ model và đợi view gọi, xác nhận vài thứ cần xác nhận  </br>
- Model: Thằng này kết nối tới database đến gọi dữ liệu ra
- View: Thằng này hiển thị và xử lý event thực hiện trên giao diện, truyền dữ liệu và gọi đến Controller </br>
- Util: Thằng này viết là do lười, mấy hàm hay xài ném vào đây cho lẹ

