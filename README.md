# Java Spring Boot API - CI/CD Demo

Dự án mẫu Spring Boot REST API nhẹ phục vụ học tập CI/CD với GitHub Actions.

## Chức năng
- API `/api/hello`: Trả về thông điệp chào mừng
- API `/api/health`: Kiểm tra trạng thái service (Health check)
- Unit test với Spring WebMvcTest & JUnit 5
- Tích hợp GitHub Actions CI tự động:
  - Check cú pháp & biên dịch (`mvn clean compile`)
  - Chạy kiểm thử (`mvn test`)
  - Đóng gói ứng dụng (`mvn package`)
  - Lưu file `.jar` vào Artifacts
