# Website demo Chè Thịnh An

## Chạy localhost

Từ thư mục `site`, chạy một trong hai lệnh:

```powershell
python -m http.server 4173
```

hoặc dùng bất kỳ static server nào và mở `http://localhost:4173`.

## Phạm vi demo

- 6 trang nội dung tiếng Việt: Trang chủ, Về chúng tôi, Huyền Trà Xưa, Sản phẩm, Trà Đàm, Liên hệ.
- 10 sản phẩm mẫu, lọc danh mục, giỏ hàng cố định desktop và popup một lần mỗi phiên trên mobile.
- Checkout mô phỏng VNPay/QR, tính phí theo vùng và khối lượng, miễn phí từ 1.000.000đ.
- Trang `admin.html` mô phỏng quản trị đơn hàng, CRM, sản phẩm và nội dung SEO bằng `localStorage`.
- Hình ảnh AI và dữ liệu minh họa phải được thay bằng tài sản/hồ sơ thật trước khi xuất bản.
- Font tiêu đề dùng stack `SVN Manus` → `Charm`. SVN Manus chỉ hiển thị khi có file/font được cấp phép; hiện website tải Charm (Google Fonts, hỗ trợ tiếng Việt) để thay thế an toàn. Montserrat tiếp tục dùng cho nội dung.
- Ảnh báo chí thật trong `assets/images/press` chỉ dùng cho bản localhost có ghi nguồn. Cần xin quyền sử dụng ảnh trước khi xuất bản thương mại.

