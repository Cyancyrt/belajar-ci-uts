# Proyek Toko

Ini adalah proyek sederhana aplikasi toko berbasis web menggunakan CodeIgniter 4. Proyek ini dibuat untuk memenuhi tugas kuliah pada mata kuliah Pemrograman Web Lanjut.

## 📌 Fitur

Beberapa fitur yang sudah tersedia dalam aplikasi ini antara lain:

- Login dan Logout untuk pengguna
- Hak akses berdasarkan role (admin dan user)
- Dashboard dengan informasi transaksi
- Manajemen kategori produk (tambah, edit, hapus)
- Manajemen produk (tambah, edit, hapus, termasuk foto)
- Transaksi pembelian produk
- Riwayat transaksi pengguna
- Fitur diskon otomatis
- Halaman profil untuk melihat riwayat pembelian
- API endpoint (`/api`) untuk mendapatkan data transaksi dan detailnya (dengan API Key)

## ⚙️ Installasi

Berikut langkah-langkah untuk menjalankan proyek ini:

1. Clone repository:

   ```bash
   git clone https://github.com/Cyancyrt/belajar-ci-uts.git

   ```

2. composer install

3. php spark migrate

4. php spark db:seed UserSeeder
   php spark db:seed ProductCategorySeeder.php
   php spark db:seed ProductSeeder
   php spark db:seed Diskon

5. php spark serve

6. akses di http://localhost:8081/
   ```

   ```

## 🗂️ STRUKTUR PROYEK

/app
/Controllers -> Logic backend, seperti Auth, Produk, Transaksi
/Models -> Berisi file model database (ProductModel, UserModel, dll)
/Views -> File tampilan (HTML+PHP), seperti halaman utama, login, dashboard
/Database
/Migrations -> File migrasi untuk membuat tabel
/Seeds -> File seeder untuk isi data awal
/public -> Folder publik (CSS, JS, gambar, index.php)
/writable -> Cache, logs, session
/.env -> File konfigurasi lingkungan (tidak dikomit ke git)


Terima kasih sudah membaca. Kalau ada error, mungkin saya juga belum tahu 😅
