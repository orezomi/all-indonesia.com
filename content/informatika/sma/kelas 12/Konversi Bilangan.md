---
title: "Konversi Bilangan"
date: 2023-03-16T08:44:04+07:00
draft: false
weight: 1
categories:
    - Informatika
    - Kelas 12
description: >
    Konversi bilangan adalah proses mengubah bilangan dari satu sistem bilangan ke sistem bilangan lainnya.
---

## Pengertian Konversi Bilangan

Konversi bilangan adalah proses mengubah bilangan dari satu sistem bilangan ke sistem bilangan lainnya. Sistem bilangan yang paling umum digunakan adalah sistem bilangan desimal (basis 10), di mana setiap digit dapat bernilai dari 0 hingga 9. Namun, dalam dunia teknologi informasi, sistem bilangan biner (basis 2) lebih umum digunakan karena berhubungan dengan representasi data dalam sistem komputer yang menggunakan bilangan biner sebagai bahasa mesinnya.

Konversi bilangan dapat dilakukan antara sistem bilangan yang berbeda, seperti desimal ke biner, biner ke oktal, atau heksadesimal ke desimal. Konversi bilangan sangat penting dalam pemrograman komputer dan pengolahan data karena sering kali data harus diubah dari satu format ke format lainnya agar dapat digunakan secara efektif dalam suatu program atau sistem. Pemahaman dasar tentang konversi bilangan juga diperlukan untuk dapat memahami bagaimana data diolah dan disimpan dalam sistem komputer.

### Bilangan Desimal

Bilangan desimal adalah sistem bilangan yang paling umum digunakan dalam kehidupan sehari-hari. Sistem bilangan desimal menggunakan basis *10*, dan terdiri dari sepuluh digit, yaitu *0, 1, 2, 3, 4, 5, 6, 7, 8,* dan *9*.

Bilangan desimal memiliki tempat nilai yang meningkat dari kanan ke kiri, dengan nilai tempat terendah adalah 10 pangkat 0, dan setiap nilai tempat yang lebih tinggi merupakan pangkat 10 yang lebih tinggi. Misalnya, bilangan desimal 123 dapat dipecah menjadi:

- 1 x 10{^2} = 100
- 2 x 10{^1} = 20
- 3 x 10{^0} = 3

Sehingga, bilangan desimal 123 dapat dikonversi menjadi jumlah dari 100 + 20 + 3 = 123.

Bilangan desimal banyak digunakan dalam kehidupan sehari-hari dan dalam pemrograman komputer. Dalam pemrograman komputer, bilangan desimal digunakan untuk merepresentasikan data numerik, seperti nilai-nilai pengukuran atau hasil perhitungan matematika. Namun, bilangan desimal sulit dikonversi menjadi bilangan biner, yang digunakan dalam sistem komputer. Oleh karena itu, sistem bilangan lain, seperti bilangan oktal dan bilangan heksadesimal, sering digunakan dalam pemrograman komputer untuk mewakili nilai numerik dalam bentuk yang mudah dikonversi menjadi bilangan biner.

### Bilangan Biner

Bilangan biner adalah sistem bilangan yang menggunakan hanya dua simbol atau angka, yaitu 0 dan 1. Sistem bilangan biner sering digunakan dalam bidang teknologi informasi, komputer, dan elektronik karena sistem ini dapat dengan mudah diterjemahkan ke dalam kode biner atau digital yang dapat dipahami oleh komputer.

Setiap digit pada bilangan biner mewakili nilai yang berbeda, tergantung pada posisinya dalam bilangan. Misalnya, digit paling kanan mewakili nilai 2 pangkat 0 (atau 1), sedangkan digit kedua dari kanan mewakili nilai 2 pangkat 1 (atau 2), digit ketiga mewakili nilai 2 pangkat 2 (atau 4), dan seterusnya.

Contoh bilangan biner adalah 1010, yang dapat diterjemahkan ke dalam bilangan desimal dengan cara:

1 x 2{^3} + 0 x 2{^2} + 1 x 2{^1} + 0 x 2{^0} = 8 + 0 + 2 + 0 = 10

Begitu pula, bilangan desimal dapat diubah menjadi bilangan biner dengan cara mengkonversi angka desimal menjadi bentuk biner, yaitu dengan membagi angka desimal dengan 2 secara berulang-ulang hingga diperoleh hasil 0. Sisa dari setiap pembagian digunakan sebagai digit biner, mulai dari digit paling kanan hingga digit paling kiri.

Misalnya, untuk mengkonversi angka desimal 10 menjadi bentuk biner, dapat dilakukan sebagai berikut:

- 10 / 2 = 5 sisa 0
- 5 / 2 = 2 sisa 1
- 2 / 2 = 1 sisa 0
- 1 / 2 = 0 sisa 1

Maka, bentuk biner dari 10 adalah 1010.

### Bilangan Oktal

Bilangan oktal adalah sistem bilangan yang menggunakan basis 8. Sistem bilangan oktal menggunakan delapan digit, yaitu *0, 1, 2, 3, 4, 5, 6,* dan *7*. Mirip dengan sistem bilangan desimal, sistem bilangan oktal memiliki tempat nilai yang meningkat dari kanan ke kiri, dengan nilai tempat terendah adalah 8 pangkat 0, dan setiap nilai tempat yang lebih tinggi merupakan pangkat 8 yang lebih tinggi.

Contohnya, bilangan oktal 63 dapat dipecah menjadi:

- 6 x 8{^1} = 48
- 3 x 8{^0} = 3

Sehingga, bilangan oktal 63 dapat dikonversi menjadi bilangan desimal 51.

Bilangan oktal banyak digunakan dalam pengolahan data dan pemrograman komputer karena dapat dengan mudah dikonversi ke dalam bilangan biner, yang digunakan dalam sistem komputer. Setiap digit oktal dapat diubah menjadi tiga digit biner yang terkait, dengan pola 1 digit oktal = 3 digit biner. Misalnya, oktal 6 (dalam biner 110) dapat diubah menjadi oktal 60 (dalam biner 110000).

### Bilangan Heksadesimal

Bilangan heksadesimal adalah sistem bilangan yang menggunakan basis 16. Sistem bilangan heksadesimal menggunakan 16 digit, yaitu *0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E,* dan *F*. Digit A hingga F merepresentasikan bilangan desimal 10 hingga 15, dengan A merepresentasikan 10, B merepresentasikan 11, dan seterusnya hingga F yang merepresentasikan 15.

Seperti halnya sistem bilangan desimal, bilangan heksadesimal memiliki tempat nilai yang meningkat dari kanan ke kiri, dengan nilai tempat terendah adalah 16 pangkat 0, dan setiap nilai tempat yang lebih tinggi merupakan pangkat 16 yang lebih tinggi.

Contohnya, bilangan heksadesimal 3F dapat dipecah menjadi:

- 3 x 16{^1} = 48
- F x 16{^0} = 15

Sehingga, bilangan heksadesimal 3F dapat dikonversi menjadi bilangan desimal 63.

Bilangan heksadesimal banyak digunakan dalam pengolahan data dan pemrograman komputer karena dapat dengan mudah dikonversi ke dalam bilangan biner. Setiap digit heksadesimal dapat diubah menjadi empat digit biner yang terkait, dengan pola 1 digit heksadesimal = 4 digit biner. Misalnya, heksadesimal 6F (dalam biner 01101111) dapat diubah menjadi heksadesimal 60F (dalam biner 011000001111).
{{< adsense >}}

---

Konversi bilangan desimal ke bilangan biner dan sebaliknya merupakan dasar-dasar yang penting dalam pemrograman dan komputasi. Berikut ini adalah cara dasar untuk melakukan konversi bilangan desimal ke bilangan biner atau sebaliknya:

### Konversi Bilangan Desimal ke Bilangan Biner

1. Tuliskan bilangan desimal yang ingin dikonversi dan tuliskan nilai biner 1 di sebelah kiri.
2. Bagi bilangan desimal dengan 2 dan tuliskan hasilnya serta sisanya.
3. Bagi hasil pembagian sebelumnya dengan 2 dan tuliskan hasilnya serta sisanya.
4. Lakukan langkah 3 terus menerus hingga hasil bagi sudah mencapai 0.
5. Baca bilangan biner dari bawah ke atas, hasil dari tiap sisa pembagian merupakan digit biner.

***Contoh: Konversi bilangan desimal 25 ke bilangan biner***

1. Tuliskan bilangan desimal 25 dan nilai biner 1
2. 25/2 = 12, sisanya 1. Tuliskan 1 di sebelah kanan nilai biner 1.
3. 12/2 = 6, sisanya 0. Tuliskan 0 di sebelah kanan 1.
4. 6/2 = 3, sisanya 0. Tuliskan 0 di sebelah kanan 0.
5. 3/2 = 1, sisanya 1. Tuliskan 1 di sebelah kanan 0.
6. 1/2 = 0, sisanya 1. Tuliskan 1 di sebelah kanan 1.

Maka, bilangan biner dari 25 adalah 11001.

### Konversi Bilangan Biner ke Bilangan Desimal

1. Tuliskan bilangan biner yang ingin dikonversi.
2. Mulai dari digit terkiri (digit terkecil), tuliskan nilai digit biner 1.
3. Kalikan nilai digit biner dengan 2 pangkat yang sesuai dengan posisinya dalam bilangan biner.
4. Lakukan langkah 2 dan 3 untuk setiap digit biner dalam bilangan biner.
5. Jumlahkan hasil perkalian dari setiap digit biner.

***Contoh: Konversi bilangan biner 11001 ke bilangan desimal***

1. Tuliskan bilangan biner 11001.
2. Mulai dari digit terakhir, tuliskan nilai digit biner 1, yaitu 1.\
1 x 2{^0} = 1
3. Lanjutkan ke digit berikutnya, tuliskan nilai digit biner 0, yaitu 0.\
0 x 2{^1} = 0
4. Lanjutkan ke digit berikutnya, tuliskan nilai digit biner 0, yaitu 0.\
0 x 2{^2} = 0
5. Lanjutkan ke digit berikutnya, tuliskan nilai digit biner 1, yaitu 1.\
1 x 2{^3} = 8
6. Lanjutkan ke digit berikutnya, tuliskan nilai digit biner 1, yaitu 1.\
1 x 2{^4} = 16

Maka, bilangan desimal dari 11001 adalah 25

### Konversi Bilangan Desimal ke Bilangan dengan Basis Oktal

Konversi bilangan desimal ke bilangan berbasis oktal melibatkan pembagian bilangan desimal dengan basis 8, kemudian mengambil sisa dari setiap pembagian dan menuliskannya secara berurutan dari bawah ke atas.

Berikut adalah langkah-langkah konversi bilangan desimal ke bilangan berbasis oktal:

1. Bagi bilangan desimal dengan 8 dan simpan hasil bagi serta sisanya.
2. Jika hasil bagi lebih besar dari 0, ulangi proses pembagian dengan hasil bagi sebagai bilangan desimal. Jika tidak, proses konversi selesai.
3. Urutkan sisa-sisa yang didapat dari bawah ke atas untuk membentuk bilangan oktal.

Contoh:
Konversi bilangan desimal 187 ke bilangan berbasis oktal:

- 187 ÷ 8 = 23 sisa 3
- 23 ÷ 8 = 2 sisa 7
- 2 ÷ 8 = 0 sisa 2

Sehingga, bilangan desimal 187 dalam basis oktal adalah 273.

Dalam representasi bilangan oktal, setiap digit merepresentasikan kelipatan dari 8 mulai dari pangkat 0 pada digit paling kanan. Sebagai contoh, bilangan oktal 273 dapat dipecah menjadi:

- 2 x 8{^2} = 128
- 7 x 8{^1} = 56
- 3 x 8{^0} = 3

Sehingga, bilangan oktal 273 dapat dikonversi menjadi bilangan desimal 187.

### Konversi Bilangan Berbasis Oktal ke Bilangan Desimal

Konversi bilangan berbasis oktal ke bilangan desimal melibatkan perkalian digit-digit bilangan oktal dengan kelipatan dari basis 8 dan menjumlahkannya.

Berikut adalah langkah-langkah konversi bilangan oktal ke bilangan desimal:

1. Tentukan digit dan pangkat untuk setiap digit dalam bilangan oktal, mulai dari pangkat 0 pada digit paling kanan dan meningkatkan pangkat secara bertahap ke kiri.
2. Untuk setiap digit, kalikan digit tersebut dengan 8 pangkat pangkatnya.
3. Jumlahkan hasil perkalian pada langkah kedua untuk mendapatkan bilangan desimal.

Contoh:
Konversi bilangan oktal 273 ke bilangan desimal:

Digit kanan adalah 3, yang memiliki pangkat 0. Digit kiri adalah 7, yang memiliki pangkat 1, dan digit paling kiri adalah 2, yang memiliki pangkat 2.

Hitung nilai dari setiap digit dalam bilangan oktal, dengan mengalikannya dengan pangkat 8 yang sesuai:

- 3 x 8{^0} = 3
- 7 x 8{^1} = 56
- 2 x 8{^2} = 128

Jumlahkan hasil perkalian pada langkah kedua untuk mendapatkan bilangan desimal:

3 + 56 + 128 = 187

Sehingga, bilangan oktal 273 dapat dikonversi menjadi bilangan desimal 187.

### Konversi Bilangan Desimal ke Bilangan Heksadesimal

Konversi bilangan desimal ke bilangan heksadesimal melibatkan pembagian bilangan desimal dengan basis 16, kemudian mengambil sisa dari setiap pembagian dan menuliskannya secara berurutan dari bawah ke atas. Untuk digit heksadesimal dengan nilai lebih besar dari 9, digunakan huruf A hingga F sebagai pengganti.

Berikut adalah langkah-langkah konversi bilangan desimal ke bilangan heksadesimal:

1. Bagi bilangan desimal dengan 16 dan simpan hasil bagi serta sisanya.
2. Jika hasil bagi lebih besar dari 0, ulangi proses pembagian dengan hasil bagi sebagai bilangan desimal. Jika tidak, proses konversi selesai.
3. Untuk digit heksadesimal dengan nilai lebih besar dari 9, gunakan huruf A hingga F sebagai pengganti.
4. Urutkan sisa-sisa yang didapat dari bawah ke atas untuk membentuk bilangan heksadesimal.

Contoh:
Konversi bilangan desimal 456 ke bilangan heksadesimal:

- 456 ÷ 16 = 28 sisa 8
- 28 ÷ 16 = 1 sisa 12 (menggunakan C sebagai pengganti)
- 1 ÷ 16 = 0 sisa 1

Sehingga, bilangan desimal 456 dalam basis heksadesimal adalah 1C8.

Dalam representasi bilangan heksadesimal, setiap digit merepresentasikan kelipatan dari 16 mulai dari pangkat 0 pada digit paling kanan. Sebagai contoh, bilangan heksadesimal 1C8 dapat dipecah menjadi:

- 1 x 16{^2} = 256
- 12 x 16{^1} = 192
- 8 x 16{^0} = 8

Sehingga, bilangan heksadesimal 1C8 dapat dikonversi menjadi bilangan desimal 456.

***Tabel Konversi Bilangan Desimal ke Heksadesimal***

|Desimal|Heksadesimal|
|:-----:|:-----------|
|0  |  0 |
|1  |  1 |
|2  |  2 |
|3  |  3 |
|4  |  4 |
|5  |  5 |
|6  |  6 |
|7  |  7 |
|8  |  8 |
|9  |  9 |
|10 |  A |
|11 |  B |
|12 |  C |
|13 |  D |
|14 |  E |
|15 |  F |

### Konversi Bilangan Heksadesimal ke Bilangan Desimal

Konversi bilangan heksadesimal ke bilangan desimal melibatkan mengalikan setiap digit heksadesimal dengan basis 16 yang dinaikkan ke pangkat yang sesuai, kemudian menjumlahkan hasil kali tersebut.

Berikut adalah langkah-langkah konversi bilangan heksadesimal ke bilangan desimal:

1. Identifikasi setiap digit heksadesimal dan tentukan nilai numeriknya. Untuk digit heksadesimal dengan nilai lebih besar dari 9, gunakan huruf A hingga F sebagai pengganti.
2. Hitung nilai dari setiap digit heksadesimal dengan mengalikannya dengan basis 16 yang dinaikkan ke pangkat yang sesuai.
3. Jumlahkan hasil kali tersebut untuk mendapatkan nilai bilangan desimal.

Contoh:
Konversi bilangan heksadesimal 1C8 ke bilangan desimal:

1. Digit pertama adalah 1, yang merepresentasikan nilai 1.
2. Digit kedua adalah C, yang merepresentasikan nilai 12.
3. Digit ketiga adalah 8, yang merepresentasikan nilai 8.
4. Hitung nilai setiap digit dengan mengalikannya dengan basis 16 yang dinaikkan ke pangkat yang sesuai:

- 1 x 16{^2} = 256
- 12 x 16{^1} = 192
- 8 x 16{^0} = 8

Jumlahkan hasil kali tersebut: 256 + 192 + 8 = 456.
Sehingga, bilangan heksadesimal 1C8 dalam basis desimal adalah 456.

### Konversi Bilangan Biner ke Bilangan Heksadesimal

Untuk mengonversi bilangan biner 4 bit ke bilangan heksadesimal, kita perlu membagi bit biner menjadi kelompok-kelompok, yaitu per 4 bit, kemudian mengonversikan setiap kelompok bit menjadi bilangan heksadesimal.

Berikut adalah langkah-langkah konversi bilangan biner 4 bit ke bilangan heksadesimal:

1. Bagi bilangan biner menjadi kelompok per 4 bit dari kanan ke kiri.
2. Konversikan setiap kelompok empat bit ke bilangan heksadesimal yang setara.
3. Susun setiap bilangan heksadesimal dari kanan ke kiri untuk membentuk bilangan heksadesimal akhir.

***Tabel Konversi Bilangan Biner (4 Bit) ke Heksadesimal***

|Bilangan Biner|Bilangan Heksadesimal|
|:---:|:---:|
|0000|0|
|0001|1|
|0010|2|
|0011|3|
|0100|4|
|0101|5|
|0110|6|
|0111|7|
|1000|8|
|1001|9|
|1010|A|
|1011|B|
|1100|C|
|1101|D|
|1110|E|
|1111|F|

Contoh:

1. Biner : 11111111 --> 1111 1111\
Heksadesimal : FF
2. Biner : 11111101 --> 1111 1101\
Heksadesimal : FD
3. Biner : 10011101 --> 1001 1101\
Heksadesimal : 9D

{{< adsense >}}
