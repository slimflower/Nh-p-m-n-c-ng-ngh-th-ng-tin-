# Mô hình mạng là gì ?
- `Mô hình mạng máy tính` là hệ thống kết nối nhiều máy tính với nhau thông qua một đường truyền vật lý và được xây dựng trên một kiến trúc mạng cụ thể.
- Mục đích của việc xây dựng mô hình mạng máy tính nhằm thu thập, trao đổi dữ liệu và chia sẻ tài nguyên cho nhiều máy tính trong 1 hệ thống cùng sử dụng. 
## Cấu tạo của mô hình máy tính 
- Gồm 3 thành phần chính:
    - **Máy trạm (Client)**: Không cung cấp tài nguyên, sử dụng tài nguyên từ mạng.
    - **Máy chủ (Server)**: Cung cấp tài nguyên và các dịch vụ cho các máy trên mạng.
    - **Peer**: Sử dụng tài nguyên và đồng thời cũng cung cấp tài nguyên cho mạng.
### Ưu điểm của mô hình mạng máy tính
- Ưu điểm của các mô hình mạng bao gồm:
  - Cho phép các máy tính trong hệ thống có thể sử dụng chung các công cụ tiện ích.
  - Chia sẻ kho dữ liệu dùng chung dựa trên sự phân cấp thẩm quyền.
  - Cải thiện độ tin cậy của hệ thống.
  - Trao đổi thông điệp, hình ảnh nhanh chóng, không cần bất kỳ thiết bi trao đổi ngoại vi nào.
  - Khả năng chia sẻ quyền sử dụng các thiết bị ngoại vi (máy in, máy vẽ, Fax, modem …)
  - Giảm thiểu chi phí và thời gian đi lại với khả năng truy cập từ xa không gián đoạn.
### Các dạng kiến trúc mạng thông dụng hiện nay
-  **LAN (Local Area Network)**:là kiến trúc mạng nội bộ được sử dụng để kết nối các thiết bị trong cùng một bộ phận, doanh nghiệp,... Mạng Lan là mạng khép kín, nhằm mục đích giao tiếp và chia sẻ dữ liệu nội bộ mà không công khai ra bên ngoài.
-  **WAN (Wide Area Network)**:là mạng diện rộng nhằm kết nối giữa các mạng đô thị, các tòa nhà, công ty, … cách xa nhau về phạm vi địa lý. Kiến trúc mạng này sẽ yêu cầu nhà cung cấp dịch vụ trung gian (Service Provider).
- **MAN (Metropolitan Area Network)**:còn gọi là kiến trúc mạng đô thị kết nối các chi nhánh Office trong đô thị hay thành phố lại với nhau, tốc độ của mạng MAN khá cao do sử dụng các công nghệ hiện đại như Ethernet, Fast Ethernet, Giga Ethernet, …)
- **PAN (Personal Area Network)**: là kiến trúc mạng mạng cá nhân không dây dùng sóng vô tuyến trong tầm phạm vi ngắn khoảng 10m. Mạng PAN chỉ kết nối được giữa hai thiết bị trong một phạm vi hẹp như các thiết bị không dây như Chuột,loa đài, bàn phím, tai nghe, máy chơi Game, điều khiển smart tivi,…
- **CAN (Campus Area Network)**:là kiến trúc mạng đặc biệt được tạo thành từ sự kết nối giữa các mạng cục bộ trong một khu vực địa lý cụ thể.Tốc độ truyền dữ liệu giữa các hệ thống sử dụng kiến trúc giao tiếp CAN thường nhanh hơn so với Internet.
### Các mô hình mạng máy tính được sử dụng phổ biến nhất hiện nay
- **Mô hình mạng máy tính Peer-to-Peer ( Mạng ngang hàng)**:hay còn được gọi là mạng hàng ngang hoặc P2P, là một dạng mô hình mạng trong đó toàn bộ các thiết bị máy tính đều có vai trò và quyền tương đồng nhau. Mỗi thiết bị có thể cung cấp trực tiếp tài nguyên cho các thiết bị khác trên cùng hệ thống.
- **Mô hình mạng Client - Server ( Mô hình khách chủ)**:Client - Server hay mô hình Khách - Chủ sẽ có sự phân cấp rõ ràng hơn so với mô hình mạng ngang hàng. Trong mô hình này thì 1 hoặc 2 máy tính được lựa chọn để trở thành Máy chủ Server.
- **Mô hình mạng lai (Hybrid)**:Phần lớn các mạng máy tính trên thực tế hiện nay đều sử dụng mô hình này. Đây là sự kết hợp giữa Client-Server và Peer-to-Peer. Mô hình mạng lai giúp đảm bảo chất lượng.
- **Mô Hình Mạng Star (Star topology)** :Mô hình mạng sao là mô hình mạng đơn giản,các thiết bị máy tính được kết nối thông qua một bộ kết nối tập trung như Hub hoặc Switch.
- **Mô hình mạng hình tuyến (Bus Topology)**:Đường truyền chính sẽ có nhiệm vụ kết nối qua 2 đầu nối có tên là Terminator. Mỗi trạm sẽ được kết nối trực tiếp vào trục chính thông qua đầu nối chữ T hoặc các thiết bị thu phát.
- **Mô Hình Mạng Full Mesh**: Mô hình mạng Full Mesh được xây dựng với mỗi thiết bị kết nối với tất cả các thiết bị khác trong mạng. Mô hình này đảm bảo rằng mạng luôn sẵn sàng và có tính dự phòng cao nhất
- **Mô Hình Mạng Partial Mesh**: Mô hình Partial Mesh là mô hình hỗn hợp của mô hình Mesh. Điểm khác biệt với mô hình Full Mesh chính là một điểm kết nối đến tất cả các điểm khác, trong khi các điểm còn lại chỉ kết nối tới một vài điểm lân cận tùy thuộc vào thiết kế.

`Các lý thuyết trên là bổ sung kiến thức mở rộng cho mô hình mạng nội bộ`
# Mô Hình Mạng Nội Bộ
## Hệ thống mạng nội bộ là gì?
- Mạng nội bộ với các tên gọi khác như mạng LAN (viết tắt của từ **Local Area Network**) hay mạng cục bộ.
- Mạng nội bộ là hệ thống mạng để kết nối các máy tính, thiết bị trong một phạm vi hẹp thường không quá 100m (nhà ở, phòng học, văn phòng,…). Các thiết bị được kết nối trong cùng một mạng nội bộ có thể chia sẻ dữ liệu, sử dụng chung tài nguyên, truyền lệnh đến các thiết bị ngoại vi như máy in, máy scan, máy fax,…

<img width="802" alt="Ảnh màn hình 2024-12-10 lúc 16 20 11" src="https://github.com/user-attachments/assets/8772ce4c-796e-43f3-bc2f-f684c1dc252c">

## Cách kết nối trong mạng LAN nội bộ
- Để kết nối mạng cục bộ, người ta sử dụng 2 phương thức khác nhau là:
  - **Mạng dây Ethernet**: Các thiết bị được kết nối với nhau bằng dây cáp mạng. Nếu nhiều mạng LAN cần ghép nối thì sẽ tạo thành mạng WAN diện rộng. Để giao tiếp dễ dàng hơn thì các thiết bị sẽ cần kết nối đến một hoặc một vài thiết bị Router thu phát tín hiệu mạng. Ở cách kết nối này đòi hỏi thiết bị phải có cổng RJ45 hoặc cổng mạng LAN (thường là máy tính bàn, laptop).
  - **Mạng LAN không dây**: Sử dụng công nghệ wifi để kết nối các thiết bị trong nội bộ. Ưu điểm của cách kết nối này là các thiết bị chỉ cần tích hợp card mạng là có thể sử dụng. Bao gồm cả các thiết bị điện tử thông minh như: điện thoại di động, máy tính bảng. Hơn thế nữa, về mặt thẩm mỹ của mạng không dây sẽ có phần vượt trội hơn. Tuy nhiên về mức độ ổn định thì không được đánh giá cao như mạng dây.
## Các sơ đồ hệ thống mạng nội bộ cơ bản
### Mạng LAN cơ bản sẽ bao gồm các loại thiết bị sau đây:
- Thiết bị làm máy chủ hay còn gọi là server mạng nội bộ (có một số hệ thống mạng LAN không cần máy chủ, các máy có quyền ngang nhau). Máy chủ có chức năng để quản lý, kiểm soát và phân quyền truy cập cho các máy khách.
- Các thiết bị hỗ trợ kết nối như: Router, modem, switch mạng nội bộ,…
- Hệ thống máy khách, thiết bị kết nối trong mạng. Ở đây, các thiết bị phải đảm bảo đã được tích hợp card mạng NIC (Network Interface Card). Thường thì card mạng đã được lắp đặt sẵn trong laptop nhưng nếu là máy tính để bàn nếu muốn kết nối mạng không dây wifi thì sẽ phải bổ sung thêm bên ngoài.
### Setup mạng nội bộ thì có 3 mô hình mạng cơ bản 
- **Mạng hình vòng**: Thiết bị bố trí theo hình vòng và chỉ có thể truyền tín hiệu một chiều.
- **Mạng hình sao**: Lấy máy chủ làm trung tâm và quản lý hoạt động các máy khách xung quanh. Nếu một máy khách hỏng thì không ảnh hưởng đến hệ thống. Nhưng nếu máy chủ gặp trục trặc thì toàn bộ hoạt động sẽ bị dừng lại.
- **Mạng định tuyến**: Các thiết bị được ghép nối ngang hàng trên một trục cáp chính và bịt 2 đầu bằng thiết bị terminator.

<img width="790" alt="Ảnh màn hình 2024-12-10 lúc 16 26 53" src="https://github.com/user-attachments/assets/8197823e-5d2d-47d7-95b5-9a61c97ab135">

`Trên đây là lý thuyết về mạng nội bộ`

