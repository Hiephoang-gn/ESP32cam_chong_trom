# 📷 ESP32cam_chong_trom – Hệ thống cảnh báo chống trộm thông minh

**ESP32cam_chong_trom** là một dự án IoT ứng dụng **ESP32-CAM** để xây dựng hệ thống giám sát và cảnh báo chống trộm thời gian thực. Hệ thống có khả năng phát hiện người đột nhập bằng AI, gửi ảnh về server và thông báo ngay lập tức qua **Telegram Bot**. Giao diện web giúp người dùng theo dõi camera và điều khiển từ xa dễ dàng.

## 🛠️ Tính năng nổi bật

- 🎥 **Livestream video trực tiếp** từ ESP32-CAM qua trình duyệt
- 📸 **Tự động chụp ảnh khi phát hiện chuyển động hoặc người lạ**
- 🧠 **Gửi ảnh về server AI (YOLOv5/YOLOv8)** để nhận diện người xâm nhập
- 🚨 **Gửi cảnh báo đến gmail ngay khi có người đột nhập
- 🌐 **Giao diện web thân thiện** (dùng Bootstrap), hỗ trợ chụp ảnh và giám sát trạng thái

## 🔧 Phần cứng sử dụng

- ESP32-CAM (AI Thinker)
- Module FTDI để nạp chương trình
- Nguồn 5V ổn định
- Server Python (Flask) để xử lý ảnh và gửi cảnh báo

## 🗂️ Cấu trúc thư mục
