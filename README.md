# Giới thiệu thư viện Numpy

## NumPy là gì?

**NumPy** (viết tắt của Numerical Python) từ lâu đã là nền tảng của điện toán số (numerical computing) trong Python. Nó cung cấp cấu trúc dữ liệu, thuật toán và thư viện cần thiết cho hầu hết các ứng dụng khoa học liên quan đến dữ liệu số trong Python. Thư viện NumPy bao gồm các đối tượng mảng đa chiều (multidimensional array) và một tập hợp các phương thức để xử lý mảng đa chiều đó. Sử dụng Numpy, các toán tử toán học và logic có thể được thực hiện. Ngoài các khả năng xử lý mảng nhanh mà NumPy có, một trong những ứng dụng chính của Numpy trong phân tích dữ liệu là làm nơi chứa dữ liệu được truyền giữa các thuật toán và thư viện. Đối với dữ liệu số, mảng NumPy hiệu quả hơn để lưu trữ và thao tác dữ liệu so với các cấu trúc dữ liệu Python tích hợp khác. 

**Cài đặt:**  

`pip install numpy`

Sau khi cài đặt hoàn tất, chúng ta cần import nó để sử dụng như các thư viện khác của Python để sử dụng các hàm số của NumPy:

`import numpy as np`

**Ưu điểm:**
-	Chứa bộ các giá trị
-	Có thể chứa các loại dữ liệu khác nhau
-	Có thể thay đổi, thêm, xoá
-	Đầy đủ chức năng tính toán
-	Rất nhiều thư viện được xây dựng sẵn trong NumPy
-	Cần cho Data Science vì thực hiện công việc tính toán trên các bộ dữ liệu với tốc độ cao.

## NumPy – Ndarray Object

Đối tượng quan trọng nhất trong Numpy là kiểu mảng N-dimensional được gọi là `ndarray`. Nó mô tả một bộ các item cùng kiểu. Item trong mảng có thể truy xuất bằng cách sử dụng zero-based index.
Mỗi item trong ndarray có cùng kích thước block trong bộ nhớ và là một đối tượng data-type gọi là `dtype`.
Bất kì item nào được trích xuất từ ndarray object bằng cách cắt ra được đại diện bởi một Python object của một kiểu mảng vô hướng (array scalar type).
Một thực thể của ndarray class có thể được tạo ra từ nhiều phương thức tạo mảng khác nhau. Ndarray cơ bản được tạo bằng cách sử dụng phương thức: `numpy.array`.

**Cú pháp:**

`numpy.array(object, dtype=None, copy=True, ndmin=0`

**Trong đó:**
+ **Object**: đối tượng có phương thức giao diện mảng.
+ **Dtype**: loại dữ liệu mong muốn của mảng (tuỳ chọn)
+ **Copy**: mặc định = True đối tượng được copy (tuỳ chọn)
+ **ndmin**: chỉ định kích thước tổi thiểu của mảng kết quả.

## Numpy – Data Type

Numpy hỗ trợ rất nhiều kiểu dữ liệu khác nhau như:  
+ **bool** (hay **Boolean**): Đúng hoặc sai, được lưu trữ dưới dạng byte.
+ **int_**: Kiểu số nguyên mặc định (thường là int64 hoặc int32).
+ **int8**: Byte (-128 đến 127).
+ **int16**: Số nguyên (-32768 đến 32767).
+ **int32**: Số nguyên (-2147483648 đến 2147483647).
+ **int64**: Số nguyên (-9223372036854775808 đến 9223372036854775807).
+ **float_**: Viết tắt cho float64.
+ **float16**: bit dấu, số mũ 5 bit, phần định trị 10 bit.
+ **float32**: bit dấu, số mũ 8 bit, phần định trị 23 bit.
+ **float64**: bit dấu, số mũ 11 bit, phần định trị 52 bit.
