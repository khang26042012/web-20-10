# 🌸 TỔNG QUAN & TÓM TẮT DỰ ÁN WEBSITE 20/10: "SỰ THỨC GIẤC CỦA KHANG"

> **Dự án:** Website nghệ thuật tương tác chào mừng ngày Phụ nữ Việt Nam 20/10  
> **Tác giả & Ý tưởng:** [phantrongkhangg](https://www.tiktok.com/@phantrongkhangg)  
> **Quản trị Repository & DevOps:** [khang26042012](https://github.com/khang26042012)  
> **Trải nghiệm trực tiếp (GitHub Pages):** [https://khang26042012.github.io/web-20-10/](https://khang26042012.github.io/web-20-10/)

---

## 📖 1. Giới Thiệu Chung
Website **"Sự thức giấc của Khang"** là một tác phẩm web tương tác đậm chất điện ảnh (Cinematic Interactive Web Experience), được xây dựng để gửi gắm những tình cảm chân thành, ấm áp và lời chúc tôn vinh người phụ nữ nhân ngày 20/10.

Trang web kết hợp hài hòa giữa **kể chuyện tương tác (interactive storytelling)**, **đồ họa 3D Origami**, **âm thanh tổng hợp trực tiếp (Web Audio Synthetic SFX)** và các tiêu chuẩn thiết kế hiện đại đạt chuẩn **GSAP 3** & **UI/UX Pro Max**.

---

## 🌟 2. Hành Trình Trải Nghiệm Người Dùng (User Journey)

Trải nghiệm được chia thành các chương cảm xúc liền mạch:

### Giai đoạn 1: Mở màn & Thức giấc
- Màn hình khởi đầu với hiệu ứng hạt stardust lung linh và âm thanh chuông êm dịu.
- Nhân vật Khang xuất hiện với lối xưng hô gần gũi, dịu dàng: *"Nè, cậu ơi... tớ là Khang đây. Hôm nay tớ xuất hiện ở đây là vì có một điều muốn nói với cậu..."*

### Giai đoạn 2: Lời chúc & Món quà Cỏ 4 Lá
- Dẫn dắt người xem qua những thông điệp yêu thương:
  - Khích lệ sự tự tin: *"Mong cậu sẽ luôn xinh đẹp theo cách riêng của mình, chẳng cần phải giống bất kỳ ai cả."*
  - Trao tặng ngọn **Cỏ Bốn Lá** may mắn tương tác kèm lời cầu chúc những ước mơ sớm thành hiện thực.
  - Vỗ về những lúc mệt mỏi: *"Cậu không cần lúc nào cũng phải mạnh mẽ, cũng chẳng cần làm hài lòng tất cả mọi người."*

### Giai đoạn 3: Kết thúc hành trình & Kêu gọi chia sẻ
- Thẻ cảm ơn và gợi ý chia sẻ thông điệp yêu thương đến bạn bè.
- Nút dẫn tới kênh TikTok của tác giả: **@phantrongkhangg**.

### Giai đoạn 4: Phong bì thư 3D & Bức tâm thư Hoàng gia
- Khi nhấn vào nút **"Bức thư gửi cậu 💌"**, màn hình mở ra một phong bì thư 3D với con dấu sáp đỏ viền vàng khắc biểu tượng trái tim và số `20/10`.
- Chạm vào con dấu sáp sẽ kích hoạt hiệu ứng mở nắp 3D, bức thư trượt ra bồng bềnh cùng hợp âm tiên nữ (Celestial Arpeggio) và mưa pháo hoa confetti.

### Giai đoạn 5: Tiện ích mở rộng & Rút quẻ may mắn
- **Rút quẻ may mắn Cỏ 4 lá 3D**: Chạm vào cỏ bốn lá để lật thẻ 180° và nhận 1 trong 10 thông điệp may mắn ngẫu nhiên, có thể rút lại nhiều lần.
- **Thả đèn lồng ước nguyện (Sky Lanterns)**: Thả đàn đèn hoa đăng lung linh bay lên trời đêm.

---

## 🛠️ 3. Điểm Nhấn Công Nghệ & Kỹ Thuật (Tech Stack Highlights)

| Hạng mục | Công nghệ / Kỹ thuật áp dụng | Mô tả chi tiết |
| :--- | :--- | :--- |
| **Animation Engine** | **GSAP 3 & CSS3 3D Transform** | Hiệu ứng chuyển cảnh 60 FPS, nắp phong bì xoay `rotateX(-180deg)`, perspective 1100px. |
| **Âm thanh** | **Web Audio API Pure Synthesis** | Bộ phát âm thanh độc lập hoàn toàn không cần tải tệp MP3 ngoài (`OscillatorNode`, `GainNode`). |
| **Nhạc nền** | **Base64 Audio Data** | Nhạc nền được nhúng trực tiếp, phát mượt mà không lo lỗi mạng hay đứt gãy link. |
| **Voice Speech** | **Web Speech Synthesis API** | Giọng đọc truyền cảm tự động bằng tiếng Việt (`vi-VN`) cho bức tâm thư. |
| **Hiệu ứng hạt** | **Canvas Confetti & SVG Particles** | Mưa hoa hồng, tim vàng và sao stardust bay lượn ngập tràn màn hình. |
| **Tương tác chuột** | **Desktop Magnetic Halo Cursor** | Vòng hào quang nam châm ánh hồng bám đuổi theo chuột trên máy tính, tự động tắt trên màn hình cảm ứng. |
| **Hiệu năng & Mobile** | **Tiny Performance Profile** | Tự động phát hiện cấu hình phần cứng, điều chỉnh DPR Canvas và giới hạn FPS (18 - 60 FPS) mượt mà cho mọi thiết bị Android / iOS. |

---

## 📜 4. Toàn Văn Bức Tâm Thư 20/10

```text
Gửi cậu,

Tớ là Khang. Tớ không biết khi cậu đọc được những dòng này, cậu đang vui vẻ hay đang có chút mệt mỏi, nhưng tớ hy vọng bức thư nhỏ này có thể mang đến cho cậu một nụ cười.

Nhân ngày 20/10, tớ muốn gửi đến cậu những lời chúc chân thành nhất. Chúc cậu luôn xinh đẹp, mạnh khỏe, bình an và gặp thật nhiều may mắn. Mong rằng những điều tốt đẹp sẽ đến với cậu, những ước mơ của cậu sẽ dần trở thành hiện thực và mỗi ngày trôi qua đều có ít nhất một điều khiến cậu cảm thấy hạnh phúc.

Cậu biết không, đôi khi hạnh phúc chẳng phải điều gì quá lớn lao. Đó có thể là một buổi chiều đầy nắng, một bài hát yêu thích, một tin nhắn bất ngờ hay đơn giản là có ai đó thật lòng quan tâm đến cậu.

Tớ mong cậu sẽ luôn gặp được những người tử tế, những người biết trân trọng cậu và không khiến cậu phải nghi ngờ giá trị của chính mình. Nếu một ngày nào đó cậu cảm thấy mệt mỏi, hãy cho bản thân thời gian nghỉ ngơi nhé. Cậu không cần phải hoàn hảo, cũng không cần lúc nào cũng tỏ ra mạnh mẽ. Chỉ cần cậu vẫn đang cố gắng sống tốt và yêu thương bản thân, như thế đã là đáng quý rồi.

Tớ chẳng có món quà gì quá lớn lao để tặng cậu, chỉ có những dòng chữ này cùng một chút chân thành được gửi gắm vào đó. Hy vọng khi đọc đến đây, cậu sẽ cảm nhận được rằng trên thế giới rộng lớn này, vẫn luôn có những điều nhỏ bé nhưng ấm áp đang chờ đón cậu..

Cuối cùng, chúc cậu một ngày 20/10 thật vui vẻ. Mong nụ cười sẽ luôn ở trên môi cậu, ánh mắt luôn lấp lánh những điều hy vọng và trái tim luôn đủ dịu dàng để yêu thương cuộc sống.

Chúc cậu luôn hạnh phúc, không chỉ riêng ngày 20/10 mà còn trong tất cả những ngày bình thường sau này.

Thân gửi,
Khang.
```

---

## 🍀 5. Bộ 10 Thông Điệp Quẻ May Mắn Cỏ Bốn Lá
1. *"Mong nụ cười của cậu hôm nay sẽ làm bừng sáng cả một góc trời! 💖"*
2. *"Cậu là phiên bản duy nhất, đặc biệt và vô cùng quý giá trên thế giới này. 🌸"*
3. *"Gửi tặng cậu một ngọn cỏ 4 lá: Chúc mọi điều cậu đang mong ước sớm thành hiện thực! 🍀"*
4. *"Dù cuộc sống có bận rộn thế nào, nhớ luôn yêu thương và dịu dàng với bản thân nhé. 🌷"*
5. *"Chúc cậu mỗi sáng thức dậy đều ngập tràn niềm vui, mỗi tối về đều an giấc bình yên. ✨"*
6. *"Món quà tuyệt vời nhất hôm nay không phải thứ xa xỉ, mà là nụ cười rạng rỡ của chính cậu. 🎁"*
7. *"Cậu tỏa sáng theo cách rất riêng, chẳng cần phải giống bất kỳ ai cả. 🌟"*
8. *"20/10 thật hạnh phúc nhé! Mong cả thế giới này sẽ luôn đối xử thật dịu dàng với cậu. 🕊️"*
9. *"Hôm nay, hãy tự thưởng cho mình một ly nước ngon và một khoảng thời gian thật thư thái nhé! ☕"*
10. *"Cảm ơn vì cậu đã luôn kiên cường và tỏa sáng rực rỡ như một đóa hoa thơm. 💐"*

---

## ⌨️ 6. Bảng Phím Tắt Điều Khiển
- `Space` hoặc `→`: Tiến tới lời thoại / cảnh tiếp theo.
- `M`: Bật / Tắt âm thanh & nhạc nền.
- `L`: Mở / Khép lại bức tâm thư.
- `Esc`: Đóng phong bì thư hoặc bảng quẻ may mắn.

---
*Tài liệu tổng hợp bởi AI Assistant - Hệ thống quản trị tự động hóa repo `web-20-10`.*
