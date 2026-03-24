# bai6bbb
- Bài tập HDH Nhúng - Ứng dụng tổng hợp
- Giao tiếp với Device Driver từ ứng dụng
- Kích hoạt Device Driver của BBB để tương tác.
- Tương tác với device driver của GPIO của BBB thông qua 2 lệnh cat và echo với device
- tương ứng trong thư mục /dev/.
- Điều khiển thành công ngoại vi LED: ON, OFF.

- https://github.com/user-attachments/assets/e600e4eb-9076-4d88-bcd9-28d601d97cc6
  
- Viết chương trình giao tiếp:
- Từ Device Driver đã tương tác, viết 1 chương trình C/C++ thực hiện giao tiếp với DeviceDriver GPIO để điều khiển Blink LED.
- Đóng gói chương trình theo yêu cầu của tuần 5, đảm bảo Driver và Chương trình đều
nằm sẵn trong Image được tạo ra bởi Buildroot.

![v1](https://github.com/user-attachments/assets/a57f152d-92c7-4385-8510-347ca40f36ae)
![v2](https://github.com/user-attachments/assets/34231494-eb6d-41d3-ad62-0938b9c68809)
![v3](https://github.com/user-attachments/assets/19930282-87f6-46da-84c4-71bf1ce5e4a7)


Tự khởi chạy
- Yêu cầu: Cấu hình ứng dụng tự động khởi động ngay sau khi OS đã khởi động thành
công. Sau khi tạo Image, cài đặt vào thẻ nhớ, cắm nguồn cho Board, ứng dụng tự động
- khởi chạy và nhấp nháy LED mà không yêu cầu một can thiệp nào cả.-

![v4](https://github.com/user-attachments/assets/7dbcf9a7-f212-4b7d-91b7-ce761a4a985d)

https://github.com/user-attachments/assets/05e7e6f5-24c4-449a-a7c1-efabf08e1eff
