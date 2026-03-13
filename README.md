khtn@phonghoc

## Cơ sở lập trình (Th Thúc)
- Giao bài tập mỗi tuần viết lại trên giấy buổi sau nộp lại
- Không cần thu
- I63 DAC Lab, sáng t7 hằng tuần
## Xử lý dữ liệu (Th Tế)
- Đồ án xử lý dữ liệu
- Nộp đồ án

---

> # Buổi 1: THUẬT GIẢI VÀ CHƯƠNG TRÌNH 

- Làm quen thuật ngữ
- Nghĩ theo lối máy tính

- algorithms: An algorithm is a step-by-step set of instructions for solving a problem or doing a task.

## 1. THUẬT GIẢI (ALGORITHM)

### Khái niệm

- Thuật giải (algorithm) là **dãy các lệnh có thứ tự xác định** để giải một bài toán.
- Không phải là tập hợp lệnh rời rạc → **thứ tự thực hiện rất quan trọng**.
- Mỗi lệnh khi thực thi sẽ làm thay đổi **trạng thái (state)** của máy tính.

## 2. BÀI TOÁN TRONG TIN HỌC

Một bài toán gồm 4 thành phần:

- **Input**: dữ liệu đầu vào
- **Pre-Conditions**: điều kiện ràng buộc trên dữ liệu đầu vào
- **Output**: dữ liệu đầu ra
- **Post-Conditions**: điều kiện ràng buộc trên dữ liệu đầu ra

👉 Cách mô tả này gọi là **đặc tả bài toán (problem specification – spec)**

### Ví dụ: Bài toán GCD(a, b)

- Input: a, b
- Pre-Conditions: a > 0, b > 0
- Output: c
- Post-Conditions:  
  - c chia hết cho a và b  
  - Nếu d cũng chia hết cho a và b thì d ≤ c  
  (c là ước chung lớn nhất)


## 3. CÂU LỆNH (STATEMENT)

Lệnh là phát biểu mệnh lệnh làm thay đổi trạng thái chương trình.

Có 3 nhóm chính:

### 3.1 Lệnh nhập / xuất

- Nhập dữ liệu: input(x)

- Xuất dữ liệu:

```
print(x)
print("chuỗi")
print(x + y)
```

### 3.2 Lệnh gán (thay đổi giá trị)

x = expression


- Tính expression trước
- Gán kết quả cho biến x

### 3.3 Lệnh điều khiển

Có 3 cấu trúc điều khiển cơ bản:

#### a) Tuần tự (Sequence)

Thực hiện lệnh theo thứ tự từ trên xuống dưới.

#### b) Chọn (Selection – If/Else)

- Điều kiện phải trả về True hoặc False.

#### c) Lặp (Iteration – While)

while điều_kiện:

- Lặp khi điều kiện còn đúng.
- Dừng khi điều kiện sai.


## 4. TÍNH CHẤT CỦA THUẬT GIẢI

Một thuật giải đúng phải đảm bảo:

### ✔ Tính tất định
- Cùng input → luôn cho cùng output.

### ✔ Tính dừng
- Chạy trong thời gian hữu hạn.

### ✔ Tính đúng
- Kết quả phải thỏa đặc tả bài toán.


## 5. CHIẾN LƯỢC GIẢI BÀI TOÁN

### Bước 1: Hiểu bài toán
- Làm rõ yêu cầu
- Cho ví dụ cụ thể

### Bước 2: Làm trên ví dụ nhỏ
Thử với dữ liệu cụ thể để hiểu cách hoạt động.

### Bước 3: Giải pháp vét cạn (Brute Force)
Làm cách đơn giản trước → sau đó tối ưu.

Ví dụ:
- Tìm phần tử đầu tiên > k → duyệt từ đầu mảng.
- Có thể cải tiến bằng **tìm kiếm nhị phân** nếu mảng đã tăng dần.

## Bước 4: Biểu diễn lời giải

- Phân rã từ tổng quát → chi tiết (top-down)
- Thử với dữ liệu hợp lệ
- Thử với dữ liệu ngoại lệ
- Viết mã giả


## 6. BIỂU DIỄN THUẬT GIẢI

Có 3 mức biểu diễn:


### 6.1 Ý tưởng (Idea Phase)

- Mô tả bằng ngôn ngữ tự nhiên.
- Ví dụ: “Duyệt từng phần tử cho đến khi tìm thấy số lớn hơn k”.

### 6.2 Mã giả (Pseudo-code)

Ngôn ngữ trung gian giữa tiếng Việt và Python.

### 6.3 Chương trình (Programming Phase)

---

> # Buổi 2: LẬP TRÌNH CẤU TRÚC

---

> # Buổi 3: LẬP TRÌNH CẤU TRÚC

---
---
---
> # Buổi 1

tena@ueh.edu.vn

Subject: [DHKHTN-CSTN]

## 1. Giới thiệu 

- NN biên dịch: C, C++, Pascal,.. Sau khi viết code xong -> kiểm tra syntax -> chuyển qua file binary -> kết nối thư viện tạo thành file con
- NN thông dịch: Python.
  - mã nguồn mở
  - hướng đối tượng. Procedural programming mạnh ở bài nhỏ, rõ bước. (Procedural programming là kiểu lập trình xây dựng chương trình chủ yếu bằng các thủ tục / hàm để xử lý công việc theo từng bước.) OOP mạnh ở bài lớn, nhiều thành phần, cần mở rộng lâu dài
  - .py: file mã nguồn Python thông thường, .ipynb: notebook tương tác, vừa viết code vừa xem kết quả từng phần
 
#### Các bước tìm hiểu 1 NN lập trình mới
- B1: Tìm hiểu syntax
  - từ khoá, có phân biệt chữ hoa vs chữ thường không(case sensitive), quy tắc sử dụng định danh (cách đặt tên,..)
- B2: Built-in data type
  - kiểu số gồm những kiểu số nào, kiểu chuỗi gồm gì, mỗi kiểu dữ liệu sẽ có những phép tình toán nào (operators)
  - cách thức chuyển đối kiểu dữ liệu từ kiểu này sang kiểu khác
  - biến và biểu thức, biến cục bộ và biến toàn cục
- B3: Nhập/ xuất dữ liệu (console)
  - console có nghia là màn hình và bàn phím
- B4: block, control structures
  - Sequential structure — cấu trúc tuần tự
  - Selection structure — cấu trúc chọn / rẽ nhánh
  - Iteration structure — cấu trúc lặp
- B5: Hàm UDF (user-define function)
  - passing pattern - cách truyền dữ liệu/đối số vào hàm.
- B6: Lập trình hướng đối tượng OOP
- B7: Xử lý tập tin

## 2. Các khái niệm cơ bản 
### 2.1. Định danh 

- Quy tắc đặt tên theo mnemonic là: đặt tên biến, hàm, hoặc hằng sao cho tên đó gợi nhớ ý nghĩa/chức năng của nó.
### 2.2. Các kiểu dữ liệu cơ bản 

- Kiểu số (numeric): int, float, complex(real, image).
  - Các toán tử kiểu số gồm có + - * / ,...
- Kiểu chuỗi (string)
  - ' ', " "
  - ký tự điều khiển: \n, \t
  - slice: [start:end]
    ```
    s = "Python"
      print(s[2:5])
    ```
  - toán tử: toán tử + nối 2 chuỗi
- Kiểu ngày giờ (datetime)
  - Khi chuyển từ ngày -> chuỗi phải theo yyyymmdd
- Kiểu luận lý (boolean)
    - True, False
    - default là False
    - Là kết quả của những phép so sánh ==, !=,..

### 2.3. Hằng(literal), biến và biểu thức(variable)

## 3. Nhập, xuất dữ liệu với console

- Nhập từ bàn phím thì kêt qủa luôn luôn là kiểu chuỗi -> phải chuyển đổi kiểu dữ liệu
- print thì nên dùng f'

## 4. Cấu trúc điều khiển
- 3 cấu trúc chính
  - rẽ nhánh
    - rẽ theo đk logic (if..else)
        - rẽ 2 nhánh
        - rẻ nhiều nhánh
    - rẽ theo giá trị của 1 biến (switch case)
  - cấu trúc lặp
  - cấu trúc nhảy (break, continue,..)

---
> # Buổi 2

## 1. Cấu trúc dữ liệu tập hợp 

- list
  - [], các phần tử cách nhau bằng dấu (,)
  - có thể không cùng kiểu dữ liệu
  - có thể truy cập bằng chỉ số index bắt đầu từ 0. -> list[1] lấy phần tử thứ 2.
  - muốn lấy nhiều phần tử thì dùng cơ chế slice ví dụ list[m:n] -> lấy từ m+1 đến n 
- tuple
  - giống list nhưng các phần tử không thể cập nhật
- dictionary
  - {}, các phần tử cách nhau bằng dấu (,)
  - mỗi phần tử key:value
  - các key có thể do ngừoi sử dụng định nghĩa miễn là không trùng (k khuyến khích dùng)
- set

- nên chuyển các kiểu dữ liệu khác thành list để dễ xử lý trong các thư viện numpy pandas sklearn,...
```
d = {"x": 100, "y": 200}
t = (1, 2, 3)
s = {7, 8, 9}

print(list(d))             # ['x', 'y']
print(list(d.values()))    # [100, 200]
print(list(t))             # [1, 2, 3]
print(list(s))             # [7, 8, 9] (thứ tự có thể khác)
```


  
