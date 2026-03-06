# Authentication_Vulnerbilities
# Xác thực đầu vào 
# Các dạng lỗ hổng xác thực phổ biến
#### Brute Force & Credential Stuffing: Kẻ tấn công thử hàng loạt mật khẩu hoặc sử dụng danh sách tài khoản bị lộ từ các vụ rò rỉ dữ liệu khác để đăng nhập vào hệ thống của bạn.
#### Thiếu kiểm soát phiên làm việc (Broken Session Management): Sau khi đăng nhập, nếu mã định danh phiên (session token) không được bảo mật (dễ đoán hoặc không đổi sau khi đăng nhập), kẻ tấn công có thể chiếm quyền điều khiển phiên (Session Hijacking).
#### Lỗi logic trong quy trình phục hồi mật khẩu: Câu hỏi bảo mật quá dễ đoán hoặc gửi mã khôi phục qua các kênh không bảo mật.
#### Credential Exposure: Mật khẩu được lưu trữ dưới dạng văn bản thuần (plain text) hoặc sử dụng các thuật toán băm (hash) yếu (như MD5, SHA-1).
