---------------OOP-----------------------

Tìm hiểu về Github

-Vài thông tin về GIT:
        +Là công cụ giúp quản lý source code tổ chức theo dạng dữ liệu phân tán, giúp đồng bộ source code của team lên 1 server.
        +Hỗ trợ các thao tác kiểm tra source code trong quá trình làm việc (diff, check modifications, show history, merge source, …)
-GitHub là một dịch vụ cung cấp kho lưu trữ mã nguồn Git dựa trên nền web cho các dự án phát triển phần mềm.
-Github cung cấp các tính năng social networking như feeds, followers, và network graph để các developer học hỏi kinh nghiệm của nhau thông qua lịch sử commit.
-Tính năng của Github
GitHub được coi là một mạng xã hội dành cho lập trình viên lớn nhất và dễ dùng nhất với các tính năng cốt lõi như: 
        +Wiki, issue, thống kê, đổi tên project, project được đặt vào namespace là user.
        +Watch project: theo dõi hoạt động của project của người khác. Xem quá trình người ta phát triển phầm mềm thế nào, project phát triển ra sao.
        +Follow user: theo dõi hoạt động của người khác.
 -Các lệnh git cơ bản
git config
Để kiểm tra tên và kiểu email trong cấu hình dùng git config -- global và git config -- global user.email..
Để set email hoặc tên mới git config -- global usee.name = "User name" và git config -- global user.email = "useremail@gmail.com".
git init
Dùng để khởi tạo 1 git repository.
git clone
Copy 1 git repository từ remote source.
git status
Để check trạng thái của những file bạn đã thay đổi trong thư mục làm việc.
git add
Thêm thay đổi đến stage/index trong thư mục làm việc.
git commit
Một hành động để git lưu lại một snapshot của các sự thay đổi trong thư mục làm việc.
git push/git pull
Push hoặc Pull các thay đổi đến remote.
git branch
Liệt kê tất cả các branch.
git checkout
Chuyển sang branch khác.
git stash
Lưu thay đổi không muốn commit ngay lập tức.
git merge
Hợp 2 branch lại với nhau.
