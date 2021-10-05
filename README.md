# Restfull-API
API là gì?
- Là một chương trình tương tác với database để lấy dữ liệu ra 
- Ví dụ :  https://api.instagram.com/oauth/authorize
  ?client_id={instagram-app-id}
  &redirect_uri={redirect-uri}
  &scope={scope}
  &response_type=code
  &state={state}   
- Client_id trả về chuỗi số ,ID ứng dụng trên Instagram hiển thị trong Bảng điều khiển ứng dụng > Sản phẩm > Instagram > Basic Display
- Redirect_uri trả về chuỗi "https://socialsizzle.herokuapp.com/auth/" . URI sẽ chuyển hướng người dùng đến đó sau khi họ cho phép hoặc từ chối yêu cầu cấp quyền
- Response_type trả về chuỗi "code" , đặt giá trị thành code
- Scope danh sách được phân tách bằng dấu phẩy hoặc khoảng trắng "user_profile,user_media".Danh sách được phân tách bằng dấu phẩy hoặc danh sách được phân tách bằng khoảng trắng mã hóa URL có các quyền cần yêu cầu từ người dùng ứng dụng
- State trả về chuỗi "1".Giá trị tùy chọn cho biết trạng thái cụ thể theo máy chủ.
REST API là gì?
- Là một tiêu chuẩn được sử dụng trong việc thiết kế API cho các ứng dụng web để tạo thuận tiện hơn cho việc quản lí các nguồn tài nguyên
- Get(select):Thực hiện việc trả lại dữ liệu là một resource 
- Post(create): Thực hiện tạo mới một resoure
- Put(Update): Thực hiện việc cập nhật thông tin cho resource
- Delete: Thực hiện việc xóa một resource
