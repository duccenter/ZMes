# Sử dụng và cập nhật ZMes 1.0.2

## Mở ứng dụng

[Tải ZMes 1.0.2 cho Windows x64](https://github.com/duccenter/ZMes/releases/download/v1.0.2/ZMes-Portable-x64-1.0.2.exe). Chép một file EXE sang máy Windows và mở, không cần bộ cài.

## Cập nhật lần này từ 1.0.0/1.0.1

Do lỗi chuyển hướng GitHub trong updater bản cũ, cần tải **ZMes-Portable-x64-1.0.2.exe** thủ công một lần. Đóng app cũ, mở EXE mới trên cùng máy; giữ nguyên thư mục dữ liệu, không cần đăng xuất Zalo. Không thể sửa mã updater đã nằm trong EXE cũ bằng cách thay latest.json.

## Từ bản 1.0.2 trở đi

Bấm Cập nhật ở sidebar hoặc Cài đặt. App kiểm tra bản mới, tải, xác minh chữ ký/hash rồi lưu phiên và mở EXE mới. Hoàn tất/dừng tác vụ đang bận theo thông báo trước khi cập nhật. Kiểm tra nền chỉ thông báo, không tự mở EXE.

Client 2.x cũ cũng cần mở EXE 1.0.2 thủ công một lần.

## Hộp thư và đồng bộ

App mở vào Tin nhắn, Hộp thư của mọi tài khoản. Hội thoại đã chuyển vào nhóm riêng được loại khỏi Hộp thư; chọn Tất cả để xem toàn bộ.

Mở **Tiến trình đồng bộ** bên trái. Mỗi tài khoản có Tải gần đây, Từ điện thoại và Tài khoản. Chọn đúng dòng cần thao tác; Từ điện thoại vẫn yêu cầu xác nhận. Popup giữ mở tới khi chủ động thu gọn.

**Báo cáo** ở dưới menu chứa Thống kê và Lịch sử.

## Chuyển máy

EXE không mang theo dữ liệu. Xem vị trí ở Cài đặt → Lưu trữ; dùng Sao lưu & Phục hồi để chuyển tin nhắn/media đã lưu, rồi đăng nhập Zalo lại. Key VIP gắn với phần cứng máy, không chuyển qua bản sao lưu.

## Khi cập nhật chưa được

- Kiểm tra mạng rồi thử lại; hoàn tất hoặc dừng tác vụ đang bận theo thông báo.
- Nếu chữ ký/hash không hợp lệ, dùng đúng tệp phát hành chính thức, không sửa JSON.
- Nếu chưa có bản mới, app báo đang dùng bản mới nhất.

[Xem các bản phát hành](https://github.com/duccenter/ZMes/releases)
