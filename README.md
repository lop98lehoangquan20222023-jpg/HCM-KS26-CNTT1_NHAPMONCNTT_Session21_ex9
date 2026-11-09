# Phần 1:Thiết kế Prompt 3 Phần 
1. Nguyên nhân AI Hallucination khi hỏi ngắn:
- Thiếu dữ liệu thực tế.
- AI tự dự đoán chung chung như (Khuyên tháo vỏ trạm sạc).
2. Prompt :
- "trụ sạc nhanh số 04 đột ngột dừng cung cấp điện cho một chiếc xe taxi điện TERMINAL ERROR LOG - VOLTCHARGE CHARGER giải thích lỗi bằng tiếng việt và đưa ra 3 bước khắc phục.
# PHẦN 2: GIẢI MÃ LỖI & KỊCH BẢN KHẮC PHỤC
3. Bản dịch và giải thích nguyên nhân lỗi:
- Dịch sang tiếng Việt: Lỗi truy cập bị từ chối vào đường dẫn C:\Program Files\VoltCharge\data\session.log.Tiến trình bị dừng với mã thoát 5.
4. 3 bước xử lý thực tế trên Windows 11
- Bước 1: Cho phép ứng dụng chạy với quyền Quản trị viên (Run as Administrator)
- Bước 2: Cấp quyền ghi dữ liệu cho thư mục chứa file log
- Bước 3: Khởi động lại tiến trình hệ thống
5. Xử lý bẫy an ninh (Bảo mật API Key)
- Cách xử lý : Trước khi copy đoạn log có chứa chuỗi khóa dán vào ChatGPT hay Gemini,phải xóa hoặc thay thế nó bằng một chuỗi ẩn.
