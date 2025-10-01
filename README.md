# 🏨 Hotel Booking System – Lab 02

## 🎯 Giới thiệu
Đây là project **Lab 02** môn Phân tích & Thiết kế Hệ thống, với đề tài:  
**Hệ thống quản lý đặt phòng khách sạn**.  

Project bao gồm các phần:
- Thiết kế **ERD** (Entity Relationship Diagram)  
- Thiết kế **Use Case Diagram**  
- Thiết kế **Sequence Diagram**  
- Xây dựng **Product Backlog & Sprint Plan** trên Jira  
- Kết nối với **GitHub** và quản lý code bằng commit message theo chuẩn Jira  

---

## 👤 Thông tin sinh viên
- **Họ tên**: [Trần Thanh Hà]  
- **MSSV**: [N23DCPT018]  

---

## 🗂️ Nội dung chính
- **ERD**: [erd.puml](./diagrams/erd.puml)  
- **Use Case Diagram**: [usecase.puml](./diagrams/usecase.puml)  
- **Sequence Diagram**:  
  - [Đặt phòng online](./diagrams/seq_booking.puml)  
  - [Check-in/Check-out](./diagrams/seq_checkin.puml)  
- **Jira Backlog**: [jira-backlog.csv](./docs/jira-backlog.csv)  
- **Sprint Planning**: [jira-sprint-backlog.csv](./docs/jira-sprint-backlog.csv)  

---

## 🚀 Hướng dẫn sử dụng
1. Clone repo:
   ```bash
   git clone https://github.com/<your-username>/lab02-hotel-booking.git
Mở các file .puml bằng PlantUML hoặc VSCode plugin để render thành sơ đồ.

Import file CSV vào Jira:

jira-backlog.csv → tạo Product Backlog

jira-sprint-backlog.csv → phân chia theo Sprint

📊 Sprint Plan
Sprint 1: Auth (Đăng ký/Đăng nhập), Search & Room Details

Sprint 2: Booking, Payment, Email confirmation

Sprint 3: Check-in & Check-out (Receptionist)

Sprint 4: Housekeeping, Quản lý giá phòng, Báo cáo doanh thu

Smart Commit với Jira

bash

git commit -m "HBS-12 #comment Added booking sequence diagram #time 2h #done"
