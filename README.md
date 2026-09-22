# Lab 2: Ngôn ngữ HTML5 & Tối ưu SEO

**Họ và tên:** Lê Nguyễn Thiện Lộc  
**Môn học:** Lập trình Web  

---

## 1. Giới thiệu dự án
Dự án bao gồm website cá nhân dạng tĩnh được xây dựng bằng **HTML5 Semantic**, hỗ trợ **Form Validation** và tích hợp chuẩn hóa **SEO** (Meta Description, Title riêng biệt, thẻ Open Graph).

---

## 2. Cấu trúc thư mục dự án
* `index.html`: Trang chủ giới thiệu tổng quan hồ sơ cá nhân và kỹ năng nổi bật.
* `about.html`: Trang giới thiệu bản thân chi tiết, hình ảnh chân dung, kỹ năng lập trình và bảng lộ trình môn học.
* `contact.html`: Trang biểu mẫu liên hệ chứa 2 fieldset, tích hợp các ràng buộc HTML5 Validation (required, pattern, minlength), datalist gợi ý và xem trước thông tin nhập.
* `README.md`: File mô tả dự án.

---

## 3. Các tính năng nổi bật đã thực hiện
1. **HTML5 Semantic:** Sử dụng đúng các thẻ chuẩn như `<header>`, `<nav>`, `<main>`, `<section>`, `<figure>`, `<figcaption>`, `<fieldset>`, `<footer>`.
2. **Form Validation:** Kiểm tra dữ liệu đầu vào ngay ở Front-end (bắt buộc nhập, kiểm tra định dạng Email, SĐT 10–11 số, độ dài chuỗi).
3. **Chuẩn hóa SEO & Accessibility:** 
   * Thêm `<title>` và `<meta name="description">` chuẩn 150–160 ký tự cho từng trang.
   * Cấu hình thẻ `<meta property="og:...">` (Open Graph).
   * Liên kết thẻ `<label for="...">` trỏ chính xác đến `id` của từng `<input>` để hỗ trợ truy cập (Accessibility).