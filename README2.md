# BÀI TẬP TỔNG HỢP: STUDENT MANAGEMENT SYSTEM (UI/UX)

## Thông tin cá nhân
- **Tên môn học:** Phát triển ứng dụng Desktop / C# Windows Forms
- **Họ và tên:** [Điền Họ và Tên của bạn]
- **Mã số sinh viên (MSSV):** [Điền MSSV của bạn]
- **Lớp:** [Điền Tên Lớp của bạn]

## Mô tả Project
Hệ thống Quản lý Sinh viên ứng dụng nguyên tắc thiết kế UI/UX theo tiêu chuẩn Bài 2.9 (tối ưu luồng nhìn Z-pattern, phân cụm chức năng rõ ràng, phối màu chuẩn dưới 3 màu chính). Dự án áp dụng quy trình quản lý mã nguồn **Feature Branch Workflow** với Git/GitHub.

## Danh sách Control & Cấu hình UI (Bài 2.9)
1. **Container Controls:** 
   - `Panel` (`pnlHeader`): Header tiêu đề (Màu chủ đạo Navy Blue `#003366`).
   - `GroupBox`: Phân vùng `Thông tin sinh viên`, `Tìm kiếm`, `Thao tác` và `Danh sách sinh viên`.
2. **Input Controls:** 
   - `TextBox`: `txtStudentId` (MSSV), `txtFullName` (Họ tên), `txtEmail` (Email), `txtSearch` (Từ khóa).
   - `DateTimePicker`: `dtpBirthDate` (Ngày sinh - `dd/MM/yyyy`).
   - `RadioButton`: `rdoMale`, `rdoFemale` (Giới tính Nam/Nữ).
   - `ComboBox`: `cboFaculty` (Khoa - `DropDownStyle = DropDownList`).
3. **Action Controls (8 Buttons):** 
   - `btnAdd` (Thêm), `btnEdit` (Sửa), `btnDelete` (Xóa), `btnSave` (Lưu), `btnCancel` (Hủy), `btnRefresh` (Làm mới), `btnExit` (Thoát), `btnSearch` (Tìm kiếm).
4. **Display & Status Controls:** 
   - `DataGridView` (`dgvStudents`): `Dock = Fill`, `ReadOnly = True`, `SelectionMode = FullRowSelect` chứa 6 cột thuộc tính.
   - `StatusStrip` (`statusStrip1`): Thanh trạng thái hiển thị thông tin hệ thống.