# 🌸 Ứng Dụng Bán Hoa Trực Tuyến

Đây là ứng dụng bán hoa được phát triển trong khuôn khổ môn học **Lập trình đa nền tảng**. Ứng dụng cho phép người dùng duyệt, đặt mua hoa, quản lý đơn hàng và thông tin cá nhân một cách thuận tiện trên thiết bị di động.

## 1.🚀 Tổng quan

### 🛍️ Tính năng chính (Dành cho người dùng)
- Xem danh sách hoa theo danh mục
- Sắp xếp hoa theo: liên quan, mới nhất, giá, đánh giá
- Tìm kiếm sản phẩm
- Thêm vào giỏ hàng, đặt hàng
- Nhận thông báo trạng thái đơn hàng
- Theo dõi đơn mua: đang giao, đã giao
- Quản lý địa chỉ giao hàng
- Cập nhật thông tin tài khoản

## 🚀 Công nghệ sử dụng

### ✅ Frontend
- **React Native (Expo)**: Framework phát triển ứng dụng di động đa nền tảng.
- **React Navigation**: Quản lý luồng điều hướng và chuyển màn hình trong ứng dụng.
- **Expo**: Hỗ trợ phát triển, build và debug ứng dụng React Native dễ dàng hơn.

### 🖥️ Backend
- **Node.js**: Môi trường thực thi JavaScript phía máy chủ.
- **Express.js**: Framework web nhẹ, hỗ trợ xây dựng REST API nhanh chóng.

### 🗄️ Cơ sở dữ liệu
- **MySQL**: Hệ quản trị cơ sở dữ liệu quan hệ, dùng để lưu trữ thông tin sản phẩm, người dùng và đơn hàng.

### 🖼️ Quản lý hình ảnh
- **Multer**: Middleware xử lý việc tải ảnh lên server, lưu trữ ảnh dạng URL để truy cập dễ dàng.

### 🔐 Xác thực người dùng
- **JWT (JSON Web Token)**: Cơ chế xác thực và phân quyền dựa trên token, bảo vệ các API quan trọng.

### 🛠️ Công cụ phát triển
- **Postman**: Công cụ kiểm thử và mô phỏng các request đến backend.
- **VS Code**: Trình soạn thảo mã nguồn hiện đại, mạnh mẽ.
  ## 🛍️ Tính năng chính

### 1. Hệ thống sản phẩm và danh mục
- **Xem danh sách hoa**: Hiển thị sản phẩm theo danh mục như hoa hồng, hoa cúc, hoa lan,...
- **Chi tiết sản phẩm**: Thông tin mô tả, giá tiền, đánh giá, ảnh minh họa.
- **Sắp xếp linh hoạt**: Theo giá tăng/giảm, đánh giá.
- **Tìm kiếm nâng cao**: Tìm sản phẩm bằng từ khóa tên hoa.

### 2. Giỏ hàng và đặt hàng
- **Thêm vào giỏ hàng**: Chọn số lượng sản phẩm và thêm vào giỏ.
- **Xem giỏ hàng**: Xem toàn bộ sản phẩm đã chọn, cập nhật số lượng hoặc xoá sản phẩm.
- **Đặt hàng**: Gửi yêu cầu mua hàng, hệ thống ghi nhận và xử lý đơn.

### 3. Theo dõi đơn hàng
- **Trạng thái đơn hàng**: Xem tiến trình: đang xử lý, đang giao, đã giao.
- **Thông báo đơn hàng**: Nhận thông báo tự động khi trạng thái đơn thay đổi.

### 4. Quản lý tài khoản người dùng
- **Đăng ký / Đăng nhập**: Sử dụng JWT để xác thực người dùng.
- **Cập nhật thông tin cá nhân**: Họ tên, email, số điện thoại,...
- **Quản lý địa chỉ giao hàng**: Thêm/sửa/xoá địa chỉ nhận hàng.
- **Ảnh đại diện**: Cho phép người dùng tải ảnh đại diện (upload bằng Multer, lưu URL).

### 5. Giao diện và trải nghiệm người dùng
- **Responsive UI**: Giao diện tương thích nhiều thiết bị khác nhau.
- **Điều hướng rõ ràng**: Sử dụng React Navigation để điều hướng giữa các màn hình.
- **Trạng thái tải & lỗi**: Hiển thị loading khi đang xử lý và thông báo lỗi thân thiện.
- **Tối ưu trải nghiệm**: Giao diện nhẹ, mượt, dễ sử dụng.

### 6. Hệ thống backend và bảo mật
- **REST API**: Thiết kế rõ ràng, dễ mở rộng.
- **Xác thực JWT**: Bảo vệ các endpoint quan trọng.
- **Upload ảnh**: Xử lý upload bằng Multer, lưu link ảnh trong database.
- **Mã hoá mật khẩu**: Bảo mật thông tin người dùng với Bcrypt.
- **Quản lý dữ liệu với MySQL**: Tổ chức bảng hoa, người dùng, đơn hàng, chi tiết đơn hàng.

## 📌 Kết luận

Ứng dụng Bán Hoa là một nền tảng thương mại điện tử đơn giản nhưng hiệu quả, hướng đến việc cung cấp trải nghiệm mua sắm hoa trực tuyến tiện lợi, nhanh chóng và thân thiện với người dùng. Với các tính năng như tìm kiếm, phân loại, giỏ hàng, đặt hàng và theo dõi đơn hàng, người dùng có thể dễ dàng lựa chọn và mua sản phẩm hoa yêu thích chỉ trong vài thao tác.

Giao diện người dùng được xây dựng rõ ràng, dễ sử dụng với các component tuỳ chỉnh riêng cho từng loại nội dung. Backend được thiết kế an toàn và hiệu quả với các công nghệ hiện đại như Node.js, Express, JWT và MySQL, đảm bảo bảo mật dữ liệu và hoạt động ổn định.

Dự án này là bước đầu để xây dựng một hệ thống bán hàng online có thể mở rộng và nâng cấp về sau, đồng thời giúp nhóm thành viên tiếp cận quy trình phát triển ứng dụng thực tế từ frontend đến backend.

## 👥 Tác giả (team DHCN)

- Ninh Thị Duyên  
- Nguyễn Mạnh Hùng
- Nguyễn Khánh Chi 
- Nguyễn Văn Nam

## 🙏 Lời cảm ơn

Chúng tôi xin gửi lời cảm ơn đến:

- Thầy giáo **Nguyễn Đình Quý** đã tận tình hướng dẫn trong suốt quá trình thực hiện đồ án.  
- Các **thư viện mã nguồn mở** đã cung cấp nền tảng kỹ thuật vững chắc để phát triển ứng dụng.  
- Cộng đồng **React Native**, **Node.js** và **Expo** với tài liệu và sự hỗ trợ quý giá.



  
