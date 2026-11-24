> Bản hiện tại: **1.0.4** — Nội dung nhanh, sản phẩm có ảnh/giá và sửa hiển thị danh thiếp Zalo.

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

Mở **Nội dung nhanh**, chọn Tin nhắn mẫu hoặc Sản phẩm, nhập nội dung/giá/ảnh và đặt lệnh như `/sp01`. Trong hội thoại, gõ `/` để chọn hoặc bấm **Mẫu**. Enter chỉ chèn nội dung và ảnh vào bản nháp; kiểm tra người nhận rồi mới gửi. Ghi chú riêng chỉ để xem nội bộ, không được đưa vào gợi ý gửi hoặc chiến dịch.
