# ZMes

Phần mềm Windows miễn phí, được phát triển bởi Diticoms. Quản lý tài khoản Zalo, hội thoại, danh bạ/nhóm và chăm sóc khách hàng.

## Cài đặt và chạy

- **Setup:** [ZMes-Setup-x64-1.0.4.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.4/ZMes-Setup-x64-1.0.4.exe). Cài đặt theo hướng dẫn, đọc và đồng ý điều khoản, chọn thư mục. Có shortcut và mục gỡ cài đặt.
- **Portable:** [ZMes-Portable-x64-1.0.4.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.4/ZMes-Portable-x64-1.0.4.exe). Chép một EXE sang máy Windows x64 và mở. EXE không tự mang theo dữ liệu hoặc phiên đăng nhập từ máy khác.

Dữ liệu làm việc nằm riêng với thư mục chương trình. Xem vị trí thực tế trong Cài đặt. Cài lại/cập nhật và gỡ cài đặt thông thường giữ dữ liệu. Mã kích hoạt gắn với phần cứng; sao lưu không tự chuyển mã sang máy mới.

## Cập nhật

Bấm **Cập nhật** trên sidebar hoặc trong Cài đặt. Ứng dụng tải gói đúng loại, xác minh chữ ký và SHA-256 trước khi mở. Bản Setup mở trình cài đặt mới; bản Portable mở EXE Portable mới. Xem [UPDATING.md](UPDATING.md).

## Phiên bản 1.0.4

- **Nội dung nhanh:** lưu tin nhắn mẫu, sản phẩm có giá/mô tả/tối đa 2 ảnh và ghi chú riêng.
- Gõ `/` hoặc bấm **Mẫu** trong ô chat để tìm; dùng `/sp01`, `/chao` hay lệnh tự đặt. Enter chèn vào bản nháp, bạn xem lại rồi mới gửi.
- Ghi chú nội bộ không xuất hiện trong gợi ý lệnh hoặc danh sách mẫu chiến dịch.
- Sửa hiển thị danh thiếp Zalo: đọc đúng UID chuỗi dài, điện thoại trong metadata; hiện thẻ liên hệ, ảnh và nút **Nhắn tin**. Danh thiếp đã lưu được nhận diện lại khi mở hội thoại.

Đã đạt 452 kiểm thử, 28 kiểm tra Electron và 201 kiểm tra giao diện trong môi trường QA; không gửi tin thật khi kiểm thử.

Đây là kho bản phát hành. Mã nguồn, khóa ký, mã kích hoạt và dữ liệu người dùng không được công khai tại đây. ZMes là ứng dụng độc lập, không phải sản phẩm chính thức của Zalo/VNG.

Hỗ trợ: 0935 71 5151 · [app.diticoms.vn](https://app.diticoms.vn).

## Tùy chọn mới

Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Nội dung xem trước mặc định tắt; Windows có thể tạm ẩn thông báo khi bật Không làm phiền. Đóng hoàn toàn app sẽ dừng nhận tin.

Cài đặt → Giao diện để đổi màu nền, khung chat, viền và nhấn; có xem trước, lưu và khôi phục mặc định. Mục Lưu trữ được bố trí lại để chọn vị trí dữ liệu và mở Sao lưu/Phục hồi.

Nếu đang dùng Portable và muốn dùng các tùy chọn Windows, tải bản Setup và cài một lần. Cập nhật từ Portable vẫn giữ dạng Portable. Trên cùng máy/tài khoản Windows, bản Setup tiếp tục dùng vị trí dữ liệu đã cấu hình.
