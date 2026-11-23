# ZMes — Quản lý Zalo trên Windows

ZMes là ứng dụng desktop cho việc nhắn tin và quản lý khách hàng Zalo: xem hội thoại cá nhân/nhóm, phân loại khách hàng, quản lý danh bạ và chiến dịch trong một giao diện.

**Bản phát hành hiện tại: [2.9.9](https://github.com/duccenter/ZMes/releases/tag/v2.9.9)** · Windows x64 · một tệp EXE portable.

[**Tải phiên bản mới nhất**](https://github.com/duccenter/ZMes/releases/latest) · [**Hướng dẫn cập nhật**](UPDATING.md)

## Tải và sử dụng

1. Mở **Releases**, tải tệp `ZMes-Portable-x64-2.9.9.exe` trong mục **Assets**.
2. Chép EXE vào máy Windows x64 và mở ứng dụng, không cần chạy bộ cài.
3. Đăng nhập tài khoản Zalo để sử dụng các luồng tương ứng. Một số chức năng cần key VIP.

EXE là tệp chạy; phiên đăng nhập, lịch sử và media được lưu riêng trong thư mục dữ liệu trên PC. Có thể xem vị trí dữ liệu trong **Cài đặt → Lưu trữ**. Chép EXE sang máy khác không tự chuyển lịch sử, phiên đăng nhập hoặc bản quyền. Khi chuyển máy, dùng sao lưu/phục hồi nội dung theo tính năng được cấp và đăng nhập lại tài khoản; key được ràng buộc theo máy.

## Các luồng chính

- **Tin nhắn:** hộp thư cá nhân và nhóm, lọc theo tài khoản, hội thoại ghim, nhóm phân loại, số tin gửi tới chưa đọc; trả lời, chuyển tiếp, sao chép và thu hồi khi Zalo cho phép.
- **Khách hàng/CRM:** danh bạ, nhóm danh sách ZMes, nhãn, phân luồng và số đơn nhập trong CRM.
- **Nội dung:** mẫu tin, biến cá nhân hóa, ảnh/file, hàng đợi và lịch sử thao tác. Gửi thật chỉ bắt đầu khi người dùng thực hiện thao tác gửi.
- **Lưu trữ:** dữ liệu trên PC, media được tải/lưu theo luồng hỗ trợ, sao lưu/phục hồi và lựa chọn thư mục theo tính năng được cấp.

Khả năng nhận lịch sử và media phụ thuộc dữ liệu Zalo cung cấp cho phiên đăng nhập. Trạng thái tải gần đây không có nghĩa đã lấy toàn bộ lịch sử trên điện thoại; dữ liệu chưa tải về máy không được xem là đã lưu đầy đủ.

## Cập nhật ứng dụng

**EXE 2.9.9 đang phát hành:** nhập nguồn trong **Cài đặt → Cập nhật**, bấm **Lưu nguồn cập nhật**, rồi **Kiểm tra cập nhật**. Khi có bản cao hơn, tải và mở bản mới theo hướng dẫn của app.

```text
https://github.com/duccenter/ZMes/releases/latest/download/latest.json
```

**Bản mã nguồn 2.9.10 đang chuẩn bị, chưa phát hành:** nguồn GitHub được tích hợp sẵn và ẩn khỏi Cài đặt. Người dùng chỉ cần bấm **Cập nhật** để kiểm tra, tải, xác minh và mở bản mới. Đây chưa phải hành vi của EXE 2.9.9 đang tải ở Releases.

App chỉ nhận bản phát hành có chữ ký hợp lệ và kiểm tra tệp trước khi mở. Không cần sửa đường dẫn mỗi lần có release mới. Nếu đã dùng phiên bản mới nhất, app sẽ không báo có bản nâng cấp.

## Điểm mới ở 2.9.9

- Giữ vị trí đọc khi ảnh/video hoặc lịch sử làm thay đổi chiều cao khung chat.
- Tiếp tục bám tin mới khi đang ở cuối hội thoại.
- Nút **Tin mới nhất** đưa về cuối ngay khi đang đọc phía trên.
- Giữ bản nháp và luồng nhắc thành viên nhóm bằng `@`.

Bản EXE này đã qua 376 unit tests, 27 self-tests và 187 kiểm tra giao diện bằng dữ liệu QA; không gửi tin thật trong kiểm thử.

## Các cải tiến đang chuẩn bị

Chưa có trong EXE 2.9.9: tách tên riêng ở hộp thư khỏi tên hồ sơ dùng trong chiến dịch; kế thừa tắt âm và ghim từ điện thoại theo dữ liệu SDK; nguồn cập nhật tích hợp; cải thiện chuyển hội thoại, cập nhật nền và trải nghiệm media. Chỉ xem là đã phát hành khi có release mới kèm EXE và `latest.json` tương ứng.

---

Repository công khai này chỉ chứa **hướng dẫn và tệp phát hành**. Mã nguồn riêng, khóa ký, key bản quyền, phiên đăng nhập và dữ liệu khách hàng không được đăng tại đây.
