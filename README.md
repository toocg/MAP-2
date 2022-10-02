# MAP-2
Bai nha thay Kien 
Quay thưởng
Công ty Omega tổ chức chương trình quay số siêu trúng thưởng cho khách
hàng nhân dịp kỷ niệm 100 năm ngày thành lập công ty. Công ty có một bảng
điện tử gồm n ô được đánh số từ 1 đến n, mỗi ô hiển thị một số nguyên dương.
Người quay số được quay m lần, mỗi lần quay được một số nguyên dương khi
đó trên bảng điện tử các ô có số trùng với số của mỗi lần quay sẽ bị xóa. Sau m
lần quay tiền thưởng của khách hàng là tổng lớn nhất của một loại số trong các
số còn hiển thị trên bảng điện tử. Em hãy đóng vai là người quay số đó và thử
vận may của mình nhé.
Yêu cầu: Hãy cho biết các số còn hiển thị trên bảng điện tử và tổng số tiền
thưởng của mình là bao nhiêu?
Dữ liệu: Vào từ tệp văn bản THUONG.INP gồm:
- Dòng 1: ghi 2 số nguyên dương n và m (n, m ≤ 3x106);
-Dòng 2: ghi n số nguyên dương A1, A2, …, An (Ai ≤ 109, với i=1..n) là các số trên
bảng điện tử;
- Dòng 3: ghi m số nguyên dương B1, B2, …, Bm (Bj ≤ 109, với j=1..m) là các số
sau m lần quay;
Kết quả: Ghi ra tệp văn bản THUONG.OUT gồm:
- Dòng 1: ghi các số còn hiển thị trên bảng điện tử sau m lần quay theo thứ
tự ban đầu;
- Dòng 2: ghi tổng tiền thưởng nhiều nhất có thể được.
Nếu các số trên bảng điện tử bị xoá hết, thì đưa ra số 0
Ví dụ:
THUONG.INP THUONG.OUT
8 5
1 7 5 3 2 5 7 5
3 1 4 6 4
7 5 2 5 7 5
15

8 5
1 7 5 3 2 5 7 16
3 1 4 6 4
7 5 2 5 7 16
16
Giới hạn:
- Mỗi kết quả bài toán được 50% số điểm của test;
- Có 15/25 test, tương ứng 3 điểm với n, m ≤ 103;
- Có 5/25 test, tương ứng 1 điểm với 103< n, m ≤ 105;
- Có 5/25 test, tương ứng 1 điểm với 105< n, m ≤ 3x106 và Ai, Bj ≤ 106;
