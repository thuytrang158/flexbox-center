# CodeGym Career — Landing Page

Landing page tiếng Việt giới thiệu chương trình CodeGym Career, được xây dựng theo phong cách Material Design với MDBootstrap 4 và Bootstrap 4. Trang có bố cục responsive cho máy tính và thiết bị di động.

## Nội dung

- `index.html` — cấu trúc trang, nội dung chương trình, lộ trình học, khóa học và thông tin liên hệ.
- `style.css` — màu sắc, bố cục và kiểu hiển thị responsive.

## Chạy trên máy

Mở `index.html` bằng trình duyệt. Các thư viện giao diện và biểu tượng được tải từ CDN nên cần kết nối Internet.

## Các lệnh Git cơ bản

Chạy các lệnh sau trong thư mục dự án. Thay URL mẫu bằng URL repository GitHub của bạn.

```bash
git init
git remote add origin https://github.com/thuytrang158/flexbox-center.git
git add README.md
git commit -m "Add README.md file"
git push origin main
```

- `git init` khởi tạo một local Git repository trong thư mục hiện tại. Nếu thư mục đã là một repository, không cần khởi tạo lại.
- `git remote add origin <URL>` thêm địa chỉ remote repository và đặt tên ngắn cho nó là `origin`. Dùng `git remote -v` để xem các remote hiện có; nếu `origin` đã được cấu hình, dùng `git remote set-url origin <URL>` để cập nhật địa chỉ thay vì thêm trùng.
- `git add README.md` đưa README vào staging area để chuẩn bị lưu trong commit. Có thể thay tên file hoặc dùng `git add .` để thêm các thay đổi khác.
- `git commit -m "..."` tạo commit từ các thay đổi đã staged. Nội dung sau `-m` là thông điệp mô tả commit.
- `git push origin main` đẩy các commit trên nhánh local `main` lên nhánh `main` của remote `origin`.

## Repository

[https://github.com/thuytrang158/flexbox-center](https://github.com/thuytrang158/flexbox-center)
