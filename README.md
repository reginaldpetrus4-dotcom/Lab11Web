# Praktikum 11 – PHP OOP & Routing Sederhana

Repository ini dibuat untuk memenuhi tugas **Praktikum 11** pada mata kuliah **Pemrograman Web**.
Praktikum ini berfokus pada penerapan **Object Oriented Programming (OOP)**, **routing sederhana**, dan **struktur folder modular** menggunakan PHP.

## Tujuan Praktikum

- Memahami konsep routing sederhana pada PHP
- Menerapkan struktur direktori modular
- Mengimplementasikan konsep Object Oriented Programming (OOP)
- Memisahkan logika program, modul, dan template
- Menggunakan file `.htaccess` untuk URL tanpa ekstensi `.php`

## Struktur Direktori

- lab11_php_oop
  - .htaccess
  - index.php
  - config.php
  - class
    - Database.php
    - Form.php
  - module
    - artikel
      - index.php
      - tambah.php
      - ubah.php
  - template
    - header.php
    - sidebar.php
    - footer.php

## Penjelasan File dan Folder

### .htaccess
- Digunakan untuk mengaktifkan URL rewriting
- Memungkinkan halaman diakses tanpa menuliskan ekstensi `.php`

### index.php
- Berfungsi sebagai router utama aplikasi
- Mengatur modul dan aksi berdasarkan URL yang diakses

### Folder class
- Berisi class berbasis Object Oriented Programming (OOP)
- Database.php digunakan untuk koneksi database
- Form.php digunakan sebagai library pembuatan form

### Folder module/artikel
- Berisi modul halaman artikel
- index.php untuk halaman utama artikel
- tambah.php untuk halaman tambah artikel
- ubah.php untuk halaman ubah artikel

### Folder template
- Berisi bagian tampilan aplikasi
- header.php sebagai header halaman
- sidebar.php sebagai menu navigasi
- footer.php sebagai footer halaman

## Cara Menjalankan Program

- Jalankan XAMPP
- Aktifkan Apache
- Simpan folder project di dalam direktori:
  - C:\xampp\htdocs\
- Akses aplikasi melalui browser:
  - http://localhost/lab11_php_oop/

Contoh URL routing:
- http://localhost/lab11_php_oop/artikel/index
- http://localhost/lab11_php_oop/artikel/tambah

## Hasil Pengujian

- Routing berjalan tanpa ekstensi `.php`
- Modul dapat diakses sesuai URL
- Template berhasil ditampilkan
- Program berjalan tanpa error

## Kesimpulan

- Praktikum ini menerapkan konsep OOP pada PHP
- Routing sederhana digunakan untuk pengelolaan modul
- Struktur folder modular membuat aplikasi lebih rapi dan mudah dikembangkan
