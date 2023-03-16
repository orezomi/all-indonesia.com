---
title: "MATCH"
date: 2023-03-16T07:42:16+07:00
draft: false
weight: 17
categories:
    - Microsoft Excel
description: >
    Fungsi MATCH di Excel digunakan untuk mencari posisi suatu nilai dalam suatu daftar atau rentang data.
---
## Fungsi MATCH

Fungsi MATCH di Excel digunakan untuk mencari posisi suatu nilai dalam suatu daftar atau rentang data. Berikut adalah cara menggunakan fungsi MATCH di Excel:

1. Tulis fungsi MATCH di sel yang ingin Anda isi dengan hasil pencarian. Contohnya, untuk mencari posisi nilai "Budi" dalam rentang A2:A6, Anda dapat menulis:
{{< highlight go >}}
=MATCH("Budi",A2:A6,0)
{{< / highlight >}}
2. Argumen pertama fungsi MATCH adalah nilai yang ingin Anda cari. Argumen kedua adalah rentang data tempat Anda ingin mencari nilai tersebut. Argumen ketiga (0) menunjukkan bahwa pencarian dilakukan secara eksak.
3. Jika nilai "Budi" ditemukan pada posisi ketiga dalam rentang A2:A6, maka fungsi MATCH akan mengembalikan nilai 3.
4. Jika nilai "Budi" tidak ditemukan dalam rentang A2:A6, maka fungsi MATCH akan mengembalikan nilai error #N/A.

### Kombinasi MATCH dan INDEX

Anda juga dapat menggabungkan fungsi MATCH dengan fungsi INDEX untuk mengambil nilai dari posisi yang ditemukan. Misalnya, jika Anda ingin mengambil nilai pada posisi ketiga dalam rentang B2:B6 jika nilai "Budi" ditemukan dalam rentang A2:A6, maka Anda dapat menulis:

{{< highlight go >}}
=INDEX(B2:B6,MATCH("Budi",A2:A6,0))
{{< / highlight >}}

Dalam contoh ini, fungsi MATCH digunakan untuk mencari posisi nilai "Budi" dalam rentang A2:A6, dan kemudian fungsi INDEX digunakan untuk mengambil nilai pada posisi tersebut dalam rentang B2:B6.


***Contoh selanjutnya untuk kombinasi MATCH dan INDEX***

Misalnya, Anda memiliki tabel berisi data karyawan dan gajinya seperti di bawah ini:
|Karyawan|Gaji|
|--------|:-------:|
|A|4000|
|B|5000|
|C|6000|
|D|5500|
|E|4500|

Anda ingin mencari gaji karyawan dengan nama "C". Anda dapat menggunakan kombinasi fungsi MATCH dan INDEX seperti ini:

1. Tulis fungsi MATCH di sel yang ingin Anda isi dengan hasil pencarian. Misalnya, untuk mencari posisi karyawan "C" dalam rentang A2:A6, Anda dapat menulis:
{{< highlight go >}}
=MATCH("C",A2:A6,0)
{{< / highlight >}}
2. Fungsi MATCH akan mengembalikan posisi karyawan "C" dalam rentang A2:A6, yaitu 3.
3. Tulis fungsi INDEX untuk mengambil nilai gaji pada posisi tersebut dalam rentang B2:B6. Misalnya, untuk mengambil gaji karyawan "C", Anda dapat menulis:
{{< highlight go >}}
=INDEX(B2:B6,MATCH("C",A2:A6,0))
{{< / highlight >}}
4. Fungsi INDEX akan mengambil nilai pada posisi ketiga dalam rentang B2:B6, yaitu 6000.

Dengan kombinasi fungsi MATCH dan INDEX, Anda dapat mencari dan mengambil nilai dari posisi tertentu dalam rentang data berdasarkan nilai pencarian dengan cepat dan mudah.
