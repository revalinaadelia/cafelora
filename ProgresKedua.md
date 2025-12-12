# PRAKTIKUM 12: PROGRES TUBES 2 - APLIKASI CAFELORA

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
## Deskripsi Cafelora

Cafelora adalah konsep aplikasi yang dirancang untuk mendukung operasional kafe modern dengan menekankan kemudahan pemesanan, penyajian informasi menu yang jelas, serta proses transaksi yang cepat dan efisien. Pembuatan sistem ini berawal dari kebutuhan untuk menghadirkan pelayanan yang praktis dan responsif bagi pelanggan yang ingin menikmati hidangan berkualitas tanpa hambatan. Dalam sistem Cafelora, seluruh menu ditampilkan secara informatif sehingga pelanggan dapat dengan mudah memilih makanan dan minuman yang diinginkan. Di sisi lain, antarmuka kasir dibuat sederhana namun tetap terstruktur, memungkinkan proses pemesanan dan pembayaran berlangsung lebih ringkas serta minim kesalahan. Setiap menu menggunakan bahan segar yang diolah setiap hari, dan informasi tersebut disampaikan melalui aplikasi untuk meningkatkan kepercayaan pelanggan. Pendekatan digital yang diterapkan Cafelora menciptakan alur pelayanan yang lebih tertata, meningkatkan efisiensi staf, serta memperkaya pengalaman pelanggan. Seiring perkembangannya, Cafelora terus berfokus pada konsistensi rasa, harga yang kompetitif, dan sistem pemesanan yang praktis. Aplikasi ini hadir sebagai solusi digital yang membantu meningkatkan kualitas layanan sekaligus mendukung kelancaran operasional kafe secara keseluruhan.

---
## Fitur Aplikasi Cafelora

### Fitur Admin

1. CRUD menu, kategori, varian, dan topping.
2. Upload dan manajemen gambar menu.
3. Sistem manajemen stok otomatis.
4. Workflow status transaksi dari awal hingga selesai.
5. Pengelolaan user.
6. Dashboard pendapatan serta grafik penjualan harian dan bulanan.
7. Export laporan transaksi ke format PDF/Excel.

### Fitur Kasir/Staff (POS)

1. Input pesanan menggunakan komponen Repeater.
2. Penambahan topping dan modifier secara dinamis.
3. Perhitungan total harga secara otomatis.
4. Fitur input uang bayar dan kalkulasi kembalian.
5. Cetak struk transaksi dalam bentuk PDF/HTML.
6. Akses halaman yang dibatasi sesuai role (khusus transaksi).

### Fitur Pelanggan (Frontend)

1. Melihat daftar menu makanan dan minuman.
2. Filter menu berdasarkan kategori dan varian.
3. Tampilan menu berbentuk kartu untuk memudahkan pemilihan.
4. Halaman detail menu untuk memberikan informasi lebih lengkap.

### Fitur Tambahan (Opsional)

1. Integrasi payment gateway (Midtrans atau Xendit).
2. Filter laporan berdasarkan tanggal dan status transaksi.
3. Fitur chart penjualan untuk monitoring transaksi 7 hari terakhir.

---
## Pembagian Jobdesk

### 1. Chaerul Cahyadi (Ketua) (4523210120)

1. Menyusun struktur proyek secara keseluruhan.
2. Mengintegrasikan fitur transaksi dan perhitungan harga.
3. Menangani dashboard serta visualisasi data laporan.
4. Melakukan final review terhadap seluruh fitur.

### 2. Arya Wicaksana Putra (4520210092)

1. Mendesain ERD serta relasi antar tabel database.
2. Membuat CRUD data master seperti kategori dan topping.
3. Mengimplementasikan validasi form dan upload gambar menu.

### 3. Aditya Nur Lintang (4523210003)

1. Melakukan setup awal Laravel dan Filament.
2. Mengimplementasikan role, Policy, dan access control.
3. Mengelola user Admin dan Staff.

### 4. Alip Khoeril Akbar (4523210009)

1. Mendesain UI untuk tampilan menu pelanggan (frontend).
2. Mengatur layout grid pada halaman menu.
3. Membuat komponen kartu menu dan fitur filter.

### 5. Muhammad Fauzan (4523210073)

1. Mengembangkan fitur POS kasir.
2. Mengimplementasikan Repeater item transaksi dan kalkulasi otomatis.
3. Membuat fitur cetak struk dalam format HTML-PDF.

### 6. Revalina Adelia (4523210091)

1. Mengembangkan fitur laporan dan export PDF/Excel.
2. Mengatur workflow status transaksi.
3. Menyusun dokumentasi teknis proyek dan README.

---
## Panduan Manajemen Repositori GitHub

### 1. Inisialisasi (Tugas Ketua Kelompok)

1. Membuat repository baru di GitHub.
2. Mengatur visibilitas ke **Private**.
3. Mengundang dosen (_username_github_dosen_) serta seluruh anggota tim sebagai **collaborator**.
4. Melakukan inisialisasi awal proyek **Laravel & Filament**, kemudian melakukan _push_ ke branch **main**.
5. Memastikan file **.gitignore** sudah benar (hindari mengunggah folder **/vendor** dan file **.env**).

### 2. Aturan Penggunaan Branch

Strategi yang digunakan adalah **Simplified Feature Branch**.
1. **main** : Cabang utama. Hanya ketua yang boleh melakukan _merge_.
2. **branch fitur anggota** : Setiap anggota membuat branch sesuai fitur yang dikerjakan.

**Format Penamaan Branch**

`dev-[nama_panggilan]-[nama_fitur]`

**Branch Sementara**

1. `dev-aditya-setup-role-policy`  : Mengerjakan setup Laravel, konfigurasi role, dan implementasi policy akses pengguna.
2. `dev-chaerul-erd-cafelora`      : Membuat dan menyempurnakan ERD serta struktur database Cafelora.
3. `dev-chaerul-crud-table-master` : Mengerjakan fitur CRUD master data (menu, kategori, topping, varian) pada sistem.
4. `dev-alip-frontend-pelanggan`   : Membuat tampilan frontend pelanggan beserta fitur pencarian dan filter menu.
5. `dev-fauzan-pos-transaksi`      : Membangun fitur POS transaksi meliputi penambahan item, perhitungan total, dan cetak struk.
6. `dev-revalina-dokumentasi`      : Membuat dokumentasi laporan mengenai Fitur, Jobdesk, Hasil Tampilan, Langkah Instalasi, Deployment, Agenda, dan poin lainnya yang memperkuat pengerjaan project.

<img width="347" height="453" alt="Branch" src="https://github.com/user-attachments/assets/7074d523-a979-4ffa-aadc-e02d3dcd3b0d" />

### 3. Alur Kerja Harian (Workflow)

#### a. Memulai Pekerjaan

Lakukan checkout dari **main** terbaru:

```bash
git checkout main
git pull origin main
git checkout -b dev-budi-crud-produk
```
<img width="645" height="135" alt="git pull" src="https://github.com/user-attachments/assets/50e582e7-ed0b-4808-bf65-caa99b65e8ad" />

<img width="636" height="84" alt="git checkout" src="https://github.com/user-attachments/assets/448e470b-1097-425f-912f-6e97301c380e" />

#### b. Mengerjakan Fitur

Lakukan pekerjaan seperti coding, membuat Filament Resource, migrasi, dan logika fitur.

#### c. Commit secara Berkala

Gunakan pesan commit yang jelas:

```bash
git add .
git commit -m "Menambahkan dokumentasi Fitur, Tampilan, Instalasi, dan Agenda"
```

<img width="900" height="336" alt="Commit" src="https://github.com/user-attachments/assets/471095d7-3cdd-4a2e-9696-dd18a802d1e9" />

#### d. Push ke GitHub

`git push origin dev-revalina-dokumentasi`

<img width="789" height="352" alt="Push GitHub" src="https://github.com/user-attachments/assets/ca9e78f4-e8cb-49bb-ab0c-bbb6f0e00a73" />

### 4. Pull Request (PR)

1. Buka GitHub dan buat **Pull Request** dari branch fitur kalian ke branch **main**.
2. Jelaskan perubahan yang kalian kerjakan dalam deskripsi PR.
3. _Assign_ ketua kelompok sebagai reviewer.

### 5. Proses Merge (Tugas Ketua)

1. Ketua melakukan _review_ kode.
2. Jika semua perubahan sudah sesuai, ketua menekan tombol **Merge**.

---
## Agenda Pekerjaan di GitHub

| No. | Nama               | Fitur                       | Deskripsi Progres                                                                                       | Tanggal Push GitHub |
|-----|--------------------|-----------------------------|---------------------------------------------------------------------------------------------------------|---------------------|
| 1.  | Chaerul Cahyadi    | Tidak Ada                   | Inisialisasi Cafelora                                                                                   | 26/11/2025          |
| 2.  | Aditya Nur Lintang | Manajemen User dan Role     | Setup Laravel + Filament, Implementasi Role + Policy (Admin, Staff, Customer)                           | 26/11/2025          |
| 3.  | Chaerul Cahyadi    | Tidak Ada                   | Fix Error Implementasi Role Policy                                                                      | 27/11/2025          |
| 4.  | Chaerul Cahyadi    | Menu Management             | ERD dan Struktur Tabel Sistem Cafelora                                                                  | 29/11/2025          |
| 5.  | Chaerul Cahyadi    | Tidak Ada                   | Update .env.example                                                                                     | 29/11/2025          |
| 6.  | Chaerul Cahyadi    | Tidak Ada                   | Update Policy dan Crud Menu Management                                                                  | 30/11/2025          |
| 7.  | Chaerul Cahyadi    | Tidak Ada                   | Fix Policy                                                                                              | 30/11/2025          |
| 8.  | Alip Khoeril Akbar | Frontend (Pelanggan)        | Membuat Frontend Untuk Pelanggan Melihat Daftar Menu dan Sedikit Penyesuaian Code Pada MenuResource.php | 30/11/2025          |
| 9.  | Chaerul Cahyadi    | Tidak Ada                   | Update ERD Documentation and Replace Image                                                              | 6/12/2025           |
| 10. | Chaerul Cahyadi    | Tidak Ada                   | Fix Landing Page and ERD                                                                                | 6/12/2025           |
| 11. | Alip Khoeril Akbar | Frontend (Pelanggan)        | Modifikasi Tampilan Frontend Pelanggan                                                                  | 6/12/2025           |
| 12. | Alip Khoeril Akbar | Frontend (Pelanggan)        | Membuat Fitur Search Pada Halaman Frontend (Pelanggan) Berdasarkan Nama menu, Harga, Kategori           | 7/12/2025           |
| 13. | Alip Khoeril Akbar | Frontend (Pelanggan)        | Membuat Fitur Search Pada Halaman Frontend (Pelanggan) Berdasarkan Nama menu, Harga, Kategori           | 8/12/2025           |
| 14. | Alip Khoeril Akbar | Frontend (Pelanggan)        | Fix URL Filter Frontend (Pelanggan)                                                                     | 10/12/2025          |
| 15. | Muhammad Fauzan    | Menu Transaction Management | Transactions dan POS Kasir                                                                              | 10/12/2025          |
| 16. | Revalina Adelia    | Dokumentasi                 | Menambahkan dokumentasi Fitur, Tampilan, Instalasi, dan Agenda                                          | 12/12/2025          |

---
## Agenda Presentasi Progres Tugas Besar

| No. | Hari/Tanggal           | Presentasi ke-             | Hasil Progres                                                     |
|-----|------------------------|----------------------------|-------------------------------------------------------------------|
| 1.  | Rabu, 10 Desember 2025 | Presentasi Progres Pertama | Master Menu, Dashboard Filament, GitHub dan Branch sudah Berjalan |

### Bukti Dokumentasi Presentasi

#### 1. Rabu, 10 Desember 2025

<img width="1919" height="1079" alt="Presentasi Progres Pertama" src="https://github.com/user-attachments/assets/9b0d9002-3189-43d5-82a0-3a98f900955a" />

---
## Rekap Uji Fungsionalitas & Status Progres Fitur

Bagian ini digunakan untuk mengetahui fitur apa saja yang *sudah selesai dan sudah diuji* serta fitur yang *masih dalam proses pengembangan*. Pengerjaan dimulai pada tanggal *26 November 2025* sampai saat ini.

### 1. Chaerul Cahyadi (Ketua): Struktur Proyek, Integrasi Transaksi, Dashboard, Review Fitur

| No. | Fitur yang Diuji                  | Deskripsi Uji                                                            | Status                                  | Tanggal Mulai     |
|-----|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------|-------------------|
| 1   | Struktur Proyek & Routing         | Mengecek konsistensi struktur folder, routing utama, dan manajemen modul | ✅ Selesai & Stabil                     | 26 November 2025  |
| 2   | Integrasi Logika Transaksi (Awal) | Memastikan relasi model transaksi & item berjalan awalnya                | 🔄 Dalam Progres (Bergantung POS Kasir) | 2-8 November 2025 |
| 3   | Dashboard Admin                   | Visualisasi dasar sudah tampil, grafik belum 100% data real-time         | 🔄 Dalam Progres                        | 2-8 November 2025 |
| 4   | Review & Validasi Fitur           | Pengecekan keseluruhan fitur anggota lain                                | 🔄 Berjalan Bertahap                    | 26 November 2025  |

### 2. Arya Wicaksana Putra: ERD, CRUD Master Data, Validasi Form, Upload Gambar

| No. | Fitur yang Diuji   | Deskripsi Uji                                                  | Status                       | Tanggal Mulai    |
|-----|--------------------|----------------------------------------------------------------|------------------------------|------------------|
| 1   | Desain ERD         | ERD diverifikasi dan konsisten dengan model Laravel            | ✅ Selesai                   | 26 November 2025 |
| 2   | CRUD Kategori      | Tambah, edit, hapus, dan list kategori berjalan baik           | ✅ Selesai & Berjalan Normal | 26 November 2025 |
| 3   | CRUD Topping       | Form & relasi topping berhasil disimpan                        | ✅ Selesai                   | 26 November 2025 |
| 4   | Validasi Form      | Field wajib terisi, format harga, dan input gambar tervalidasi | ✅ Selesai                   | 26 November 2025 |
| 5   | Upload Gambar Menu | Mengunggah gambar ke storage dan menampilkannya di card menu   | ✅ Selesai                   | 26 November 2025 |

### 3. Aditya Nur Lintang: Setup Laravel, Filament, Role, Policy, User Management

| No. | Fitur yang Diuji                | Deskripsi Uji                                            | Status                 | Tanggal Mulai    |
|-----|---------------------------------|----------------------------------------------------------|------------------------|------------------|
| 1   | Setup Laravel & Filament        | Proyek berhasil berjalan dan panel admin siap digunakan  | ✅ Selesai             | 26 November 2025 |
| 2   | Implementasi Role (Admin/Staff) | Pengujian akses halaman sesuai role                      | ✅ Selesai & Berfungsi | 26 November 2025 |
| 3   | Policy & Permission             | Staff dibatasi untuk akses tertentu (tanpa delete)       | ✅ Selesai             | 26 November 2025 |
| 4   | Manajemen User                  | CRUD user admin/staff berjalan optimal                   | ✅ Selesai             | 26 November 2025 |

### 4. Alip Khoeril Akbar: Frontend Pelanggan – Tampilan Menu & Filter

| No. | Fitur yang Diuji    | Deskripsi Uji                      | Status     | Tanggal Mulai    |
|-----|---------------------|------------------------------------|------------|------------------|
| 1   | Tampilan Grid Menu  | Card tampil responsif              | ✅ Selesai | 26 November 2025 |
| 2   | Filter Kategori     | Menu menyesuaikan pilihan kategori | ✅ Selesai | 26 November 2025 |
| 3   | Filter Varian       | Menu berganti sesuai varian        | ✅ Selesai | 26 November 2025 |
| 4   | Komponen Card Menu  | Gambar, nama, harga tampil baik    | ✅ Selesai | 26 November 2025 |
| 5   | Halaman Detail Menu | Informasi menu tampil lengkap      | ✅ Selesai | 26 November 2025 |
| 6   | Responsivitas UI    | Mobile & desktop tampak konsisten  | ✅ Selesai | 26 November 2025 |

### 5. Muhammad Fauzan: POS Kasir – Repeater Item, Perhitungan, Cetak Struk

| No. | Fitur yang Diuji          | Deskripsi Uji                                     | Status                   | Tanggal Mulai     |
|-----|---------------------------|---------------------------------------------------|--------------------------|-------------------|
| 1   | Tampilan Awal POS         | Repeater dasar tampil                             | ✅ UI Dasar Berjalan     | 2-8 November 2025 |
| 2   | Penambahan Item Transaksi | Penambahan baris item berhasil                    | 🟡 Perlu Logika Tambahan | 2-8 November 2025 |
| 3   | Dropdown Menu & Varian    | Dropdown tampil, harga belum sepenuhnya otomatis  | 🔄 Dalam Progres         | 2-8 November 2025 |
| 4   | Kalkulasi Total Otomatis  | Subtotal & total belum final                      | ⏳ Belum Selesai         | 2-8 November 2025 |
| 5   | Input Bayar & Kembalian   | Field muncul, logika backend belum lengkap        | 🔄 Dalam Progres         | 2-8 November 2025 |
| 6   | Cetak Struk HTML/PDF      | Template awal ada, belum final                    | 🔄 Dalam Progres         | 2-8 November 2025 |

### 6. Revalina Adelia: Laporan, Export PDF/Excel, Workflow Transaksi, Dokumentasi

| No. | Fitur yang Diuji           | Deskripsi Uji                                        | Status               | Tanggal Mulai     |
|-----|----------------------------|------------------------------------------------------|----------------------|-------------------|
| 1   | Halaman Laporan            | Tabel laporan tampil                                 | ✅ UI Dasar Berjalan | 2-8 November 2025 |
| 2   | Filter Laporan             | Filter tanggal & status belum terhubung backend      | 🔄 Dalam Progres     | 2-8 November 2025 |
| 3   | Export PDf/Excel           | Tombol tampil, backend belum final                   | 🔄 Dalam Progres     | 2-8 November 2025 |
| 4   | Workflow Status Transaksi  | Status pending → paid → completed belum terintegrasi | ⏳ Belum Selesai     | 2-8 November 2025 |
| 5   | Dokumentasi README         | Struktur sudah tersusun dan sedang diisi             | 🔄 Dalam Progres     | 2-8 November 2025 |

---
## Struktur Folder Sementara

```
CAFELORA/
├── app/
│   ├── Filament/
│   │   ├── Pages/                     # Halaman custom Filament (POS)
│   │   └── Resources/                 # CRUD Resource (Menu, Category, User, dll)
│   ├── Http/
│   │   └── Controllers/               # Controller untuk frontend pelanggan
│   ├── Models/                        # Model database (Menu, Category, Transaction, dll)
│   └── Policies/                      # Policy untuk akses role
│
├── bootstrap/                         # File bootstrap Laravel
│
├── config/                            # Konfigurasi Laravel & Filament
│
├── database/
│   ├── migrations/                    # Struktur tabel database
│   ├── seeders/                       # Seeder (Role, Menu, DatabaseSeeder)
│   └── factories/                     # Factory untuk generate data dummy
│
├── docs/                              # Dokumentasi proyek
│   ├── images/                        # Gambar pendukung dokumen
│   ├── 1_ERD.md
│   ├── 2_FITUR.md
│   ├── 3_TAMPILAN.md
│   ├── 4_INSTALASI.md
│   ├── 5_DEPLOYMENT.md
│   └── 6_AGENDA.md
│
├── public/
│   ├── css/                           # File CSS aplikasi
│   ├── js/                            # File JS aplikasi
│   └── index.php                      # Entry point Laravel
│
├── resources/
│   └── views/                         # Halaman frontend (pelanggan & welcome page)
│
├── routes/
│   ├── web.php                        # Routing utama aplikasi
│   └── console.php
│
├── .env.example                       # Contoh konfigurasi environment
├── composer.json                      # Dependency PHP
└── package.json                       # Dependency JS
```

---
