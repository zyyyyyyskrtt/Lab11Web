# Praktikum 11 – Framework PHP OOP (Modular & Routing)

## Identitas Mahasiswa
- Nama        : Razy Al Farisi  
- NIM         : 312410524
- Program Studi : Teknik Informatika  
- Universitas : Universitas Pelita Bangsa  

---

## Pendahuluan
Praktikum 11 ini bertujuan untuk menerapkan konsep **Object Oriented Programming (OOP)** pada PHP dengan membangun sebuah framework sederhana berbasis **modular dan routing**.  
Aplikasi dirancang agar memiliki struktur kode yang rapi, terorganisir, serta mudah dikembangkan pada tahap selanjutnya.

---

## Tujuan Praktikum
Tujuan dari pelaksanaan praktikum ini adalah:
1. Memahami penerapan konsep OOP pada bahasa pemrograman PHP  
2. Menerapkan routing URL menggunakan file `.htaccess`  
3. Membuat framework PHP sederhana dengan struktur modular  
4. Menghubungkan aplikasi PHP dengan database MySQL  
5. Mengimplementasikan fitur CRUD (Create, Read, Update, Delete)  

---

## Teknologi yang Digunakan
- PHP 8.x  
- MySQL  
- Apache (XAMPP)  
- Bootstrap 5  
- CSS  
- Visual Studio Code  

---

## Fitur Aplikasi
- Routing URL menggunakan `.htaccess`
- Struktur folder modular (class, module, template)
- CRUD Artikel:
  - Menampilkan daftar artikel
  - Menambahkan artikel
  - Mengubah artikel
  - Menghapus artikel
- Koneksi database menggunakan class berbasis OOP
- Tampilan antarmuka menggunakan Bootstrap dan CSS

---

## Struktur Folder Project

```text
lab11_php_oop/
├── index.php            (Router utama)
├── config.php           (Konfigurasi database)
├── .htaccess            (Routing URL)
├── class/
│   └── Database.php
├── module/
│   ├── home/
│   │   └── index.php
│   └── artikel/
│       ├── index.php
│       ├── tambah.php
│       ├── ubah.php
│       └── hapus.php
├── template/
│   ├── header.php
│   └── footer.php



## Struktur Database
**Nama Database:** `latihan_oop`  

**Tabel:** `artikel`

| Field | Tipe Data |
|------|----------|
| id | INT (Primary Key, Auto Increment) |
| judul | VARCHAR(100) |
| isi | TEXT |

---

## Cara Menjalankan Aplikasi
1. Jalankan Apache dan MySQL melalui XAMPP  
2. Simpan folder project di direktori `htdocs`  
3. Buat database `latihan_oop` di phpMyAdmin  
4. Buat tabel `artikel` sesuai struktur  
5. Akses aplikasi melalui browser:

---

## Dokumentasi Aplikasi

### 1. Struktur Folder Project
Menampilkan struktur folder aplikasi yang menunjukkan penerapan konsep modular.

![Struktur Folder](img/struktur_folder.png)

---

### 2. Halaman Daftar Artikel
Menampilkan seluruh data artikel yang tersimpan di dalam database.

![Daftar Artikel](img/artikel.png)

---

### 3. Halaman Tambah Artikel
Digunakan untuk menambahkan data artikel baru ke dalam database.

![Tambah Artikel](img/tambah_artikel.png)

---

### 4. Halaman Edit Artikel
Digunakan untuk mengubah data artikel yang telah tersimpan di dalam database.

![Edit Artikel](img/edit_artikel.png)

---

### 5. Database Artikel
Menampilkan data artikel pada database `latihan_oop`.

![Database](img/database.png)




