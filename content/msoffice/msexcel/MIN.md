---
title: "MIN"
date: 2023-03-09T22:33:13+07:00
draft: false
weight: 6
categories:
    - Microsoft Excel
tags:
    - min
description: >
    Formula MIN pada Excel digunakan untuk menemukan nilai minimum dalam sebuah range atau daftar nilai numerik.
---

## Formula MIN

Formula MIN pada Excel digunakan untuk menemukan nilai minimum dalam sebuah range atau daftar nilai numerik. Formula ini berguna untuk menganalisis data numerik dan mengambil nilai terkecil dalam range tersebut.

Berikut adalah sintaks dari formula MIN pada Excel:
{{< highlight go >}}
=MIN(value1, [value2], ...)
{{< / highlight >}}

- `value1` adalah nilai atau range pertama yang ingin dicari nilai minimumnya.
- `[value2]` adalah nilai atau range kedua (opsional) yang ingin dicari nilai minimumnya.

Tips penggunaan formula MIN pada Excel:

1. Gunakan tanda `$` pada range nilai yang ingin dicari nilai minimumnya agar dapat digunakan pada sel yang berbeda.
2. Jika menggunakan range nilai, pastikan range tersebut hanya terdiri dari nilai numerik, jika tidak maka formula akan menghasilkan error.
3. Formula MIN juga dapat digunakan pada sel yang mengandung formula atau nilai hasil perhitungan.
Contoh penggunaan formula MIN pada Excel:

Misalnya, kita ingin mencari nilai minimum dari range nilai A1:A10, maka sintaks yang digunakan adalah sebagai berikut:
{{< highlight go >}}
=MIN(A1:A10)
{{< / highlight >}}

Jika kita ingin mencari nilai minimum dari dua range nilai yaitu A1:A10 dan B1:B10, maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=MIN(A1:A10, B1:B10)
{{< / highlight >}}

Selain itu, kita juga dapat menggunakan formula MIN pada sel yang mengandung formula atau nilai hasil perhitungan seperti contoh berikut:

{{< highlight go >}}
=MIN(10, 5, 20, A1, B2)
{{< / highlight >}}

Formula tersebut akan mencari nilai minimum dari angka 10, 5, 20, nilai pada sel A1, dan nilai pada sel B2.
