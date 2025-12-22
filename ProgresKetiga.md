# PRAKTIKUM 13: PROGRES TUBES 3 - APLIKASI CAFELORA

# 📃 Identitas Diri

- **Kelompok**         : Kelompok 1
- **Anggota Kelompok** : 
  1. Arya Wicaksana Putra (4520210092)
  2. Aditya Nur Lintang (4523210003)
  3. Alip Khoeril Akbar (4523210009)
  4. Muhammad Fauzan (4523210073)
  5. Revalina Adelia (4523210091)
  6. Chaerul Cahyadi (4523210120)
- **Mata Kuliah**      : Pemrograman Berbasis Web (A)
- **Dosen Pengampu**   : Adi Wahyu Pribadi, S.Si., M.Kom.
- **Topik Proyek**     : Cafe

---
# Latar Belakang

Perkembangan teknologi informasi telah membawa perubahan dalam berbagai sektor usaha, termasuk pada bidang kuliner dan kafe. Kafe sebagai usaha jasa dituntut untuk mampu memberikan pelayanan yang cepat, akurat, dan efisien guna meningkatkan kepuasan pelanggan serta mendukung kelancaran operasional. Dalam aktivitas sehari-hari, kafe melibatkan proses penyajian informasi menu, pencatatan pesanan, transaksi pembayaran, hingga pengelolaan data penjualan. Apabila proses tersebut masih dilakukan secara manual atau tidak terintegrasi, maka berpotensi menimbulkan permasalahan seperti kesalahan pencatatan, keterlambatan pelayanan, serta kesulitan dalam penyusunan laporan penjualan.

Selain itu, perubahan perilaku pelanggan yang semakin terbiasa dengan pembayaran digital menuntut kafe untuk menyediakan metode pembayaran yang lebih fleksibel. Keterbatasan sistem pembayaran yang hanya mengandalkan transaksi tunai dapat mengurangi kenyamanan pelanggan dan memperlambat proses transaksi. Di sisi lain, pengelola kafe juga menghadapi kendala dalam memantau stok, mengevaluasi performa penjualan harian maupun bulanan, serta mengambil keputusan berdasarkan data yang akurat apabila belum didukung oleh sistem yang terstruktur.

Berdasarkan permasalahan tersebut, diperlukan sebuah sistem aplikasi yang mampu mengintegrasikan seluruh proses operasional kafe dalam satu platform yang terpusat dan mudah digunakan. Oleh karena itu, dibuatlah Cafelora, yaitu sistem yang dirancang untuk mendukung operasional kafe modern melalui sistem pemesanan, transaksi, dan pengelolaan data yang terintegrasi. Cafelora menyediakan tampilan menu yang informatif bagi pelanggan, sistem Point of Sale (POS) yang terstruktur untuk kasir, serta dukungan pembayaran non-tunai melalui integrasi payment gateway. Dengan adanya aplikasi ini, diharapkan proses pelayanan kafe dapat berjalan lebih efisien, akurat, dan responsif, sekaligus membantu pengelola kafe dalam meningkatkan kualitas layanan dan efektivitas operasional secara keseluruhan.

---
# Tujuan Proyek

Tujuan dari pembuatan aplikasi *Cafelora* adalah sebagai berikut:
1. Membuat sistem aplikasi yang mampu mendukung operasional kafe secara terintegrasi dan terstruktur.
2. Menyediakan sistem pemesanan dan transaksi yang cepat, akurat, serta mudah digunakan oleh kasir dan staf.
3. Menyajikan informasi menu secara jelas dan informatif untuk membantu pelanggan dalam memilih produk.
4. Mendukung proses pembayaran baik secara tunai maupun non-tunai melalui integrasi *payment gateway*.
5. Membantu pengelola kafe dalam mengelola data menu, stok, serta laporan penjualan secara efisien sebagai bahan evaluasi usaha.

---
# Kondisi Objek Permasalahan

Berdasarkan hasil pengamatan terhadap proses operasional kafe, diperoleh beberapa kondisi permasalahan sebagai berikut:
1. Proses pemesanan dan pencatatan transaksi masih berpotensi dilakukan secara manual atau tidak terintegrasi dalam satu sistem.
2. Informasi menu belum disajikan secara terstruktur sehingga kurang optimal dalam membantu pelanggan.
3. Kesalahan dalam perhitungan harga dan pencatatan transaksi masih mungkin terjadi.
4. Metode pembayaran yang tersedia masih terbatas dan belum sepenuhnya mendukung transaksi non-tunai.
5. Proses pengelolaan laporan penjualan dan pemantauan performa usaha belum berjalan secara efisien dan sistematis.

---
# Solusi yang Ditawarkan

Sebagai upaya untuk mengatasi permasalahan tersebut, aplikasi *Cafelora* menawarkan solusi berupa:
1. Penerapan sistem pemesanan dan transaksi terintegrasi berbasis aplikasi.
2. Penyediaan tampilan menu yang informatif dan mudah dipahami oleh pelanggan.
3. Penggunaan sistem *Point of Sale* (POS) dengan perhitungan harga otomatis untuk meminimalkan kesalahan transaksi.
4. Integrasi *payment gateway* guna mendukung proses pembayaran non-tunai yang lebih fleksibel.
5. Penyediaan fitur laporan penjualan dan visualisasi data sebagai pendukung evaluasi dan pengambilan keputusan pengelola kafe.

---
# Deskripsi Cafelora

Cafelora merupakan sistem yang dirancang untuk mendukung operasional kafe modern melalui sistem pemesanan, transaksi, dan pengelolaan data yang terintegrasi. Sistem ini dibuat untuk membantu kafe dalam menyajikan informasi menu secara jelas, memproses pesanan dengan lebih terstruktur, serta mempercepat alur transaksi secara efisien. 

Dalam penerapannya, Cafelora menyediakan antarmuka pelanggan yang informatif untuk memudahkan pemilihan menu, serta antarmuka kasir yang sederhana namun sistematis guna menimalkan kesalahan dalam proses pemesanan dan pembayaran. Pendekatan digital yang diterapkan memungkinkan alur pelayanan kafe menjadi lebih tertata, meningkatkan efisiensi kerja staf, serta membantu pengelola dalam memantau dan mengelola aktivitas oeprasional secara lebih efektif.

Sebagai solusi berbasis aplikasi, Cafelora berperan dalam mendukung peningkatan kualitas layanan dan kelancaran operasional kafe secara keseluruhan melalui sistem yang praktis, terstruktur, dan mudah digunakan.

---
# Aktor yang Terlibat dalam Sistem

Dalam implementasi aplikasi Cafelora, sistem melibatkan beberapa aktor yang memiliki peran dan hak akses berbeda sesuai dengan kebutuhan operasional kafe. Pembagian aktor ini bertujuan untuk memastikan setiap proses berjalan secara terstruktur serta menghindari penyalahgunaan akses terhadap fitur tertentu.

## 1. Admin

Admin berperan sebagai pengelola utama sistem. Admin memiliki hak akses penuh terhadap fitur manajemen data, termasuk pengelolaan menu, kategori, varian, topping, data pengguna, serta pemantauan laporan penjualan. Selain itu, admin juga bertanggung jawab dalam mengatur alur status transaksi dan memastikan sistem berjalan sesuai kebutuhan operasional kafe.

## 2. Kasir/Staf

Kasir atau staf bertugas menangani proses transaksi penjualan secara langsung. Aktor ini memiliki akses ke sistem Point of Sale (POS) untuk mencatat pesanan pelanggan, melakukan perhitungan total harga secara otomatis, menerima pembayaran, serta mencetak struk transaksi. Akses kasir dibatasi hanya pada fitur yang berkaitan dengan transaksi agar proses operasional tetap terkontrol.

## 3. Pelanggan

Pelanggan merupakan pengguna sistem pada sisi frontend. Pelanggan dapat mengakses sistem untuk melihat daftar menu, melakukan pencarian dan penyaringan menu berdasarkan kategori atau varian, serta melihat detail informasi setiap menu. Peran pelanggan difokuskan pada kemudahan dalam memperoleh informasi menu tanpa memiliki akses ke proses pengelolaan data atau transaksi internal.

---
# Functional Requirement Aplikasi Cafelora

*Functional requirement* berikut menjelaskan kemampuan utama yang harus dimiliki oleh sistem Cafelora agar dapat mendukung operasional kafe secara optimal sesuai dengan peran masing-masing pengguna.
1. Sistem dapat mengelola data menu kafe yang meliputi penambahan, perubahan, dan penghapusan menu, kategori, varian, serta topping oleh admin.
2. Sistem dapat menyimpan dan menampilkan gambar menu untuk setiap item agar informasi menu dapat disajikan secara visual dan informatif kepada pelanggan.
3. Sistem dapat mencatat dan memperbarui stok menu secara otomatis berdasarkan transaksi yang terjadi.
4. Sistem dapat mengelola data pengguna dengan peran berbeda, seperti admin dan kasir, serta membatasi akses fitur sesuai dengan peran masing-masing.
5. Sistem dapat menerima dan memproses pesanan yang terdiri dari beberapa item menu, termasuk penambahan topping atau varian sesuai pilihan pengguna.
6. Sistem dapat menghitung total harga pesanan secara otomatis berdasarkan menu, varian, dan topping yang dipilih.
7. Sistem dapat memproses pembayaran tunai dengan fitur input uang bayar dan perhitungan kembalian secara otomatis.
8. Sistem dapat mendukung pembayaran non-tunai melalui integrasi *payment gateway* sebagai alternatif metode pembayaran.
9. Sistem dapat mengelola status transaksi mulai dari pemesanan hingga transaksi selesai sesuai dengan alur yang telah ditentukan.
10. Sistem dapat menghasilkan struk transaksi dalam bentuk digital yang dapat dicetak atau disimpan dalam format HTML atau PDF.
11. Sistem dapat menampilkan daftar menu makanan dan minuman kepada pelanggan secara jelas dan terstruktur melalui antarmuka frontend.
12. Sistem dapat menyediakan fitur pencarian atau filter menu berdasarkan kategori dan varian untuk memudahkan pelanggan dalam memilih menu.
13. Sistem dapat menghasilkan laporan transaksi penjualan berdasarkan periode tertentu untuk membantu evaluasi usaha.
14. Sistem dapat menampilkan grafik atau chart penjualan sebagai ringkasan performa transaksi harian dan bulanan.
15. Sistem dapat mengekspor laporan transaksi ke dalam format PDF atau Excel untuk kebutuhan dokumentasi dan analisis lanjutan.

---
# Fitur Aplikasi Cafelora

## Fitur Admin

### 1. CRUD Menu, Kategori, Varian, dan Topping

Fitur ini memungkinkan admin untuk menambah, mengubah, menghapus, dan melihat data menu berdasarkan kategori, varian, dan topping yang tersedia. Dengan adanya fitur ini, admin dapat memastikan data menu selalu terbarui dan sesuai dengan kebutuhan operasional kafe.

### 2. Upload dan Manajemen Gambar Menu

Admin dapat mengunggah dan mengelola gambar menu yang ditampilkan pada sistem. Gambar menu berfungsi sebagai informasi visual bagi pelanggan agar lebih mudah mengenali produk yang ditawarkan.

### 3. Sistem Manajemen Stok Otomatis

Sistem secara otomatis mengelola stok berdasarkan transaksi yang terjadi. Fitur ini membantu admin dalam memantau ketersediaan produk dan mengurangi risiko kesalahan pencatatan stok.

### 4. Workflow Status Transaksi dari Awal hingga Selesai

Fitur ini mengatur alur status transaksi mulai dari pesanan dibuat hingga transaksi selesai. Dengan workflow ini, admin dapat memantau proses transaksi secara lebih terstruktur.

### 5. Pengelolaan User

Admin memiliki akses untuk mengelola data pengguna sistem, termasuk menambah, mengubah, atau menghapus akun kasir dan staf sesuai dengan kebutuhan operasional.

### 6. Dashboard Pendapatan serta Grafik Penjualan Harian dan Bulanan

Dashboard menyajikan ringkasan pendapatan dan grafik penjualan dalam periode tertentu. Fitur ini membantu admin dalam memantau performa usaha secara cepat dan informatif.

### 7. Export Laporan Transaksi ke Format PDF/Excel

Admin dapat mengekspor laporan transaksi ke dalam format PDF atau Excel untuk keperluan dokumentasi, evaluasi, maupun pelaporan.

---
## Fitur Kasir/Staf (POS)

### 1. Input Pesanan menggunakan Komponen Repeater

Kasir dapat memasukkan beberapa item pesanan dalam satu transaksi secara fleksibel. Komponen repeater memudahkan pengelolaan item tanpa perlu mengulang proses input.

### 2. Penambahan Topping dan Modifier secara Dinamis

Fitur ini memungkinkan kasir menambahkan topping atau modifier pada menu sesuai dengan permintaan pelanggan, sehingga pesanan menjadi lebih variatif.

### 3. Perhitungan Total Harga secara Otomatis

Sistem secara otomatis menghitung total harga pesanan berdasarkan item, topping, dan jumlah yang dipilih, sehingga meminimalkan kesalahan perhitungan.

### 4. Fitur Input Uang Bayar dan Kalkulasi Kembalian

Kasir dapat memasukkan nominal pembayaran pelanggan, dan sistem akan menghitung jumlah kembalian secara otomatis.

### 5. Cetak Struk Transaksi dalam Bentuk PDF/HTML

Setelah transaksi selesai, sistem menyediakan struk dalam format PDF atau HTML yang dapat dicetak atau disimpan sebagai bukti transaksi.

### 6. Akses Halaman yang Dibatasi sesuai Role

Kasir hanya dapat mengakses fitur yang berkaitan dengan transaksi, sehingga keamanan dan fokus kerja tetap terjaga.

---
## Fitur Pelanggan (Frontend)

### 1. Melihat Daftar Menu Makanan dan Minuman

Pelanggan dapat melihat seluruh menu yang tersedia beserta informasi dasar seperti nama dan harga produk.

### 2. Filter Menu Berdasarkan Nama, Harga, dan Kategori

Fitur filter membantu pelanggan dalam menyaring menu sesuai dengan nama, harga, dan kategori yang diinginkan.

### 3. Tampilan Menu Berbentuk Kartu 

Menu ditampilkan dalam bentuk kartu untuk memudahkan pelanggan dalam melihat dan memilih produk secara visual.

### 4. Halaman Detail Menu 

Halaman ini menyajikan informasi lebih lengkap mengenai menu, seperti deskripsi dan detail tambahan yang relevan.

---
## Fitur Tambahan (Opsional)

### 1. Integrasi Payment Gateway (Midtrans atau Xendit)

Sistem mendukung pembayaran non-tunai melalui integrasi *payment gateway* untuk memberikan fleksibilitas metode pembayaran kepada pelanggan.

### 2. Filter Laporan Berdasarkan Tanggal dan Status Transaksi

Admin dapat menyaring laporan transaksi berdasarkan rentang waktu dan status tertentu agar analisis data lebih terfokus.

### 3. Fitur Chart Penjualan untuk Monitoring Transaksi 7 Hari Terakhir

Grafik penjualan disediakan untuk membantu pemantauan tren transaksi dalam jangka waktu pendek secara visual.

---
# Pembagian Jobdesk

## 1. Chaerul Cahyadi (Ketua) (4523210120)

1. Menyusun struktur proyek secara keseluruhan.
2. Mengintegrasikan fitur transaksi dan perhitungan harga.
3. Menangani dashboard serta visualisasi data laporan.
4. Melakukan final review terhadap seluruh fitur.

## 2. Arya Wicaksana Putra (4520210092)

1. Mendesain ERD serta relasi antar tabel database.
2. Membuat CRUD data master seperti kategori dan topping.
3. Mengimplementasikan validasi form dan upload gambar menu.

## 3. Aditya Nur Lintang (4523210003)

1. Melakukan setup awal Laravel dan Filament.
2. Mengimplementasikan role, Policy, dan access control.
3. Mengelola user Admin dan Staff.

## 4. Alip Khoeril Akbar (4523210009)

1. Mendesain UI untuk tampilan menu pelanggan (frontend).
2. Mengatur layout grid pada halaman menu.
3. Membuat komponen kartu menu dan fitur filter.

## 5. Muhammad Fauzan (4523210073)

1. Membuat fitur POS kasir.
2. Mengimplementasikan Repeater item transaksi dan kalkulasi otomatis.
3. Membuat fitur cetak struk dalam format HTML-PDF.

## 6. Revalina Adelia (4523210091)

1. Membuat fitur laporan dan export PDF/Excel.
2. Mengatur workflow status transaksi.
3. Menyusun dokumentasi teknis proyek dan README.

---
# Teknologi yang Digunakan

Aplikasi Cafelora dibangun menggunakan kombinasi teknologi backend, forntend, dan database yang saling terintegrasi untuk mendukung proses operasional kafe secara optimal. Pemilihan teknologi ini didasarkan pada kebutuhan pengembangan aplikasi yang terstruktur, mudah dikembangkan, serta sesuai dengan praktik pembuatan aplikasi web modern.

| Teknologi         | Versi  | Keterangan                                                                                                                                     | 
|-------------------|--------|------------------------------------------------------------------------------------------------------------------------------------------------|
| PHP               | ^8.2   | Bahasa pemrograman server-side yang digunakan untuk menangani logika bisnis, proses transaksi, dan pengelolaan data aplikasi.                  |
| Laravel Framework | ^12.0  | Framework PHP berbasis MVC yang digunakan untuk mengatur alur aplikasi, mulai dari routing, controller, model, hingga view secara terstruktur. | 
| Composer          | Latest | Dependency manager PHP yang digunakan untuk mengelola library dan package yang dibutuhkan oleh Laravel.                                        | 
| NPM               | Latest | Package manager JavaScript yang digunakan untuk mengelola dependency frontend.                                                                 |
| Vite              | Latest | Build tool frontend yang digunakan untuk mengelola dan mengompilasi aset frontend agar lebih cepat dan optimal.                                | 
| MySQL/PostgreSQL  | Latest | Database relasional yang digunakan untuk menyimpan data aplikasi seperti menu, transaksi, pengguna, dan laporan penjualan.                     | 
| Filament          | ^3.3   | Admin panel Laravel yang digunakan untuk mempercepat pembuatan fitur CRUD, form, tabel, serta manajemen data pada sisi admin dan kasir.        |

---
# Persyaratan Sistem

Sebelum menjalankan aplikasi Cafelora, perangkat yang digunakan harus memenuhi beberapa persyaratan sistem agar aplikasi dapat berjalan dengan baik dan stabil.

## 1. PHP >= 8.2

Digunakan sebagai runtime utama aplikasi Laravel. Versi ini dipilih karena kompatibel dengan Laravel 12 dan mendukung fitur bahasa terbaru.

## 2. Composer

Digunakan untuk mengelola dependency PHP yang dibutuhkan oleh framework Laravel dan library pendukung lainnya.

## 3. Node.js & NPM     

Digunakan untuk menjalankan proses instalasi dependency frontend serta membangun aset frontend menggunakan Vite.

## 4. MySQL atau PostgreSQL

Digunakan sebagai sistem manajemen basis data untuk menyimpan seluruh data aplikasi.

## 5. Web Server           

Aplikasi dapat dijalankan menggunakan web server seperti Apache atau Nginx, maupun menggunakan Laravel built-in server untuk kebutuhan development.

Untuk pengguna sistem operasi Windows, disarankan menggunakan salah satu tools beriktu:
1. *Laragon*, karena menyediakan PHP, MySQL, dan Apache dalam satu paket sehingga memudahkan proses setup.
2. *XAMPP*, sebagai alternatif server lokal yang umum digunakan.
3. *Herd*, sebagai alternatif yang lebih ringan untuk pengembangan Laravel secara lokal.

---
# Langkah Instalasi

## 1. Clone atau Download Repository

```bash
# Clone repository (jika menggunakan git)
https://github.com/xnoname2003/cafelora.git
cd cafelora
```

Langkah ini bertujuan untuk memperoleh kode sumber aplikasi Cafelora. Repository dapat di-clone menggunakan Git atau diunduh secara manual. Setelah proses selesai, pengguna masuk ke direktori proyek untuk melanjutkan ke tahap instalasi berikutnya.

## 2. Install Dependencies PHP

```bash
composer install
```

Perintah ini digunakan untuk menginstal seluruh dependency PHP yang dibutuhkan oleh aplikasi Laravel. Dependency tersebut didefinisikan dalam file `composer.json` dan diperlukan agar aplikasi dapat berjalan sesuai dengan konfigurasi yang telah ditentukan.

## 3. Install Dependencies JavaScript

```bash
npm install
```

Perintah ini digunakan untuk menginstal seluruh dependency JavaScript yang dibutuhkan untuk pengelolaan frontend aplikasi. Dependency ini mencakup library pendukung antarmuka dan proses build aset frontend menggunakan Vite.

## 4. Konfigurasi Environment

```bash
# Copy file .env.example menjadi .env
copy .env.example .env

# Generate application key
php artisan key:generate
```

Langkah ini dilakukan untuk menyiapkan file konfigurasi environment aplikasi:
1. File `.env` digunakan untuk menyimpan konfigurasi penting seperti koneksi database dan pengaturan aplikasi.
2. Perintah `php artisan key:generate` digunakan untuk membuat *application key* yang berfungsi menjaga keamanan data, seperti enkripsi session dan informasi sensitif lainnya.

## 5. Konfigurasi Database

Pengguna perlu menyesuaikan konfigurasi database pada file `.env` agar aplikasi dapat terhubung dengan database lokal.

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=cafelora
DB_USERNAME=root
DB_PASSWORD=
```

Pengaturan ini meliputi jenis database, alamat server, port, nama database, serta kredensial yang digunakan. Pastikan database dengan nama yang sesuai sudah dibuat sebelumnya.

## 6. Jalankan Migration & Seeder

```bash
# Membuat tabel-tabel di database
php artisan migrate

# (Optional) Generate data dummy untuk testing
php artisan db:seed
```

1. `php artisan migrate` digunakan untuk membuat seluruh tabel database berdasarkan file migration.
2. `php artisan db:seed` bersifat opsional dan digunakan untuk mengisi database dengan data awal (dummy) agar aplikasi dapat langsung diuji tanpa memasukkan data secara manual.

## 7. Build Assets Frontend

```bash
# Untuk development (dengan hot reload)
npm run dev

# Untuk production
npm run build
```

1. `npm run dev` digunakan pada tahap pengembangan karena mendukung *hot reload* sehingga perubahan kode frontend dapat langsung terlihat.
2. `npm run build` digunakan untuk membangun aset frontend versi production yang lebih optimal.

## 8. Jalankan Aplikasi

```bash
# Menggunakan Laravel built-in server
php artisan serve
```

Perintah ini digunakan untuk menjalankan *Laravel built-in server*. Setelah server berjalan, aplikasi dapat diakses melalui browser pada alamat:

`http://127.0.0.1:8000`

---
# Agenda Pekerjaan di GitHub

---

| No. | Nama               | Fitur                                        | Deskripsi Progres                                                                                       | Tanggal Push GitHub |
|-----|--------------------|----------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------|
| 1.  | Chaerul Cahyadi    | Tidak Ada                                                       | Inisialisasi Cafelora                                                                                     | 26/11/2025        |
| 2.  | Aditya Nur Lintang | Manajemen User dan Role                                         | Setup Laravel + Filament, Implementasi Role + Policy (Admin, Staff, Customer)                                                                                    | 26/11/2025        |
| 3.  | Chaerul Cahyadi    | Tidak Ada                                                       | Fix Error Implementasi Role Policy                                                                                       | 27/11/2025        |
| 4.  | Chaerul Cahyadi    | Menu Management                                                 | ERD dan Struktur Tabel Sistem Cafelora                                                                                     | 29/11/2025        |
| 5.  | Chaerul Cahyadi    | Tidak Ada                                                       | Update .env.example                                                                                      | 29/11/2025        |
| 6.  | Chaerul Cahyadi    | Tidak Ada                                                       | Update Policy dan Crud Menu Management                                                                                   | 30/11/2025        |
| 7.  | Chaerul Cahyadi    | Tidak Ada                                                       | Fix Policy                                                                                       | 30/11/2025        |
| 8.  | Alip Khoeril Akbar | Frontend (Pelanggan)                                            | Membuat Frontend Untuk Pelanggan Melihat Daftar Menu dan Sedikit Penyesuaian Code Pada MenuResource.php                                                       | 30/11/2025        |
| 9.  | Chaerul Cahyadi    | Tidak Ada                                                       | Update ERD Documentation and Replace Image                                                                                        | 6/12/2025         |
| 10. | Chaerul Cahyadi    | Tidak Ada                                                       | Fix Landing Page and ERD                                                                                          | 6/12/2025         |
| 11. | Alip Khoeril Akbar | Frontend (Pelanggan)                                            | Modifikasi Tampilan Frontend Pelanggan                                                                                    | 6/12/2025         |
| 12. | Alip Khoeril Akbar | Frontend (Pelanggan)                                            | Membuat Fitur Search Pada Halaman Frontend (Pelanggan) Berdasarkan Nama menu, Harga, Kategori                                                                        | 7/12/2025         |
| 13. | Alip Khoeril Akbar | Frontend (Pelanggan)                                            | Membuat Fitur Search Pada Halaman Frontend (Pelanggan) Berdasarkan Nama menu, Harga, Kategori                                                                        | 8/12/2025         |
| 14. | Alip Khoeril Akbar | Frontend (Pelanggan)                                            | Fix URL Filter Frontend (Pelanggan)                                                                                  | 10/12/2025        |
| 15. | Muhammad Fauzan    | Menu Transaction Management                                     | Transactions dan POS Kasir                                                                                        | 10/11/2025        |
| 16. | Revalina Adelia    | Dokumentasi                                                     | Menambahkan Dokumentasi Fitur, Tampilan, Instalasi, dan Agenda                                                                                       | 12/12/2025        |
| 17. | Alip Khoeril Akbar | Membuat Halaman Detail Menu dari Setiap Menu                    | Membuat Halaman Detail Menu dari Setiap Menu                                                                                         | 13/12/2025        |
| 18. | Alip Khoeril Akbar | Membuat Section Rekomendasi Menu (BestSeller) dan Fix Responsif | Membuat Section Rekomendasi Menu (BestSeller) dan Fix Responsif                                                                                    | 13/12/2025        |
| 19. | Muhammad Fauzan    | Responsive POS Kasir, BestSeller Menu, dan fitur struk          | Menambahkan Fitur Responsive pada Halaman POS, BestSeller serta Struk untuk Otomatisasi Print                                                                      | 13/12/2025        |
| 20. | Chaerul Cahyadi    | Metode Pembayaran                                               | Implementasi Payment Gateway Midtrans                                                                                     | 17/12/2025        |
| 21. | Revalina Adelia    | Dokumentasi                                                     | Menambahkan Pendahuluan dan Tampilan, Update Fitur + Instalasi + Agenda
                                                                                             | 17/12/2025        |

---
# Agenda Presentasi Progres Tugas Besar

| No. | Hari/Tanggal           | Presentasi ke-             | Hasil Progres                                                     |
|-----|------------------------|----------------------------|-------------------------------------------------------------------|
| 1.  | Rabu, 10 Desember 2025 | Presentasi Progres Pertama | Master Menu, Dashboard Filament, GitHub dan Branch sudah Berjalan |
| 2.  | Rabu, 17 Desember 2025 | Presentasi Progres Kedua   |                                                                   |

---
# Bukti Dokumentasi Presentasi

## 1. Rabu, 10 Desember 2025 (Progres Pertama)

![alt text](images/PresentasiProgresPertama.png)

## 2. Rabu, 17 Desember 2025 (Progres Kedua)

---
# Rekap Uji Fungsionalitas & Status Progres Pengembangan Fitur

Bagian ini menyajikan hasil *uji fungsionalitas* serta *perkembangan progres fitur* aplikasi *Cafelora* yang dikerjakan secara kolaboratif oleh tim. Dokumentasi disusun berdasarkan *tahapan waktu pengembangan* untuk menunjukkan alur pengerjaan mulai dari *inisialisasi sistem, pengembangan fitur inti,* hingga *finalisasi dan validasi*.

Pengembangan dimulai pada *26 November 2025* dan berlangsung secara bertahap hingga tahap penyelesaian.

---
## Tahap 1 - Inisialisasi Sistem & Fondasi Fitur (Rabu, 26 November 2025 - Selasa, 2 Desember 2025)

### 1. Chaerul Cahyadi (Ketua)

| No. | Fitur                     | Deskripsi Uji                                               | Status      | Tanggal Mulai     |
|-----|---------------------------|-------------------------------------------------------------|-------------|-------------------|
| 1   | Struktur Proyek & Routing | Validasi struktur folder Laravel dan routing utama aplikasi | ✅ Selesai  | 26 November 2025  |
| 2   | Review Awal Fitur Tim     | Pengecekan awal hasil pekerjaan anggota                     | 🔄 Berjalan | 26 November 2025  |
| 3   | Dashboard Admin           | Tampilan dashboard admin berhasil ditampilkan               | ✅ Selesai  | 29 November 2025  |

### 2. Arya Wicaksana Putra

| No. | Fitur                   | Deskripsi Uji                                         | Status     | Tanggal Mulai    |
|-----|-------------------------|-------------------------------------------------------|------------|------------------|
| 1   | Desain ERD              | ERD disusun dan disesuaikan dengan kebutuhan sistem   | ✅ Selesai | 29 November 2025 |
| 2   | CRUD Kategori & topping | Operasi tambah, ubah, hapus, dan tampil data berjalan | ✅ Selesai | 29 November 2025 |
| 3   | Validasi Form           | Validasi input dan format data berjalan sesuai aturan | ✅ Selesai | 29 November 2025 |
| 4   | Upload Gambar Menu      | Upload dan preview gambar menu berhasil               | ✅ Selesai | 29 November 2025 |

### 3. Aditya Nur Lintang

| No. | Fitur                    | Deskripsi Uji                                    | Status     | Tanggal Mulai    |
|-----|--------------------------|--------------------------------------------------|------------|------------------|
| 1   | Setup Laravel & Filament | Proyek berhasil dijalankan dan panel admin siap  | ✅ Selesai | 26 November 2025 |
| 2   | Role & Policy            | Hak akses Admin dan Staf terdefinisi dengan baik | ✅ Selesai | 26 November 2025 |
| 3   | Manajemen User           | CRUD user berjalan tanpa error                   | ✅ Selesai | 26 November 2025 |

### 4. Alip Khoeril Akbar

| No. | Fitur               | Deskripsi Uji                                       | Status           | Tanggal Mulai    |
|-----|---------------------|-----------------------------------------------------|------------------|------------------|
| 1   | Tampilan Grid Menu  | Grid menu tampil responsif di berbagai ukuran layar | ✅ Selesai       | 30 November 2025 |
| 2   | Responsivitas UI    | Tampilan konsisten di mobile dan desktop            | ✅ Selesai       | 30 November 2025 |

### 5. Revalina Adelia

| No. | Fitur                  | Deskripsi Uji                                    | Status      | Tanggal Mulai    |
|-----|------------------------|--------------------------------------------------|-------------|------------------|
| 1   | Dokumentasi Awal       | Struktur README dan folder dokumentasi disiapkan | 🔄 Berjalan | 26 November 2025 |

---
## Tahap 2 - Pengembangan Fitur Inti & Frontend (Rabu, 3 Desember 2025 - Selasa, 9 Desember 2025)

### 1. Chaerul Cahyadi (Ketua)

| No. | Fitur                       | Deskripsi Uji                                                                                              | Status      | Tanggal Mulai    |
|-----|-----------------------------|------------------------------------------------------------------------------------------------------------|-------------|------------------|
| 1   | Review & Validasi Lanjutan  | Validasi hasil card menu, filter kategori dan harga, penambahan item transaksi, dan dropdown menu & varian | 🔄 Berjalan | 26 November 2025 |

### 2. Alip Khoeril Akbar

| No. | Fitur               | Deskripsi Uji                              | Status     | Tanggal Mulai    |
|-----|---------------------|--------------------------------------------|------------|------------------|
| 1   | Komponen Card Menu  | Informasi menu tampil lengkap              | ✅ Selesai | 6 Desember 2025  |
| 2   | Filter Kategori     | Menu menyesuaikan kategori yang dipilih    | ✅ Selesai | 8 Desember 2025  |
| 3   | Filter Harga        | Filter harga minimum dan maksimum berjalan | ✅ Selesai | 8 Desember 2025  |

### 3. Muhammad Fauzan

| No. | Fitur                     | Deskripsi Uji                        | Status           | Tanggal Mulai    |
|-----|---------------------------|--------------------------------------|------------------|------------------|
| 1   | Penambahan Item Transaksi | Item transaksi dapat ditambahkan     | ✅ Selesai       | 5 Desember 2025  |
| 2   | Dropdown Menu & Varian    | Harga dan varian terupdate otomatis  | ✅ Selesai       | 8 Desember 2025  |

---
## Tahap 3 - Integrasi Sistem & Penyempurnaan (Rabu, 10 Desember 2025 - Selasa, 16 Desember 2025)

### 1. Chaerul Cahyadi (Ketua)

| No. | Fitur                       | Deskripsi Uji                                   | Status      | Tanggal Mulai    |
|-----|-----------------------------|-------------------------------------------------|-------------|------------------|
| 1   | Review & Validasi Lanjutan  | Validasi hasil detail menu dan POS              | 🔄 Berjalan | 26 November 2025 |

### 2. Alip Khoeril AKbar

| No. | Fitur               | Deskripsi Uji                              | Status     | Tanggal Mulai    |
|-----|---------------------|--------------------------------------------|------------|------------------|
| 1   | Halaman Detail Menu | Informasi detail menu ditampilkan lengkap  | ✅ Selesai | 12 Desember 2025 |

### 3. Muhammad Fauzan

| No. | Fitur                    | Deskripsi Uji                            | Status     | Tanggal Mulai    |
|-----|--------------------------|------------------------------------------|------------|------------------|
| 1   | Tampilan Awal POS        | Struktur dasar halaman POS ditampilkan   | ✅ Selesai | 10 Desember 2025 |
| 2   | Kalkulasi Total Otomatis | Subtotal & total transaksi valid         | ✅ Selesai | 10 Desember 2025 |
| 3   | Input Bayar & Kembalian  | Logika pembayaran dan kembalian berjalan | ✅ Selesai | 10 Desember 2025 |
| 4   | Cetak Struk              | Template struk HTML/PDF berhasil dicetak | ✅ Selesai | 12 Desember 2025 |

### 4. Revalina Adelia

| No. | Fitur             | Deskripsi Uji                        | Status           | Tanggal Mulai    |
|-----|-------------------|--------------------------------------|------------------|------------------|
| 1   | Halaman Laporan   | Data laporan transaksi ditampilkan   | 🔄 Dalam Progres | 17 Desember 2025 |
| 2   | Filter Laporan    | Filter tanggal & status dikembangkan | 🔄 Dalam Progres | 17 Desember 2025 |
| 3   | Export PDf/Excel  | Fitur ekspor laporan dikembangkan    | 🔄 Dalam Progres | 17 Desember 2025 |

---
## Tahap 4 - Finalisasi & Validasi Akhir (Rabu, 17 Desember 2025 - Selasa, 23 Desember 2025)

### 1. Chaerul Cahyadi (Ketua)

| No. | Fitur                       | Deskripsi Uji                                   | Status      | Tanggal Mulai    |
|-----|-----------------------------|-------------------------------------------------|-------------|------------------|
| 1   | Review Akhir                | Pengecekan akhir pada keseluruhan sistem        | ✅ Selesai  | 26 November 2025 |
| 2   | Integrasi Logika Transaksi  | Relasi transaksi dan item terhubung dengan baik | ✅ Selesai  | 17 Desember 2025 |

### 2. Revalina Adelia

| No. | Fitur                     | Deskripsi Uji                                | Status     | Tanggal Mulai    |
|-----|---------------------------|----------------------------------------------|------------|------------------|
| 1   | Halaman Laporan           | Tabel laporan tervalidasi                    | ✅ Selesai | 17 Desember 2025 |
| 2   | Filter Laporan            | Filter berfungsi sesuai kebutuhan            | ✅ Selesai | 17 Desember 2025 |
| 3   | Export PDf/Excel          | Laporan dapat diekspor dengan benar          | ✅ Selesai | 17 Desember 2025 |
| 4   | Workflow Status Transaksi | Status transaksi terintegrasi penuh          | ✅ Selesai | 17 Desember 2025 |
| 5   | Dokumentasi & README      | Dokumentasi lengkap dan siap dipresentasikan | ✅ Selesai | 17 Desember 2025 |

---
# Hasil Tampilan Aplikasi Cafelora

## Halaman Admin (Sabtu, 29 November 2025)

### 1. Halaman Dashboard Admin

![alt text](images/DashboardAdmin.png)

### 2. Halaman Users

![alt text](images/UsersAdmin.png)

### 3. Halaman Categories

![alt text](images/CategoriesAdmin.png)

### 4. Halaman Menus

![alt text](images/MenusAdmin.png)

### 5. Halaman Toppings

![alt text](images/ToppingsAdmin.png)

### 6. Halaman Variants

![alt text](images/VariantsAdmin.png)

---
## Halaman Staf (Sabtu, 29 November 2025)

### 1. Halaman Dashboard Staf

![alt text](images/DashboardStaf.png)

### 2. Halaman Categories

![alt text](images/CategoriesStaf.png)

### 3. Halaman Menus

![alt text](images/MenusStaf.png)

### 4. Halaman Toppings

![alt text](images/ToppingsStaf.png)

### 5. Halaman Variants

![alt text](images/VariantsStaf.png)

---
## Halaman Frontend Menu

### 1. Minggu, 30 November 2025

![alt text](images/FrontendMenu.png)

### 2. Sabtu, 6 Desember 2025

![alt text](images/FrontendMenu2.png)

### 3. Senin, 8 Desember 2025

![alt text](images/FrontendMenu3.png)

### 4. Sabtu, 13 Desember 2025

![alt text](images/FrontendMenu4.png)

![alt text](images/FrontendMenu5.png)

---
## Halaman POS dan Transaksi

### 1. Halaman POS Kasir

#### 1. Rabu, 10 Desember 2025

![alt text](images/POSKasir1.png)

#### 2. Jum'at, 12 Desember 2025

![alt text](images/POSKasir2.png)

![alt text](images/POSKasir3.png)

![alt text](images/KeranjangBelanja.png)

#### 3. Sabtu, 13 Desember 2025

![alt text](images/POSTerbaru.png)

![alt text](images/TransaksiBerhasil.png)

---
### 2. Halaman Transactions 

#### 1. Rabu, 10 Desember 2025

![alt text](images/Transactions.png)

#### 2. Sabtu, 13 Desember 2025

![alt text](images/Transactions2.png)

---
### 3. Halaman Detail Transactions (Rabu, 10 Desember 2025)

![alt text](images/DetailTransactions.png)

---
