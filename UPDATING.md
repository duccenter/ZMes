# Cập nhật ZMes trên Windows

## Bản 2.9.9 đang phát hành

1. Mở **Cài đặt → Cập nhật**.
2. Nhập link bên dưới, bật/tắt tự kiểm tra theo nhu cầu, rồi bấm **Lưu nguồn cập nhật**.
3. Bấm **Kiểm tra cập nhật**. Nếu có phiên bản cao hơn, bấm **Tải bản mới**.
4. Chờ app kiểm tra tệp, chọn **Mở bản mới & khởi động lại** và xác nhận. Hoàn tất hoặc dừng tác vụ đang chạy nếu app yêu cầu.

```text
https://github.com/duccenter/ZMes/releases/latest/download/latest.json
```

Nếu đang dùng đúng bản mới nhất, app báo không có bản mới. Bản 2.9.7 trở xuống cần tải EXE mới và mở một lần để có tính năng cập nhật.

## Từ bản 2.9.10 — đang chuẩn bị, chưa phát hành

Nguồn trên được tích hợp sẵn, không hiển thị ô nhập link. Bấm **Cập nhật** ở sidebar hoặc trong **Cài đặt → Cập nhật**: app kiểm tra → tải → xác minh → lưu phiên → mở EXE mới. Có thanh tiến trình, hủy tải và thông báo lỗi để thử lại. Nếu tác vụ đang bận, bản đã tải được giữ và có thể bấm cập nhật lại khi sẵn sàng.

Tự kiểm tra nền chỉ thông báo có phiên bản mới. App bắt đầu tải/mở bản mới sau thao tác **Cập nhật** của người dùng. Phiên bản này chưa được đưa lên Releases; EXE 2.9.9 vẫn làm theo hướng dẫn ở trên.

## Nâng cấp thủ công và chuyển máy

- Nâng cấp cùng máy: đóng bản cũ, giữ nguyên dữ liệu và mở EXE mới. Không cần bấm Đăng xuất chỉ để cập nhật.
- Chuyển máy: EXE không chứa lịch sử/phiên của máy cũ. Sao lưu/phục hồi nội dung bằng tính năng phù hợp và đăng nhập lại Zalo. Bản quyền gắn với máy, không đi theo bản sao EXE hay bản sao lưu.
- Tệp tải chưa đủ, sai chữ ký hoặc sai mã kiểm tra sẽ không được app mở. Chỉ tải từ trang Releases chính thức.

## Khi chưa cập nhật được

- Kiểm tra kết nối Internet và thử lại.
- Xem [Releases mới nhất](https://github.com/duccenter/ZMes/releases/latest) có đủ EXE và `latest.json` hay chưa.
- Nếu báo đang bận: hoàn tất/dừng đồng bộ, gửi hoặc sao lưu rồi thử lại.
- Nếu báo chữ ký/tệp không hợp lệ: không sửa JSON; tải lại bản chính thức hoặc chờ nhà phát hành sửa gói phát hành.
