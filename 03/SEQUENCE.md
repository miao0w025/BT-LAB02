## Sequence Diagram
a) Luồng Đặt phòng online:

- Guest chọn phòng → hệ thống giữ phòng (hold).

- Guest nhập thông tin → hệ thống xác nhận & tạo Reservation.

- Thanh toán online → Payment Gateway trả kết quả.

- Hệ thống gửi mail xác nhận.

![seq_diagram_booking](https://github.com/miao0w025/BT-LAB02/blob/main/03/SEQ_BOOKING.png)

b) Luồng Check-in/Check-out (Lễ tân):

- Receptionist nhập mã đặt phòng.

- Hệ thống tìm & trả về thông tin phòng.

- Check-in: gán phòng thực tế, cập nhật trạng thái.

- Check-out: tổng hợp chi phí, cập nhật trạng thái phòng, in hóa đơn.

![seq_diagram_checkinout](https://github.com/miao0w025/BT-LAB02/blob/main/03/SEQ_CHECKIN.png)
