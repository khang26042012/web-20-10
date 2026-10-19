# 🌸 Sự Thức Giấc Của Tiny - Kỷ Niệm 20/10 🌸

Dự án tương tác nghệ thuật chào mừng ngày Phụ nữ Việt Nam 20/10: **"Sự thức giấc của Tiny"**.

🔗 **Truy cập trực tiếp tại:** [https://khang26042012.github.io/web-20-10/](https://khang26042012.github.io/web-20-10/)

---

## 🌟 Đặc Điểm Nổi Bật & Tiêu Chuẩn Kỹ Thuật

1. **Độc lập tuyệt đối (100% Self-Contained):**
   - Toàn bộ nhạc nền MP3 gốc được inlined trực tiếp vào thẻ `<audio>` dưới định dạng `data:audio/mpeg;base64,...`.
   - Toàn bộ 5 hình ảnh nghệ thuật của Tiny được mã hóa Base64 (WebP/PNG/JPEG).
   - Toàn bộ styles CSS và Javascript được nhúng nguyên khối trong file `index.html`. Không phụ thuộc hosting ngoài.

2. **Hiệu ứng đồ họa 60 FPS:**
   - Hệ thống cực quang **Aurora CSS Keyframe** rực rỡ, chuyển màu mềm mại.
   - Vector cỏ 4 lá may mắn phát sáng định dạng SVG tương tác.
   - Bầu trời sao tương tác qua HTML5 Canvas với hiệu ứng hạt lấp lánh và vệt sao rơi khi chạm/di chuột.

3. **Bộ điều phối di động `TINY_PERF`:**
   - Tự động nhận diện thiết bị di động (Android / iOS) và thiết bị màn hình cảm ứng (`pointer: coarse`).
   - Tự động điều chỉnh Canvas DPR (Device Pixel Ratio) và giới hạn số lượng hạt/nhịp animation để chống tụt khung hình, đảm bảo độ mượt 60 FPS ngay cả trên máy yếu.

4. **Autoplay Policy Bypass:**
   - Màn che mở đầu tinh tế (*"đợi chút xíu đii"* / tap-to-start) kích hoạt AudioContext & âm thanh nền trơn tru theo chuẩn bảo mật trình duyệt hiện đại.

---

## 🛠️ Công Nghệ Sử Dụng
- **HTML5 Canvas & SVG**
- **Vanilla JavaScript (ES6+)**
- **Modern CSS3 (Keyframes, Glassmorphism, CSS Gradients)**
- **GitHub Pages CI/CD & DevOps Automation**

---
*Nguồn gốc bản phát hành: [https://ngay-2010.pages.dev/](https://ngay-2010.pages.dev/)*
