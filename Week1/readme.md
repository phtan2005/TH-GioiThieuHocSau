Giải thích nội dung và các bài tập
Code sử dụng thư viện torch , numpy , pandas và matplotlib

BTVN 1
- Tạo một tensor vô hướng x có giá trị là 2.0
- Tạo ra một đồ thị tính toán
- Thực hiện lan truyền ngược
BTVN 2
- Tạo một tensor ban đầu có giá trị là 2
- Learning rate và số vòng lặp
- Định nghĩa hàm
- Tính gradient
- Lưu kết quả
- Cập nhật x 
- Reset gradient
- Tạo bảng kết quả
BTVN 3 
- Tạo dữ liệu
- Khởi tạo tham số
- Dự đoán
- MSE Loss
- Tính gradient
- Lưu kết quả
- Cập nhật Gradient Descent
- Reset gradient
BTVN 4
- Trường hợp 1 :
    x chia sẻ chung bộ nhớ với arr
    Khi bạn thay đổi arr, thì x thay đổi theo
    Không copy dữ liệu chỉ tạo view và numpy array
- Trường hợp 2 :
    x không thay đổi
    x và arr không chung bộ nhớ
    Copy dữ liệu sang vùng mới
BTVN 5
- torch.empty() : Cấp phát bộ nhớ nhưng không gán giá trị ban đầu , Giá trị bên trong là rác trong bộ nhớ
- torch.zeros() : Tạo tensor toàn số 0
- torch.rand() : Tạo tensor ngẫu nhiên trong khoảng [0, 1]
- view() : Thay đổi shape của tensor mà không copy dữ liệu
- view_as() : Reshape tensor theo shape của tensor khác