# demo-git

## Một số câu lệnh git cơ bản:

- git clone: Kéo code từ kho server (github) về kho local,
- git init : Tạo Tạo file .git (đánh dấu, tạo kho local cho project)
- git add file_name: Thêm file_name vào kho local.
- git add .:  Thêm tất cả các file đang được thay đổi trong project vào kho local
- git commit -m "Your comment." : Để commet sự thay đổi của các file đã được thêm vào kho local trước đó.
- git remote origin your_url: Tạo sự liên kết giữa kho local và kho server (github)
- git push origin your_branch: Đẩy code của bạn từ kho local vào kho server (github) tại nhánh your_branch.
- git checkout branch_name: Chuyển nhánh từ branch hiện tại sang branch_name.
- git checkout -b brand_name: Tạo mới 1 nhánh có tên branh_name và đồng thời chuyển sang nhánh đó.
- git status: kiểm tra trang thái các file thay đổi trong project.