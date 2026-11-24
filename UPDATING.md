> Bản hiện tại: **1.0.7** — Công cụ tin nhắn, tìm toàn lịch sử, ngày tin cũ và giao diện gọn hơn.

# Cập nhật ZMes

Người dùng chỉ cần bấm **Cập nhật** trong ứng dụng. App tự chọn kênh đúng loại, kiểm tra thông tin phiên bản và chữ ký; chỉ tải/cài khi người dùng chủ động yêu cầu. Tác vụ đang bận hoặc lỗi lưu phiên sẽ chặn khởi động cập nhật để bảo vệ dữ liệu.

- Portable dùng `latest.json` và gói Portable.
- Setup dùng `setup-latest.json` và gói Setup; sau tải xong, ứng dụng đóng và mở wizard để hoàn tất nâng cấp. Giữ nguyên đường dẫn cài hiện có nếu không cần đổi.
- Gói sai chữ ký, sai SHA-256, thiếu byte hoặc nguồn lỗi không được chạy. Có thể thử lại khi kết nối ổn định.
- Các bản 1.0.0/1.0.1 có lỗi updater cũ cần tải EXE mới thủ công một lần. Bản Setup được cung cấp từ 1.0.3.

Khi phát hành phiên bản mới, đơn vị phát triển đặt cả hai EXE và hai manifest đã ký trong cùng GitHub Release. Không ghi đè EXE của phiên bản cũ. Không công khai khóa ký hoặc dữ liệu người dùng. Nếu một kênh chưa có manifest, người dùng có thể tải đúng loại EXE trực tiếp ở Releases.

## Tùy chọn mới

Bản Setup: Cài đặt → Windows để bật khởi động cùng Windows và thông báo góc màn hình cho hội thoại đang bật thông báo. Nội dung xem trước mặc định tắt; Windows có thể tạm ẩn thông báo khi bật Không làm phiền. Đóng hoàn toàn app sẽ dừng nhận tin.

Cài đặt → Giao diện để đổi màu nền, khung chat, viền và nhấn; có xem trước, lưu và khôi phục mặc định. Mục Lưu trữ được bố trí lại để chọn vị trí dữ liệu và mở Sao lưu/Phục hồi.

Nếu đang dùng Portable và muốn dùng các tùy chọn Windows, tải bản Setup và cài một lần. Cập nhật từ Portable vẫn giữ dạng Portable. Trên cùng máy/tài khoản Windows, bản Setup tiếp tục dùng vị trí dữ liệu đã cấu hình.

## Dùng Nội dung nhanh

Mở **Nội dung nhanh**, chọn Tin nhắn mẫu hoặc Sản phẩm, nhập nội dung/giá/ảnh và đặt lệnh như `/sp01`. Trong hội thoại, gõ `/` để chọn hoặc bấm biểu tượng **Mẫu trả lời nhanh**. Enter chỉ chèn nội dung và ảnh vào bản nháp; kiểm tra người nhận rồi mới gửi. Ghi chú riêng chỉ để xem nội bộ, không được đưa vào gợi ý gửi hoặc chiến dịch.

## Chuyển dữ liệu và tin nhắn ghim

Đóng bản cũ rồi mở/cài bản mới, không bấm Đăng xuất. Vị trí dữ liệu đã chọn vẫn được giữ. Chuyển vị trí trong Cài đặt → Lưu trữ; chọn thư mục đích trống. Nếu lần trước chuyển lỗi và đích còn bản sao dở, chọn một thư mục trống mới. Giữ ứng dụng và các ổ đĩa kết nối trong khi tiến trình chạy; chỉ đổi vị trí sau khi sao chép và kiểm tra xong, bản gốc được giữ.

Khi mở hội thoại có tin ghim, thanh Tin nhắn đã ghim xuất hiện ở đầu chat sau khi tải được từ Zalo; mở thanh để xem hoặc Làm mới. Bấm vào tin ghim để tìm tin gốc trong lịch sử đã lưu. Nếu tin gốc chưa có trên máy, cần đồng bộ thêm lịch sử. Tin ghim đã lưu được giữ khi mất mạng.

## Kiểm tra đồng bộ đã đọc

Sau khi cập nhật, giữ ZMes kết nối và mở một hội thoại có tin chưa đọc trên Zalo điện thoại. Khi Zalo gửi xác nhận đã xem đủ thông tin, số tương ứng ở ZMes được giảm; các tin đến sau mốc đó vẫn chưa đọc. Bản Setup cũng đóng thông báo Windows của tin đã đọc. Không cần bấm đánh dấu đã đọc thêm trên desktop.

Luồng mới đã kiểm thử với dữ liệu mô phỏng và mã đóng gói; chưa xác nhận trên tài khoản mobile thật. Nếu Zalo không cung cấp receipt hoặc app ngoại tuyến khi bạn đọc, trạng thái local có thể chưa cập nhật; app giữ số hiện tại thay vì tự xóa nhắc nhở chưa đọc.


## Sau khi lên 1.0.7

- Mở **Công cụ khác** (dấu ba chấm trên thanh soạn) để dùng gửi số tài khoản, nhắc hẹn, tin nhanh Zalo, sản phẩm, My Documents, GIF, vẽ hình, kiểu chữ và liên kết. Danh thiếp/ảnh/file/emoji/sticker vẫn có icon riêng.
- Ô tìm trong Tin nhắn đọc toàn lịch sử đã lưu trên PC, kể cả tin cũ ngoài trang đang xem. Có kết quả liên hệ và tin nhắn riêng, tiến độ tìm, từ khóa tô sáng và nút tìm lại khi cần. Tài khoản và các bộ lọc đang chọn tiếp tục được áp dụng; tìm trên mọi nhóm hộp thư để tránh bỏ sót hội thoại đã phân nhóm.
- Tin hôm nay chỉ hiện giờ; tin cũ có ngày và giờ. Chỉ dữ liệu đã đồng bộ về PC mới có thể được tìm và mở lại.
- Cài đặt → Thông tin ứng dụng có QR để truy cập app Diticoms. ZMes miễn phí 100%; key mở tính năng được cấp miễn phí theo phần cứng, không cần mua key.
