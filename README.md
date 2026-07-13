# Ba Na SmartLink – Nền tảng AI kết nối dữ liệu Thôn - Xã

[![Status](https://img.shields.io/badge/Status-Development-yellow)](https://github.com/jhihihij/web-smartlink/)
[![Frontend](https://img.shields.io/badge/Tech-HTML5_CSS3_JS-orange)](https://developer.mozilla.org/)
[![Bootstrap](https://img.shields.io/badge/Framework-Bootstrap_5.3-purple)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Ba Na SmartLink** là giải pháp chuyển đổi số toàn diện, đóng vai trò là "cầu nối" thông minh giữa chính quyền cấp Xã, cán bộ cấp Thôn và người dân tại địa phương. Hệ thống tích hợp các công cụ AI hiện đại để tối ưu hóa quy trình quản trị, kê khai dữ liệu dân cư và phản ánh kiến nghị trực tuyến.

---

## Các phân hệ tính năng chính

*   **Hệ thống AI Trợ lý thông minh:**
    *   Tích hợp nhận diện giọng nói (**Web Speech API**) giúp người dân và cán bộ nhập liệu nhanh.
    *   Công cụ tự động soạn thảo văn bản hành chính theo mẫu.
    *   Chatbot AI hỗ trợ tra cứu dữ liệu địa phương, thông tin lãnh đạo và quy mô dân số nhanh chóng.
*   **Quản trị & Điều hành số:**
    *   Bảng điều khiển (Dashboard) phân quyền cho Cán bộ Thôn và Cán bộ Xã.
    *   Cơ chế kiểm duyệt dữ liệu số liệu (Grid-based validation) trước khi phê duyệt.
*   **Cổng thông tin công dân (Smart Portal):**
    *   Xem tin tức, sự kiện và thông báo quan trọng thời gian thực.
    *   Form liên hệ, phản ánh hiện trường tích hợp (gửi thông tin, góp ý nhanh).
*   **Hiển thị trực quan:**
    *   Giao diện responsive, trải nghiệm mượt mà với hiệu ứng SPA (Single Page Application).
    *   Slideshow trình chiếu dữ liệu địa bàn và danh lam thắng cảnh (Sun World, Cầu Vàng).

---

## Công nghệ & Kỹ thuật

*   **Giao diện:** HTML5 Semantic Markup, Bootstrap 5.3 (Grid, Components).
*   **Tương tác:** JavaScript (ES6+), xử lý SPA (Single Page Application) không tải lại trang.
*   **Trải nghiệm người dùng:** Font Awesome 6, Google Fonts (Baloo 2, Quicksand).
*   **Đặc điểm nổi bật:** Sử dụng `backdrop-filter` cho hiệu ứng Glassmorphism và CSS Animations.

---

## Cấu trúc dự án

```text
ba-na-smartlink/
├── assets/
│   ├── css/            # Tệp định kiểu CSS tùy chỉnh
│   └── images/         # Tài nguyên hình ảnh minh họa
├── web1.html           # File giao diện chính (Trang chủ & Điều hướng)
├── congdan.html        # Phân hệ dành riêng cho Công dân
├── thon-1.html         # Giao diện quản trị Cấp Thôn
└── xa-1.html           # Giao diện quản trị Cấp Xã
```

---

## Hướng dẫn khởi chạy

1. **Yêu cầu:** Trình duyệt web hiện đại (Chrome, Edge, Firefox).
2. **Cài đặt:**
    * Tải mã nguồn về máy cục bộ.
    * Đảm bảo các đường dẫn ảnh (`xa-ba-na.jpg`, `sun-world.jpg`, `cau-vang.jpg`) khớp với file cấu trúc.
3. **Chạy ứng dụng:**
    * Mở `web1.html` trực tiếp bằng trình duyệt.
    * *Khuyến nghị:* Sử dụng extension **Live Server** trong VS Code để theo dõi các thay đổi trực tiếp (Hot Reload).

---

## Đơn vị quản lý
* **Đơn vị chủ quản:** UBND xã Bà Nà, thành phố Đà Nẵng.
* **Chủ tịch UBND:** Lê Minh Tuấn.
* **Địa chỉ:** Thôn Thạch Nham Tây, xã Bà Nà, TP. Đà Nẵng.

---
*Dự án hướng tới mục tiêu xây dựng chính quyền số, công dân số trong thời đại công nghệ 4.0.*
