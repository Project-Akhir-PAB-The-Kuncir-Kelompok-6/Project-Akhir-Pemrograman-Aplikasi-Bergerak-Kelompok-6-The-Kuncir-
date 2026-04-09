# ☕ Panasea Zone Coffee: Smart Cashier & Management System

Selamat datang di repository **Panasea Zone Coffee System**, sebuah solusi digital manajemen operasional kedai kopi yang modern. Aplikasi ini dikembangkan menggunakan framework **Flutter** dan **Supabase** sebagai backend untuk membantu proses transaksi kasir dan pelaporan manajemen secara real-time.

---

## 👤 Anggota Team The Kuncir (Kelompok 6) Kelas C

1. **Nabil Daffa Athalasyah** | 2409116090
2. **Moreno Ferdinand Farhantino** | 2409116097
3. **Danial Hirzan Akbary** | 2409116098
4. **Reswara Ganendra Rashi Dewa** | 2409116100

---

## 📝 Deskripsi Aplikasi & Alur Fitur

**Panasea Zone Coffee System** dirancang untuk mendigitalisasi pencatatan pesanan dan laporan keuangan. Aplikasi ini mengintegrasikan **Flutter** dengan **Supabase** untuk mengelola seluruh ekosistem kedai kopi:

1. **Sistem Kasir (Order Entry)**: Staff kasir dapat menginput pesanan customer, memilih menu kopi/makanan, dan memproses transaksi dengan cepat.
2. **Riwayat Transaksi**: Setiap transaksi yang selesai akan otomatis tersimpan ke database cloud (Supabase) secara real-time.
3. **Monitoring Owner**: Owner atau Manager memiliki akses khusus untuk melihat riwayat transaksi harian dan total omzet per hari.
4. **Laporan Penjualan**: Sistem otomatis mengkalkulasi total laporan penjualan harian untuk memudahkan evaluasi bisnis.
5. **Autentikasi Keamanan**: Sistem login yang membedakan akses antara Staff (Kasir) dan Owner (Manajer).

---

## 📸 Dokumentasi Aplikasi

### Dashboard & Transaksi
| Halaman Kasir | Input Pesanan | Riwayat Penjualan | Laporan Owner |
| :---: | :---: | :---: | :---: |
| ![Kasir](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Daftar%20List%20Aset.png) | ![Order](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Tambah%20Aset.png) | ![History](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Table%20Editor.png) | ![Report](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Update%20Profile%20Page.png)

### Mode Tampilan
| **Dark Mode (Night Shift)** | **Light Mode (Day Shift)** |
| :---: | :---: |
| ![Dark](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Dark%20Theme.png) | ![Light](https://raw.githubusercontent.com/EazysPeazys/Mini-Project-2-PAB_Nabil-Daffa-Athalasyah/main/Light%20Theme.png) |

---

## ✨ Fitur Teknis Utama

1. **Real-time Database**: Menggunakan **Supabase** agar owner bisa memantau penjualan dari mana saja secara instan.
2. **State Management**: Implementasi **GetX** untuk logika keranjang belanja dan navigasi aplikasi yang ringan.
3. **Secure Credentials**: Penggunaan `flutter_dotenv` untuk melindungi API Key dan kredensial database.
4. **Dynamic Reporting**: Penarikan data (Fetch) laporan harian yang akurat berdasarkan timestamp transaksi.

---

## 🛠️ Widget yang Digunakan

* **Layout & Navigation**: `Scaffold`, `GetMaterialApp`, `ListView.builder`, `BottomNavigationBar`.
* **Data & Logic**: `GetXController`, `Obx`, `FutureBuilder`, `SupabaseClient`.
* **Design & Theme**: `ThemeData` (Dynamic Dark/Light Mode), `Card`, `GoogleFonts`.

---

## 🚀 Cara Menjalankan Project

1. Clone repository ini.
2. Siapkan file `.env` berisi `SUPABASE_URL` dan `SUPABASE_KEY`.
3. Jalankan `flutter pub get` di terminal.
4. Jalankan aplikasi dengan `flutter run`.

---

*Project ini dibuat oleh The Kuncir Team untuk memodernisasi operasional Panasea Zone Coffee - Praktikum Pemrograman Aplikasi Bergerak 2026.*
