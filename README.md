# 📦 CRUD Barang Laravel

Sebuah aplikasi web sederhana untuk manajemen data barang (CRUD - Create, Read, Update, Delete) menggunakan **Laravel 10+**, **Bootstrap**, dan **XAMPP**.

![Laravel](https://img.shields.io/badge/Laravel-php--framework-red?logo=laravel)
![PHP](https://img.shields.io/badge/PHP-8.1%2B-blue?logo=php)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## ✨ Fitur

✅ Tambah Barang  
✅ Edit Barang  
✅ Hapus Barang  
✅ Lihat Detail Barang  
✅ Upload Foto Barang  
✅ Validasi Form Otomatis

## 🚀 Cara Menjalankan

### Installasi
```bash
git clone https://github.com/Fikkanel/Tugas-RPL-PHP-Laravel.git
cd Tugas-RPL-PHP-Laravel
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```
---
## 📂 Struktur Folder
```bash
├── app/
│ └── Http/
│ └── Controllers/
│ └── BarangController.php
├── resources/
│ └── views/
│ └── barangs/
│ ├── index.blade.php
│ ├── create.blade.php
│ ├── edit.blade.php
│ └── show.blade.php
├── public/
│ └── foto_barang/
```

### 🖼️ Preview Antarmuka
| Halaman   | Tampilan                                                             |
| --------- | -------------------------------------------------------------------- |
| Dashboard | ![Tampilan Aplikasi](tampilan/Dashboard.png)   |
| Tambah    | ![Tampilan Aplikasi](tampilan/tambah.png) |
| Detail    | ![Tampilan Aplikasi](tampilan/detail.png)    |
