📚 Perpustakaan SMA 1 BLP

Sistem Informasi Perpustakaan SMA 1 BLP merupakan aplikasi berbasis web yang dibuat untuk membantu pengelolaan perpustakaan secara lebih mudah, cepat, dan terstruktur.

Website ini dapat digunakan untuk mengelola data buku, anggota, peminjaman, pengembalian, serta informasi perpustakaan.

🌐 Demo Website

Website: "https://perpustakaan-sma1blp.free.nf"

✨ Fitur

- 🏠 Halaman beranda
- 📚 Data dan katalog buku
- 👨‍🎓 Data anggota perpustakaan
- 📖 Peminjaman buku
- 🔄 Pengembalian buku
- 📋 Riwayat peminjaman
- 🔍 Pencarian buku
- 👤 Login pengguna/admin
- ⚙️ Pengelolaan data perpustakaan
- 📊 Informasi dan laporan perpustakaan

🛠️ Teknologi

Project ini menggunakan beberapa teknologi berikut:

- HTML5 — struktur halaman website
- CSS3 — desain dan tampilan
- JavaScript — interaksi pada halaman
- PHP — backend dan proses sistem
- MySQL — database
- XAMPP — server lokal saat proses pengembangan

📁 Struktur Project

perpustakaan-sma1blp/
│
├── index.php
├── login.php
├── dashboard.php
├── buku.php
├── anggota.php
├── peminjaman.php
├── pengembalian.php
├── koneksi.php
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── img/
│   └── ...
│
└── database/
    └── perpustakaan.sql

«Struktur folder dapat disesuaikan dengan struktur project yang sebenarnya.»

🗄️ Database

Database digunakan untuk menyimpan seluruh data yang diperlukan oleh sistem perpustakaan.

Contoh tabel:

Tabel| Keterangan
"users"| Data pengguna/admin
"buku"| Data koleksi buku
"anggota"| Data anggota
"peminjaman"| Data transaksi peminjaman
"pengembalian"| Data transaksi pengembalian

🚀 Instalasi

1. Clone atau download project

git clone https://github.com/username/perpustakaan-sma1blp.git

2. Pindahkan project

Jika menggunakan XAMPP, letakkan folder project ke:

C:/xampp/htdocs/

3. Jalankan XAMPP

Aktifkan:

- Apache
- MySQL

4. Buat database

Buka:

http://localhost/phpmyadmin

Buat database, kemudian import file:

database/perpustakaan.sql

5. Atur koneksi database

Sesuaikan konfigurasi pada file:

koneksi.php

Contoh:

$host = "localhost";
$user = "root";
$password = "";
$database = "perpustakaan";

6. Jalankan website

Buka browser dan akses:

http://localhost/perpustakaan-sma1blp/

👨‍💻 Pengembangan

Project ini dikembangkan sebagai project Rekayasa Perangkat Lunak (RPL) untuk menerapkan konsep pengembangan aplikasi berbasis web, database, serta sistem informasi.

🎯 Tujuan

Tujuan dibuatnya sistem ini adalah:

1. Mempermudah pengelolaan data buku.
2. Mempermudah proses peminjaman dan pengembalian.
3. Mengurangi pencatatan secara manual.
4. Mempermudah pencarian informasi buku.
5. Membantu pengelola perpustakaan dalam mengelola data.

📌 Status Project

Status: "Development / Pengembangan"

Project masih dapat dikembangkan dengan menambahkan fitur baru seperti notifikasi peminjaman, denda keterlambatan, laporan PDF, dashboard statistik, dan sistem role pengguna.

📄 Lisensi

Project ini dibuat untuk keperluan pembelajaran dan pengembangan sistem informasi perpustakaan SMA 1 BLP.

---

👥 Developer

Perpustakaan SMA 1 BLP

«Sistem Informasi Perpustakaan Berbasis Web»
