# 🏥 MedCampus - Sistem Informasi Klinik Digital

[![License: politeknik](https://img.shields.io/badge/License-politeknik-blue.svg)](LICENSE)
[![Status Proyek](https://img.shields.io/badge/Status-Completed-green.svg)]()
[![Bahasa](https://img.shields.io/badge/Bahasa-PHP%20%7C%20Python%20%7C%20JS-orange)]()

> **MedCampus** adalah aplikasi berbasis web untuk manajemen klinik kesehatan kampus yang dikembangkan sebagai bagian dari mata kuliah *Project Based Learning* (PBL). Aplikasi ini bertujuan untuk mendigitalisasi proses pendaftaran pasien, rekam medis elektronik, dan penjadwalan dokter guna meningkatkan efisiensi layanan kesehatan di lingkungan kampus.

![Demo Dashboard MedCampus](./assets/dashboard-preview.png)
*(Ganti dengan screenshot asli aplikasi Anda)*

## 📋 Daftar Isi

- [Latar Belakang PBL](#latar-belakang-pbl)
- [Fitur Utama](#fitur-utama)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Anggota Tim](#iwan gayus, joshua togar, jose joshua)
- [Prasyarat](#prasyarat)
- [Instalasi & Jalankan Lokal](#instalasi--jalankan-lokal)
- [Struktur Database](#struktur-database)
- [Dokumentasi API](#dokumentasi-api)
- [Kendala & Solusi](#kendala--solusi)
- [Lisensi](#lisensi)

## 🎓 Latar Belakang PBL

Proyek ini dikembangkan untuk memenuhi kebutuhan studi kasus nyata dalam mata kuliah PBL Semester [2]. Masalah utama yang diangkat adalah ineffisiensi dalam pencatatan manual di klinik kampus yang sering menyebabkan antrian panjang dan hilangnya data riwayat pasien.

**Tujuan Pembelajaran:**
1. Menerapkan prinsip *Software Development Life Cycle* (SDLC).
2. Mengimplementasikan arsitektur MVC / Clean Architecture.
3. Bekerja secara kolaboratif menggunakan Git & GitHub Flow.

## ✨ Fitur Utama

### 👤 Untuk Pasien (Mahasiswa/Dosen)
- **Registrasi & Login:** Autentikasi menggunakan NIM/NIP.
- **Booking Online:** Memilih dokter dan jadwal konsultasi tersedia.
- **Riwayat Medis:** Melihat diagnosa dan resep obat sebelumnya.
- **Notifikasi:** Pengingat jadwal kunjungan via email/WhatsApp.

### 👨‍⚕️ Untuk Dokter
- **Manajemen Jadwal:** Mengatur ketersediaan jam praktik.
- **Rekam Medis Elektronik (EMR):** Input diagnosa, gejala, dan resep obat.
- **Daftar Antrian:** Melihat daftar pasien yang akan datang hari ini.

### 🛠️ Untuk Admin
- **Manajemen Pengguna:** Tambah/edit/hapus data dokter, staf, dan pasien.
- **Laporan Bulanan:** Statistik jumlah kunjungan dan penyakit terbanyak.
- **Manajemen Obat:** Stok obat dan kategori.

## 🛠️ Teknologi yang Digunakan

### Backend
- **Framework:** [Laravel v10 / Node.js Express ] *(Sesuaikan)*
- **Database:** MySQL / PostgreSQL

### Frontend
- **Framework:** [html,css]
- **Styling:** Tailwind CSS / Bootstrap 5
- **State Management:** Redux / Context API

### Tools & DevOps
- **Version Control:** Git & GitHub
- **API Testing:** Postman
- **Deployment:** [Heroku / Vercel / AWS / Localhost]

## 👥 Anggota Tim

| Nama | NIM | Peran | Kontribusi Utama |
| :--- | :--- | :--- | :--- |
| [Joshua togar sibuea | [3312501104] | Project Manager & Backend Lead | Desain DB, API Auth, Deployment |
| [Iwan gayus pasaribu] | [3312501107] | Frontend Developer | UI/UX Design, Integrasi API Pasien |
| [Jose joshua hutagaol | [3312501110] | Backend Developer | Logika Booking, Rekam Medis |
## 📋 Prasyarat

Pastikan perangkat Anda telah terinstal:
- [PHP 8.1+](https://www.php.net/) atau [Node.js 18+](https://nodejs.org/)
- [Composer](https://getcomposer.org/) atau [npm/yarn](https://www.npmjs.com/)
- [MySQL](https://www.mysql.com/)
- Web Server (Apache/Nginx) atau XAMPP/Laragon

## ⚙️ Instalasi & Jalankan Lokal

Ikuti langkah berikut untuk menjalankan proyek di komputer lokal:

1. **Clone Repositori**
   ```bash
   git clone https://github.com/username-kelompok/medcampus.git
   cd medcampus
