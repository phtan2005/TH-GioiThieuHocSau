# Tuần 2: Bài Tập NumPy, Pandas, Matplotlib

Kho lưu trữ này chứa các giải pháp cho các bài tập (BTVN) của Tuần 2 trong khóa học Deep Learning, tập trung vào các kiến thức cơ bản về NumPy.

## Tổng Quan Bài Tập

### BTVN 1: Trò Chơi Tic-Tac-Toe
- **Mô tả**: Triển khai trò chơi Tic-Tac-Toe bằng NumPy.
- **Luật chơi**:
  - Bảng 3x3 được khởi tạo với 99 (trống).
  - X là 1, O là 0.
  - Người chơi luân phiên, X bắt đầu.
  - O không thể chơi tại (0,0).
  - Trò chơi kết thúc khi một người chơi có ba hàng liên tiếp (hàng, cột, đường chéo).
- **Triển khai**: Vòng lặp trò chơi tương tác với xác thực đầu vào và kiểm tra thắng.

### BTVN 2: Lập Chỉ Mục NumPy
- **Mô tả**: Cho mảng 3x3 `y = [[1,2,3], [4,5,6], [7,8,9]]`, thực hiện các thao tác lập chỉ mục cụ thể.
- **Nhiệm vụ**:
  - Trích xuất [4,5,6] (hàng thứ hai).
  - Trích xuất [2,5] (cột thứ hai).
  - Trích xuất các phần tử 3 và 4 (vị trí cụ thể).
  - Trích xuất [9,6,3] (cột thứ ba theo thứ tự ngược).

### BTVN 3: Lọc Số Chẵn
- **Mô tả**: Cho `x = [1,2,3,4,5,6,7,8,9,10]`, trích xuất các giá trị chẵn.
- **Nhiệm vụ**:
  - Sử dụng lập chỉ mục có điều kiện (tương đương if).
  - Sử dụng list comprehension (mặc dù trong ngữ cảnh NumPy, hiển thị với mảng).

### BTVN 4: Chia Dữ Liệu và Chuẩn Bị Cross-Validation
- **Mô tả**: Tạo mảng NumPy 150x5 với dữ liệu sinh viên (chiều cao, cân nặng, tuổi, lương, GPA).
- **Nhiệm vụ**:
  - Chia thành X (4 cột đầu) và y (cột cuối).
  - Chia thành train/test với 70% train.
  - Tạo 10 tập con không chồng chéo từ X_train cho cross-validation tiềm năng.

## Cách Chạy
- Mở notebook `numpy_pandas.ipynb` trong Jupyter hoặc VS Code.
- Chạy từng ô tương ứng với các bài tập BTVN.
- Đối với BTVN 1, tương tác qua đầu vào terminal.

## Phụ Thuộc
- NumPy
- (Môi trường notebook cho các phần tử tương tác)

## Ghi Chú
- Hạt giống ngẫu nhiên được đặt để tái tạo trong BTVN 4.
- Các bài tập minh họa các thao tác cơ bản của NumPy: tạo mảng, lập chỉ mục, cắt lát, lựa chọn có điều kiện và thao tác dữ liệu.