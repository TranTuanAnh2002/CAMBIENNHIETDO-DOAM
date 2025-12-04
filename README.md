
# 📱 Ứng dụng Giám Sát nhiệt độ và độ ẩm

## 🎥 Video Demo

[![Watch the video](https://img.youtube.com/vi/WhR6thEL0Lo/hqdefault.jpg)](https://www.youtube.com/watch?v=WhR6thEL0Lo)


---

## 👨‍💻 Nhóm thực hiện

- TRẦN TUẤN ANH
- LÊ MINH DŨNG
- GIÁP TÙNG LINH

---

## 📌 Tính năng chính

- Giám sát **nhiệt độ** và **độ ẩm** từ cảm biến.
- Điều khiển **bật/tắt LED** thông qua app.
- Lưu và hiển thị dữ liệu thời gian thực lên **Firebase Realtime Database**.
- Ứng dụng Android giao diện trực quan dễ sử dụng.

---

## 📸 Hình ảnh minh họa

### 🔥 Ảnh Firebase
| Dữ liệu Firebase | Cấu hình Rules |
|:----------------|:---------------|
| ![Firebase Data](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhfirebase/dữ%20liệu%20firebase.jpg) | ![Firebase Rules](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhfirebase/dữ%20liệu%20rules.jpg) |

---

### 📌 Ảnh Code

#### 🔹 Code 1
![Code 1](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhcode/%E1%BA%A3nh%20code1.jpg)

#### 🔹 Code 2
![Code 2](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhcode/%E1%BA%A3nh%20code2.jpg)

#### 🔹 Code 3
![Code 3](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhcode/%E1%BA%A3nh%20code3.jpg)

#### 🔹 Code 4
![Code 4](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhcode/%E1%BA%A3nh%20code4.jpg)

---

### 📱 Ảnh Thiết kế App
| Thiết kế Blocks |  App thực tế |
|:----------------|:------------|
| ![Thiết kế Blocks](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhthietkeapp/%E1%BA%A3nh%20thi%E1%BA%BFt%20k%E1%BA%BF%20blocks.jpg) | ![App thực tế](https://raw.githubusercontent.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM/main/anhthietkeapp/app%20th%E1%BB%B1c%20t%E1%BA%BF.jpg) |


## 🛠️ Hướng dẫn cài đặt:

### 📌 1. Cài đặt Arduino IDE
- Tải và cài Arduino IDE từ: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

### 📌 2. Thêm board ESP32 cho Arduino IDE:
- Vào **File > Preferences**
- Tại **Additional Board Manager URLs** dán: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
- Vào **Tools > Board > Boards Manager**
- Tìm **ESP32** và cài đặt

### 📌 3. Cài đặt thư viện:
- **Firebase ESP Client**
- **DHT sensor library**
- Cài trực tiếp trong **Tools > Manage Libraries**

### 📌 4. Kết nối Firebase:
- Tạo Realtime Database trên Firebase Console
- Lấy `Database URL` và `Secret key` để khai báo vào code Arduino

### 📌 5. Làm App bằng Mit App Inventor:
- Vào [https://ai2.appinventor.mit.edu/](https://ai2.appinventor.mit.edu/)
- Import file thiết kế blocks hoặc làm theo demo ảnh `Blocks.png`
- Kết nối API Firebase và control thiết bị

### 📥 Clone project từ GitHub

```bash
git clone https://github.com/TranTuanAnh2002/CAMBIENNHIETDO-DOAM.git
```

## 📞 Liên hệ
- ☎️ **Số điện thoại**: 0352413098
- 📧 **Email**: tuananh2002songphuong@gmail.com
