# Quét Đáp Án CCAR-F

App quét câu hỏi bằng camera, nhận dạng chữ (OCR) và hiển thị đáp án đúng cho bộ đề CCAR-F (172 câu).

## Dùng trên iPhone
1. Mở link trang (GitHub Pages) trong Safari.
2. Tab **Quét**: bấm "Bật camera" → chụp câu hỏi → app tự nhận dạng và hiện đáp án đúng.
3. Tab **Tra cứu**: gõ/dán nội dung câu hỏi.
4. Tab **Danh sách**: xem toàn bộ 172 câu theo nhóm.

Lưu ý: lần đầu quét cần internet (tải engine OCR từ CDN). Có thể thêm vào màn hình chính: Safari → Share → Add to Home Screen.

## Cập nhật dữ liệu
Dữ liệu câu hỏi được nhúng sẵn trong `scan-dapan.html` (biến `RAW`). Muốn cập nhật: chạy lại script trích xuất từ `cca-f.html` rồi thay thế `RAW`.