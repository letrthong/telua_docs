# Sphinx Documentation Template (Furo theme)

This project sử dụng theme Furo cho giao diện hiện đại, đẹp mắt.

## Cấu trúc chính
- index.rst: Trang chính, mục lục.
- conf.py: Cấu hình Sphinx, đã thiết lập theme furo.
- _static/: Thư mục chứa CSS tuỳ chỉnh.
- chapter1.rst, chapter2.rst, ...: Các chương/nội dung tài liệu.

## Hướng dẫn build
1. Cài đặt các gói cần thiết:
   
   pip install sphinx furo

2. Build tài liệu:
   
   sphinx-build -b html . _build/html

3. Mở file _build/html/index.html để xem giao diện.

## Tuỳ chỉnh giao diện
- Thêm CSS vào _static/custom.css nếu muốn thay đổi chi tiết giao diện.
- Có thể chỉnh sửa conf.py để thêm extension hoặc cấu hình khác.

---

Mẫu này phù hợp cho tài liệu kỹ thuật, hướng dẫn sử dụng, hoặc tài liệu nội bộ.


pip install furo==2024.08.06
