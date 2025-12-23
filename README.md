# Praktikum 11 – PHP OOP Lanjutan

Repository ini berisi hasil pengerjaan **Praktikum 11 PHP OOP Lanjutan**  
Mata Kuliah Pemrograman Web – Universitas Pelita Bangsa.

Praktikum ini berfokus pada penerapan:
- Konsep **PHP Object Oriented Programming (OOP)**
- **Modularisasi program**
- **Routing sederhana** menggunakan `.htaccess`
- Struktur framework sederhana tanpa library tambahan

---

## Identitas Mahasiswa
- **Nama** : Razy Al Farisi  
- **NIM** : 312410524  
- **Kelas** : TI.24.A5  

---

## Tujuan Praktikum
- Memahami konsep framework modular sederhana
- Menerapkan routing pada aplikasi PHP
- Menggunakan class OOP untuk database dan form
- Mengelola modul artikel dengan struktur terpisah

---

## Struktur Folder Project
Project disusun dengan struktur sebagai berikut:

![Struktur Folder](img/struktur-folder.png)

---

## Routing & Modularisasi
Routing diterapkan menggunakan file `.htaccess` sehingga URL dapat diakses tanpa menyebutkan file `.php`.

Contoh URL:
- `/lab11_php_oop/artikel`
- `/lab11_php_oop/artikel/tambah`

Routing dikendalikan melalui file `index.php` yang bertugas memuat modul sesuai request URL.

---

## Halaman Artikel
Halaman ini menampilkan daftar artikel yang tersedia.

![Halaman Artikel](img/artikel.png)

---

## Tambah Artikel
Halaman ini digunakan untuk menambahkan data artikel baru melalui form input.

![Tambah Artikel](img/tambah-artikel.png)

---

## Penyimpanan Data ke Database
Data artikel yang ditambahkan melalui form berhasil disimpan ke dalam database `latihan_oop` pada tabel `artikel` menggunakan class `Database`.

![Database Artikel](img/db-artikel.png)

---

## Kesimpulan
Melalui praktikum ini, konsep PHP OOP, modularisasi, dan routing berhasil diterapkan dalam sebuah framework sederhana.  
Fitur yang diimplementasikan meliputi penampilan dan penambahan data artikel sesuai dengan kebutuhan praktikum.

