# DENBROWN AI PHOTO V13 — Ghép theo ảnh tham chiếu

## Sử dụng
1. Mở `index.html` qua GitHub Pages (HTTPS).
2. Thêm ảnh cưới.
3. Trong mục **Ảnh tham chiếu**, chọn ảnh album mẫu.
4. Kiểm tra viền xanh nhận diện các khung. Có thể chọn số khung 1–8 và phân tích lại.
5. Bấm **GHÉP THEO ẢNH MẪU**. Sau đó chỉnh sửa và dùng nút **Lưu vào Ảnh / Xuất JPG**.

## Thực chất kỹ thuật
- Phân tích các đường có phương sai màu thấp (khoảng trắng/gutter) bằng pixel, chia ảnh thành vùng chữ nhật và áp dụng cho album mới. **Không phải AI học sâu hiểu layout**, không sao chép chính xác mọi chi tiết mẫu.
- Mô hình BlazeFace học sâu từ V11 vẫn có thể được tải thủ công để phát hiện mặt. Lần đầu cần internet để tải model, không cần API key/credit.
- Vẫn giữ xuất JPG và bảng chia sẻ iOS của V12. Safari yêu cầu xác nhận **Lưu hình ảnh**.
- Khung lồng nhau, khung nghiêng, viền trang trí, typography, ảnh không có đường chia rõ có thể bị nhận diện sai.
- Mã chưa được kiểm thử trực tiếp trên Safari iPhone.
