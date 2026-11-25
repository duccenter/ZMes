# ZMes

Phần mềm Windows **miễn phí 100%**, được phát triển bởi **Diticoms Việt Nam**. Quản lý tài khoản Zalo, hội thoại, danh bạ/nhóm và chăm sóc khách hàng. Key mở tính năng được cấp miễn phí theo thiết bị.

## Tải và cài đặt

- **Setup:** [ZMes-Setup-x64-1.0.9.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.9/ZMes-Setup-x64-1.0.9.exe). Cài theo hướng dẫn, đọc và đồng ý điều khoản, chọn thư mục. Có shortcut, khởi động cùng Windows, thông báo và mục gỡ cài đặt.
- **Portable:** [ZMes-Portable-x64-1.0.9.exe](https://github.com/duccenter/ZMes/releases/download/v1.0.9/ZMes-Portable-x64-1.0.9.exe). Chép một EXE sang máy Windows x64 và mở. EXE không tự mang theo dữ liệu hoặc phiên đăng nhập.

Dữ liệu làm việc nằm riêng với thư mục chương trình; xem vị trí thực tế trong Cài đặt → Lưu trữ. Cài lại/cập nhật và gỡ cài đặt thông thường giữ dữ liệu. Key gắn phần cứng; sao lưu không tự chuyển key hoặc phiên đăng nhập sang máy mới.

## Có gì mới trong 1.0.9

- Ảnh gửi/nhận cùng lượt được gom thành album, kể cả ảnh đồng bộ từ điện thoại; có chuyển tiếp cả album 4–8 ảnh. Vượt giới hạn của phiên Zalo được chia lô, không bỏ ảnh âm thầm hoặc tự gửi lại khi chưa rõ kết quả.
- Mở link web và link mời nhóm; xem thông tin nhóm, kiểm tra tài khoản và xác nhận trước khi tham gia. Phân biệt đã là thành viên, cần quản trị viên duyệt và kết quả chưa xác định.
- Thẻ xem trước link gồm tên miền, tiêu đề, mô tả ngắn và ảnh thu nhỏ khi Zalo cung cấp. Có trong ô soạn, hộp gửi link và tin nhận; xem trước không tự gửi hoặc làm mất bản nháp.
- Tạo/xem/bình chọn nhóm, bật/tắt thông báo hội thoại trên Zalo và gửi/đồng ý/từ chối lời mời kết bạn có xác nhận.
- Giữ sửa lỗi số chưa đọc giữa các thiết bị của bản 1.0.8 và các công cụ danh thiếp, ngân hàng, nhắc hẹn, file, sticker, cảm xúc, tìm toàn lịch sử đã lưu.

Các công cụ mới đã được kiểm thử bằng SDK và dữ liệu QA riêng, chưa nghiệm thu trên tài khoản Zalo thật. Thẻ xem trước, media, quyền nhóm và trạng thái đọc còn phụ thuộc dữ liệu/API của Zalo. Không có chức năng gọi thoại/video trực tiếp, feed hoặc đầy đủ bộ quản trị nhóm nâng cao.

## Cập nhật

Bấm **Cập nhật** trên sidebar hoặc trong Cài đặt. App tải gói đúng loại, xác minh chữ ký manifest và SHA-256 trước khi mở. Setup mở trình cài đặt mới; Portable mở EXE Portable mới. Xem [hướng dẫn cập nhật](UPDATING.md).

## Dữ liệu và tùy chọn

- Giữ lịch sử/CRM, lọc hội thoại theo tài khoản hoặc nhóm hộp thư, ghim hội thoại và quản lý nhãn.
- Cài đặt → Lưu trữ để chọn vị trí dữ liệu; Sao lưu & Phục hồi để chuyển tin nhắn và media đã lưu. Đổi máy cần đăng nhập và nhận key phù hợp máy mới.
- Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Đóng hoàn toàn app sẽ dừng nhận tin.
- Cài đặt → Giao diện để đổi màu nền, khung chat, viền và màu nhấn; có xem trước, lưu và khôi phục mặc định.
- Nội dung nhanh gồm tin mẫu, sản phẩm có giá/ảnh và ghi chú riêng. Gõ `/` trong chat để chèn vào bản nháp, kiểm tra người nhận rồi gửi.

## Kiểm chứng và phạm vi

Đạt 535 unit tests, 28 kiểm tra Electron, 206 kiểm tra giao diện, 6 kiểm tra gói/bảo mật và 13 kiểm tra payload Setup. Các luồng gửi mới đã kiểm thử bằng API giả lập và module trong ASAR; không gửi tin thật trong phát triển. Chưa nghiệm thu cài/gỡ Setup trên máy sạch hoặc đo lại startup lạnh với dữ liệu thật.

EXE chưa ký chứng thư Authenticode. Manifest cập nhật ký Ed25519 để ứng dụng xác minh nguồn bản cập nhật và SHA-256; đây là cơ chế riêng với chữ ký Windows.

Kho này chỉ chứa bản phát hành và hướng dẫn. Mã nguồn, khóa ký, danh sách key và dữ liệu người dùng không được công khai. ZMes là ứng dụng độc lập, không phải sản phẩm chính thức của Zalo/VNG.

Hỗ trợ và cấp key miễn phí: **0935 71 5151** · [app.diticoms.vn](https://app.diticoms.vn).
