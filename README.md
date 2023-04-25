## Janji
Saya Ananda Myzza Marhelio NIM 2100702 mengerjakan soal Latihan 7 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Deskripsi Tugas Latihan 7 DPBO 2023
Modifikasi kode yang sudah diberikan, dengan ketentuan sebagai berikut:
* Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
* Skor hanya bertambah jika pemain berbelok, bukan bergerak berurutan. Detail:
  - Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.
  - Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).
  - Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.
  - Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.
* **[BONUS]** Buatlah sistem game yang menambahkan satu kotak atau objek apapun secara acak. Jika pemain menyentuh objek tersebut, skor bertambah +5 atau +10, lalu objek akan berpindah lagi ke posisi lain secara acak.
* Belajar untuk meng-compile secara manual, bukan di-run via IDE. Hal ini bertujuan untuk membantu saat presentasi TMD nanti.

## Alur Program
Pengguna dapat menggerakkan objek lingkaran menggunakan tombol WASD pada keyboard. Score akan bertambah +1 jika pengguna menggerakan objek tersebut, namun score tidak akan bertambah jika pengguna menekan tombol yang sama setelahnya, sehingga score hanya akan bertambah +1 jika pengguna terus menekan tombol yang berbeda sesuai dengan ketentuan soal.

## Dokumentasi
![Dokumentasi](https://github.com/anandamyzza/LP7C2DPBO2023/blob/main/Dokumentasi.mp4?raw=true)
