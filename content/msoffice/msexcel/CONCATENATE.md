---
title: "CONCATENATE"
date: 2023-03-12T11:40:44+07:00
draft: false
weight: 10
categories:
    - Microsoft Excel
tags:
    - CONCATENATE
description: >
    Formula CONCATENATE di Excel digunakan untuk menggabungkan beberapa teks atau nilai dari beberapa sel menjadi satu sel atau string.
---
## Formula CONCATENATE

Formula CONCATENATE di Excel digunakan untuk menggabungkan beberapa teks atau nilai dari beberapa sel menjadi satu sel atau string. Berikut adalah contoh penggunaan formula CONCATENATE:

Contoh 1:
Gabungkan teks "Produk A" dan "Harga: " sehingga menjadi "Produk A Harga: ".
{{< highlight go >}}
=CONCATENATE("Produk A", " Harga: ")
{{< / highlight >}}

Contoh 2:
Gabungkan teks dari sel A1 dan B1 sehingga menjadi satu sel.
{{< highlight go >}}
=CONCATENATE(A1, " ", B1)
{{< / highlight >}}

Tips dalam menggunakan formula CONCATENATE:

1. Pastikan tanda kutip di awal dan akhir teks yang ingin digabungkan sudah benar.
2. Pastikan urutan sel atau teks yang ingin digabungkan sudah benar sesuai dengan kebutuhan Anda.
3. Anda juga dapat menggunakan simbol & untuk menggabungkan beberapa teks atau nilai. Misalnya `=A1&" "&B1` akan menggabungkan teks dari sel A1 dan B1 dengan spasi di antaranya.

Dalam penggunaan formula `CONCATENATE`, Anda dapat menggabungkan beberapa teks atau nilai dari beberapa sel menjadi satu sel atau string. Dengan menggunakan formula `CONCATENATE`, Anda dapat mempersiapkan data yang dibutuhkan untuk analisis atau presentasi dengan lebih efektif dan efisien.
