# Project Structure

Monorepo chứa các ứng dụng chạy/deploy độc lập và các package dùng chung.

- `apps/`: web, admin, API, worker và mobile.
- `packages/`: contracts, UI, logic, config và tiện ích dùng chung.
- `database/`, `infrastructure/`, `tests/`, `docs/`, `scripts/`: tài nguyên cấp hệ thống.

Chọn framework/ngôn ngữ cho từng ứng dụng rồi bổ sung cấu hình build tương ứng trong thư mục `apps/<app>`.
