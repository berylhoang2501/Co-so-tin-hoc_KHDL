khtn@phonghoc

## Cơ sở lập trình (Th Thúc)
- Giao bài tập mỗi tuần viết lại trên giấy buổi sau nộp lại
- Không cần thu
- I63 DAC Lab, sáng t7 hằng tuần
## Xử lý dữ liệu (Th Tế)
- Đồ án xử lý dữ liệu
- Nộp đồ án


> # Buổi 1: THUẬT GIẢI VÀ CHƯƠNG TRÌNH 

- Làm quen thuật ngữ
- Nghĩ theo lối máy tính

- algorithms: An algorithm is a step-by-step set of instructions for solving a problem or doing a task.

## 1. THUẬT GIẢI (ALGORITHM)

### 1.1 Khái niệm

- Thuật giải (algorithm) là **dãy các lệnh có thứ tự xác định** để giải một bài toán.
- Không phải là tập hợp lệnh rời rạc → **thứ tự thực hiện rất quan trọng**.
- Mỗi lệnh khi thực thi sẽ làm thay đổi **trạng thái (state)** của máy tính.

---

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

---

## 3. CÂU LỆNH (STATEMENT)

Lệnh là phát biểu mệnh lệnh làm thay đổi trạng thái chương trình.

Có 3 nhóm chính:

---

### 3.1 Lệnh nhập / xuất

- Nhập dữ liệu:
