# Website-Toko-Sepatu-Online-Aerostreet-Bootstrap-oleh-Kelompok-3-Universitas-Pamulang---05TPLP009
Selamat datang di proyek **Aerostreet**, sebuah website toko sepatu online yang dirancang untuk memberikan pengalaman belanja sepatu modern, praktis, dan responsif. Proyek ini dikembangkan oleh **Kelompok 3 Universitas Pamulang** sebagai bagian dari tugas mata kuliah *Pemrograman Web 1*, di bawah bimbingan **Ari Syaripudin, S.Kom., M.Kom. (0406028802)**.

Website ini mengintegrasikan teknologi Bootstrap untuk tampilan yang elegan dan fungsional, lengkap dengan fitur-fitur canggih yang menjadikan belanja sepatu lebih mudah, baik untuk pengguna maupun admin toko.

---

## 🎯 Tujuan Proyek
1. Membangun platform online untuk mempermudah penjualan sepatu Aerostreet.
2. Memberikan pengalaman pengguna yang menyenangkan dengan desain modern dan responsif.
3. Mempermudah admin dalam mengelola produk dan pesanan.

---

## 👥 Tim Pengembang
- **Miftah Fathu Ramadhan** - Pengembang Halaman Utama (*Landing Page*).
- **Muhammad Micko Biagi** - Spesialis Formulir Pemesanan.
- **Farhan Asshadath** - Pengembang Keamanan Login Admin.
- **Mu’ammar Kurniawan** - Pengembang CRUD Dashboard Produk.

---

## ✨ Fitur Utama
1. **Landing Page Interaktif**  
   Halaman utama yang menampilkan koleksi sepatu Aerostreet dengan desain visual menarik, dikembangkan oleh **Miftah Fathu Ramadhan**. Terdapat navigasi sederhana dan promo menarik untuk menarik perhatian pelanggan.

2. **Form Pemesanan Simpel**  
   Pengguna dapat memesan sepatu dengan mudah melalui formulir yang dirancang oleh **Muhammad Micko Biagi**, mencakup detail pesanan dan informasi pelanggan.

3. **Sistem Login Admin Aman**  
   Dikembangkan oleh **Farhan Asshadath**, sistem ini memastikan bahwa hanya admin resmi yang dapat mengakses dashboard untuk pengelolaan data.

4. **CRUD Dashboard yang Efisien**  
   Admin dapat dengan mudah menambah, mengedit, dan menghapus produk sepatu melalui dashboard responsif yang dikembangkan oleh **Mu’ammar Kurniawan**.

---

## 🗂 Struktur Folder
- **`admin/`**  
  Berisi file backend untuk pengelolaan data admin, produk, dan fitur CRUD.
  - `produk.php`: Menampilkan daftar produk di dashboard admin.
  - `edit-produk.php`: Halaman untuk mengedit produk.
  - `hapus-produk.php`: Proses penghapusan produk.

- **`db/`**  
  Konfigurasi database untuk koneksi aplikasi.
  - `koneksi.php`: Skrip koneksi MySQL.

- **`assets/`**  
  Menyimpan aset visual (gambar, ikon, produk).
  - `icon/`: Logo toko.
  - `img/`: Gambar pendukung.
  - `produk/`: Gambar produk.

- **`css/`**  
  Berisi file gaya (*stylesheets*).
  - `bootstrap.min.css`: Framework Bootstrap.
  - `style.css`: Kustomisasi tambahan.

- **`js/`**  
  Berisi file JavaScript untuk fitur dinamis.
  - `bootstrap.bundle.min.js`: Skrip untuk komponen interaktif Bootstrap.

---

## 📜 Cara Menjalankan Proyek
1. Clone repository ini ke komputer lokal:  
   ```bash
   git clone https://github.com/aamarkurniawan/Website-Toko-Sepatu-Online-Aerostreet-Bootstrap-oleh-Kelompok-3-Universitas-Pamulang---05TPLP009.git

2. **Konfigurasi file database di `db/koneksi.php`**  
   Buka file `db/koneksi.php` dan lakukan pengaturan sesuai dengan server lokal Anda:
   - **Host**: Gunakan `localhost`.
   - **Username**: Untuk server lokal seperti XAMPP, biasanya menggunakan `root`.
   - **Password**: Kosong (default untuk XAMPP).
   - **Database**: Masukkan nama database yang sudah Anda buat di phpMyAdmin.

3. **Jalankan proyek di server lokal seperti XAMPP atau Laragon**  
   - Tempatkan folder proyek ini ke dalam direktori `htdocs` (untuk XAMPP) atau direktori yang sesuai untuk server lainnya.  
   - Aktifkan layanan **Apache** dan **MySQL** melalui panel kontrol server.  
   - Buka phpMyAdmin di browser Anda dan buat database baru.  
   - Impor file database (jika tersedia), atau buat tabel sesuai kebutuhan aplikasi.  
   - Pastikan konfigurasi database sudah benar di `db/koneksi.php`.

4. **Akses halaman utama melalui browser**  
   - Ketikkan alamat berikut di browser:  
     ```
     http://localhost/toko-online/
     ```
   - Mulai eksplorasi fitur-fitur yang tersedia seperti landing page, formulir pemesanan, dan dashboard admin untuk pengelolaan produk.

---

## 🎥 Preview
- **Landing Page**: Halaman utama dengan desain modern dan interaktif, menampilkan koleksi sepatu terbaik Aerostreet.  
- **Form Pemesanan**: Formulir sederhana yang memudahkan pelanggan untuk memesan sepatu favorit.  
- **Dashboard Admin**: Sistem lengkap untuk admin mengelola produk dengan fitur CRUD (Create, Read, Update, Delete).

---

## ❤️ Ucapan Terima Kasih
Proyek ini tidak hanya membantu kami mengembangkan kemampuan dalam pemrograman web, tetapi juga mempererat kerja sama tim. Kami berterima kasih kepada **Ari Syaripudin, S.Kom., M.Kom.**, yang telah memberikan bimbingan selama proses pengerjaan tugas ini.

Dibuat dengan penuh dedikasi oleh **Kelompok 3 Universitas Pamulang**.
