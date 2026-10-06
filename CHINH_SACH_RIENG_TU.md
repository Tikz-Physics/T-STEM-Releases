# Chính sách quyền riêng tư T-STEM

> Phiên bản 1.0 (2026-10-06), theo tinh thần Nghị định 13/2023/NĐ-CP về bảo vệ dữ liệu cá nhân.

## Dữ liệu T-STEM thu thập

| Dữ liệu | Khi nào | Để làm gì | Lưu ở đâu |
|---|---|---|---|
| Email | Khi bạn kích hoạt gói Pro | Gắn khóa bản quyền với người mua, hỗ trợ khi đổi máy | Máy chủ bản quyền (Google Firebase) và máy của bạn |
| Mã máy | Khi kích hoạt và mỗi lần mở app có mạng | Giới hạn số máy dùng một khóa | Máy chủ bản quyền và máy của bạn |

- Mã máy là chuỗi băm một chiều SHA-256. Nó không chứa tên máy, tên người dùng hay địa chỉ IP.
- Gói Miễn phí và Dùng thử không gửi dữ liệu nào lên máy chủ bản quyền.
- Khi mở app, T-STEM tải một tệp nhỏ từ GitHub để biết có bản mới không. Yêu cầu này
  không kèm dữ liệu nào của bạn, nhưng GitHub thấy địa chỉ IP như mọi lượt truy cập web.
- T-STEM không có quảng cáo, không theo dõi hành vi và không bán dữ liệu.

## Dữ liệu T-STEM không thu thập

- **Ảnh Quét đề và đề bài nhập tay.** Chúng được gửi thẳng từ máy bạn tới Google Gemini
  bằng khóa API của chính bạn. Tác giả không nhận được.
  - Với gói miễn phí của Gemini, Google có thể dùng nội dung để cải thiện dịch vụ.
  - Đừng quét giấy có họ tên hay thông tin của học sinh.
- **Khóa API Gemini.** Khóa lưu trong Windows Credential Manager trên máy bạn.
- **Hình bạn tự lưu và cài đặt.** Chúng chỉ nằm trong thư mục `%APPDATA%\T-STEM` trên máy bạn.

## Quyền của bạn

Bạn có thể yêu cầu xem, sửa hoặc xóa email và mã máy gắn với khóa của bạn. Xóa dữ liệu
đồng nghĩa với việc ngừng gói Pro trên các máy đó.

Liên hệ: https://github.com/Tikz-Physics/T-STEM-Releases/issues
