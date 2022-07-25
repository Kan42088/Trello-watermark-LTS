# Trello-watermark-LTS
*Note: 
- Phần mềm là file rar trong file được tải về.
- Để xác thực với trang web muốn thêm sản phẩm PHẢI cài đặt plugin "JSON Basic Authentication" tại đây hoặc https://github.com/WP-API/Basic-Auth
- Bản ổn định hiện tại: v1.5.3-EOS | v2.4.2

*Bản 2.4.5:
- Thử nghiệm thông báo phân biệt sản phẩm trùng và sản phẩm tải lên do lỗi data.
- Sửa lại vị trí cache file ảnh tạm. 

*Bản 2.4.4:
- Sửa lỗi 400 đối với một số mô tả.
- Thử nghiệm sửa lỗi một vài ảnh png giảm dung lượng không đáng kể.


*Bản 1.5.3-EOS:
- Sửa lỗi không nhận được ảnh mark/background khi ảnh mark/background đã bị xoá.
- Cải thiện hiệu năng khi xác thực tài khoản.
- Dừng cập nhật cho bản v1.x .

*Bản 2.4.2:
- Hiển thị ảnh preview của từng luồng khi nhấn vào tên trên danh sách luồng chạy.
- Sửa lỗi không nhận được ảnh mark/background khi ảnh mark/background đã bị xoá.
- Cải thiện hiệu năng khi mở chỉnh sửa luồng

*Bản 2.3.1:
- Tăng cường bảo mật.
- Sửa lỗi hệ thống.

*Bản 1.5.1:
- Tăng cường bảo mật.
- Sửa lỗi hệ thống.

*Bản 2.2.4:
- Thay đổi downloadable name từ tên sản phẩm thành mã sku.

*Bản 2.2.3:
- Mở lại chức năng chuyển card đã qua watermark sang list mới.
- Comment vào các thẻ đã watermawrk các web đã hoàn thành và chưa hoàn thành.
- Sửa logo.
- Sửa lỗi mất dữ liêụ danh mục sản phẩm => 400 bad request.
- Sửa lỗi ảnh preview xử lí sai ảnh khi không có web nào.

*Bản 2.0.0:
- Chạy đa luồng, đa website cùng một lần chạy.
- Loại bỏ chuyển thẻ sang cột mới sau khi đã đẩy sản phẩm lên các trang Woocommerce ở bản v1(đơn luồng).
- Điều chỉnh dài rộng của ảnh gốc không quá ảnh thành phẩm.

*Bản 1.4.1:
- Thông báo và dừng tiến trình nếu sai tài khoản đăng nhập vào web.
- Thêm nút tắt mở thanh cuộn bên.

*Bản 1.3.7:
- Sửa lỗi lấy link ảnh trong trash làm ảnh sản phẩm đối với những sản phẩm tải lên sau lần đầu.

*Bản 1.3.6:
- Sửa lỗi không tìm thấy ảnh sản phẩm khi upload lên Wooocommerce.

*Bản 1.3.5:
- Sửa lỗi cash app và GDI.

*Bản 1.3.4:
- Hiệu chỉnh "chỉ dùng màu nền từ nhãn Trello cho png" thành "màu nền từ nhãn Trello cho png".
- Nhận diện nhãn Trello không phân biệt viết hoa viết thường.
- Sửa lỗi tự thêm nền đen vào ảnh trong suốt (png) và lỗi hệ thống.

*Bản 1.3.1:
- Loại bỏ thanh cuộn dưới.
- Thêm tính năng tự động lấy label chứa từ "White" làm nền trắng hoặc "Black" làm nền đen cho ảnh png và không lấy ảnh nền đã chọn làm ảnh nền cho ảnh png.

*Bản 1.2.0:
- Hỗ trợ thanh cuộn cho màn hình độ phân giải thấp (Chiều cao 768).

*Bản 1.1.1:
- Giảm hiệu năng truy xuất trello giữa mỗi thẻ đi 0.5s (tránh lỗi 503).
- Các trường thông tin khác đã được lưu lại cho lần đăng nhập sau.

*Bản 1.0.1:
- Sửa lỗi tên sản phẩm nhân đôi.

*Bản 1.0.0:
- Sửa lỗi tên sản phẩm bị thiếu khi trong tên chứa dấu "-".
- Thêm tính năng tự động xóa ảnh trùng trong media.
- Hướng dẫn sử dụng phần mềm.

*Bản 0.3.0:
- Hệ thống đăng nhập bằng tài khoản Twobros.
- Chọn list các thẻ trello sẽ được chuyển đến sau khi hoàn thành chuyển đổi watermark.
- Nút dừng tiến trình đã hoạt động.

*Bản 0.2.1:
- Sửa lỗi đóng băng ứng dụng sau khi chạy xong tiến trình đẩy sản phẩm.

*Bản 0.2.0:
- Lưu lại thông tin của cài đặt trello và woocommerce.
- Cho phép điều chỉnh vị trí, kích thước ảnh gốc, tự động căn chỉnh ảnh gốc theo size đặt trước.
- Loại bỏ Logo.
- Thêm cài đặt cho ảnh nền.
- Thêm tùy chọn không đẩy sản phẩm lên woocommerce(chỉ lấy ảnh về máy).
- Thêm tùy chọn không đặt category cho sản phẩm.
- Thêm tùy chọn tự động lấy tags từ trello cho sản phẩm.

*Bản 0.1.1:
- Tùy chọn nguồn ảnh từ bảng và danh sách trên trello.
- Căn chỉnh kích thước đầu ra, dung lượng, màu  của ảnh thành phẩm.
- Tùy chọn lưu ảnh gốc hoặc ảnh đã qua quá trình watermark về máy.
- Watermark vói 2 lớp phủ có thể tùy chỉnh kích thước, vị trí và độ trong suốt.
- Xem trực tiếp ảnh đã qua watermark thông qua picture preview.
