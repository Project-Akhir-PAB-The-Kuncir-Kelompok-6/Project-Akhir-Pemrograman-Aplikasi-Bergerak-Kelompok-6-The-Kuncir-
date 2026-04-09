# ☕ Panasea Zone Coffee | Smart Cashier & Management System

Selamat datang di repository **Panasea Zone Coffee System**. Aplikasi ini adalah solusi digital untuk manajemen operasional kedai kopi, mulai dari sistem kasir (Point of Sale) hingga pelaporan penjualan harian untuk manajemen/owner.

---

## 👤 Informasi Project (Kelompok 6 - Kelas C)

* **Nama Anggota**:
    1. Nabil Daffa Athalasyah (2409116090)
    2. Moreno Ferdinand Farhantino (2409116097)
    3. Danial Hirzan Akbary (2409116098)
    4. Reswara Ganendra Rashi Dewa (2409116100)
* **Mata Kuliah**: Praktikum Pemrograman Aplikasi Bergerak 2026
* **Framework**: Flutter
* **Backend**: Supabase (Database & Auth)

---

## 📝 Deskripsi Aplikasi

**Panasea Zone Coffee System** dirancang untuk membantu UMKM kedai kopi dalam mendigitalisasi proses transaksi. Aplikasi ini menggantikan pencatatan manual dengan sistem berbasis cloud, memungkinkan kasir menginput pesanan dengan cepat dan pemilik (owner) dapat memantau total omzet serta riwayat transaksi harian secara real-time dari mana saja.

---

## 🚀 Fitur Utama

1.  **Sistem Kasir (Order Entry)**: Input menu pesanan customer secara dinamis.
2.  **Manajemen Transaksi (CRUD)**: Menambah, melihat, mengedit, dan menghapus data transaksi/pesanan.
3.  **Laporan Penjualan Harian**: Dashboard khusus bagi Manager/Owner untuk melihat total pendapatan per hari.
4.  **Autentikasi User**: Login aman menggunakan Supabase Auth untuk Staff dan Owner.
5.  **Real-time Database**: Sinkronisasi data instan antara aplikasi kasir dan dashboard owner.
6.  **Dual Theme Support**: Mendukung tampilan Light Mode dan Dark Mode.

---

## 🛠️ Widget yang Digunakan

Aplikasi ini dibangun menggunakan berbagai widget Flutter untuk menciptakan UI yang responsif:
* **Layout**: `Scaffold`, `Container`, `Column`, `Row`, `Padding`, `SizedBox`, `Expanded`, `Stack`.
* **Navigation**: `GetMaterialApp`, `BottomNavigationBar`, `Drawer`.
* **Form & Input**: `TextField`, `TextFormField`, `IconButton`, `ElevatedButton`.
* **Data Display**: `ListView.builder` (untuk daftar menu & riwayat), `Card`, `ListTile`, `FutureBuilder`, `Obx`.
* **Feedback**: `Get.snackbar`, `CircularProgressIndicator`.

---

## 📦 Penjelasan Package (Nilai Tambah)

Untuk meningkatkan fungsionalitas aplikasi, kami menggunakan beberapa library pihak ketiga:

1.  **`get` (GetX)**: Digunakan sebagai *State Management* untuk mengelola logika keranjang belanja dan navigasi antar halaman tanpa *context*.
2.  **`supabase_flutter`**: Library utama untuk menghubungkan aplikasi dengan database PostgreSQL dan sistem autentikasi Supabase.
3.  **`flutter_dotenv`**: Digunakan untuk keamanan data sensitif (API Key dan URL Supabase) agar tidak terekspos langsung di dalam kode sumber.
4.  **`google_fonts`**: Digunakan untuk kustomisasi tipografi agar tampilan aplikasi lebih modern dan profesional.
5.  **`intl`**: Digunakan untuk memformat mata uang (IDR) dan tanggal pada laporan penjualan agar mudah dibaca.

---

## 📸 Dokumentasi Aplikasi

| Landing Page | Login Kasir | Input Pesanan | Laporan Owner |
| :---: | :---: | :---: | :---: |
| ![Landing](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Landing%20Page.png) | ![Login](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Login%20Page.png) | ![Order](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Tambah%20Aset.png) | ![Report](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Update%20Profile%20Page.png)

---

## ⚙️ Cara Menjalankan Project

1.  Pastikan Flutter SDK sudah terinstall.
2.  Clone repository ini: `git clone [URL_REPO]`.
3.  Buat file `.env` di root project dan masukkan kredensial Supabase Anda.
4.  Jalankan `flutter pub get`.
5.  Hubungkan device/emulator, lalu jalankan `flutter run`.

---

*Project ini dibuat untuk memodernisasi operasional Panasea Zone Coffee - Praktikum Pemrograman Aplikasi Bergerak 2026.*
