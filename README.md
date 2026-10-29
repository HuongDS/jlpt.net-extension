# JLPT Master - Voice & Sentence Practice Extension (Universal AI Powered) 

Extension dành cho trình duyệt (Chrome, Microsoft Edge, Brave, Cốc Cốc, Kiwi Browser...) giúp nâng cao hiệu quả học Flashcard và luyện dịch câu trên website [JLPT Master (jlptmaster.net)](https://www.jlptmaster.net) với sự hỗ trợ của **Groq, Grok (xAI) và Google Gemini**.

---

##  Tính năng nổi bật

1. Tự động hỗ trợ Groq (gsk_...), Grok xAI (xai-...) & Gemini (AIzaSy...):
   - Nhận diện trực tiếp tiền tố khóa API của bạn:
     - **Groq (`gsk_...`)**: Tốc độ phản hồi siêu tốc (300+ token/giây) với các mô hình tiếng Nhật chất lượng cao như `qwen/qwen3.8-27b`, `openai/gpt-oss-120b`.
     - **Grok xAI (`xai-...`)**: Sử dụng mô hình `grok-2-latest`.
     - **Gemini (`AIzaSy...`)**: Sử dụng mô hình `gemini-2.0-flash`.
   - **Chấm bài dịch công tâm**: Đánh giá ngữ nghĩa, ngữ pháp tự nhiên, chấm điểm (thang 100) và nhận xét chi tiết bằng tiếng Việt.
   - **Không tự động tắt popup**: Sau khi dịch đúng, popup giữ nguyên để bạn thong thả đọc nhận xét và câu mẫu. Bạn chỉ cần nhấn phím **`Enter`** (hoặc click nút *Tiếp tục*) khi sẵn sàng chuyển sang câu kế tiếp.
   - **Bảo mật tuyệt đối**: Key được lưu **hoàn toàn tại bộ nhớ máy cá nhân (Local Storage)** của bạn.

2. **Tự động phát âm từ vựng khi lật thẻ**:
   - Khi lật thẻ flashcard sang mặt sau, extension tự động đọc từ vựng (ví dụ: **主人** - *しゅじん*) bằng giọng đọc tiếng Nhật chuẩn (*Web Speech API ja-JP*).

3. **🇻🇳 Giao diện Popup câu ví dụ (Tone Cam Nhạt, Rộng Rãi)**:
   - Kích thước lớn thoáng đãng (`680px`), cỡ chữ to rõ, bo tròn mềm mại với phong cách màu cam nhạt ấm áp (*warm amber/light orange*), loại bỏ hoàn toàn các icon/emoji gây rối mắt.

4. **Luyện tập Ngẫu nhiên (Random Practice) các câu đã dịch**:
   - Tự động tích lũy ngân hàng câu hỏi từ các thẻ bạn đã lật hoặc có trên trang.
   - Nút **Luyện ngẫu nhiên** ở góc phải màn hình cho phép bạn ôn lại ngẫu nhiên bất cứ lúc nào.

---

## Hướng dẫn cập nhật / cài đặt vào trình duyệt

1. Mở trang quản lý tiện ích:
   - **Chrome**: `chrome://extensions/`
   - **Cốc Cốc**: `coccoc://extensions/`
   - **Edge**: `edge://extensions/`
2. Bật **Chế độ dành cho nhà phát triển** (**Developer mode**).
3. Nhấp vào biểu tượng **Tải lại (mũi tên xoay tròn )** tại tiện ích này.
4. Mở icon Extension trên thanh công cụ, dán key `gsk_...` của bạn vào và nhấn **Lưu & Kiểm tra kết nối AI**.
5. Mở lại trang [JLPT Master](https://www.jlptmaster.net/level/n2/mimikara-n2-goi), nhấn `F5` tải lại trang và bắt đầu học!
