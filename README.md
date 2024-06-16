# QUY ĐỊNH THỰC HIỆN ĐỒ ÁN
## MÔN LẬP TRÌNH PYTHON

### 1. Mô tả Yêu Cầu
Sinh viên sẽ phát triển một ứng dụng hoàn chỉnh sử dụng ngôn ngữ lập trình Python và thư viện `tkinter` để tạo giao diện người dùng. Ứng dụng sẽ là một hệ thống quản lý thông tin với các chức năng CRUD (Create, Read, Update, Delete), sử dụng file JSON để lưu trữ dữ liệu thay vì sử dụng cơ sở dữ liệu.

### 2. Chi Tiết Yêu Cầu
#### Giao Diện Người Dùng (GUI)
- Ứng dụng cần có giao diện người dùng sử dụng thư viện `tkinter`, với giao diện dễ sử dụng và thân thiện với người dùng.
- Giao diện cần phản ánh các chức năng CRUD một cách rõ ràng và dễ hiểu.

#### Chức Năng CRUD
- **Create (Tạo mới)**: Cho phép người dùng thêm mới dữ liệu vào ứng dụng.
- **Read (Đọc dữ liệu)**: Hiển thị dữ liệu từ file JSON trên giao diện người dùng để người dùng xem.
- **Update (Cập nhật)**: Cho phép người dùng chỉnh sửa thông tin của các mục đã có trong dữ liệu.
- **Delete (Xóa)**: Cho phép người dùng xóa các mục không cần thiết từ dữ liệu.

#### Đọc Ghi File JSON
- Thay vì sử dụng cơ sở dữ liệu, ứng dụng sẽ sử dụng file JSON để lưu trữ và quản lý dữ liệu.
- Cần có các hàm để đọc và ghi dữ liệu từ/ra file JSON một cách an toàn và hiệu quả.

#### Crawl Dữ Liệu hoặc Get API
- Sinh viên cần sử dụng một trong các thư viện phù hợp để crawl dữ liệu từ website hoặc sử dụng API để lấy dữ liệu từ nguồn bên ngoài.
- Dữ liệu thu được cần được xử lý và lưu trữ vào file JSON để sử dụng trong ứng dụng.

#### Tạo User và Phân Quyền
- Ứng dụng cần có chức năng tạo tài khoản người dùng và phân quyền đơn giản.
- Cần có ít nhất hai loại người dùng: người dùng thông thường và người quản trị.
- Người quản trị có quyền truy cập và thực hiện tất cả các chức năng, trong khi người dùng thông thường có giới hạn trong số các chức năng.

#### Đóng gói ứng dụng
- Đóng gói thành file cài đặt hoặc thực thi được để dễ phân phối cho người dùng.

### 3. Thang Điểm - Phần app
- Giao Diện Người Dùng (GUI): 2 điểm
- Chức Năng CRUD: 3 điểm
- Đọc Ghi File JSON: 2 điểm
- Crawl Dữ Liệu hoặc Get API: 1 điểm
- Tạo User và Phân Quyền: 1 điểm
- Đóng gói ứng dụng: 1 điểm

### 4. Hình thức báo cáo
- Thời gian nộp bài: Trước Buổi 14 (Theo dõi trên Classroom)
- Báo cáo: Bằng ppt và Demo app. Báo cáo vào buổi 15.
- Sinh viên nộp bài trên Classroom bao gồm: Source Code (Bao gồm các file json), File word báo cáo và File ppt báo cáo.

### Lưu Ý
- Sinh viên cần lập trình theo hướng đối tượng.
- Sinh viên cần bổ sung hướng dẫn sử dụng và hướng dẫn cài đặt để người dùng có thể sử dụng ứng dụng một cách dễ dàng.
- Sinh viên cần thực hiện kiểm thử và debug kỹ lưỡng để đảm bảo ứng dụng hoạt động một cách ổn định và mượt mà.
