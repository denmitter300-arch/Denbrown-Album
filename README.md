# DENBROWN AI PHOTO V11 — Deep Learning Local

Bản nâng cấp từ V10. Tải `index.html` lên GitHub Pages để chạy.

## Có thật
- Mô hình học sâu MediaPipe BlazeFace chạy suy luận trên thiết bị (CPU / WebAssembly), phát hiện khuôn mặt sau khi bấm nút AI.
- Khi ghép, tự căn vùng cắt theo tâm khuôn mặt đầu tiên, trong giới hạn vùng ảnh.
- Phân tích độ sáng, độ nét và ảnh gần trùng bằng thuật toán V10.
- Tự ghép trang, kéo/zoom/xoay, xuất JPG.

## Chưa có
- AI chọn ảnh đẹp bằng mạng học sâu; phân loại cô dâu/chú rể; nhận diện cảm xúc; huấn luyện mô hình; Gemini hoặc ChatGPT tích hợp.
- Chưa có kiểm thử trực tiếp trên Safari iPhone.

## Điều kiện
- Lần đầu cần internet tải JavaScript WASM và model từ CDN/Google. Không cần API key/credit.
- Ảnh được xử lý cục bộ, nhưng các thư viện và model được tải từ bên ngoài.
- Nếu CDN bị chặn hoặc thiết bị thiếu bộ nhớ, nhận diện không chạy; chế độ ghép thuật toán vẫn hoạt động.
- Dùng HTTPS (GitHub Pages) để chạy ổn định.
