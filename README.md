Nama : Reza Afzaal Faizullah Taqy <br>
NRP : 5025241051 <br>
Kelas : A <br>

<img width="478" height="477" alt="image" src="https://github.com/user-attachments/assets/855b4183-62b9-48a8-92e3-287385be658b" />
<img width="841" height="759" alt="image" src="https://github.com/user-attachments/assets/e60006b3-080b-4514-9348-1ba130ff1373" />

1. Kelas Review

Kelas ini merepresentasikan satu ulasan pengguna.
Fitur utama:

Menyimpan user, komentar, rating

Menyimpan waktu pembuatan review (timestamp)

Mendukung upvote dan downvote

Menghitung vote balance melalui getScore()

Method print() untuk menampilkan detail review

Kelas ini menjadi blueprint dari setiap komentar yang diberikan.

2. Kelas Product

Kelas ini merepresentasikan produk yang memiliki:

Nama produk

Harga

Daftar review

Fungsi yang disediakan:

addReview() → menambah review dengan validasi:

Rating harus 1–5

User tidak boleh komentar dua kali

getReviewByUser() → mengambil review berdasarkan nama user

getMostHelpfulReview() → mencari review dengan vote balance tertinggi

getAverageRating() → menghitung rata-rata rating

showDetails() → menampilkan informasi produk & semua review

3. Kelas ProductReviewTest

Kelas ini berfungsi sebagai program penguji (tester).
Di dalamnya dilakukan:

Pembuatan objek produk

Penambahan beberapa review

Pengujian validasi rating dan komentar ganda

Memberikan upvote/downvote pada review tertentu

Menampilkan review paling membantu

Menampilkan informasi lengkap produk

Kelas ini memastikan semua fitur bekerja sesuai desain.

4. Kesimpulan

Melalui pembuatan program ini, konsep OOP seperti enkapsulasi, objek, method, validasi data, dan interaksi antar kelas dapat dipahami lebih dalam. Program berhasil mensimulasikan sistem review sederhana dengan fitur yang cukup realistis, seperti rating, komentar unik per user, serta voting.
