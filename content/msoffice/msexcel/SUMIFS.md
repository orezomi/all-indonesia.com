---
title: "SUMIFS"
date: 2023-03-09T07:54:16+07:00
draft: false
weight: 3
categories:
    - Microsoft Excel
tags:
    - sumifs
description: >
    Formula SUMIFS digunakan untuk menjumlahkan nilai-nilai dalam rentang sel yang memenuhi beberapa kriteria tertentu.
---

## Formula SUMIFS

Formula SUMIFS digunakan untuk menjumlahkan nilai-nilai dalam rentang sel yang memenuhi beberapa kriteria tertentu. Berikut adalah contoh penggunaan formula SUMIFS:

***Contoh 1:***
Jumlahkan nilai dari sel A1 hingga A5 yang nilainya lebih besar dari 10 dan lebih kecil dari 20.
{{< highlight go >}}
=SUMIFS(A1:A5, A1:A5, ">10", A1:A5, "<20")
{{< / highlight >}}

***Contoh 2:***
Jumlahkan nilai dari sel A1 hingga A5 yang memiliki teks "Produk A" dan terjual lebih dari 50 unit.
{{< highlight go >}}
=SUMIFS(B1:B5, A1:A5, "Produk A", B1:B5, ">50")
{{< / highlight >}}

Tips dalam menggunakan formula SUMIFS:

1. Pastikan rentang sel dan kriteria yang Anda gunakan sudah benar dan sesuai dengan kebutuhan Anda.
2. Gunakan operator logika AND atau OR untuk memfilter nilai-nilai yang ingin dijumlahkan.
3. Pastikan format sel-sel tersebut adalah format angka, jika tidak, maka Excel tidak akan dapat menjumlahkan nilai-nilai tersebut.

Dalam penggunaan formula SUMIFS, Anda dapat memfilter nilai-nilai yang ingin dijumlahkan berdasarkan beberapa kriteria tertentu. Dengan menggunakan formula SUMIFS, Anda dapat melakukan analisis data yang lebih spesifik dan akurat.
