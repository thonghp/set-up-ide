# Day 2: SHORTCUT & SYNTAX & CONFIG

## Mục Lục Nội Dung

- [1. Shortcut trong intellij thường dùng nhất](#1-shortcut-trong-intellij-thường-dùng-nhất)
  - [1.1. Add maven](#11-add-maven)
  - [1.2 Connect database SQL Server](#12-connect-database-sql-server)
  - [1.3 Connect database My SQL](#13-connect-database-my-sql)
  - [1.4 Sử dụng git](#14-sử-dụng-git)
    - [1.4.1 Clone git về](#141-clone-git-về)
    - [1.4.2 Úp dự án bất kỳ lên git mà chưa clone](#142-úp-dự-án-bất-kỳ-lên-git-mà-chưa-clone)
  - [1.5 Plugin reset intellij](#15-plugin-reset-intellij)
  - [1.6 Biến thành thư mục test và thêm thư viện maven](#16-biến-thành-thư-mục-test-và-thêm-thư-viện-maven)
    - [1.6.1 Biến thành thư mục test](#161-biến-thành-thư-mục-test)
    - [1.6.2 Thêm thư viện maven](#162-thêm-thư-viện-maven)
  - [1.7 Truy cập file trên project trong cục bộ](#17-truy-cập-file-trên-project-trong-cục-bộ)
- [2. Shortcut trong eclipse thường dùng nhất](#2-shortcut-trong-eclipse-thường-dùng-nhất)
  - [2.1. Tùy chỉnh cài đặt trong eclipse thường dùng](#21-tùy-chỉnh-cài-đặt-trong-eclipse-thường-dùng)
- [3. Shortcut trong visual studio code thường dùng nhất](#3-shortcut-trong-visual-studio-code-thường-dùng-nhất)
  - [3.1 Emmet](#31-emmet)
  - [3.2 Truy cập file trên project trong cục bộ](#32-truy-cập-file-trên-project-trong-cục-bộ)
- [4. Shortcut trong Windows 10 thường dùng nhất](#4-shortcut-trong-windows-10-thường-dùng-nhất)
- [5. Sử dụng workbench trong My SQL](#5-sử-dụng-workbench-trong-my-sql)
- [6. Xóa phần mềm trên máy tính](#6-xóa-phần-mềm-trên-máy-tính)
- [7. Shortcut trong cmd](#7-shortcut-trong-cmd)
- [8. Shortcut trong run](#8-shortcut-trong-run)
- [9. Cấu hình evkey](#9-cấu-hình-evkey)
- [10. Lệnh terminal trong xampp](#10-lệnh-terminal-trong-xampp)

## 1. Shortcut trong intellij thường dùng nhất

- nhảy tới lỗi => `F2`
- tạo command **`//`** => **`ctrl + /`** và command **`\*`** => **`shift + ctrl + /`**
- format => `ctrl + atl + L`
- rename => `shift + F6`
- tạo nhanh println => `sout`
- nhân đôi line => `ctrl + D`
- xóa line => `ctrl + Y`
- move line => `alt + shift + arrow`
- tạo nhanh for => `fori` và for-each => `iter`
- tạo nhanh constructor, get & set,...=> `alt + insert`
- tạo nhanh class => `alt + home => alt + insert`
- move file => `F6`
- hiện đề xuất, viết nhanh var và method => `alt + enter`
- tạo nhanh test => `ctrl + shift + T`
- viết nhanh đk if, try,... => `(statement) + ctrl + alt + T`
- chọn class bên phần tab xem code không cần mở => `space`
- replace => `ctrl + R`
- tìm nhanh method, class, file => `shift + shift`
- tìm kiếm thông tin trong file, class, project, module => `ctrl + shift + F`
- xoá import thừa => `ctrl + alt + O`
- đóng cửa sổ => `ctrl + F4`
- hint => `ctrl + space`
- mở các file gần đây => `ctrl + E`
- điều hướng tới class => `ctrl + B`
- tìm method trong class => `ctrl + F12`
- hiện các method in class => `alt + F7`
- tìm class file => `ctrl + shift + N`

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.1. Add maven

- B1: chọn project => click chuột phải => add framework support => chọn maven

![alt text](/assets/day-02-add-maven1.png)

- B2: thêm các library vào trong file pom.xml

![alt text](/assets/day-02-add-maven2.jpg)

- B3: lần lượt thêm các thư viện

![alt text](/assets/day-02-add-maven3.jpg)

> vd ở đây thêm 2 thư viện mssql jdbc và jcalendar

- B4: tiến hành tải thông qua chữ m

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.2 Connect database SQL Server

- B1: chọn database => chọn biểu tượng `+` => chọn data source => chọn database mình sử dụng

![alt text](/assets/day-02-connect-database1.png)

- B2: nhập name, host, instance, nhập pass và nhập tên database, lưu ý host coi trong database

![alt text](/assets/day-02-connect-database2.png)
![alt text](/assets/day-02-connect-database1a.png)

- B3: chọn vô tải driver thiếu ở dấu chấm thang màu vàng
- B4: nhấn test connection để kiểm tra xem đã chạy được chưa, nếu được nhấn ok

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.3 Connect database My SQL

- B1: chọn database => chọn biểu tượng `+` => chọn data source => chọn database mình sử dụng, ở đây chọn My SQL

![alt text](/assets/day-02-connect-db-mysql-01.png)

- B2: nhập name, host, instance, nhập pass và nhập tên database

![alt text](/assets/day-02-connect-db-mysql-02.png)

- B3: chọn vô tải driver thiếu ở dấu chấm thang màu vàng
- B4: nhấn test connection để kiểm tra xem đã chạy được chưa, nếu được nhấn ok

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.4 Sử dụng git

#### 1.4.1 Clone git về

- clone thư mục git => chọn VCS => get from version control

![alt img](/assets/intellij-clone-git.png)

- Nhập url của clone => lúc nay chọn new windows

#### 1.4.2 Úp dự án bất kỳ lên git mà chưa clone

Mở vô file dự án muốn úp

- B1: Chọn create git repository => chọn folder project

![alt img](/assets/intellij-create-git-repo.png)

- B2: Chọn file muốn add => chuột phải chọn git add
- B3: Commit => push (ở đây chưa connect với repo)
- B4: define remote => chọn url clone => sau đó nhấn push (**lưu ý nếu đây là nhánh master thì có thể rename thành main**)

![alt img](/assets/intellij-define-remote.jpg)

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.5 Plugin reset intellij

![alt img](/assets/reset-intellij.png)

### 1.6 Biến thành thư mục test và thêm thư viện maven

#### 1.6.1 Biến thành thư mục test

- B1: Tạo thư mục đặt tên là test, ngang hàng với src
- B2: Chọn `Mark directory as` ==> `test source root`

![create test folder](/assets/create-test-folder.png)

#### 1.6.2 Thêm thư viện maven

- B1 chọn `File` => `project structure`
- B2 chọn `Libraries` => `+` => `From maven`
- B3 tìm thư viện mình muốn xài

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 1.7 Truy cập file trên project trong cục bộ

Nhấp chuột phải vào file muốn truy cập => `Open In` => `Explorer`

![explorer](/assets/explorer-intellij.png)

## 2. Shortcut trong eclipse thường dùng nhất

- tạo command => `ctrl + shift + C`
- save xong run => `ctrl + F11`
- xóa line => `ctrl + D`
- format => `ctrl + shift + F`
- copy line => `ctrl + alt + arrow`
- move line => `alt + arrow`
- hint => `ctrl + space`
- rename var method hàng loạt => `alt + shift + R`
- auto thêm xóa import thiếu thừa => `ctrl + shift + O`
- hỗ trợ phím tắt => `ctrl + shift + L`
- find và replace => `ctrl + F`
- đóng class => `ctrl + W` và đóng tất cả class => `ctrl + shift + W`
- tạo mới trong menu => `alt + shift + N`
- mở thanh điều hướng ở trên => `alt + F`
- nhảy tới dòng chỉ định => `ctrl + L`

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 2.1. Tùy chỉnh cài đặt trong eclipse thường dùng

- format vn => `Window => references => workspace => other => UTF-8`
- hỗ trợ gợi ý code => `Window => references => Java => Editor => Content Assist`
- format font chữ => `Window => references => appearence => colors and fonts => basic => text font`

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

## 3. Shortcut trong visual studio code thường dùng nhất

- Tạo nhiều con trỏ với vị trí trên 1 cột => `ctrl + alt + arrow`
- Tạo nhiều con trỏ với vị trí ngẫu nhiên => `alt + click`
- Di chuyển dòng hiện tại lên/xuống => `alt + arrow`
- copy hàng trên/dưới => `shift + alt + arrow`
- Format => `shift + alt + F`
- Format cột nếu quá dài => `alt + Z`
- Chọn dòng hiện tại => `ctrl + L`
- Tìm kiếm từ hoặc cụm từ giống nội dung => `ctrl + D`
  - Mỗi lần nhấn nó sẽ chọn từ/cụm khớp, nó sẽ chọn từ vị trí hiện tại xong tìm xuống dưới
- Chọn tất cả từ/cụm khớp => `ctrl + shift + L`
- Nhảy đến dòng/cột chỉ định => `ctrl + G`
- Tìm => `ctrl + F` và replace => `ctrl + H`
- Chọn đoạn văn bản => `click + (shift + click)`
- Comment => `Ctrl + /`
- Di chuyển giữa các tab => ctrl tab
- Đóng file => `Ctrl + F4` or `ctrl + W`
- Xóa dòng hiện tại => `Ctrl + Shift + K`
- Hiển thị terminal => **ctrl + `**
- Mở command palette để tìm kiếm tính năng, lệnh, extension => `Ctrl + Shift + P`
- ẩn/hiển thanh explorer của vscode => `Ctrl + B`
- hint => `ctrl + space`
- Open bảng các phím tắt => `ctrl + K + S`

**Dùng trong code**

- Mở quick open (để tìm file) => `ctrl + P`
- Xem hàm hoặc biến trong file đang chọn => `ctrl + shift + O`
- Tìm hàm hoặc biến trong toàn bộ file => `ctrl + T`
- Nhảy tới hàm => `F12` và nhấn `alt + ←` để quay trở lại
- Xem hàm được dùng ở đâu => `Shift + F12`
- Đổi tất cả tên hàm cùng lúc => `F2`

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

### 3.1 Emmet

- Div chứa class bên trong => `div.className + tab`
- Div chứa id bên trong => `div#idName + tab`
- Div lồng div (ở đây chứa 2 div con trong 1 div) => `div>div+div` or `div>div*2`

### 3.2 Truy cập file trên project trong cục bộ

Nhấp chuột phải vào file muốn truy cập => `Reveal in file explorer` hoặc phím tắt `Shift + alt + R`

![explorer](/assets/explorer-vsc.png)

## 4. Shortcut trong Windows 10 thường dùng nhất

- Chia cửa sổ
  - `Windows + →` => chia ứng dụng làm đôi và để bên phải
  - `Windows + ←` => chia ứng dụng làm đôi và để bên trái
- `Windows + E` => vô ngay thư mục
- `ctrl + shift + esc` => mở task manager
- `Windows + I` => mở setting trên win 10
- `Windows + D` => quay về màn hình desktop
- `ctrl + shift + T` => mở lại những tab đã coi nếu đã tắt
- `Windows + ;` => lấy icon
- `Windows + R` => mở run
  - `psr.exe` => mở ra cái hướng dẫn từng bước chạy chương trình
  - `osk` => mở bàn phím ảo
- `Windows + L` => khóa màn hình về chế độ lock screen
- `Windows + tab` => mở ra các tab đang chạy
- `alt + chuột trái` => để tải hình ảnh
- `ctrl + W` => đóng tab
- `Snipping Tool` => chụp nhanh màn hình
- Thao tác trong cmd
  - `wmic csproduct get name` => xem tên laptop
  - `wmic bios get serialnumber` => coi seri laptop
- `/` => nhảy tới thanh tìm kiếm trên google

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

## 5. Sử dụng workbench trong My SQL

- Sử dụng ngôi sao để lưu snippet code lại

![alt text](/assets/day-02_snippet_workbench.png)

Xem thêm hướng dẫn [ở đây][mysql]

[mysql]: https://www.youtube.com/watch?v=chezeWdTHbo

## 6. Xóa phần mềm trên máy tính

Xóa toàn bộ phần mềm trên máy tính:

- Vào ổ đĩa **`C: ==> Program Files`** và xóa folder của phần mềm
- Vào ổ đĩa **`C: ==> ProgramData`** và xóa folder của phần mềm
  - ProgramData phải bật lên vì nó là ổ đĩa ẩn
- Vào ổ đĩa **`C: ==> Users => Admin => AppData => Roaming`** => xóa folder của phần mềm
  - AppData phải bật lên vì nó là ổ đĩa ẩn

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

## 7. Shortcut trong cmd

- **`cls`** => xóa màn hình lệnh như clear trong github
- **`dir`** => xem các file có trong thư mục
- **`cd <name>`** => di chuyển tới ổ đĩa chỉ định
- **`cd ..`** => lùi thư mục hiện tại lại một bậc
- **`code .`** => mở vsc 

## 8. Shortcut trong run

- **`dxdiag` ==>** xem thông số máy tính
- **`shell:startup` ==>** mở thư mục start up, nơi chứa các file muốn khởi động cùng window khi mở máy
- **`services.msc` ==>** mở phần mềm quản lý service, nơi có thể tắt / bật các dịch vụ như bluetooth, update window
- **`regedit` ==>** mở registry editor
- **`msinfo32` ==>** coi system information bao gồm thông số máy, tên máy, bios,...
- **`eventvwr.msc` ==>** xem thông số Event viewer, chủ yếu xem khi máy tắt đột xuất

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

## 9. Cấu hình evkey

![evkey](/assets/evkey1.jpg)

- Ở trang này lưu ý phần kiểu gõ là chọn **telex đơn giản** vì nếu chọn telex thì gõ w là nó ra ư xong nhấn cái nữa mới ra w
- Chọn sửa lỗi dấu của gợi ý 2 tránh bị lỗi khi gõ address

![evkey hệ thống](/assets/evkey2.jpg)

- Loại trừ ứng dụng tự động để nó lưu evkey riêng cho từng app

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**

## 10. Lệnh terminal trong xampp

- B1: chạy xampp > chạy apache + mysql
- B2: chọn shell
- B3: nhập lệnh **`mysql -u root -p`**
- B4: phần **`enter password`** để trống
- B5: **`show databases;`** => để xem các database hiện có
- B6: **`USE <name-database>;`** => truy cập vào database;

**[⬆ Quay trở lại đầu trang](#mục-lục-nội-dung)**
