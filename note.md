# Terms(Danh từ):

- Repository (repo): là kho, là thư mục dự án.
- Branch: cành.
- Conflict: Xung đột.
- Local: những gì có trong máy tính chúng ta
- Remote: ngược lại local.

# Commands(Câu lệnh):

- git init: làm cho repo thành git repo(làm cho dự án có thể sử dụng git).

- git status: cho thấy trạng thái của project(thấy những thay đổi của project).

- git add <tên file>: chuẩn bị lưu lại file.
- git add .: chuẩn bị lưu tất cả các file.
- git reset: hủy chuẩn bị lưu.
- git commit: chính thức lưu(sử dụng khi giải quyêt conflict).
- git commit -m '<ghi chú>': ghi chú khi lưu.
- git log: xem những thời điểm đã lưu.
- git log --oneline: gọn hơn log.
- git checkout <mã id>: quay về lại commit có id là mã id.
- git checkout master: quay về trước đó.
- :q để thoát end.
- git branch: xem các branch.
- git checkout -b <branch name>: tạo branch mới.
- git checkout <branch name>: trở về branch.
- git merge <branch name>: gộp với branch master.
- git branch -d <branch name>: xóa 1 branch.
- git push <link Github> <branch name>: đẩy repo local lên repo remote.
- git remote add <name> <repo url>: đặt tên cho đường dẫn.
- git clone <repo url>: lấy repo remote về máy.
- code . : vào thư mục của repo rồi sử dụng lệnh này để mở project.
- git push -u (<repo url> hoặc <elious name>) <branch name> : đẩy branch lên github.
- git fetch (<repo url> hoặc <elious name>) +
  git checkout -b <branch name> (<repo url> hoặc <elious name>)/<branch name> : kéo branch về local.
- git pull: kéo sự thay đổi khi merge trên github về local.
