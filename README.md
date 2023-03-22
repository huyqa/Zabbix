# Zabbix
Zabbix là gì? Zabbix là một công cụ mã nguồn mở nổi tiếng giải quyết cho ta các vấn đề về giám sát – là phần mềm sử dụng các tham số của một mạng, tình trạng và tính toàn vẹn của Server cũng như các thiết bị mạng.

Zabbix sử dụng một cơ chế thống báo linh hoạt và khả năng tuỳ biến cao cho phép người dùng cấu hình email hoặc sms để cảnh báo dựa trên sự kiện được ta thiết lập sẵn. Ngoài ra Zabbix cung cấp báo cáo và dữ liệu chính xác dựa trên cơ sở dữ liệu. Điều này khiến cho Zabbix trở nên lý tưởng hơn, thích hợp phục vụ cho hệ thống mạng tầm trung và lớn của các doanh nghiệp hiện tại với mức chi phí đầu tư vừa phải.
Zabbix được sáng lập bởi Alexei Vladishev và hiện tại được phát triển cũng như hỗ trợ bởi tổ chức Zabbix SIA. Zabbix được viết và phát hành dưới bản quyền General Public License GPL phiên bản 2

Tất cả báo cáo, thống kê cũng như cấu hình thông số của Zabbix có thể dễ dàng truy cập qua giao diện web tinh tế đẹp mắt. Giúp chúng ta theo dõi được tình trạng hệ thống thiết bị server, dịch vụ,..
# 2. Ưu/nhược điểm của Zabbix là gì. 
# 2.1 Ưu điểm.
## Ưu điểm của Zabbix là gì mà được đánh giá là mã nguồn mở được đánh giá cao? Bởi vì có các ưu điểm sau mà bạn không nên bỏ qua:
Giám sát, tự động tìm phát hiện server và hệ thống mạng.

Hỗ trợ server cài đặt trên dòng hệ điều hành Unix/Linux.

Hỗ trợ máy trạm client nhiều hệ điều hành.

Giao diện web cực kì tinh tế và đẹp mắt.

Thông báo sự cố qua email, OTP App và SMS.

Mã nguồn mở, chi phí đầu tư thấp.

Biểu đổ theo dõi và báo cáo qua giao diện.

Kiểm soát theo dõi việc đăng nhập.

Linh hoạt trongphân quyền người dùng.

Nhiều Plugin hỗ trợ.

## 2.1 Nhược điểm.

Không có giao diện web mobile hỗ trợ.

Không phù hợp với hệ thống mạng lớn, nhiều thiết bị client cần giám sát. 

Lúc này phát sinh vấn đề hiệu suất về PHP và Database, v..v..

Thiết kế template/alerting rule đôi khi khá phức tạp.

# 3. Các thành phần của hệ thống giám sát dịch vụ Zabbix.

Zabbix Server: Đây là ứng dụng chương trình dịch vụ chính của dịch vụ Zabbix. Zabbix Server sẽ chịu trách nhiệm cho các hoạt động kiểm tra dịch vụ mạng từ xa, thu thập thông tin, lưu trữ, hiển thị, cảnh báo,… từ đó các quản trị viên có thể thao tác giám sát hệ thống tốt nhất.

Zabbix Proxy: là một máy chủ được dùng cho việc quản lý nhiều nhánh hệ thống ở xa, hoặc ở các lớp mạng khác nhau. Từ Zabbix Proxy sẽ thu thập các thông tin thiết bị mạng rồi chuyển tiếp về cho máy chủ dịch vụ chính Zabbix Server.

Zabbix Agent: để giám sát chủ động các thiết bị cục bộ và các ứng dụng (ổ cứng, bộ nhớ, …) trên hệ thống mạng. Zabbix Agent sẽ được cài lên trên Server và từ đó Agent sẽ thu thập thông tin hoạt động từ Server mà nó đang chạy và báo cáo dữ liệu này đến Zabbix Server để xử lý.

Giao diện web: cung cấp giao diện web trên nền tảng mã nguồn PHP cùng phong cách metro tinh tế. Hiện tại có thể xem Zabbix là một trong những ứng dụng có giao diện đẹp nhất, thiết kế vị trí tính năng bắt mắt và hợp lý.

Như vậy bạn đã hiểu thêm về Zabbix là gì? Chúc bạn thành công có thể tham khảo thêm bài viết liên quan đến System tại đây

#https://huyqa-home.com
