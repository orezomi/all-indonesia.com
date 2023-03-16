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
