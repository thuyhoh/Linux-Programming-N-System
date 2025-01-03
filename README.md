# Linux-Programming-N-System
## I. 
## II. Giao thức SSH và SFTP
### 1. SSH 
- SSH viết đầy đủ là Secure Shell, đây là một giao thức hỗ trợ các nhà quản trị mạng truy cập vào máy chủ từ xa thông qua mạng internet không bảo mật. Ngoài ra, SSH còn cung cấp các bộ tiện ích phục vụ phát triển chính giao thức SSH 
- SSH tạo ra cơ chế xác thực qua mật khẩu mạnh, hình thành mối liên kết giao tiếp dữ liệu mã hóa ra giữa hai máy qua môi trường internet. Ngày nay giao thức SSH được giấy quản trị mạng sử dụng phổ biến trong quá trình quản lý, điều chỉnh ứng dụng từ xa. Nó cho phép vị tự đăng nhập vào mạng máy tính và thực hiện một số tác vụ cơ bản như dịch chuyển file 
### 2. SFTP 
- SFTP là từ viết tắt của Secure File Transfer Protocol, hoặc SSH File Transfer Protocol. Đây là một giao thức mạng giúp bạn có thể upload hoặc download dữ liệu trên máy chủ. Bạn cũng có thể sử dụng giao thức này để sửa, tạo hoặc xóa các tập tin và thư mục trên máy chủ Linux 
### 3. Cấu hình trên Vscode
1.  Lấy IP  
![image](IPconfig_linux.png)
3. Cài extension SFTP 
4. Tổ hợp phím CTRL + P $\to$ chọn SFTP:config
5. Cấu hình trên sftp.json file 
``` c
    "name": "My Server",
    "host": "192.168.153.128",                      -> ip của máy ảo 
    "protocol": "sftp",                             -> tên giao thức 
    "port": 22,     
    "username": "thuy",                             -> tên máy ảo 
    "remotePath": "/home/thuy/Desktop/MyWorkspace", -> đường đẫn file muốn truyền
    "uploadOnSave": true,
    "useTempFile": true,
    "openSsh": true
```
## III. Command line
1. List file
2. change directory
3. remove
4. Current Working Directory
5. vim
6. cat
7. tree 
8. top 
9. ps aux| grep ten_process

### IV. Document
- Playlist Youtube : https://www.youtube.com/playlist?list=PL831drV1RoWunpiXBC442qlY9FIkMepNI
 