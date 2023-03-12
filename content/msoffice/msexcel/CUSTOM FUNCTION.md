---
title: "CUSTOM FUNCTION"
date: 2023-03-12T11:55:38+07:00
draft: false
weight: 0
---

## Cara Membuat Rumus atau Function sendiri di Excel

Anda dapat membuat fungsi sendiri di Excel menggunakan Visual Basic for Applications (VBA). Berikut adalah langkah-langkahnya:

1. Buka Excel dan tekan Alt + F11 untuk membuka Editor VBA.
2. Di jendela Project Explorer, klik kanan pada nama workbook Anda dan pilih Insert > Module untuk menambahkan modul baru.
3. Mulailah menulis kode VBA Anda di dalam modul.
4. Beri nama fungsi Anda dengan menggunakan sintaks Function dan End Function, dan masukkan kode di antara keduanya. Pastikan untuk menyertakan deskripsi fungsi di awal kode menggunakan sintaks Comment.
5. Simpan modul dan kembali ke workbook Excel Anda.
6. Panggil fungsi yang baru saja Anda buat di dalam sel atau dalam formula di sel lain.

Berikut adalah contoh pembuatan fungsi sederhana menggunakan VBA di Excel:

1. Buka Excel dan tekan Alt + F11 untuk membuka Editor VBA.
2. Di jendela Project Explorer, klik kanan pada nama workbook Anda dan pilih Insert > Module.
{{< figure src="/img/excel 1 vba new module.png" link="/img/excel 1 vba new module.png" caption="***VBA New Module***" alt="VBA New Module" >}}
3. Ketik kode berikut ini di dalam modul:
{{< highlight go >}}
Function LuasPersegiPanjang(p, l)
    LuasPersegiPanjang = p * l
End Function
{{< / highlight >}}
{{< figure src="/img/excel 2 vba function.png" link="/img/excel 2 vba function.png" caption="***VBA New Module***" alt="Module Function" >}}

4. Simpan modul dan kembali ke workbook Excel Anda.
5. Di dalam sel, ketik `=LuasPersegiPanjang(5, 10)` untuk menghitung luas persegi panjang dengan panjang 5 dan lebar 10.
{{< figure src="/img/excel 4 rumus 2.png" link="/img/excel 4 rumus 2.png" caption="***VBA New Module***" alt="Module Function" >}}
6. Tekan Enter, maka hasilnya akan muncul di dalam sel.
{{< figure src="/img/excel 5 hasil.png" link="/img/excel 5 hasil.png" caption="***VBA New Module***" alt="Module Function" >}}