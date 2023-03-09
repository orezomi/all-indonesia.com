---
title: "MAX"
date: 2023-03-09T17:36:52+07:00
draft: false
weight: 5
categories:
    - Microsoft Excel
tags:
    - max
description: >
    Formula MAX pada Excel digunakan untuk menemukan nilai maksimum dalam sebuah range atau daftar nilai numerik.
---

## Formula MAX

Formula MAX pada Excel digunakan untuk menemukan nilai maksimum dalam sebuah range atau daftar nilai numerik. Formula ini berguna untuk menganalisis data numerik dan mengambil nilai terbesar dalam range tersebut.

Berikut adalah sintaks dari formula MAX pada Excel:
{{< highlight go >}}
=MAX(value1, [value2], ...)
{{< / highlight >}}

- value1 adalah nilai atau range pertama yang ingin dicari nilai maksimumnya.
- [value2] adalah nilai atau range kedua (opsional) yang ingin dicari nilai maksimumnya.

Tips penggunaan formula MAX pada Excel:

- Gunakan tanda *$* pada range nilai yang ingin dicari nilai maksimumnya agar dapat digunakan pada sel yang berbeda.
- Jika menggunakan range nilai, pastikan range tersebut hanya terdiri dari nilai numerik, jika tidak maka formula akan menghasilkan error.
- Formula MAX juga dapat digunakan pada sel yang mengandung formula atau nilai hasil perhitungan.

### Contoh penggunaan formula MAX pada Excel:

Misalnya, kita ingin mencari nilai maksimum dari range nilai A1:A10, maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=MAX(A1:A10)
{{< / highlight >}}

Jika kita ingin mencari nilai maksimum dari dua range nilai yaitu A1:A10 dan B1:B10, maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=MAX(A1:A10, B1:B10)
{{< / highlight >}}

Selain itu, kita juga dapat menggunakan formula MAX pada sel yang mengandung formula atau nilai hasil perhitungan seperti contoh berikut:
{{< highlight go >}}
=MAX(10, 5, 20, A1, B2)
{{< / highlight >}}
Formula tersebut akan mencari nilai maksimum dari angka 10, 5, 20, nilai pada sel A1, dan nilai pada sel B2.
