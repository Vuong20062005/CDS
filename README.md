<img width="1600" alt="demo-app" src="https://github.com/user-attachments/assets/b0756efb-814e-4f31-a8ae-1aa88fa48491" />

🌍 Travel Chatbot
📌 Tổng quan

Travel Chatbot là một ứng dụng web xây dựng bằng Flask kết hợp Google Gemini API.
Ứng dụng giúp người dùng tìm kiếm và nhận gợi ý combo du lịch dựa trên ngân sách, sở thích và thời gian mong muốn.

Chatbot trả lời theo định dạng chuẩn, bao gồm:

Tóm tắt nhanh (điểm đến, thời lượng, số người, ngân sách).

Lịch trình chi tiết theo ngày.

Gợi ý khách sạn/resort.

Thông tin di chuyển.

Ăn uống & trải nghiệm nổi bật.

Ước tính chi phí.

Lưu ý & mẹo tiết kiệm.

🚀 Tính năng chính

💬 Chatbot AI: Gợi ý combo du lịch bằng Gemini AI.

📑 Cấu trúc trả lời rõ ràng: 7 phần cố định, dễ theo dõi.

🖥️ Giao diện hiện đại: Thiết kế bằng Bootstrap 5, tối ưu cho desktop & mobile.

📝 Nhập liệu tiện lợi: Hỗ trợ Enter để gửi, Shift+Enter để xuống dòng.

🔄 Cuộn tự động: Chatbox luôn hiển thị tin nhắn mới nhất.

🛠️ Công nghệ sử dụng

Backend: Flask (Python).

Frontend: HTML5, CSS3, Bootstrap 5.

AI: Google Gemini API (gemini-2.0-flash).

Cấu hình: dotenv để quản lý API key.

📂 Cấu trúc dự án
.
├── app.py         # Flask backend, xử lý request/response với Gemini
├── index.html     # Giao diện chatbot (Bootstrap + custom CSS/JS)
├── .env           # File môi trường (API key Gemini)

⚡ Hướng dẫn cài đặt & chạy
1️⃣ Clone repo
git clone https://github.com/your-username/travel-chatbot.git
cd travel-chatbot

2️⃣ Tạo môi trường ảo (tuỳ chọn)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3️⃣ Cài đặt thư viện
pip install flask python-dotenv google-generativeai

4️⃣ Cấu hình API Key

Tạo file .env và thêm:

GEMINI_API_KEY=your_api_key_here

5️⃣ Chạy ứng dụng
python app.py


Truy cập tại: http://127.0.0.1:5000

📸 Giao diện minh họa

Màn hình chat: hiển thị hội thoại giữa người dùng và chatbot.

Bong bóng tin nhắn: phân biệt rõ ràng giữa user và bot.

Bot trả lời có phân mục: hiển thị đẹp mắt theo từng phần.

✨ Đối tượng sử dụng

Người dùng cá nhân muốn lên kế hoạch du lịch nhanh chóng.

Các công ty lữ hành muốn demo giải pháp chatbot tư vấn du lịch.

Sinh viên/lập trình viên học cách tích hợp Gemini API với Flask.
