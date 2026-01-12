# Personal AI Secretary 

## Mục tiêu
Xây dựng một hệ thống **thư ký cá nhân thông minh** hỗ trợ người dùng quản lý lịch làm việc, theo dõi thời gian, ghi nhận hành vi học tập/làm việc và phân tích trạng thái tinh thần ở mức cơ bản dựa trên văn bản, nhằm nâng cao hiệu quả cá nhân.

Hệ thống hướng tới vai trò **hỗ trợ và gợi ý**, không thay thế con người và không mang tính chẩn đoán hay trị liệu.

---

## Phạm vi
- Web application (Frontend Web + Backend API)
- Chat text-based giữa người dùng và “thư ký”
- Quản lý lịch trình trong ngày và nhắc nhở theo thời gian
- Phiên làm việc (start/stop) để đo thời lượng tập trung
- Thống kê hành vi theo ngày/tuần
- Phân tích trạng thái tinh thần ở mức cơ bản (5 trạng thái) dựa trên văn bản
- Text-to-Speech (TTS) trên trình duyệt (tùy chọn)

---

## Ngoài phạm vi
- Phân tích cảm xúc qua giọng nói
- Trị liệu tâm lý hoặc chẩn đoán y khoa
- Ứng dụng mobile native

---

## Đối tượng sử dụng
- Sinh viên
- Người tự học, làm việc cá nhân
- Người cần công cụ hỗ trợ quản lý thời gian và thói quen

---

## Chức năng chính
- Chat với “thư ký” thông qua giao diện web
- Lưu trữ và truy xuất lịch sử trò chuyện, ghi chú
- Tạo task theo lịch và nhắc nhở đúng thời điểm
- Bắt đầu/kết thúc phiên làm việc và ghi nhận thời lượng
- Dashboard thống kê hành vi học tập/làm việc theo ngày/tuần
- Phân loại trạng thái tinh thần từ văn bản:
  - calm
  - focused
  - tired
  - stressed
  - unmotivated

---

## Công nghệ dự kiến
- Backend: FastAPI (Python)
- Database: SQLite (phục vụ TTCS), có thể mở rộng PostgreSQL
- AI/ML: Text Classification (Logistic Regression / SVM)
- Frontend: Web (React + Vite hoặc HTML/CSS/JS đơn giản)

---

## Định hướng học thuật
- Áp dụng kiến thức về:
  - Thiết kế hệ thống web
  - RESTful API
  - Cơ sở dữ liệu
  - Xử lý văn bản và học máy cơ bản
- Tập trung vào tính rõ ràng, dễ hiểu và khả năng mở rộng
- Phù hợp với quy mô và mục tiêu của học phần **Thực tập cơ sở (TTCS)**

---
