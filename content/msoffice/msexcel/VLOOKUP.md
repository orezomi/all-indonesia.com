---
title: "VLOOKUP"
date: 2023-03-11T22:19:11+07:00
draft: false
weight: 9
categories:
    - Microsoft Excel
tags:
    - VLOOKUP
description: >
    VLOOKUP digunakan untuk mencari nilai dalam range data berdasarkan kunci pencarian tertentu dan mengembalikan nilai yang sesuai dari kolom yang ditentukan.
---

Formula VLOOKUP (Vertical Lookup) pada Excel digunakan untuk mencari nilai dalam tabel atau range data berdasarkan kunci pencarian tertentu dan mengembalikan nilai yang sesuai dari kolom yang ditentukan. Formula ini berguna untuk mencari data dalam tabel atau range data yang besar.

Berikut adalah sintaks dari formula VLOOKUP pada Excel:
{{< highlight go >}}
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])
{{< / highlight >}}

- `lookup_value` adalah nilai atau kunci pencarian yang ingin dicari dalam tabel atau range data.
- `table_array` adalah range data atau tabel yang ingin dicari nilai berdasarkan kunci pencarian.
- `col_index_num` adalah nomor kolom pada tabel atau range data yang ingin diambil nilainya.
- `[range_lookup]` adalah nilai opsional yang menentukan apakah nilai yang dicari harus benar-benar cocok atau hanya cocok dengan nilai terdekat dalam tabel atau range data. Jika nilai range_lookup bernilai TRUE atau tidak diisi, maka akan dicari nilai yang cocok dengan kunci pencarian, dan jika nilai range_lookup bernilai FALSE, maka akan dicari nilai yang benar-benar cocok dengan kunci pencarian.

Tips penggunaan formula VLOOKUP pada Excel:

1. Pastikan nilai yang dicari dalam kunci pencarian telah sesuai dengan format data dalam tabel atau range data.
2. Gunakan tanda `$` pada range data atau tabel yang ingin dicari nilainya agar dapat digunakan pada sel yang berbeda.
3. Gunakan nomor kolom yang benar-benar mengandung nilai yang ingin diambil, dan pastikan nomor kolom tersebut terhitung dari kolom pertama pada tabel atau range data yang digunakan dalam formula.
4. Jika nilai `range_lookup` tidak diisi atau bernilai TRUE, pastikan tabel atau range data telah diurutkan secara benar berdasarkan kunci pencarian.

***Contoh penggunaan formula VLOOKUP pada Excel:***

Misalnya, kita memiliki tabel berikut:

| Nama   |  Nilai  |
|--------|:-------:|
| Budi   |    80   |
| Ani    |    90   |
| Candra |    75   |
| Diah   |    85   |
| Eko    |    70   |

Kita ingin mencari nilai dari nama "Budi" pada tabel tersebut. Maka sintaks yang digunakan adalah sebagai berikut:
{{< highlight go >}}
=VLOOKUP("Budi", A1:B6, 2, FALSE)
{{< / highlight >}}

Formula tersebut akan mencari nilai "Budi" dalam kolom pertama (A) pada tabel, dan mengembalikan nilai 80 pada kolom kedua (B).

Selain itu, kita juga dapat menggunakan formula VLOOKUP untuk mencari nilai berdasarkan kunci pencarian yang ditemukan di dalam sel lain seperti contoh berikut:

| Nama   |  Nilai  |
|--------|:-------:|
| Budi   |    80   |
| Ani    |    90   |
| Candra |    75   |
| Diah   |    85   |
| Eko    |    70   |

Misalkan kita menggunakan sel F7 sebagai tempat kata kunci pencarian data. Kita ingin mencari nilai dari nama yang terdapat dalam sel F7 pada tabel tersebut, misalkan cel F7 ini berisi nama "Ani". Maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=VLOOKUP(F7, A1:B6, 2, FALSE)
{{< / highlight >}}

{{< adsense >}}

Formula tersebut akan mencari nilai dari nama yang terdapat dalam sel F7, yaitu "Ani" dalam kolom pertama (A) pada tabel, dan mengembalikan nilai 90 pada kolom kedua (B).

Kita juga dapat menggunakan formula VLOOKUP untuk mencari nilai berdasarkan kunci pencarian yang hampir cocok dengan nilai dalam tabel atau range data dengan menggunakan nilai `[range_lookup]` bernilai `TRUE`. Misalnya, kita memiliki tabel berikut:

| Nama   |  Nilai  |
|--------|:-------:|
| Budi   |    80   |
| Ani    |    90   |
| Candra |    75   |
| Diah   |    85   |
| Eko    |    70   |

Kita ingin mencari nilai dari nama "Ani" yang hampir cocok pada tabel tersebut. Maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=VLOOKUP("Any", A1:B6, 2, TRUE)
{{< / highlight >}}

Karena nilai `[range_lookup]` bernilai `TRUE`, maka formula akan mencari nilai "Any" yang hampir cocok pada kolom pertama (A) pada tabel, dan mengembalikan nilai yang cocok terdekat pada kolom kedua (B), yaitu nilai 90 dari nama "Ani".

Demikianlah penjelasan tentang formula VLOOKUP pada Excel beserta contoh dan tips penggunaannya.
