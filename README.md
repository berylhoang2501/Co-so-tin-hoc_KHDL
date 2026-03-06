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
