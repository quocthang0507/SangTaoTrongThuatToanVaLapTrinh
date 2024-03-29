﻿# 1.1. Số thân thiện

*Tìm tất cả các số tự nhiên hai chữ số mà khi đảo trật tự của hai chữ số đó sẽ thu được một số nguyên tố cùng nhau với số đã cho.*

## Hiểu đầu bài

Ta kí hiệu (a, b) là ước chung lớn nhất (ucln) của hai số tự nhiên a và b. Hai số tự nhiên a và b được gọi là nguyên tố cùng nhau khi và chỉ khi (a, b) = 1.

Ví dụ:

``` c#
(23, 32) = 1 // Vậy 23 và 32 là một số cần tìm

(12, 21) = 3 // 12 và 21 không phải là một số cần tìm
```

**Đặc tả:**

(1) x = ab

(2) a, b = 0..9 (a và b biến thiên trong khoảng 0..9)

(3) a > 0 vì x là số có hai chữ số

(4) (ab, ba) = 1

Ta ký hiệu x' là số đối xứng của x theo nghĩa của đầu bài, khi đó ta có đặc tả như sau:

(5) x = 10..99 (x biến thiên từ 10 đến 99, vì x là số có hai chữ số)

(6) (x, x') = 1

## Kết quả

```
0 31 13 32 23 41 14 43 34 52 25 53 35 61 16 65 56 71 17 73 37 74 47 76 67 83 38 85 58 91 19 92 29 94 49 95 59 97 79 98 89 Tong cong: 41 so
```
