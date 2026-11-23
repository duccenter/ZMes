# ZMes — Windows Portable

Kho phát hành ứng dụng ZMes cho Windows x64. Mã nguồn và dữ liệu tài khoản không được lưu trong repository này.

## Tải và chạy

1. Mở [Releases](https://github.com/duccenter/ZMes/releases/latest).
2. Tải `ZMes-Portable-x64-2.9.9.exe` trong phần Assets.
3. Chép EXE sang máy Windows x64 và mở để sử dụng, không cần cài đặt.

Nâng cấp trên cùng máy: đóng bản cũ, không bấm Đăng xuất, rồi mở EXE mới. Dữ liệu lưu riêng ở vị trí đã cấu hình trên máy; EXE không chứa phiên đăng nhập hay lịch sử của người khác.

## Cập nhật trong app

Mở **Cài đặt → Cập nhật**, nhập URL sau và bấm **Lưu nguồn cập nhật**:

```text
https://github.com/duccenter/ZMes/releases/latest/download/latest.json
```

Bấm **Kiểm tra cập nhật**. Khi có bản cao hơn, chọn **Tải bản mới**, chờ kiểm tra chữ ký/tệp rồi chọn **Mở bản mới & khởi động lại**. App không tự tải hoặc tự mở bản mới khi chưa có thao tác người dùng.

Bản 2.9.8 trở lên hỗ trợ cập nhật theo URL này. App đang dùng đúng phiên bản mới nhất sẽ không thông báo nâng cấp.

## 2.9.9

- Giữ vị trí đang đọc khi ảnh/video hoặc lịch sử thay đổi chiều cao.
- Tiếp tục bám tin mới khi đang ở cuối hội thoại.
- Thêm nút **Tin mới nhất** để xuống cuối ngay khi đang đọc phía trên.
- Giữ bản nháp và luồng nhắc thành viên nhóm bằng `@` của bản trước.

Bản này đã qua 376 kiểm thử chức năng, 27 self-test và 187 kiểm tra giao diện trên EXE, với dữ liệu QA. Không thực hiện gửi tin nhắn thật trong kiểm thử.