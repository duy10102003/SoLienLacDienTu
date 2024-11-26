# Student Management

Ứng dụng Sổ Liên Lạc Điện Tử.


## 2. Mục đích xây dựng ứng dụng

<details>
  <summary>Mục đích xây dựng ứng dụng</summary>

- Xây dựng một nền tảng tất cả trong một. Người quản trị, giáo viên, sinh viên có thể sử dụng công cụ để học tập trực tuyến, tra cứu kết quả học tập, đăng ký học phần, quản trị đào tạo, ...
- Nâng cao tính chính xác, bảo mật trong quản lý thông tin sinh viên.
- Thay thế các ứng dụng quản lý đã lỗi thời.
- Giao diện, luồng xử lý phù hợp hơn với nhu cầu của người sử dụng.
</details>

## 3. Yêu cầu chức năng chi tiết

<details>
  <summary>Quản lý lớp môn học</summary>

- Hiển thị thông tin lớp môn học: môn học, mã môn, sĩ số, giáo viên, thời khóa biểu, …
- Tìm kiếm các lớp môn học theo mã lớp, giáo viên giảng dạy.
- Thêm, sửa, xóa các lớp môn học.
- Hiển thị các lớp môn học theo quyền, theo học kỳ.
- Đi đến trang thông tin chi tiết của lớp môn học.

</details>

<details>
  <summary>Quản lý chi tiết lớp môn học</summary>
  
- Bảng tin lớp học
  - Thêm, sửa, xóa bài đăng.
  - Tạo thông báo khi đăng bài.
  - Đăng bài kèm hình ảnh.
  - Thêm, sửa, xóa bình luận của bài đăng.
  - Tạo thông báo khi bình luận bài đăng.
- Lịch học, báo nghỉ, báo bù
  - Xem lịch học, lịch nghỉ, lịch bù.
  - Thêm ngày nghỉ học, ngày học bù.
  - Xóa ngày nghỉ học, ngày học bù.
  - Tạo thông báo khi báo nghỉ, báo bù.
- Tài liệu lớp học:
  - Thêm, sửa, xóa thư mục.
  - Thêm, sửa, xóa tài liệu.
  - Tải tài liệu.
  - Tải toàn bộ tài liệu lớp học.
  - Tra cứu tài liệu lớp học.
- Danh sách sinh viên lớp học
  - Xem tổng quan, thống kê điểm số sinh viên trong lớp.
  - Xem thông tin sinh viên trong lớp.
  - Thêm sinh viên vào lớp.
  - Xóa sinh viên ra khỏi lớp.
  - Tra cứu sinh viên trong lớp.
  - Thêm, sửa, xóa điểm thành phần cho lớp học.
  - Thêm, sửa, xóa điểm cho sinh viên trong lớp.

</details>

<details>
  <summary>Quản lý khoa - hệ đào tạo</summary>

- Hiển thị thông tin, số lượng sinh viên ứng với từng khoa.
- Hiển thị thông tin, số lượng sinh viên ứng với từng hệ đào tạo.
- Thêm, sửa, xóa khoa.
- Thêm, sửa, xóa hệ đào tạo.
- Tìm kiếm khoa theo tên khoa hoặc theo tên hệ đào tạo mà khoa có.
- Thêm hệ đào tạo tương ứng với khoa.

</details>

<details>
  <summary>Quản lý môn học</summary>

- Hiển thị danh sách và thông tin các môn học : tên môn, mã môn, số tín chỉ, mô tả, …
- Tìm kiếm môn học theo mã môn, tên môn.
- Thêm, sửa, xóa môn học.
- Thêm môn học từ excel.

</details>

<details>
  <summary>Quản lý đăng ký học phần</summary>
  
- Quản trị viên
  - Thêm học kỳ và đóng mở học kỳ.
  - Thêm lớp môn học thủ công hoặc thêm từ file excel.
  - Xem chi tiết, sửa, xóa lớp môn học.
  - Tìm kiếm lớp môn học theo tên môn học, mã lớp học.
- Sinh viên
  - Đăng ký, hủy đăng ký lớp môn học.
  - Trực quan hóa các lớp môn học bằng thời khóa biểu.
  - Đánh dấu những lớp bị trùng giờ học.
  - Tìm kiếm lớp môn học chưa đăng ký theo tên môn học, mã lớp học.

</details>

<details>
  <summary>Quản lý thời khóa biểu</summary>
  
- Hiển thị danh sách các lớp môn học dưới dạng bảng thời khóa biểu.
- Hiển thị các lớp môn học theo quyền (giáo viên, sinh viên), theo học kỳ.

</details>

<details>
  <summary>Quản lý Thông báo</summary>
  
  - Quản trị viên:
    - Thêm, xóa, sửa, xem chi tiết thông báo thông báo.
    - Thêm thông báo nghỉ, thông báo bù
    - Tìm kiếm thông báo theo chủ đề, thời gian, loại thông báo

- Giáo viên:

  - Xem chi tiết thông báo thông báo. - Thêm thông báo nghỉ, thông báo bù
  - Tìm kiếm thông báo theo chủ đề, thời gian, loại thông báo

- Sinh viên:
  - Xem chi tiết thông báo thông báo.
  - Tìm kiếm thông báo theo chủ đề, thời gian, loại thông báo

</details>

<details>
  <summary>Quản lý Thông tin cá nhân</summary>

- Hiển thị thông tin cá nhân của người dùng
- Chỉnh sửa thông tin cá nhân theo quyền

</details>

<details>
  <summary>Quản lý cài đặt Thông tin cá nhân (Quản trị viên)</summary>

- HIển thị các trường thông tin cá nhân theo role
- Thêm, xóa , sửa, ẩn, xem các cài đặt của trường thông tin theo role

</details>

<details>
  <summary>Quản lý người dùng (Quản trị viên)</summary>

- Thiết lập, cung cấp tài khoản và mật khẩu cho người dùng (sinh viên, giáo viên, Quản trị viên).
- Thêm người dùng thủ công và từ file.
- Chỉnh sửa, cập nhật thông tin cho người dùng.
- Tìm kiếm thông tin người dùng.

</details>

<details>
  <summary>Quản lý điểm (sinh viên)</summary>

- Xem bảng điểm sinh viên.
- Xuất bảng điểm sinh viên (future work)

</details>



