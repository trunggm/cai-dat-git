# Cài đặt Git
## 1. Cài đặt ở máy tính mới
a. Cài đặt Git và tạo ssh-key
  * Tải Git-csm tại đây [link](https://git-scm.com/downloads)
  * Tạo ssh-key cho máy tính
  Bật GitBash vừa được cài đặt và lần lượt gõ các lệnh sau
  `ssh-keygen -t rsa -b 4096 -C "your-email"`
  Nhấn Enter cho đến khi kết thúc
  * Gõ lệnh tiếp theo
  `cat ~/.ssh/id_rsa.pub`
  * Copy ssh-key hiện ra trong Git Bash và copy vào phần SSH key trong Github và lưu lại.
  * Kiểm tra thử kết nối tới Github bằng cách gõ vào trong Git Bash
  `ssh -T git@github.com`
  Sau đó gõ `yes`
  *
