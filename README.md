# Thực hành Quản lý Phiên bản với Git và GitHub

- **Sinh viên thực hiện:** Hà Tấn Minh
- **Repository:** ThucHanhGit_HaTanMinh

## 1. Mục đích
Repository này được xây dựng nhằm thực hành quy trình quản lý phiên bản bằng Git trên máy tính cá nhân, kết hợp sử dụng GitHub để lưu trữ, chia sẻ mã nguồn và phối hợp phát triển theo các yêu cầu của bài tập thực hành.

## 2. Cách sử dụng
- **Clone repository về máy tính (bao gồm cả submodule):**
  `git clone --recurse-submodules [https://github.com/](https://github.com/)<username>/ThucHanhGit_HaTanMinh.git`
- **Di chuyển vào thư mục dự án:**
  `cd ThucHanhGit_HaTanMinh`
- **Cập nhật submodule (nếu clone thông thường):**
  `git submodule update --init --recursive`

## 3. Các kỹ thuật đã thực hiện
- **A. Cài đặt và thao tác Git cơ bản:** Cấu hình định danh (`git config`), khởi tạo kho (`git init`), theo dõi trạng thái (`git status`, `git diff`), xem lịch sử (`git log`), thiết lập `.gitignore` và chỉnh sửa commit gần nhất (`git commit --amend`).
- **B. Nhánh và hợp nhất:** Tạo, chuyển và đổi tên nhánh (`git branch`, `git switch`), hợp nhất nhánh (`git merge`), xử lý xung đột (Conflict Resolution), tái định vị lịch sử (`git rebase`) và xem sơ đồ nhánh trực quan.
- **C. Làm việc với GitHub và cộng tác:** Kết nối remote qua HTTPS và SSH, đẩy/kéo dữ liệu (`git push`, `git pull`, `git clone`), tạo Pull Request, đánh dấu phiên bản với Release Tag (`v1.0.0`), xuất bản trang tĩnh qua GitHub Pages và quản lý nhiều remote.
- **D. Kiểm tra, khôi phục và tìm lỗi:** Khôi phục thay đổi (`git restore`), ngừng theo dõi tệp (`git rm --cached`), truy xuất lịch sử tệp (`git show`, `git log -p`), tìm kiếm chuỗi (`git grep`), dò tìm commit gây lỗi (`git bisect`), khôi phục commit đã xóa (`git reflog`) và hoàn tác commit trên remote (`git revert`).
- **E. Công cụ và tính năng nâng cao:** Lưu tạm thay đổi chưa commit (`git stash`), rút gọn lệnh với `git alias` và quản lý kho mã nguồn phụ bằng `git submodule`.
