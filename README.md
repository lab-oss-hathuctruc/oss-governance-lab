# OSS Governance Lab)

Dự án thực hành môn **Quản trị dự án & Vận hành cộng đồng mã nguồn mở (OSS)**.
Repo mô phỏng cách một dự án OSS tổ chức quản trị, ra quyết định và tiếp nhận đóng góp.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Giới thiệu

Dự án vận hành theo mô hình **Đồng thuận mở (Consensus-Seeking)** kết hợp **Công trạng kỹ thuật (Meritocracy)**.
Mọi quyền hạn trên repo gắn với đóng góp thực tế và được công khai trong bậc thang thăng tiến.

## Tài liệu quản trị

| Tệp | Nội dung |
| --- | --- |
| [GOVERNANCE.md](.github/GOVERNANCE.md) | Quy chế quản trị và Bậc thang thăng tiến (Contributor Ladder) |
| [MAINTAINERS.md](MAINTAINERS.md) | Danh sách người bảo trì và kế hoạch chuyển giao khẩn cấp |
| [ROADMAP.md](ROADMAP.md) | Lộ trình phát triển theo mô hình Now - Next - Later |
| [docs/rfc/](docs/rfc/) | Các đề xuất kiến trúc (RFC) |

## Vai trò trong nhóm

| Thành viên | Vai trò | Quyền trên GitHub |
| --- | --- | --- |
| @artemisha22 | Project Lead / Steering Council | Admin |
| @doremimi22 | Core Maintainer | Write |
| @MinhTruc53 | Triager / Reviewer | Triage |
| @<username_D> | Community Contributor | Read (Fork) |

## Cách đóng góp

1. **Fork** repo về tài khoản của bạn.
2. Tạo nhánh mới từ `main`, ví dụ: `feat/ten-tinh-nang` hoặc `fix/ten-loi`.
3. Commit thay đổi với thông điệp rõ ràng (ví dụ: `docs: sửa lỗi chính tả README`).
4. Mở **Pull Request** vào nhánh `main` và mô tả ngắn gọn thay đổi.
5. Chờ Maintainer review. Mỗi PR cần tối thiểu **01 approval** trước khi được gộp.

### Báo lỗi (Issue)

Khi mở Issue, vui lòng cung cấp: **log lỗi, hệ điều hành, phiên bản** và các bước tái hiện.
Đội ngũ Triager sẽ gán nhãn và phản hồi sớm nhất có thể.

### Đề xuất thay đổi lớn (RFC)

Các thay đổi ảnh hưởng đến kiến trúc cốt lõi cần có RFC trong `docs/rfc/` (ví dụ: `RFC-0001.md`).
RFC áp dụng cơ chế **Lazy Consensus**: nếu sau **72 giờ** không có phản đối kỹ thuật có lý do (-1 Veto),
đề xuất được xem là thông qua.

## Hệ thống nhãn (Labels)

- **Loại việc:** `type: bug`, `type: feature`, `type: documentation`
- **Ưu tiên:** `priority: P0 (Critical)`, `priority: P1 (High)`, `priority: P2 (Medium)`
- **Người mới:** `good first issue`

## Quy tắc ứng xử

Mọi thành viên cần giao tiếp tôn trọng, không công kích cá nhân.
Hành vi vi phạm sẽ được Steering Committee xử lý theo các cấp độ của
[Contributor Covenant](https://www.contributor-covenant.org/): Correction, Warning, Temporary Ban, Permanent Ban.

## Giấy phép

Phát hành theo giấy phép [MIT](LICENSE).

## Liên hệ

- Project Lead: sv_a@university.edu
