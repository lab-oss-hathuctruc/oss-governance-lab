## 3. Phân tích tác động phá vỡ (Breaking Changes)

- Phiên bản v1.4 tiếp tục sử dụng Plain Text làm định dạng log mặc định, đảm bảo không làm gián đoạn kế hoạch phát hành.

- Bổ sung biến môi trường LOG_FORMAT=json|text:
  - LOG_FORMAT=text: Sử dụng định dạng log hiện tại (mặc định).
  - LOG_FORMAT=json: Sử dụng Structured JSON Logging.

- Duy trì khả năng tương thích ngược trong giai đoạn chuyển giao 6 tháng.

- Sau giai đoạn chuyển giao, tại phiên bản MAJOR v2.0.0, JSON sẽ trở thành định dạng log mặc định.

- Người dùng hiện tại có đủ thời gian để cập nhật parser và hệ thống thu thập log.
