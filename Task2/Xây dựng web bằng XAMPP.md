# Tìm Hiểu XAMPP
- `XAMPP` là cụm từ viết tắt trong đó X là viết tắt của Cross-Platform, A là viết tắt của Apache, M là viết tắt của MYSQL và PP là viết tắt của PHP và Perl. Nó là một gói giải pháp web mã nguồn mở bao gồm các bản phân phối Apache và các tệp thực thi dòng lệnh cho nhiều máy chủ, bao gồm các module như Apache server, MariaDB, PHP, và Perl.
- `XAMPP` là một phần mềm có thể tải về máy tính để tạo ra các web server. Nó tạo ra môi trường host server giả lập ngay trên máy tính, để từ đó có thể lưu trữ website mà không cần thuê hosting hay máy chủ.
- **Ưu điểm** lớn của Xampp là nó tương thích với hầu hết các hệ điều hành phổ biến hiện nay. Vì thế việc cài đặt và sử dụng Xampp trên các máy tính Windows, Linux, MacOS,...đều rất dễ dàng.
## Các thành phần XAMPP
- **Cross-Platform**: Các hệ thống cục bộ khác nhau có cấu hình hệ điều hành khác nhau. Nó tích hợp các thành phần đa nền tảng để tăng tiện ích và đối tượng của bản phân phối Apache này, hỗ trợ các gói cho các nền tảng như Windows, Linus và MAC OS.
- **Apache**: Nó là một máy chủ web HTTP đa nền tảng. Với sự hỗ trợ của Apache Software Foundation, các máy chủ từ xa của Apache sẽ gửi các tệp, hình ảnh và các tài liệu khác được yêu cầu cho người dùng.
- **Maria DB**: Ban đầu MySQL DBMS là một phần của XAMPP, nhưng bây giờ nó đã được thay thế bởi MariaDB
- **PHP**: Là một ngôn ngữ lập trình chủ yếu được sử dụng trong phát triển web.
- **Perl**: Nó là sự kết hợp của hai ngôn ngữ động cấp cao, Perl 5 và Perl 6. Rất linh hoạt và mạnh mẽ.
- **phpMyAdmin**: Nó là một công cụ để làm việc với MariaDB. Phiên bản 4.0.4 hiện có sẵn trong XAMPP. Quản lý DBMS là vai trò chính.
- **OpenSSL**: Nó là một triển khai mã nguồn mở của SSL và TLP. Phiên bản hiện tại 0.9.8 là một phần của XAMPP.
- **XAMPP Control Panel**: Đây là bảng điều khiển giúp vận hành và điều chỉnh các thành phần khác của XAMPP phiên bản 3.2.1 như bản cập nhật mới nhất. Mô tả chi tiết về bảng điều khiển được hoàn thành trong phần tiếp theo của hướng dẫn này.
- **Webalizer**: Đây là một giải pháp phần mềm phân tích trang web cho hồ sơ người dùng và cung cấp thông tin chi tiết về việc sử dụng nó.
- **Mercury**: Đây là phiên bản mới nhất của hệ thống gửi thư, 4.62, là một máy chủ email giúp quản lý email trên web.
- **Tomcat**: XAMPP đang chạy phiên bản 7.0.42, nó là một servlet dựa trên Java với các hàm Java.
- **Filezilla**: Nó là một máy chủ giao thức truyền tệp hỗ trợ và làm cho việc truyền tệp dễ dàng hơn. Phiên bản cập nhật gần đây nhất là 0.9.41
## Tải xuống và cài đặt XAMPP trên máy tính của bạn
- Truy cập https://www.apachefriends.org/download.html
# Xây dựng web trên XAMPP
- Chia làm 3 phần để có thể dễ hình dung và khái quát hơn
  - Phần 1 : Khởi động XAMPP
  - Phần 2 : Tạo dự án
  - Phần 3 : Chạy dự án trên XAMPP
## Phần 1. Khởi động XAMPP
- Sau khi download XAMPP và cài đặt xong thì chúng ta sẽ có được giao diện như này :

<img width="1046" alt="Ảnh màn hình 2024-12-11 lúc 20 46 58" src="https://github.com/user-attachments/assets/71998a53-df1f-4009-9252-55665dade34e">

- Sau đó chúng ta click vào **Go to Application** để khởi động XAMPP

<img width="1440" alt="Ảnh màn hình 2024-12-11 lúc 21 05 26" src="https://github.com/user-attachments/assets/36b8663f-54d1-4531-8401-125d7432965d">

- Sau khi XAMPP hiện lên như vậy thì chúng ta sẽ truy cập vào safari để xem là localhost của chúng ta có hoạt động hay không . Khi chúng ta truy cập được thì localhost của chúng ta đã chạy và chúng ta thấy rằng trên cái URL của chúng ta sẽ có `http://localhost:8080/dashboard/` thì **dashboard** nó là thư mục mặc định của XAMPP để chúng ta tạo dự án ở đó .
- Bước sau đó chúng ta sẽ đi xóa cái file mặc định của XAMPP ở thư mục htdocs.
- Chúng ta truy cập vào Application/XAMPP/htdocs và chúng ta sẽ xóa đi tất cả file trong thư mục `htdocs` này :

<img width="1150" alt="Ảnh màn hình 2024-12-11 lúc 21 15 54" src="https://github.com/user-attachments/assets/bdf739d8-3e79-46df-827c-bfa2ac7e1039">

- Sau khi xóa thì chúng ta sẽ truy câpj lại localhost .Thì ở đây chính là nơi khi chúng ta tạo dự án thì thư mục dự án của chúng ta sẽ xuất hiện 

<img width="985" alt="Ảnh màn hình 2024-12-11 lúc 21 17 09" src="https://github.com/user-attachments/assets/b48e9a74-9ad8-4e9e-af50-a9a271923fe7">

## Phần 2. Tạo dự án 
- Để tạo một trang web thì cái tất nhiên cần có là chúng ta code được trang web đó .Vì vậy chúng ta cần thành thạo các ngôn ngữ **PHP**,**JS**,**HTML**,...
- Tùy vào ý tưởng của chúng ta mà chúng ta tạo trang web đó như thế nào. Sau đây là mô tả về web của tôi(web cũng cơ bản vì không mong chờ gì ở một sinh viên năm nhất =)))
- Website có tính năng như sau:
  - **Frontend**: Code js sẽ chỉ cho phép password dài hơn 8 ký tự
  - **Backend**:
      - Đăng ký account(kết nối đến mysql làm database) - register.php, đăng nhập - login.php
      - Sau khi đăng nhập redirect user đến trang upload ảnh vào trang cá nhân - upload.php
      - file.php có tính năng đọc file.
- Sau khi code xong thì chúng ta sẽ đưa những file code hay là dự án của mình vào cái thư mục htdocs nãi (tôi phải tạo 1 thư mục trong thư mục htdocs để chứa những file dự án của mình và nó có tên là `web lỏ` ):

<img width="1104" alt="Ảnh màn hình 2024-12-11 lúc 21 23 39" src="https://github.com/user-attachments/assets/90a56343-29a0-4616-96cf-5dfc57c61983">

## Phần 3 . Chạy dự án trên XAMPP
- Đây là dự án mà tôi đã làm .Sau khi tôi đưa nó vào thì tôi truy cập vào localhost và tôi thấy được thư mục của mình hiện ở đó :

<img width="858" alt="Ảnh màn hình 2024-12-11 lúc 21 25 16" src="https://github.com/user-attachments/assets/a02969fa-571c-42ca-8065-4bd255abc5bd">

- Thì như đã thấy thì thư mục dự án của tôi đã hiện lên và tôi click vào thư mục đó thì tôi sẽ truy cập vào được web của mình :

<img width="883" alt="Ảnh màn hình 2024-12-11 lúc 21 26 38" src="https://github.com/user-attachments/assets/51f7e2d1-7015-4132-a0cb-bc12bdb81ddd">

- Như vậy thì tôi đã xây dựng được một trang web của mình với những tính năng như tôi đã nêu trên : đăng ký,đăng nhập,up load,...Nếu bạn muốn xem web tôi hoạt động như thế nào thì hãy liên hệ với tôi chứ tôi lười trình bày tiếp ....END 
