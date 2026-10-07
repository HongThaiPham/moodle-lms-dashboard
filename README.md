# Bản đồ sử dụng Moodle LHU

Dashboard thống kê mức sử dụng hoạt động, tài nguyên và loại câu hỏi trên Moodle LHU, phục vụ tham khảo khi xây dựng LMS mới năm 2027.

**Xem trang:** https://hongthaipham.github.io/moodle-lms-dashboard/

## Nội dung

- Quy mô khóa học, tài khoản và xu hướng theo năm.
- Tần suất tạo và sử dụng các loại hoạt động, tài nguyên, câu hỏi; bảng số liệu chi tiết.
- Phân nhóm mức ưu tiên tính năng và đề xuất cho LMS 2027.
- Bộ lọc năm, chế độ sáng/tối và phần phương pháp, giới hạn dữ liệu ngay trên dashboard.

## Nguồn và phạm vi

Dữ liệu tổng hợp từ cơ sở dữ liệu Moodle LHU (`MOODLE_NEW`, SQL Server) tại thời điểm **07/10/2026**. Trang là **báo cáo tĩnh**, số liệu được nhúng trong `index.html`; mở trang không kết nối trực tiếp đến cơ sở dữ liệu và không tự cập nhật. Nhật ký truy cập dùng trong báo cáo chỉ còn từ **14/01/2026**; năm 2026 chưa trọn năm. Xem mục **Phương pháp và giới hạn** trên trang trước khi diễn giải số liệu.

## Triển khai

GitHub Pages xuất bản trực tiếp `index.html` từ nhánh `main`, thư mục `/(root)`. Khi cập nhật số liệu, cần cập nhật file này và đẩy lên `main`; không cần cài đặt hay chạy build. Trang và số liệu trên đó được công khai qua GitHub Pages.
