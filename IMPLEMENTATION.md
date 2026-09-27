# Implementation Instructions

## Nhiệm vụ

Hãy xây dựng hoàn chỉnh landing page theo `REQUIREMENTS.md`.

File chính cần tạo:

`index.html`

## Bootstrap

Sử dụng Bootstrap thông qua CDN.

Không cài package hoặc yêu cầu build step.

## HTML

Sử dụng semantic HTML khi phù hợp: - `header` - `nav` - `main` -
`section` - `footer`

Các section nên có `id` để Navbar có thể điều hướng bằng anchor link.

## CSS

Thiết kế dựa trên:

``` css
--page-bg: #f2f2f2;
--primary: #2d2d86;
```

Ưu tiên: - Layout sạch - Khoảng trắng rộng - Card hiện đại - Border
radius vừa phải - Shadow nhẹ - CTA nổi bật - Hình ảnh có
`object-fit: cover`

Không làm giao diện quá nhiều màu hoặc quá nhiều hiệu ứng.

## JavaScript

Chỉ sử dụng JavaScript cho các tương tác frontend cần thiết, ví dụ: -
Smooth scrolling - Navbar mobile - CTA interaction đơn giản

Không tạo logic backend.

## Hình ảnh

Hero: - Dùng hình ảnh bất động sản / biệt thự nghỉ dưỡng cao cấp. - Hình
nằm bên phải trên desktop.

Features: - Mỗi feature sử dụng một hình ảnh khác nhau. - Hình phải phù
hợp với nội dung của từng feature.

Nếu sử dụng hình ảnh từ nguồn bên ngoài, dùng URL ảnh trực tiếp phù hợp
để trang có thể render ngay khi mở.

## Nội dung

Nội dung phải viết bằng tiếng Việt.

Hero cần: - Headline thu hút - Mô tả ngắn - 1 CTA

Features bắt buộc: 1. Lối sống thượng lưu 2. Tiện ích tối ưu 3. Pháp lý
nhanh gọn

Footer: - Copyright - Thông tin liên hệ

## Acceptance Criteria

Sản phẩm được xem là hoàn thành khi:

1.  Có file `index.html`.
2.  Trang chạy trực tiếp trên trình duyệt.
3.  Bootstrap được load qua CDN.
4.  Có đầy đủ Header/Navbar, Hero, Features và Footer.
5.  Hero có nội dung bên trái và hình ảnh bên phải trên desktop.
6.  Features có đúng 3 nội dung yêu cầu và 3 hình ảnh khác nhau.
7.  Giao diện sử dụng `#f2f2f2` và `#2d2d86` làm màu chủ đạo.
8.  Responsive trên mobile.
9.  Không có backend.
10. Không yêu cầu build hoặc cài dependency để xem trang.
