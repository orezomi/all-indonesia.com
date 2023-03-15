---
title: "TERBILANG"
date: 2023-03-15T13:11:32+07:00
draft: false
weight: 14
categories:
    - Microsoft Excel
tags:
    - CUSTOM FUNCTION
description: >
    Fungsi Terbilang merupakan custom function di Excel untuk mengubah angka menjadi terbilang menggunakan VBA (Visual Basic for Applications)
---

Anda dapat membuat custom function di Excel untuk mengubah angka menjadi terbilang menggunakan VBA (Visual Basic for Applications). Berikut ini adalah contoh kode VBA untuk custom function Excel untuk terbilang:

{{< highlight go >}}
Function Terbilang(ByVal X As Double) As String
    Dim bilangan As Variant
    Dim temp As Variant
    Dim xstr As String
    Dim i As Integer
    Dim j As Integer
    Dim hasil As String
    Dim Angka(0 To 11) As String
    Angka(0) = ""
    Angka(1) = "satu"
    Angka(2) = "dua"
    Angka(3) = "tiga"
    Angka(4) = "empat"
    Angka(5) = "lima"
    Angka(6) = "enam"
    Angka(7) = "tujuh"
    Angka(8) = "delapan"
    Angka(9) = "sembilan"
    Angka(10) = "sepuluh"
    Angka(11) = "sebelas"
    xstr = CStr(X)
    bilangan = Split(xstr, ".")
    If (Val(xstr) >= 0 And Val(xstr) <= 11) Then
        hasil = Angka(Val(xstr))
    ElseIf (Val(xstr) >= 12 And Val(xstr) <= 19) Then
        hasil = Terbilang(Val(xstr) - 10) & " belas "
    ElseIf (Val(xstr) >= 20 And Val(xstr) <= 99) Then
        hasil = Terbilang(Int(xstr / 10)) & " puluh " & Terbilang(xstr Mod 10)
    ElseIf (Val(xstr) >= 100 And Val(xstr) <= 199) Then
        hasil = "seratus " & Terbilang(xstr Mod 100)
    ElseIf (Val(xstr) >= 200 And Val(xstr) <= 999) Then
        hasil = Terbilang(Int(xstr / 100)) & " ratus " & Terbilang(xstr Mod 100)
    ElseIf (Val(xstr) >= 1000 And Val(xstr) <= 1999) Then
        hasil = "seribu " & Terbilang(xstr Mod 1000)
    ElseIf (Val(xstr) >= 2000 And Val(xstr) <= 999999) Then
        hasil = Terbilang(Int(xstr / 1000)) & " ribu " & Terbilang(xstr Mod 1000)
    ElseIf (Val(xstr) >= 1000000 And Val(xstr) <= 999999999) Then
        hasil = Terbilang(Int(xstr / 1000000)) & " juta " & Terbilang(xstr Mod 1000000)
    End If
    Terbilang = hasil
End Function
{{< / highlight >}}

Setelah kode tersebut ditambahkan, Anda dapat menggunakan fungsi `Terbilang` di dalam rumus Excel untuk mengubah angka menjadi terbilang. Misalnya, untuk mengubah angka 1234 menjadi terbilang, cukup gunakan rumus `=Terbilang(1234)` di sel Excel.
