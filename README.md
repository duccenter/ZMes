# ZMes

Phần mềm Windows **miễn phí 100%**, được phát triển bởi **Diticoms Việt Nam**. Quản lý tài khoản Zalo, hội thoại, danh bạ/nhóm và chăm sóc khách hàng. Key mở tính năng được cấp miễn phí theo thiết bị.

## Tải và cài đặt

- **Setup:** [ZMes-Setup-x64-1.0.7.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.7/ZMes-Setup-x64-1.0.7.exe). Cài theo hướng dẫn, đọc và đồng ý điều khoản, chọn thư mục. Có shortcut, khởi động cùng Windows, thông báo và mục gỡ cài đặt.
- **Portable:** [ZMes-Portable-x64-1.0.7.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.7/ZMes-Portable-x64-1.0.7.exe). Chép một EXE sang máy Windows x64 và mở. EXE không tự mang theo dữ liệu hoặc phiên đăng nhập.

Dữ liệu làm việc nằm riêng với thư mục chương trình; xem vị trí thực tế trong Cài đặt → Lưu trữ. Cài lại/cập nhật và gỡ cài đặt thông thường giữ dữ liệu. Key gắn phần cứng; sao lưu không tự chuyển key hoặc phiên đăng nhập sang máy mới.

## Có gì mới trong 1.0.7

- Thanh soạn gọn, icon rõ ràng; Esc hoặc bấm ngoài để đóng mẫu/emoji/sticker/cảm xúc. Ảnh trong chat hiển thị trực tiếp.
- Bộ chọn gửi danh thiếp; gửi số tài khoản, tạo nhắc hẹn, kiểu chữ, tin nhanh Zalo, sản phẩm và My Documents theo tài khoản.
- Sửa hiển thị thẻ tài khoản ngân hàng và nhắc hẹn; giữ số tài khoản dạng chuỗi và tọa độ vị trí chính xác.
- Tìm tên thật/tên riêng, UID/SĐT và toàn bộ nội dung tin đã lưu trên PC. Hỗ trợ tiếng Việt không dấu, nhiều từ khóa, trích đoạn và mở đúng tin cũ; có tiến độ tìm ở luồng nền.
- Tin hôm nay chỉ hiện giờ, tin cũ có ngày và giờ; giảm các thao tác quét lại dữ liệu lớn khi mở app.
- Mục Thông tin ứng dụng có QR truy cập/tải app Diticoms để ủng hộ tác giả và thông tin key cấp miễn phí.

Vị trí được gửi bằng liên kết bản đồ; GIF chọn từ máy. Chia sẻ thông tin ngân hàng không thực hiện giao dịch chuyển tiền. Công cụ phụ thuộc API và quyền của phiên Zalo; lịch sử chưa đồng bộ về PC chưa thể tìm từ dữ liệu local.

## Cập nhật

Bấm **Cập nhật** trên sidebar hoặc trong Cài đặt. App tải gói đúng loại, xác minh chữ ký manifest và SHA-256 trước khi mở. Setup mở trình cài đặt mới; Portable mở EXE Portable mới. Xem [hướng dẫn cập nhật](UPDATING.md).

## Dữ liệu và tùy chọn

- Giữ lịch sử/CRM, lọc hội thoại theo tài khoản hoặc nhóm hộp thư, ghim hội thoại và quản lý nhãn.
- Cài đặt → Lưu trữ để chọn vị trí dữ liệu; Sao lưu & Phục hồi để chuyển tin nhắn và media đã lưu. Đổi máy cần đăng nhập và nhận key phù hợp máy mới.
- Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Đóng hoàn toàn app sẽ dừng nhận tin.
- Cài đặt → Giao diện để đổi màu nền, khung chat, viền và màu nhấn; có xem trước, lưu và khôi phục mặc định.
- Nội dung nhanh gồm tin mẫu, sản phẩm có giá/ảnh và ghi chú riêng. Gõ `/` trong chat để chèn vào bản nháp, kiểm tra người nhận rồi gửi.

## Kiểm chứng và phạm vi

Đạt 497 unit tests, 28 kiểm tra Electron, 203 kiểm tra giao diện, 6 kiểm tra gói/bảo mật và 13 kiểm tra payload Setup. Các luồng gửi mới đã kiểm thử bằng API giả lập và module trong ASAR; không gửi tin thật trong phát triển. Chưa nghiệm thu cài/gỡ Setup trên máy sạch hoặc đo lại startup lạnh với dữ liệu thật.

EXE chưa ký chứng thư Authenticode. Manifest cập nhật ký Ed25519 để ứng dụng xác minh nguồn bản cập nhật và SHA-256; đây là cơ chế riêng với chữ ký Windows.

Kho này chỉ chứa bản phát hành và hướng dẫn. Mã nguồn, khóa ký, danh sách key và dữ liệu người dùng không được công khai. ZMes là ứng dụng độc lập, không phải sản phẩm chính thức của Zalo/VNG.

Hỗ trợ và cấp key miễn phí: **0935 71 5151** · [app.diticoms.vn](https://app.diticoms.vn).
