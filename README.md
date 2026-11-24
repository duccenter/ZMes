# ZMes

Phần mềm Windows miễn phí, được phát triển bởi Diticoms. Quản lý tài khoản Zalo, hội thoại, danh bạ/nhóm và chăm sóc khách hàng.

## Cài đặt và chạy

- **Setup:** [ZMes-Setup-x64-1.0.6.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.6/ZMes-Setup-x64-1.0.6.exe). Cài đặt theo hướng dẫn, đọc và đồng ý điều khoản, chọn thư mục. Có shortcut và mục gỡ cài đặt.
- **Portable:** [ZMes-Portable-x64-1.0.6.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.6/ZMes-Portable-x64-1.0.6.exe). Chép một EXE sang máy Windows x64 và mở. EXE không tự mang theo dữ liệu hoặc phiên đăng nhập từ máy khác.

Dữ liệu làm việc nằm riêng với thư mục chương trình. Xem vị trí thực tế trong Cài đặt. Cài lại/cập nhật và gỡ cài đặt thông thường giữ dữ liệu. Mã kích hoạt gắn với phần cứng; sao lưu không tự chuyển mã sang máy mới.

## Cập nhật

Bấm **Cập nhật** trên sidebar hoặc trong Cài đặt. Ứng dụng tải gói đúng loại, xác minh chữ ký và SHA-256 trước khi mở. Bản Setup mở trình cài đặt mới; bản Portable mở EXE Portable mới. Xem [UPDATING.md](UPDATING.md).

## Phiên bản 1.0.6

- **Đồng bộ đã đọc:** khi nhận xác nhận đã xem từ Zalo, cập nhật số chưa đọc đúng tài khoản và hội thoại cá nhân/nhóm; tin mới hơn chưa đọc vẫn được giữ.
- Lưu mốc đã đọc để tin cũ đến trễ không tăng số hoặc thông báo lại sau khi mở app. Huy hiệu hội thoại, hộp thư, ghim và sidebar cập nhật cùng nhau.
- Bản Setup đóng thông báo Windows của tin đã đọc, giữ thông báo của tin mới hơn.
- Giữ các tính năng trước: chuyển dữ liệu lớn với tiến trình/thời gian, tin ghim trong hội thoại, Nội dung nhanh và sản phẩm có giá/ảnh.

Đã đạt 470 unit tests, 28 kiểm tra Electron, 203 kiểm tra giao diện và 13 kiểm tra payload Setup. Luồng đã kiểm thử từ mã đóng gói bằng dữ liệu mô phỏng; chưa xác nhận lượt đọc trên tài khoản Zalo mobile thật. Không gửi tin thật khi kiểm thử.

Cập nhật đã đọc phụ thuộc Zalo gửi xác nhận đủ thông tin trên phiên đang kết nối; app không tự xóa mọi số chưa đọc hoặc suy đoán toàn bộ trạng thái trong thời gian ngoại tuyến.

EXE hiện chưa ký chứng thư Authenticode. Manifest cập nhật đã ký Ed25519; hai loại chữ ký có mục đích khác nhau.

Đây là kho bản phát hành. Mã nguồn, khóa ký, mã kích hoạt và dữ liệu người dùng không được công khai tại đây. ZMes là ứng dụng độc lập, không phải sản phẩm chính thức của Zalo/VNG.

Hỗ trợ: 0935 71 5151 · [app.diticoms.vn](https://app.diticoms.vn).

## Tùy chọn mới

Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Nội dung xem trước mặc định tắt; Windows có thể tạm ẩn thông báo khi bật Không làm phiền. Đóng hoàn toàn app sẽ dừng nhận tin.

Cài đặt → Giao diện để đổi màu nền, khung chat, viền và nhấn; có xem trước, lưu và khôi phục mặc định. Mục Lưu trữ được bố trí lại để chọn vị trí dữ liệu và mở Sao lưu/Phục hồi.

Nếu đang dùng Portable và muốn dùng các tùy chọn Windows, tải bản Setup và cài một lần. Cập nhật từ Portable vẫn giữ dạng Portable. Trên cùng máy/tài khoản Windows, bản Setup tiếp tục dùng vị trí dữ liệu đã cấu hình.
