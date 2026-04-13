# Kỹ nghệ hệ thống Trí tuệ nhân tạo — Học kì 2, năm học 2025–2026

**@Giảng viên:** Vui lòng cập nhật các file `lecture-XX.html` cho từng buổi học khi cần. Bạn có thể dùng các bài giảng hiện có làm tham khảo.

## Nội dung học kì

| Tuần | Bài giảng | Ghi chú |
|------|-----------|---------|
| 1 | Bài 1a: Giới thiệu về Thiết kế phần mềm; Bài 1b: Các loại biểu đồ UML | |
| 2 | Bài 2a: Giới thiệu Lập trình hướng đối tượng; Bài 2b: Tư duy hướng đối tượng | |
| 3 | Bài 3a: Các nguyên tắc thiết kế OOP; Bài 3b: Mẫu thiết kế OOP | |
| 4 | Bài 4a: RUP và Agile; Bài 4b: Ước lượng dự án TTNT | |
| 5 | Bài 5: Vận hành Dữ liệu | |
| 6 | Bài 6: Vận hành Hệ thống TTNT | |
| 7 | Bài 7: Kiến trúc phần mềm | |
| 8 | Bài 8: Cơ sở hạ tầng hệ thống TTNT | |
| 9 | Bài 9: Bảo mật hệ thống TTNT | |
| 10 | Bài 10: Đạo đức học máy | |

## Chạy slide

Thư mục này chứa slide bài giảng viết bằng Reveal.js, có thể serve qua GitHub Pages hoặc máy chủ web cục bộ.
Hai cách chạy dưới đây dùng hai cổng mặc định khác nhau theo cấu hình hiện tại: Node.js dùng `8000`, còn Python dùng `8765`.

### Cách 1: Node.js (hỗ trợ ghi chú giảng viên & tự động tải lại)

1. Cài [Node.js](https://nodejs.org/).
2. Trong thư mục `2526-2`, chạy `npm install` để cài dependencies.
3. Chạy `npm start` để khởi động server (port 8000).
4. Mở trình duyệt và truy cập http://localhost:8000.

### Cách 2: Python (không cần cài thêm gì)

```bash
# Chạy từ thư mục gốc của repo (dùng cấu hình .claude/launch.json)
.conda/bin/python -m http.server 8765 --directory .
# Mở http://localhost:8765
```

### Serve qua GitHub Pages

Không cần cấu hình gì thêm. Chỉ cần push thay đổi lên nhánh `main`, GitHub Pages sẽ tự động serve nội dung.
