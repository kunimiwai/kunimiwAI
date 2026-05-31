# Setup Project Laravel Baru

## Objective
Membuat project Laravel baru di folder hydroponikgo dengan konfigurasi database MySQL dan Xampp.

## Prerequisites
- Laravel CLI atau Composer terinstall
- Xampp terinstall dan berjalan (Apache & MySQL aktif)
- Git initialized di folder ini

## High-Level Steps

### 1. Inisialisasi Project Laravel
- Jalankan command Laravel untuk membuat project baru di folder ini
- Pastikan semua file Laravel tergenerate dengan benar

### 2. Konfigurasi Database
- Setup MySQL di Xampp (pastikan service berjalan)
- Buat database baru dengan nama project
- Update file .env dengan credentials database yang sesuai (host, database name, username, password)

### 3. Setup Environment
- Generate APP_KEY di Laravel
- Pastikan file .env sudah lengkap dengan konfigurasi MySQL dan Xampp

### 4. Database Migration
- Jalankan migration untuk membuat table dasar
- Verify database berhasil terkoneksi

### 5. Testing
- Jalankan development server Laravel
- Verifikasi application berjalan tanpa error
- Cek koneksi database berfungsi

## Acceptance Criteria
- ✅ Project Laravel berjalan di localhost
- ✅ Database terkoneksi dengan Xampp
- ✅ File .env sudah dikonfigurasi
- ✅ Initial migration berhasil dijalankan
- ✅ Tidak ada error pada console/terminal

## Notes
- Gunakan standar Laravel best practices
- Pastikan dependency sudah terinstall lengkap
- Commit hasil setup ke git setelah selesai
