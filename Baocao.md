# Tìm hiểu:
### Docker
Docker là một nền tảng mạnh mẽ giúp đơn giản hóa quá trình xây dựng, chia sẻ, chạy và xác minh ứng dụng bằng **containters**
#### 1. Docker là gì?
- Docker cho phép nhà phát triển tạo **image** chứa ứng dụng cùng với các phụ thuộc (dependencies), thư viện (library), môi trường chạy (runtime environment).
- Những **image** này sau đó được sử dụng để tạo **containers**, đây là các môi trường cô lập nhẹ, nơi ứng dụng có thể chạy một cách nhất quán trên các hệ thống khác nhau.
- Với Docker, ta có thể tránh rắc rối về cấu hình và quản lý môi trường, giúp quá trình phát triển và triển khai trở nên suôn sẻ hơn.
#### 2. Lợi ích chính
- **Tốc độ** (Speed): Docker tăng tốc quá trình phát triển ứng dụng bằng cách cung cấp quy trình làm việc mượt mà.
- **Tính dễ ứng dụng** (Portability): Ứng dụng được đóng gói dưới dạng Docker containers có thể chạy ở bất kỳ đâu, từ máy tính cá nhân đến dịch vụ đám mây như AWS, Azure, Google Cloud... Câu thần chú là "Build once, run anywhere".
- **Tính nhất quán** (Consistency): Containers đảm bảo hành vi nhất quán trên các môi trường khác nhau.
- **Tính tích hợp** (Integration): Docker hoạt động mượt mà với các công cụ phát triển phổ biến như VS Code, CircleCI, Github...
### docker-composer
**Docker Compose** là một công cụ dùng để định nghĩa và chạy các chương trình Docker sử dụng nhiều **container** (multi-container). Với Compose, ta sử dụng file YAML để cấu hình các dịch vụ cho ứng dụng. Sau đó, ta sử dụng các lệnh để tạo và chạy từ những cấu hình đó một cách đơn giản và hiệu quả.
### Linux
Linux là một họ các hệ điều hành tự do mã nguồn mở dựa trên **Linux kernel**, một hạt nhân hệ điều hành được phát hành lần đầu tiên vào ngày 17 tháng 9 năm 1991 bởi **Linus Torvalds**. Một số điểm chính về Linux:
- **Tính miễn phí và mã nguồn mở**: Linux là một hệ điều hành miễn phí và mọi người đều có quyền sử dụng, tùy chỉnh và phân phối lại nó. Hệ điều hành này được phát triển bởi cộng đồng và có nhiều phiên bản phân phối khác nhau.
- **Thành phần**:
  + *Bootloader*: Phần mềm quản lý quá trình khởi động máy tính.
  + *Kernel*: Kernel là phần cốt lõi của hệ thống và quản lý CPU, bộ nhớ và các thiết bị ngoại vi. Kernel là cấp độ thấp nhất của hệ điều hành.
  + *Init system*: Đây là một hệ thống con khởi động lại không gian người dùng và chịu trách nhiệm kiểm soát các daemon.
  + *Daemons*: Đây là các dịch vụ nền (printing, sound, scheduling, etc.) khởi động trong khi hoặc sau khi đăng nhập vào màn hình.
  + *Graphical server*: Đây là hệ thống phụ hiển thị đồ họa trên màn hình máy tính.
  + *Desktop environment*: Đây là phần mà người dùng thực sự tương tác. Có nhiều desktop environment có thể lựa chọn như GNOME, Cinnamon, Mate, etc.
  + *Applications*
- **Các bản phân phối Linux**: Linux thường được đóng gói thành các bản phân phối (distributions) khác nhau. Mỗi bản phân phối có các thành phần, giao diện người dùng và mục đích sử dụng khác nhau. Một số bản phân phối phổ biến như Ubuntu, Debian, Fedora, CentOS...
### Unix
- Unix là một hệ điều hành máy tính được phát triển lần đầu vào những năm 1960 bởi Bell Labs. Nó được sử dụng rộng rãi trong các máy chủ, máy tính cao cấp và các thiết bị mạng. Unix có thể chạy trên nhiều loại hệ thống máy tính khác nhau và cung cấp môi trường lập trình thuận tiện và tính linh hoạt cao. Đây là một hệ điều hành mã nguồn mở và có nhiều phiên bản khác nhau, bao gồm Linux, macOS và Solaris.
- Unix được xây dựng từ nhiều thành phần khác nhau như hệ thống tệp phân cấp, CLI và các chương trình tiện ích.
- Trước năm 1973, Unix được viết bằng ngôn ngữ bậc thấp và đến phiên bản thứ 4 được viết bằng ngôn ngữ C, tăng tính linh hoạt trên nhiều nền tảng máy tính.
- Unix gồm nhiều yếu tố quan trọng như kernel, shell, hệ thống tệp, tiện ích và các chương trình cốt lõi.
- Hệ điều hành này đã trở thành một nền tảng quan trọng cho các hệ điều hành máy tính và các thiết bị mạng, đặc biệt là Linux, một hệ điều hành mã nguồn mở dựa trên Unix. Ngoài ra, có rất nhiều phiên bản của Unix được sử dụng trong các môi trường khác nhau, bao gồm macOS và Solaris.
### BSD
- BSD (Berkeley Software Distribution) là một hệ điều hành dựa trên Unix ban đầu được phát triển tại Đại học California, Berkeley. Ban đầu, BSD là một bản sửa đổi của hệ điều hành Unix của Bell Labs, với mục đích cung cấp những cải tiến và bổ sung cho Unix.
Một số điểm quan trọng về BSD:
- BSD license cho phép tự do sử dụng, tái phân phối và sửa đổi mã nguồn mà không yêu cầu công bố mã nguồn mới như **GPL (General Public License)**. Với BSD license, người dùng có quyền mua lại, chỉnh sửa và sử dụng mã nguồn một cách tự do mà không cần phải chia sẻ các sửa đổi của họ.
- BSD có một cộng đồng phát triển mạnh mẽ và ổn định, cung cấp hỗ trợ và khả năng thích ứng cho các dự án sử dụng BSD. Cộng đồng BSD đã đóng góp vào việc phát triển và duy trì các yếu tố cơ bản của BSD, giúp nâng cao tính ổn định và của nền tảng phần mềm này.
***Trả lời câu hỏi MacOS thuộc hệ điều hành nào, câu trả lời là Unix***
### Alpine
Alpine Linux là một bản phân phối Linux hướng đến sự tối giản, cả về không gian và phạm vi, cũng như tính bảo mật cao hơn.
Một số đặc điểm của Alpine:
- **Kích thước nhỏ và tối ưu hóa tài nguyên**: Alpine Linux có kích thước nhỏ, chỉ khoảng 133 MB. Sử dụng BusyBox để cung cấp hầu hết các tiện ích trong một tệp thực thi.
- **Bảo mật**: Alpine Linux sử dụng kỹ thuật tệp thực thi độc lập với vị trí (position-independent executables) để ngẫu nhiên hóa vị trí của các chương trình trong bộ nhớ, tăng tính bảo mật. Cấu hình tối giản giúp giảm khả năng tấn công.
- **Phù hợp cho Docker và container**: Kích thước nhỏ của Alpine Linux khiến nó phù hợp cho người dùng container, đặc biệt là Docker.
### Ubuntu
Ubuntu là một hệ điều hành máy tính dựa trên Debian GNU/Linux, một bản phân phối Linux thông dụng.
Mục đích của Ubuntu bao gồm việc cung cấp một hệ điều hành ổn định, cập nhật cho người dùng thường, và tập trung vào sự tiện dụng và dễ dàng cài đặt. Ubuntu đã được đánh xếp là bản phân phối Linux thông dụng nhất cho máy tính để bàn, chiếm khoảng 30% số bản Linux được cài đặt trên máy tính để bàn năm 2007.
Ubuntu là phần mềm mã nguồn mở tự do, có nghĩa là người dùng được tự do chạy, sao chép, phân phối, nghiên cứu, thay đổi và cải tiến phần mềm theo điều khoản của giấy phép GNU GPL.
Ubuntu sử dụng công cụ quản lý gói Advanced Package Tool (APT), cung cấp kho lưu trữ lớn với các gói đã được biên dịch sẵn.
Ubuntu có cộng đồng lớn và tích cực, với tài liệu phong phú và hỗ trợ từ cộng đồng.
### VNC
VNC (Virtual Network Computing) là một giao thức cho phép bạn từ xa xem và điều khiển máy tính khác qua mạng.
Dưới đây là một số điểm quan trọng về VNC:
#### 1. VNC Viewer
- VNC Viewer là phần mềm cho phép kiểm soát các máy tính đã kích hoạt VNC từ xa.
- Ta có thể cài đặt VNC Viewer miễn phí trên nhiều thiết bị, hệ điều hành.
#### 2. VNC Server
- VNC Server cho phép ta kiểm soát các thiết bị của mình từ bất kỳ đâu.
- Ta có thể cài đặt VNC Server miễn phí trên nhiều thiết bị, hệ điều hành.
#### 3. Tích hợp VNC Viewer và VNC Server
- VNC Viewer và VNC Server được thiết kế để hoạt động tốt cùng nhau.
- Sử dụng cả hai để trải nghiệm tính bảo mật cao hơn, kết nối đáng tin cậy và truy cập các tính năng độc quyền trong VNC Connect.
