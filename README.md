##Mạng căn bản  
###1.Mạng là gì?  
- Là hệ thống gồm 2 hay nhiều máy tính liên kết để chia sẻ tài nguyên.  
- Được kết nối qua dây cáp,sống hồng ngoại ,vệ tinh.    
- Gồm 2 loại cơ bản:  
  - Local Area Network(còn được viết tẳ là LAN)    
  - Wide Area Network(còn được viết tắt là Wan)  
  
###2.Thành phần?  
- Mối liên kết:là phương tiện để chuyển dữ liệu từ điểm này đến điểm khác trong một mạng, bao gồm:  
  - Giao diện mạng: định dạng dữ liệu để truyền.  
  - Phương tiện tuyền thông mạng: những phương tiện truyền thông giúp tin hiệu được truyền đi.  
  - Bộ liên kết: cung cấp các điểm liên kết các phương tiện truyền thông.  
- Thiết bị chuyển mạch:các hệ thống đầu cuối thường được kết nối với  thiết bị chuyển mạch.  
- Routers:kết nối các mạng khác nhau và hỗ trợ lựa chọn con đường tốt nhất để truyền dữ liệu giữa hai mạng.  
- WLAN: Wireless LAN of WAN devices conected network devices.  

###3.Nguồn chia sẽ và lợi ích?  
- Dữ liệu và ứng dụng:chia sẻ tập tin, phần mềm và chương trình ứng dụng.  
- Nguồn:các thiết bị đầu vào và thiết bị đầu ra.    
- Lưu trữ mạng: lưu trữ gắn trực tiếp (DAS), mạng lưu trữ đính kèm (NAS), mạng lưu trữ (SAN).  
- Các thiết bị sao lưu: cung cấp phương tiện trung tâm để lưu các tập tin từ nhiều máy tính, có khả năng lưu trữ và khắc phục sự cố .  

###4.Ứng dụng mạng?  
- Trình duyệt wed(chrome,cốc cốc,...)  
- Ứng dụng làm việc tập thể  
- E mail( gamil,yahoo,...)  
- Chat( facebook,zalo,viber,...)  
- ...   

###5.Đặc tính?  
- Chi phí  
- Tính bảo mật  
- Tốc độ  
- Khả năng mở rộng  
- Độ tin cậy của đường truyền trong hệ thống mạng.  
- ...  


---  


##OSI-TCP//IP  
###1.OSI  
**Mô hình**  
![img](http://1.bp.blogspot.com/-dEPOLAvxsek/UzQcvDS44KI/AAAAAAAAACw/c_Fxrkuul7k/s1600/Osi-model-jb.png)  
**Trong mô hình phân lớp:**  
- *Lớp 1 Physical (lớp vật lý):* truyền dòng bit thô qua đường truyền vật lý cụ thể. Nó định nghĩa các đặc tính kĩ thuật về điện, cơ, quang, đặc tính kỹ thuật trong việc thiết lập, giải phóng , duy trì một đường truyền nào đó.  
- *Lớp 2 Data Link:* điều khiển dữ liệu truy nhập vào đường truyền vật lý,giao tiếp vớilớp Network, cung cấp cơ chế dò lỗi.
- *Lớp 3 Network:* phân bố dữ liệu ( định tuyến các gói dữ liệu),xác định đường đi tối ưu nhất để phân phối dữ liệu,định địa chỉ logic cho hệ thống mạng( địa chỉ IP).  
- *Lớp 4 Transport:* quản lý các kết nối đầu cuối( end-to-end), xử lí vấn dề truyền dẫn giữa các host, đảm bảo dữ liệu truyền một cách tin cậy từ điểm này đến điểm khác trong mạng, thu hồi hoặc duy trì các kết nối ảo, cung cấp cơ chế dò lỗi, phục hồi dữ liệu.  
- *Lớp 5 Session:* thiết lập, quản lý và giải phóng các session giữa các ứng dụng ( tổ chức các phiên kết nối giữa các ứng dụng).  
- *Lớp 6 Presentation:* dảm bảo dữ liệu từ nơi guiẻ đến nơi nhận có thể đọc ddược, cung cấp cơ chế mã hóa.  
- *Lớp 7 Application:* giao tiếp trực tiếp với người dùng,cung cấp các ứng dụng mạng,cung cấp cơ chế xác thực người dùng.  

###2.TCP// IP  
**Mô hình**  
![img](http://2.bp.blogspot.com/-jH4TzAOcspU/UzQeMUZ1JlI/AAAAAAAAADA/cWNGZjCtkI4/s1600/TCP-IP-Model.png)  
**Trong mô hình phân lớp:**  
-* Lớp truy cập mạng:* Cung cấp giao diện tương tác với mạng vật lý. Format dữ liệu cho bộ phận truyền tải trung gian và tạo địa chỉ dữ liệu cho các tiểu mạng dựa trên địa chỉ phần cứng vật lý. Cung cấp việc kiểm tra lỗi trong quá trình truyền dữ liệu.  
- *Lớp Internet:* Cung cấp địa chỉ logic, độc lập với phần cứng, để dữ liệu có thể lướt qua các tiểu mạng có cấu trúc vật lý khác nhau. Cung cấp chức năng định tuyến để giao lưu lượng giao thông và hỗ trợ việc vận chuyển liên mạng. Thuật ngữ liên mạng được dùng để đề cập đến các mạng rộng lớn hơn, kết nối từ nhiều LAN. Tạo sự gắn kết giữa địa chỉ vật lý và địa chỉ logic.  
- *Lớp vận chuyển:* Giúp kiểm soát luồng dữ liệu, kiểm tra lỗi và xác nhận các dịch vụ cho liên mạng. Đóng vai trò giao diện cho các ứng dụng mạng.  
- *Lớp ứng dụng:* Cung cấp các ứng dụng để giải quyết sự cố mạng, vận chuyển file, điều khiển từ xa, và các hoạt động Internet. Đồng thời hỗ trợ Giao diện Lập trình Ứng dụng (API) mạng, cho phép các chương trình được thiết kế cho một hệ điều hành nào đó có thể truy cập mạng.  
