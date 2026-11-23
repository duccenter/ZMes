# ZMes — Quản lý Zalo trên Windows

**Phiên bản 1.0.0 · Windows x64 · Một file EXE portable**

ZMes giúp quản lý tin nhắn, danh bạ và khách hàng Zalo trong một giao diện desktop gọn gàng. Phiên bản **1.0.0** là mốc bắt đầu chính thức của sản phẩm; các bản 2.x thuộc giai đoạn phát triển trước khi chuẩn hóa số phiên bản.

> **Tải ứng dụng:** EXE 1.0.0 đã build xong và vượt kiểm thử trên Windows; tệp được bàn giao trực tiếp. Chưa có bản 1.0.0 trên GitHub Releases. Chỉ tải bản mới khi thấy release **v1.0.0** và tệp **ZMes-Portable-x64-1.0.0.exe** tương ứng.

[Xem Releases](https://github.com/duccenter/ZMes/releases) · [Hướng dẫn sử dụng và cập nhật](UPDATING.md)

## Tính năng chính

- **Hộp thư Zalo:** hội thoại cá nhân và nhóm, lọc theo tài khoản, số tin đến chưa đọc, tìm kiếm, ghim và nhóm phân loại hội thoại.
- **Nhắn tin:** văn bản, ảnh, file, emoji, sticker, tương tác; trả lời có trích dẫn, chuyển tiếp, sao chép và thu hồi theo khả năng Zalo cho phép.
- **Ảnh và media:** album ảnh, xem ảnh trước/sau, video và trình nghe tin thoại trong app; lưu dữ liệu media được tải về PC.
- **Khách hàng và CRM:** nhãn tùy chỉnh, phân luồng chăm sóc, ghi nhận tổng đơn; quản lý khách theo từng tài khoản.
- **Danh bạ và chiến dịch:** quét bạn bè/nhóm, danh sách CSV, nhóm người nhận ZMes, mẫu tin, biến cá nhân hóa, ảnh đính kèm và theo dõi hàng đợi.
- **Dữ liệu và cài đặt:** duy trì phiên đăng nhập, chọn vị trí lưu dữ liệu, sao lưu/phục hồi nội dung và media theo tính năng được cấp.

Một số chức năng cần key VIP. Bản miễn phí dùng một tài khoản; gửi chiến dịch vào nhiều nhóm, nhập/xuất CSV, nhóm danh sách ZMes, nhãn tùy chỉnh và các chức năng nâng cấp được đánh dấu trong app.

## Trải nghiệm mới ở 1.0.0

- Chuyển lại hội thoại qua cache có giới hạn, sau đó đối soát dữ liệu đã lưu; chặn phản hồi cũ khi đổi tài khoản hoặc hội thoại.
- Cập nhật phần thay đổi khi có tin mới, giữ nội dung đang soạn, vị trí đọc và player media đang mở.
- Nút **Tin mới nhất** đưa về cuối; bấm trích dẫn để tìm tin gốc đã lưu trên máy.
- Tên hiển thị trong hộp thư dùng tên riêng/biệt danh của tài khoản; tên khách dùng cho chiến dịch lấy tên hồ sơ Zalo khi có.
- Kế thừa tắt âm và ghim từ dữ liệu SDK cung cấp, đồng thời giữ lựa chọn ghim riêng ở ZMes.
- Nguồn cập nhật GitHub tích hợp sẵn: người dùng chỉ bấm **Cập nhật**, không cần nhập đường dẫn.

## Chạy trên Windows

Dùng EXE 1.0.0 đã nhận hoặc tải từ release tương ứng khi có:

1. Chép **ZMes-Portable-x64-1.0.0.exe** vào máy Windows x64.
2. Mở EXE, không cần chạy bộ cài.
3. Đăng nhập Zalo và bắt đầu sử dụng.

EXE không chứa lịch sử hay phiên tài khoản. Dữ liệu nằm riêng tại vị trí hiển thị trong **Cài đặt → Lưu trữ**. Chép EXE sang máy khác để chạy; nếu cần mang theo dữ liệu, dùng sao lưu/phục hồi và đăng nhập lại Zalo. Key VIP ràng buộc với máy, không đi theo bản sao EXE hoặc bản sao lưu.

## Cập nhật

Trong ZMes 1.0.0, bấm **Cập nhật** ở sidebar hoặc **Cài đặt → Cập nhật**. App kiểm tra bản mới, tải tệp, xác minh rồi lưu phiên và mở phiên bản mới. Nếu đang có tác vụ cần hoàn tất, app báo để xử lý trước khi khởi động lại.

Kiểm tra tự động chỉ thông báo có bản mới; tải và mở bản mới bắt đầu sau thao tác **Cập nhật** của người dùng.

**Chuyển từ các bản 2.x cũ:** mở EXE 1.0.0 thủ công một lần sau khi nhận bản mới, giữ nguyên thư mục dữ liệu. Từ đó dùng nút Cập nhật cho các bản 1.0.1 trở lên.

## Kiểm thử bản build

Bản 1.0.0 đã đạt **403 unit tests, 27 self-tests và 189 kiểm tra giao diện trên EXE portable**, cùng 121 bố cục hiển thị. Kiểm thử dùng dữ liệu QA riêng, không gửi tin thật.

## Lưu ý về lịch sử và media

Khả năng lấy lịch sử/media phụ thuộc dữ liệu Zalo cung cấp cho phiên đăng nhập. **Tải gần đây** và **Từ điện thoại** là hai luồng riêng; không coi số tin/lô đã nhận là đã khôi phục toàn bộ lịch sử. App giữ phần dữ liệu đã lưu khi đồng bộ gián đoạn.

---

Repository này dùng cho **hướng dẫn và bản phát hành**. Mã nguồn riêng, khóa ký, key bản quyền, phiên đăng nhập và dữ liệu khách hàng được giữ riêng.
