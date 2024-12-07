# QBT-PeopleOps
Quản lý nhân viên công ty QBT bằng ngôn ngữ C#
Dưới đây là **đề cương chi tiết** cho từng thành viên, **mô tả chức năng modules** và **layout draft** cho các chức năng cần quản lý trong hệ thống (bao gồm **chấm công**, **nhân sự**, và **đăng nhập**).
để biết thêm chi tiết vui lòng liên hệ zalo 0345510330

### **Thành viên 1: Quản lý Chấm Công và Phụ Cấp**
#### **Nhiệm vụ:**
- Quản lý các thông tin về thời gian làm việc của nhân viên.
- Cung cấp các công cụ để tính toán chấm công, tăng ca, phụ cấp và ứng trước lương.
  
#### **Chức năng Modules**:
1. **Chấm công**:
   - **Đăng ký chấm công**: Ghi lại thời gian vào làm, ra về của nhân viên.
   - **Xem và chỉnh sửa lịch làm việc**: Cho phép nhân viên hoặc quản lý chỉnh sửa giờ làm việc khi cần thiết.
   - **Tính công**: Tính tổng số giờ làm việc trong tháng, tính giờ làm thêm (tăng ca) nếu có.

2. **Tăng ca và phụ cấp**:
   - **Quản lý tăng ca**: Ghi nhận số giờ làm thêm và tính toán phụ cấp tăng ca.
   - **Phụ cấp**: Quản lý các loại phụ cấp khác nhau như phụ cấp xăng xe, ăn trưa, công tác phí.

3. **Ứng trước lương**:
   - **Chức năng ứng lương**: Cho phép nhân viên ứng trước một phần lương theo quy định công ty.
   - **Theo dõi ứng trước lương**: Quản lý các khoản ứng trước lương và tự động trừ vào lương tháng sau.

#### **Layout Draft**:
- **Trang Chấm Công**: Giao diện đăng nhập chấm công vào/ra, hiển thị lịch làm việc của nhân viên.
- **Trang Tăng Ca và Phụ Cấp**: Giao diện để nhân viên báo cáo tăng ca, yêu cầu phụ cấp, và xem thông tin về số giờ làm thêm.
- **Trang Ứng Trước Lương**: Cho phép nhân viên yêu cầu ứng lương, hiển thị các khoản ứng lương đã được duyệt.

---

### **Thành viên 2: Quản lý Nhân Sự và Hợp Đồng**
#### **Nhiệm vụ:**
- Quản lý thông tin nhân viên, hợp đồng lao động, các thông tin liên quan đến nhân sự của công ty.

#### **Chức năng Modules**:
1. **Nhân sự**:
   - **Thêm mới nhân viên**: Ghi nhận các thông tin cá nhân của nhân viên như tên, địa chỉ, số điện thoại, chức vụ, ngày vào làm.
   - **Quản lý thông tin nhân viên**: Chỉnh sửa và cập nhật thông tin của nhân viên khi có thay đổi.

2. **Quản lý hợp đồng**:
   - **Tạo và quản lý hợp đồng lao động**: Cung cấp chức năng tạo, theo dõi, và gia hạn hợp đồng lao động.
   - **Hợp đồng hết hạn**: Cảnh báo khi hợp đồng lao động của nhân viên sắp hết hạn.

#### **Layout Draft**:
- **Trang Quản lý Nhân Sự**: Hiển thị danh sách nhân viên, chức năng tìm kiếm và lọc theo tên, phòng ban, chức vụ, thêm, sửa xóa.
- **Trang Quản lý Hợp Đồng**: Hiển thị danh sách các hợp đồng lao động, cho phép tạo mới, chỉnh sửa, gia hạn và theo dõi hợp đồng hết hạn.

---

### **Thành viên 3: Quản lý Đăng Nhập và Tính Năng Sao Lưu, Phục Hồi**
#### **Nhiệm vụ:**
- Quản lý đăng nhập người dùng, đảm bảo an toàn bảo mật cho tài khoản.
- Cung cấp các tính năng sao lưu và phục hồi dữ liệu của hệ thống.

#### **Chức năng Modules**:
1. **Đăng nhập và Quản lý tài khoản**:
   - **Đăng nhập**: Cho phép người dùng đăng nhập với các quyền truy cập khác nhau (quản trị viên, nhân viên).
   - **Đăng ký và Đặt lại mật khẩu**: Cung cấp chức năng đăng ký tài khoản cho người dùng mới và chức năng đặt lại mật khẩu nếu người dùng quên.
   - **Phân quyền**: Quản lý quyền truy cập của người dùng, đảm bảo chỉ những người có quyền mới có thể truy cập vào các chức năng quan trọng.

2. **Sao lưu và phục hồi dữ liệu**:
   - **Sao lưu tự động**: Cung cấp tính năng sao lưu định kỳ dữ liệu hệ thống.
   - **Phục hồi dữ liệu**: Cho phép phục hồi dữ liệu từ bản sao lưu khi cần thiết.
   - **Lịch sử sao lưu**: Xem lại các bản sao lưu đã thực hiện và phục hồi từ các điểm thời gian cụ thể.

#### **Layout Draft**:
- **Trang Đăng Nhập**: Giao diện đơn giản, dễ sử dụng cho người dùng đăng nhập vào hệ thống với các lựa chọn đăng ký, đăng nhập lại hoặc đặt lại mật khẩu.
- **Trang Quản lý Tài Khoản**: Hiển thị danh sách các tài khoản người dùng, phân quyền và quyền truy cập.
- **Trang Sao Lưu và Phục Hồi**:
   - **Sao lưu dữ liệu**: Cho phép người dùng tạo bản sao lưu mới, lựa chọn tần suất sao lưu.
   - **Phục hồi dữ liệu**: Giao diện để người quản trị chọn bản sao lưu để phục hồi dữ liệu.
   - **Lịch sử sao lưu**: Hiển thị danh sách các bản sao lưu và các thông tin chi tiết về thời gian, dung lượng và trạng thái.

---

### **Tóm lại**:

- **Thành viên 1 (Chấm công và Phụ cấp)**: Quản lý thời gian làm việc của nhân viên, tính toán tăng ca và phụ cấp, xử lý yêu cầu ứng lương.
- **Thành viên 2 (Nhân sự và Hợp đồng)**: Quản lý thông tin nhân viên và hợp đồng lao động, bao gồm việc tạo mới, chỉnh sửa, và gia hạn hợp đồng.
- **Thành viên 3 (Đăng nhập và Sao lưu, phục hồi)**: Quản lý đăng nhập tài khoản, phân quyền truy cập và tính năng sao lưu, phục hồi dữ liệu.
