1. Entity & ERD
- Các bảng dữ liệu chính:

- Guest(GuestID, Name, Phone, Email, Address)

- RoomType(TypeID, Name, Price, Capacity, Description)

- Room(RoomID, TypeID, Status, Floor)

- Reservation(ResvID, GuestID, RoomID, StaffID, CheckInDate, CheckOutDate, Status)

- Payment(PaymentID, ResvID, Amount, Method, Status, Date)

- Staff(StaffID, Name, Role, Username, PasswordHash)

## Quan hệ:

- Guest 1–N Reservation

- Reservation 1–N Payment

- RoomType 1–N Room

- Room 1–N Reservation

- Staff 1–N Reservation

## - ERD:
![SƠ ĐỒ ERD](https://github.com/miao0w025/BT-LAB02/blob/main/01/ERD.png)
