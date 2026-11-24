# ZMes

Phần mềm Windows **miễn phí 100%**, được phát triển bởi **Diticoms Việt Nam**. Quản lý tài khoản Zalo, hội thoại, danh bạ/nhóm và chăm sóc khách hàng. Key mở tính năng được cấp miễn phí theo thiết bị.

## Tải và cài đặt

- **Setup:** [ZMes-Setup-x64-1.0.8.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.8/ZMes-Setup-x64-1.0.8.exe). Cài theo hướng dẫn, đọc và đồng ý điều khoản, chọn thư mục. Có shortcut, khởi động cùng Windows, thông báo và mục gỡ cài đặt.
- **Portable:** [ZMes-Portable-x64-1.0.8.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.8/ZMes-Portable-x64-1.0.8.exe). Chép một EXE sang máy Windows x64 và mở. EXE không tự mang theo dữ liệu hoặc phiên đăng nhập.

Dữ liệu làm việc nằm riêng với thư mục chương trình; xem vị trí thực tế trong Cài đặt → Lưu trữ. Cài lại/cập nhật và gỡ cài đặt thông thường giữ dữ liệu. Key gắn phần cứng; sao lưu không tự chuyển key hoặc phiên đăng nhập sang máy mới.

## Có gì mới trong 1.0.8

- Tin bạn gửi từ điện thoại hoặc thiết bị khác không tăng số chưa đọc và không phát thông báo tin đến.
- Khi nhận xác nhận đã đọc hoặc lượt trả lời trực tiếp trên điện thoại trong hội thoại cá nhân, app xóa số chưa đọc cũ đúng hội thoại; tin đến sau mốc đó vẫn giữ thông báo.
- Tự đối soát huy hiệu còn sót khi tài khoản kết nối lại; giữ dữ liệu, lịch sử, CRM và các tài khoản khác.
- Nhận thêm biến thể sự kiện UID 0 và lịch sử thiếu metadata; đối chiếu chính xác mã tin, bỏ qua trường hợp không xác định được hội thoại.
- Cập nhật số ở hội thoại, nhóm hộp thư, ghim và sidebar; đóng thông báo Windows của tin đã đọc. Không gắn trạng thái người nhận đã xem chỉ vì chính bạn đọc trên thiết bị khác.

Các công cụ gửi danh thiếp, số tài khoản, nhắc hẹn, tin nhanh, sản phẩm, My Documents; tìm toàn lịch sử đã lưu và hiển thị ngày tin cũ được giữ từ bản trước.

Trạng thái đọc trên điện thoại phụ thuộc sự kiện Zalo cung cấp qua phiên đang kết nối. Chưa nghiệm thu tài khoản Zalo thật cho thay đổi đồng bộ đã đọc này.

## Cập nhật

Bấm **Cập nhật** trên sidebar hoặc trong Cài đặt. App tải gói đúng loại, xác minh chữ ký manifest và SHA-256 trước khi mở. Setup mở trình cài đặt mới; Portable mở EXE Portable mới. Xem [hướng dẫn cập nhật](UPDATING.md).

## Dữ liệu và tùy chọn

- Giữ lịch sử/CRM, lọc hội thoại theo tài khoản hoặc nhóm hộp thư, ghim hội thoại và quản lý nhãn.
- Cài đặt → Lưu trữ để chọn vị trí dữ liệu; Sao lưu & Phục hồi để chuyển tin nhắn và media đã lưu. Đổi máy cần đăng nhập và nhận key phù hợp máy mới.
- Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Đóng hoàn toàn app sẽ dừng nhận tin.
- Cài đặt → Giao diện để đổi màu nền, khung chat, viền và màu nhấn; có xem trước, lưu và khôi phục mặc định.
- Nội dung nhanh gồm tin mẫu, sản phẩm có giá/ảnh và ghi chú riêng. Gõ `/` trong chat để chèn vào bản nháp, kiểm tra người nhận rồi gửi.

## Kiểm chứng và phạm vi

Đạt 509 unit tests, 28 kiểm tra Electron, 203 kiểm tra giao diện, 6 kiểm tra gói/bảo mật và 13 kiểm tra payload Setup. Các luồng gửi mới đã kiểm thử bằng API giả lập và module trong ASAR; không gửi tin thật trong phát triển. Chưa nghiệm thu cài/gỡ Setup trên máy sạch hoặc đo lại startup lạnh với dữ liệu thật.

EXE chưa ký chứng thư Authenticode. Manifest cập nhật ký Ed25519 để ứng dụng xác minh nguồn bản cập nhật và SHA-256; đây là cơ chế riêng với chữ ký Windows.

Kho này chỉ chứa bản phát hành và hướng dẫn. Mã nguồn, khóa ký, danh sách key và dữ liệu người dùng không được công khai. ZMes là ứng dụng độc lập, không phải sản phẩm chính thức của Zalo/VNG.

Hỗ trợ và cấp key miễn phí: **0935 71 5151** · [app.diticoms.vn](https://app.diticoms.vn).
