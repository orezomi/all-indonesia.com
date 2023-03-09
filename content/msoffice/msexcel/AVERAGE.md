---
title: "AVERAGE"
date: 2023-03-09T17:17:01+07:00
draft: false
weight: 4
categories:
    - Microsoft Excel
tags:
    - average
description: >
    Formula AVERAGE digunakan untuk menghitung rata-rata dari sejumlah angka yang diberikan dalam rentang sel tertentu pada Microsoft Excel.
---

## Formula AVERAGE

Formula AVERAGE digunakan untuk menghitung rata-rata dari sejumlah angka yang diberikan dalam rentang sel tertentu pada Microsoft Excel.

***Contoh:***
Misalkan Anda memiliki beberapa data berikut pada kolom A pada spreadsheet Anda: 10, 20, 30, 40, dan 50. Anda ingin menghitung rata-rata dari data tersebut. Untuk melakukan hal ini, Anda dapat menggunakan formula AVERAGE seperti di bawah ini:
{{< highlight go >}}
=AVERAGE(A1:A5)
{{< / highlight >}}
Formula ini akan menghitung rata-rata dari nilai dalam sel A1 hingga A5, yang dalam contoh ini akan menghasilkan nilai 30.

***Tips:***

1. Pastikan bahwa rentang sel yang dipilih untuk formula AVERAGE hanya berisi angka. Jika ada sel kosong atau sel dengan teks, formula tersebut akan menghasilkan nilai kesalahan.

2. Anda dapat menggunakan formula AVERAGE pada seluruh kolom atau baris dengan menentukan rentang sel yang lebih besar. Misalnya, jika Anda ingin menghitung rata-rata dari seluruh kolom A, Anda dapat menggunakan formula AVERAGE seperti di bawah ini:

{{< highlight go >}}
=AVERAGE(A:A)
{{< / highlight >}}

3. Formula AVERAGE dapat digunakan bersama dengan formula lainnya seperti SUM atau COUNT untuk menghitung total atau jumlah data yang dihitung rata-ratanya.
