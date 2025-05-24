# Dự án Xe Tự Động Phát Hiện và Né Vật Cản

## Giới thiệu

Đây là đồ án lập trình hệ thống xe tự hành sử dụng mô hình xe Bosch, dành cho mục đích học tập. Xe có khả năng:
- **Phát hiện vật cản** bằng cảm biến siêu âm (ultrasonic sensors).
- **Xử lý dữ liệu cảm biến theo thời gian thực** và ra quyết định tránh vật cản.
- **Điều khiển động cơ** một cách thông minh bằng các thuật toán tự lập trình.

**Ngôn ngữ lập trình sử dụng**: C  
**Nền tảng**: Mô hình xe giáo dục do Bosch cung cấp

---

## Công Nghệ Sử Dụng

- Mô hình xe Bosch (Bosch Educational Vehicle Kit)
- Cảm biến siêu âm để phát hiện vật cản
- Vi điều khiển hoặc bộ xử lý trung tâm (MCU)
- Thuật toán điều khiển động cơ và tránh vật cản bằng ngôn ngữ C
- Xử lý dữ liệu cảm biến thời gian thực
- Logic ra quyết định khi gặp vật cản

---

## 📹 Video Demo 1: 
👉 [![Video Demo 1]](https://drive.google.com/file/d/1v9OQXBf6ikuspwDlL1Kky2d1CrhrFx25/view?usp=drive_link)

---

## 📹 Video Demo 2: 
👉 [![Video Demo 2]](https://drive.google.com/file/d/17eL64JaBLRLlMKWF38_FmX7BHsPZAvZh/view?usp=drive_link)

---

## 📁 Cấu trúc thư mục

```bash
📦xe-tu-dong
 ┣ 📂src                # Mã nguồn C điều khiển
 ┣ 📂docs               # Tài liệu hướng dẫn
 ┣ 📂video              # File video (nếu đính kèm)
 ┣ 📄README.md          # File giới thiệu dự án
 ┗ 📄Makefile / main.c  # File thực thi chương trình
