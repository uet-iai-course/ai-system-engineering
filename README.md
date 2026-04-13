# Kỹ nghệ hệ thống Trí tuệ nhân tạo — Trường Đại học Công nghệ, ĐHQGHN

Tài liệu bài giảng cho môn **Kỹ nghệ hệ thống Trí tuệ nhân tạo** tại Viện Trí tuệ Nhân tạo (IAI), Trường Đại học Công nghệ (UET), ĐHQGHN.

Slide bài giảng được xây dựng bằng [Reveal.js](https://revealjs.com/).

## Các năm học

| Năm học | Học kì | Thư mục |
|---------|--------|---------|
| 2025–2026 | 2 | [`2526-2/`](2526-2/) |

> Mỗi năm học mới sẽ được thêm vào dưới dạng một thư mục riêng (ví dụ: `2627-1/`).

## Cấu trúc mỗi năm học

> Cấu trúc dưới đây chỉ mang tính khái quát; một số thư mục có thể có thêm file cấu hình hoặc tài nguyên phụ trợ.

```
XXXX-X/
├── index.html                  # Trang chủ (lịch giảng dạy)
├── lecture-*.html              # Slide bài giảng (Reveal.js)
├── lecture-style.css           # CSS dùng chung cho các slide
├── project.html                # Đề bài tập lớn
└── img/                        # Hình minh hoạ
```

## Chạy server xem trước

Dùng cấu hình Launch trong Claude Code (`.claude/launch.json`), hoặc chạy thủ công:

```bash
.conda/bin/python -m http.server 8765 --directory .
# Mở http://localhost:8765
```

## Thêm năm học mới

1. Tạo thư mục mới (ví dụ: `2627-1/`) bằng cách copy từ năm học gần nhất.
2. Cập nhật `index.html` ở root để thêm link đến năm học mới.
3. Xem hướng dẫn chi tiết trong `README.md` của thư mục năm học tương ứng.

## Giấy phép

Dự án này được phát hành dưới [GNU General Public License v3](LICENSE).
