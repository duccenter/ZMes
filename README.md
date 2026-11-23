# ZMes — Quản lý Zalo trên Windows

**Phiên bản 1.0.1 · Windows x64 · Một file EXE portable**

ZMes giúp quản lý tin nhắn, danh bạ và khách hàng Zalo trong giao diện desktop gọn gàng.

**[Tải ZMes 1.0.1](https://github.com/duccenter/ZMes/releases/download/v1.0.1/ZMes-Portable-x64-1.0.1.exe)** · [Releases](https://github.com/duccenter/ZMes/releases) · [Hướng dẫn và cập nhật](UPDATING.md)

## Mới ở 1.0.1

- Mở app vào **Tin nhắn**. **Hộp thư** mặc định của mọi tài khoản không chứa hội thoại đã chuyển vào nhóm riêng; chọn **Tất cả** để xem đầy đủ.
- **Báo cáo** gộp Thống kê và Lịch sử, nằm dưới menu chính.
- Popup **Đồng bộ** gọn, giữ mở và có cuộn riêng. Mỗi tài khoản có **Tải gần đây · Từ điện thoại · Tài khoản**, tiến độ và số tin/media đã lưu của chính tài khoản đó.
- Sửa ô chuyển tài khoản bị cắt/lệch; menu chuột phải căn trái thống nhất, chia nhóm thao tác rõ ràng.
- Gia cố IPC, khóa debug trong bản phân phối, kiểm tra toàn vẹn tài nguyên và loại mã kiểm thử/source map khỏi gói phát hành.

## Tính năng chính

- Hộp thư cá nhân và nhóm, lọc theo tài khoản, số tin đến chưa đọc, tìm kiếm, ghim và nhóm phân loại.
- Văn bản, ảnh, file, emoji, sticker, tương tác; trả lời, chuyển tiếp, sao chép và thu hồi theo khả năng Zalo cung cấp.
- Album, video và tin thoại trong app; lưu media đã tải về PC.
- CRM: nhãn, phân luồng chăm sóc, tổng đơn nhập thủ công, dữ liệu theo tài khoản.
- Quét bạn bè/nhóm, danh sách CSV, nhóm người nhận ZMes, mẫu tin và hàng đợi chiến dịch.
- Duy trì phiên đăng nhập, chọn thư mục dữ liệu, sao lưu/phục hồi nội dung và media theo tính năng được cấp.

Bản miễn phí dùng một tài khoản. Các chức năng nâng cấp được đánh dấu VIP trong app.

## Chạy và cập nhật

1. Tải **ZMes-Portable-x64-1.0.1.exe** rồi mở trên Windows x64; không cần bộ cài.
2. Nếu đang dùng 1.0.0, bấm **Cập nhật** ở sidebar hoặc Cài đặt. App kiểm tra, tải, xác minh rồi lưu phiên và mở bản mới.
3. Nếu đang gửi/đồng bộ/sao lưu, xử lý tác vụ theo thông báo trước khi khởi động lại.

EXE chỉ là tệp chạy. Dữ liệu nằm riêng tại **Cài đặt → Lưu trữ**. Chuyển máy bằng sao lưu/phục hồi và đăng nhập lại Zalo; key VIP gắn với máy.

Bản 1.0.0 là mốc bắt đầu chính thức; các bản 2.x cũ cần mở EXE dòng 1.x thủ công một lần. Các bản 1.0.x cập nhật qua nút trong app.

## Kiểm tra và dữ liệu

Typecheck/lint, 411 unit tests, 27 self-tests và 199 kiểm tra UI đã đạt trong runtime QA riêng; 121 bố cục hiển thị. Gói rút gọn được đối chiếu nguồn, kiểm tra fuses/integrity và worker từ ASAR. Không gửi tin thật trong kiểm thử phát hành.

Phiên đăng nhập dùng Windows DPAPI. Tin nhắn, media và bản sao lưu chưa mã hóa toàn bộ; bảo vệ tài khoản Windows và thư mục dữ liệu. Việc lấy lịch sử/media phụ thuộc dữ liệu Zalo cung cấp; không coi số lô đã nhận là đã khôi phục toàn bộ lịch sử.

---

Repository này chỉ chứa **hướng dẫn và bản phát hành**. Mã nguồn, khóa ký, key cấp phép và dữ liệu khách hàng được giữ riêng.
