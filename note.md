# Quy tắc 1

- không bao giờ được dùng nhánh chính của git (main, master,...)

# Nếu ko ở nhánh main thì anh em lên làm gì

- Đặt ra 1 nhánh khác để mọi người cùng nhau control
- Mỗi người cũng cần 1 nhánh khác nhau để quản lý code của riêng mình ( phần code mình đang làm )

* Ví dụ: anh code chức năng tạo lớp ( Cần 1 nhánh tạo lớp và có người làm vào )

- quy tắc đặt tên:
  code chức năng mới: feat/leninreal/create-class/20-12 ( tạo và quản lý chức năng của mình )
  feat/leninreal/create-room/20-12

* Vấn đề gặp phải

- Mỗi người 1 code, mỗi nhánh 1 loại code 1 loại chức năng
- Nơi nào để lưu trữ toàn bộ dự án ( kết hợp code của mọi người lại với nhau)

# Chuẩn bị 1 nhánh mới khác có chức năng tương tự ánh main , nhưng mọi người đều có thể truy cập ( merge pull push, revert, rebase )

- nhánh tạo ra nó có tác dụng như main nhưng main là chỉ để khi dự án hoàn thành theo từng phase , integration
- Nhánh này anh hay đặt là : development

# tạo 1 nhánh mới trên git ( hiển thị nhánh lên remote )

- Remote tức là mọi nơi đều truy cập được nếu được phép ( online )
- Local tức là chỉ mình anh em mới có thể vào

# Tạo nhánh mới

-Cách 1: đặt tên = tạo git branch ten_nhanh
-Cách 2: tạo nhánh + Chuyển sang nhánh đó : git checkout -b ten_nhanh

- mở termical ctrl = `

- để nhánh mới xuất hiện trên remote => push code lên
