# 🖼️ Công Cụ Lấy Ảnh Từ DOCX & PDF

Ứng dụng web đa năng chạy trực tiếp trên trình duyệt, giúp tự động trích xuất hình ảnh nguyên bản từ file Word (`.docx`) hoặc chuyển đổi các trang tài liệu `PDF` thành tệp tin hình ảnh chất lượng cao một cách nhanh chóng.

---

## ✨ Tính Năng Nổi Bật

* **Hoạt động Offline 100%:** Quá trình trích xuất và chuyển đổi diễn ra hoàn toàn cục bộ ở phía client (trình duyệt), bảo mật tuyệt đối dữ liệu, không tải tệp tin lên máy chủ mạng.

* **Trích xuất thông minh file Word:** Tự động giải nén cấu trúc file `.docx` để thu về ảnh gốc và tích hợp **bộ lọc kích thước** (chiều rộng/chiều cao tối thiểu) giúp loại bỏ các icon hoặc hình ảnh biểu tượng kích thước nhỏ.

* **Chuyển đổi PDF nâng cao:** Cho phép tùy chọn dải trang cần chuyển đổi (ví dụ: `1, 3, 5-8`), cấu hình tăng độ phân giải siêu nét ($2\text{x}, 4\text{x}, 6\text{x}$) và tùy chỉnh chất lượng nén ảnh JPG.

* **Tải xuống linh hoạt:** Hỗ trợ xem trước lưới ảnh kèm thông số kích cỡ/dung lượng, tải xuống từng ảnh đơn lẻ hoặc đóng gói tải về toàn bộ dưới dạng file `.zip`.

---

## 🛠️ Hướng Dẫn Sử Dụng

* **Nạp tài liệu:** Kéo thả tệp tin `.docx` / `.pdf` vào vùng trung tâm, nhấp đúp để chọn file từ máy tính, hoặc nhấn tổ hợp phím `Ctrl + V` ở bất kỳ đâu trên trang để dán file từ bộ nhớ tạm.

* **Cấu hình trích xuất:**
* **Với file `.docx`:** Nhập kích thước pixel rộng/cao tối thiểu để lọc bỏ ảnh rác, sau đó nhấn **Áp dụng**.

* **Với file `.pdf`:** Nhập số trang cần lấy (hoặc để trống để lấy tất cả), chọn độ phân giải và chất lượng JPG mong muốn, sau đó nhấn **Áp dụng**.

* **Tải ảnh về máy:**
* Nhấp chuột vào từng thẻ ảnh hiển thị trên lưới để tải xuống ảnh đơn lẻ.

* Nhấp nút **Tải xuống trang hiện tại (.zip)** hoặc **Tải xuống tất cả ảnh (.zip)** ở thanh chức năng để tải hàng loạt.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ tích hợp:** HTML5, CSS3 (CSS Variables & Responsive Grid), JavaScript Thuần (Vanilla JS), tích hợp thư viện bổ trợ `JSZip` và `PDF.js` xử lý giải mã tệp tin trực tiếp.
