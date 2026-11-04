# App Perpustakaan

## Deskripsi & Tujuan Aplikasi
**App Perpustakaan** adalah aplikasi sistem informasi manajemen perpustakaan berbasis web yang dibangun menggunakan framework Laravel 12. Aplikasi ini bertujuan untuk mempermudah pengelolaan inventaris buku, pencatatan transaksi peminjaman dan pengembalian, serta administrasi data anggota perpustakaan secara terstruktur dan efisien.

## Cara Menjalankan Project Secara Lokal

1. **Clone repository ke komputer lokal:**
   `git clone https://github.com/bintangnasaa/app-perpustakaan.git`
   `cd app-perpustakaan`

2. **Install dependensi PHP dan JavaScript:**
   `composer install`
   `npm install`

3. **Konfigurasi file environment dan application key:**
   `cp .env.example .env`
   `php artisan key:generate`

4. **Jalankan migrasi database dan server lokal:**
   `php artisan migrate`
   `php artisan serve`

5. **Akses aplikasi melalui browser:**
   Buka `http://127.0.0.1:8000` di browser.

## Perbedaan Model, View, dan Controller (MVC)
**Model** adalah komponen yang merepresentasikan struktur data dan berhubungan langsung dengan database untuk mengelola penyimpanan, pengambilan, maupun pembaruan data. **View** merupakan bagian antarmuka pengguna (UI) yang bertugas menampilkan informasi atau data dalam bentuk halaman web yang interaktif. **Controller** bertindak sebagai penghubung yang menerima permintaan (request) dari pengguna, mengolah logika aplikasi bersama Model, lalu meneruskan hasilnya ke View untuk ditampilkan.
