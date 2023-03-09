---
title: "IF"
date: 2023-03-09T22:50:31+07:00
draft: false
weight: 8
categories:
    - Microsoft Excel
tags:
    - IF
description: >
    Formula IF pada Excel digunakan untuk menghasilkan nilai berdasarkan kondisi tertentu; berguna untuk membuat perhitungan logika pada data numerik atau teks
---

Formula IF pada Excel digunakan untuk menghasilkan nilai berdasarkan kondisi tertentu. Formula ini berguna untuk membuat perhitungan logika pada data numerik atau teks.

Berikut adalah sintaks dari formula IF pada Excel:

{{< highlight go >}}
=IF(logical_test, [value_if_true], [value_if_false])
{{< / highlight >}}

- `logical_test` adalah kondisi yang ingin diuji, misalnya apakah nilai lebih besar dari angka tertentu.
- `[value_if_true]` adalah nilai yang akan muncul jika kondisi dalam logical_test terpenuhi.
- `[value_if_false]` adalah nilai yang akan muncul jika kondisi dalam logical_test tidak terpenuhi.

Tips penggunaan formula IF pada Excel:

- Gunakan tanda `$` pada range nilai yang ingin digunakan dalam kondisi logical_test agar dapat digunakan pada sel yang berbeda.
- Pastikan nilai yang digunakan dalam kondisi logical_test telah sesuai dengan format data, misalnya untuk nilai teks diapit dengan tanda petik dua (").
- Formula IF juga dapat digunakan secara bertingkat (nested) untuk membuat perhitungan logika yang lebih kompleks.

Contoh penggunaan formula IF pada Excel:

Misalnya, kita ingin menghasilkan nilai "Lulus" jika nilai dalam sel A1 lebih besar atau sama dengan 70 dan nilai "Tidak Lulus" jika nilai dalam sel A1 kurang dari 70. Maka sintaks yang digunakan adalah sebagai berikut:

{{< highlight go >}}
=IF(A1>=70, "Lulus", "Tidak Lulus")
{{< / highlight >}}

Jika nilai dalam sel A1 adalah 80, maka hasil formula akan menjadi "Lulus". Jika nilai dalam sel A1 adalah 60, maka hasil formula akan menjadi "Tidak Lulus".

Selain itu, kita juga dapat menggunakan formula IF secara bertingkat (nested) untuk membuat perhitungan logika yang lebih kompleks seperti contoh berikut:

{{< highlight go >}}
=IF(A1>=90, "A", IF(A1>=80, "B", IF(A1>=70, "C", IF(A1>=60, "D", "E"))))
{{< / highlight >}}

Formula tersebut akan menghasilkan nilai "A" jika nilai dalam sel A1 lebih besar atau sama dengan 90, nilai "B" jika nilai dalam sel A1 lebih besar atau sama dengan 80, dan seterusnya hingga nilai "E" jika nilai dalam sel A1 kurang dari 60.
