<h2 align="center">
  <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
  🎓 Faculty of Information Technology (DaiNam University)
  </a>
</h2>

<h2 align="center">
   GAME OẲN TÙ TÌ QUA MẠNG (TCP)
</h2>

<div align="center">
  <p align="center">
    <img src="LTM/src/assets/aiotlab_logo.png" alt="AIoTLab Logo" width="160"/>
    <img src="LTM/src/assets/fitdnu_logo.png" alt="FIT DNU Logo" width="180"/>
    <img src="LTM/src/assets/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
  </p>

  [![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
  [![Faculty of Information Technology](https://img.shields.io/badge/FIT-DNU-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
  [![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)
</div>

---

## 📖 1. Giới thiệu hệ thống
Ứng dụng **Oẳn Tù Tì qua mạng (TCP Socket)** được phát triển nhằm mô phỏng trò chơi quen thuộc, cho phép người chơi thi đấu trực tuyến qua **LAN** hoặc **Internet**.

### 🔹 Hệ thống hỗ trợ:
- **Đăng ký & Đăng nhập tài khoản:** Người chơi có thể tạo tài khoản và đăng nhập vào hệ thống.
- **Tạo phòng chơi hoặc tham gia phòng ngẫu nhiên:** Người chơi có thể tạo phòng chơi riêng hoặc tham gia các phòng đã có.
- **Chọn ✊ Đá / ✋ Bao / ✌ Kéo và trả kết quả tức thì:** Game cho phép người chơi lựa chọn các động tác của trò chơi và nhận kết quả ngay sau khi lựa chọn.
- **Lưu lại lịch sử thi đấu và bảng xếp hạng người chơi:** Các trận đấu và kết quả sẽ được lưu lại, cho phép người chơi xem lại lịch sử thi đấu và theo dõi bảng xếp hạng.

### 🎯 Mục tiêu chính:
- Thực hành lập trình mạng với **TCP Socket** trong Java.
- Nắm vững kiến thức về kiến trúc **Client–Server**.
- Xây dựng ứng dụng game online cơ bản, hỗ trợ nhiều người chơi và có khả năng tương tác trực tuyến.

---

## 🛠️ 2. Công nghệ sử dụng

<p align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/TCP--Socket-008080?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Java%20Swing-6DB33F?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white"/>
</p>

- **Ngôn ngữ:** Java  
- **Mạng:** **TCP Socket** (`ServerSocket`, `Socket`, `I/O Streams`)  
- **Giao diện:** Java Swing (FlatLaf theme)  
- **Quản lý dự án:** Maven / Gradle (tùy chọn)  
- **IDE:** Eclipse, IntelliJ IDEA, NetBeans  

---

## 🖼️ 3. Giao diện hệ thống

### 🔑 Đăng nhập
<p align="center">
  <img src="LTM/src/assets/Dangnhap.png.png" alt="Login UI" width="500"/>
</p>

---

### 📝 Đăng ký
<p align="center">
  <img src="LTM/src/assets/Dangki.png.png" alt="Register UI" width="500"/>
</p>

---

### 🏠 Trang chủ
<p align="center">
  <img src="LTM/src/assets/trangchu.png.png" alt="Home UI" width="500"/>
</p>

---

### 🎮 Chơi game
<p align="center">
  <img src="LTM/src/assets/choi.png.png" alt="Game UI" width="500"/>
</p>

---

### 🏆 Bảng xếp hạng
<p align="center">
  <img src="LTM/src/assets/top.png.png" alt="Leaderboard UI" width="500"/>
</p>

---

### 📂 Lịch sử
<p align="center">
  <img src="LTM/src/assets/Lichsu.png.png" alt="History UI" width="500"/>
</p>

---

## ⚙️ 4. Cài đặt & Chạy

### 1. Cài đặt môi trường phát triển:
- **Cài đặt JDK 17+ hoặc JDK 21**  
- **Cài đặt IDE** (Eclipse / IntelliJ / NetBeans)  

### 2. Clone project từ GitHub:
Mở terminal hoặc Command Prompt và nhập các lệnh sau:

```bash
# Clone project từ GitHub
git clone https://github.com/nvninh2804nvn-boop/LTM-1604-D09-Game-TCP.git

# Di chuyển vào thư mục dự án
cd LTM-1604-D09-Game-TCP
3. Chạy chương trình:
Chạy Server:

Chạy server để quản lý các kết nối và phòng chơi. Mở terminal hoặc IDE và nhập:

# Chạy Server
java -cp LTM/src/may_chu/AppServer.java

Chạy Client:

Mở hai cửa sổ terminal hoặc IDE để kiểm tra khả năng kết nối và chơi game. Mỗi cửa sổ sẽ chạy một client.

# Chạy Client
java -cp LTM/src/nguoi_choi/UngDungClient.java


Sau khi chạy, bạn sẽ thấy giao diện đăng nhập. Đăng nhập và chọn các chức năng như tạo phòng chơi hoặc tham gia phòng ngẫu nhiên.

📬 5. Liên hệ

👤 Họ và tên: Nguyễn Việt Ninh
🎓 Khoa: Công nghệ thông tin – Trường Đại học Đại Nam
🌐 Website: Khoa CNTT – DNU

📧 Email: nvninh2804@gmail.com

📱 Fanpage: AIoTLab – FIT DNU

<p align="center"> © 2025 AIoTLab, Faculty of Information Technology, DaiNam University. All rights reserved </p> ```
