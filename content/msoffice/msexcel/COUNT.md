---
title: "COUNT"
date: 2023-03-09T22:43:14+07:00
draft: false
weight: 7
categories:
    - Microsoft Excel
tags:
    - count
description: >
    Formula COUNT pada Excel digunakan untuk menghitung jumlah sel dalam sebuah range yang memiliki nilai numerik atau teks
---

## Formula COUNT

Formula COUNT pada Excel digunakan untuk menghitung jumlah sel dalam sebuah range yang memiliki nilai numerik atau teks. Formula ini berguna untuk menghitung data dalam sebuah tabel atau daftar.

Berikut adalah sintaks dari formula COUNT pada Excel:
{{< highlight go >}}
=COUNT(value1, [value2], ...)
{{< / highlight >}}

- `value1` adalah nilai atau range pertama yang ingin dihitung jumlah selnya.
- `[value2]` adalah nilai atau range kedua (opsional) yang ingin dihitung jumlah selnya.

Tips penggunaan formula COUNT pada Excel:

1. Gunakan tanda $ pada range nilai yang ingin dihitung jumlah selnya agar dapat digunakan pada sel yang berbeda.
2. Pastikan range nilai yang ingin dihitung hanya terdiri dari nilai numerik atau teks, jika tidak maka formula akan menghasilkan error.
3. Formula COUNT juga dapat digunakan pada sel yang mengandung formula atau nilai hasil perhitungan.

Contoh penggunaan formula COUNT pada Excel:

Misalnya, kita ingin menghitung jumlah sel dalam range nilai A1:A10 yang memiliki nilai numerik atau teks, maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=COUNT(A1:A10)
{{< / highlight >}}

Jika kita ingin menghitung jumlah sel dalam dua range nilai yaitu A1:A10 dan B1:B10 yang memiliki nilai numerik atau teks, maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=COUNT(A1:A10, B1:B10)
{{< / highlight >}}

Selain itu, kita juga dapat menggunakan formula COUNT pada sel yang mengandung formula atau nilai hasil perhitungan seperti contoh berikut:

{{< highlight go >}}
=COUNT(10, 5, "Tes", A1, B2)
{{< / highlight >}}

Formula tersebut akan menghitung jumlah sel yang memiliki nilai numerik atau teks dari angka 10, angka 5, teks "Tes", nilai pada sel A1, dan nilai pada sel B2.
