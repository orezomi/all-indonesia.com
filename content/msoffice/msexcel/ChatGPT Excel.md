---
title: "ChatGPT Excel"
date: 2023-03-15T16:04:44+07:00
weight: 16
categories:
    - Microsoft Excel
tags:
    - CUSTOM FUNCTION
    - Addins
    - Chat GPT
description: >
    Anda dapat membuat fungsi Chat GPT di Ms Excel ataupun di Google Spreadsheet, ikuti langkah-langkah berikut
---

## API OpenAI di Excel dan Google Spreadsheet

### Penggunaan API OpenAI di Excel

Untuk menggunakan API OpenAI di Microsoft Excel, Anda dapat mengikuti langkah-langkah berikut:

1. Pastikan Anda memiliki akun OpenAI dan mengaktifkan API OpenAI.

2. Buka Microsoft Excel dan buat lembar kerja baru.

3. Pilih tab "Developer" di menu atas. Jika tab "Developer" tidak muncul, aktifkan terlebih dahulu dengan cara klik "File" > "Options" > "Customize Ribbon" > pilih "Developer" pada pilihan "Main Tabs" > klik "OK".

4. Pilih opsi "Visual Basic" pada grup "Code" di tab "Developer" untuk membuka editor VBA.

5. Di editor VBA, pilih menu "Tools" > "References".

6. Pilih "Microsoft WinHTTP Services, version 5.1" pada daftar referensi dan klik "OK".

Di dalam editor VBA, buat fungsi atau prosedur VBA yang memanggil API OpenAI menggunakan koneksi HTTP. Misalnya, Anda dapat membuat prosedur VBA yang memanggil API OpenAI untuk menghasilkan teks yang dihasilkan oleh model bahasa GPT-3.

Berikut adalah contoh kode VBA yang dapat Anda gunakan untuk memanggil API OpenAI:
{{< highlight go >}}
Sub callOpenAI()
    Dim sURL As String
    Dim sApiKey As String
    Dim oRequest As Object
    Dim sResult As String

    //Replace with your OpenAI API key
    sApiKey = "your-api-key-here"
    
    //Replace with your preferred API endpoint
    sURL = "https://api.openai.com/v1/engines/davinci-codex/completions"
    
    //Set up HTTP request object
    Set oRequest = CreateObject("WinHttp.WinHttpRequest.5.1")
    
    //Set request headers
    oRequest.Open "POST", sURL, False
    oRequest.SetRequestHeader "Content-Type", "application/json"
    oRequest.SetRequestHeader "Authorization", "Bearer " & sApiKey
    
    //Set request body with parameters for GPT-3 model
    oRequest.Send "{""prompt"":""Hello, I'm testing GPT-3 API."",""max_tokens"":100,""temperature"":0.5}"
    
    //Get response from API endpoint
    sResult = oRequest.ResponseText
    
    //Output result to cell A1 in current sheet
    Range("A1").Value = sResult
End Sub
{{< / highlight >}}

Pastikan Anda mengganti nilai variabel `sApiKey` dengan kunci API OpenAI Anda sendiri, dan variabel `sURL` dengan URL API OpenAI yang ingin Anda panggil.

Setelah menulis kode VBA, jalankan prosedur tersebut dengan menekan tombol F5 atau pilih "Run" pada menu atas. Hasil dari API OpenAI akan ditampilkan di dalam sel di worksheet Excel yang aktif.

Namun, perlu diingat bahwa penggunaan API OpenAI memerlukan pengetahuan tentang pemrograman dan koneksi internet yang stabil. Selain itu, Anda juga harus mematuhi aturan dan kebijakan penggunaan API OpenAI.

### Penggunaan API OpenAI di Google Spreadsheet

Untuk menggunakan API OpenAI di Google Spreadsheet, Anda dapat mengikuti langkah-langkah berikut:

1. Buka Google Spreadsheet yang ingin Anda gunakan untuk mengakses API OpenAI.
2. Buka menu "Tools" dan pilih "Script Editor".
3. Di editor skrip, klik "File" dan pilih "New Project".
4. Beri nama proyek dan klik "Create".
5. Selanjutnya, masukkan kode untuk menggunakan API OpenAI. Berikut ini adalah contoh kode untuk mengambil respons dari GPT-3 API OpenAI:
{{< highlight go >}}
function getGpt3Response(prompt) {
  var apiKey = 'YOUR_API_KEY_HERE';
  var apiUrl = 'https://api.openai.com/v1/engines/davinci-codex/completions';

  var headers = {
    'Content-Type': 'application/json',
    'Authorization': 'Bearer ' + apiKey
  };

  var data = {
    'prompt': prompt,
    'max_tokens': 10,
    'n': 1,
    'stop': '\n'
  };

  var options = {
    'method': 'POST',
    'headers': headers,
    'payload': JSON.stringify(data)
  };

  var response = UrlFetchApp.fetch(apiUrl, options);
  var json = JSON.parse(response.getContentText());

  return json.choices[0].text;
}
{{< / highlight >}}
6. Ganti `YOUR_API_KEY_HERE` dengan API key OpenAI Anda.
7. Simpan kode dan kembali ke spreadsheet.
8. Sekarang Anda dapat menggunakan fungsi `getGpt3Response()` di sel-sel spreadsheet untuk mengambil respons dari API OpenAI. Contohnya, Anda dapat mengetikkan `=getGpt3Response("What is the capital of Indonesia?")` di sel dan akan mengembalikan jawaban dari API.

Harap dicatat bahwa penggunaan API OpenAI memerlukan biaya dan perlu memastikan bahwa penggunaan Anda mematuhi ketentuan layanan dan kebijakan privasi dari OpenAI.
