# Tutorial for Advance Programming Course 2023/2024

**Nama** : **Restu Ahmad Ar Ridho** <br/>
**NPM** : **2206028951** <br/>
**Kelas** : **Advance Programming - A**

## Module 10 - Asynchoronous Programming - Chat Async

#### Experiment 2.1: Original code, and how it run
![](static/images/first.png)
Seperti yang terlihat dari hasil output di atas, setelah server dijalankan menggunakan perintah `cargo run --bin server` dan tiap-tiap klien dijalankan dengan perintah `cargo run --bin client`, masing-masing klien dan server menerima pesan yang disiarkan dari klien lainnya. Setiap kali suatu klien mengetikkan pesan di baris perintah, pesan tersebut dikirimkan ke server, yang kemudian menyebarkannya ke semua klien yang terhubung. Dengan demikian, semua klien dapat melihat pesan-pesan yang dikirim oleh klien lainnya secara real-time.