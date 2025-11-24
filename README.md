#Nama : Muhammad Hafiyainul Yakin Wahid
#NIM : 312410164

```
# Praktikum 9 – PHP Modular & Routing

## Tujuan

* Memahami konsep modularisasi pada PHP.
* Memahami penggunaan fungsi require/include.
* Menerapkan routing agar setiap halaman menggunakan template yang sama.

## Struktur Folder

```
lab9_php_modular/
│── index.php
│── header.php
│── footer.php
│── style.css
│── config.php
│── .htaccess (opsional)
│── user/
│     ├── list.php
│     ├── add.php
│     ├── edit.php
│     └── delete.php
```

## Penjelasan

1. **header.php & footer.php**
   Digunakan sebagai template agar tampilan setiap halaman seragam.

2. **index.php**
   Berfungsi sebagai router yang membaca URL `page=` kemudian memanggil file halaman sesuai permintaan.

3. **config.php**
   Berisi koneksi database.

4. **Folder user**
   Berisi halaman CRUD (list, tambah, edit, delete) menggunakan database.

5. **Routing**
   Contoh URL:

   ```
   index.php?page=user/list
   ```

6. **SEO Friendly (opsional)**
   Menambahkan file `.htaccess` untuk menghilangkan `index.php` pada URL.

## Hasil

Aplikasi dapat menampilkan halaman berbeda dengan tampilan seragam dan mendukung fitur CRUD dengan database melalui sistem routing modular.
