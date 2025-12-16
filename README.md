# Lab11Web
# Nama : Vivit Nurul Hidayah
# NIM : 312410110
# Kelas : TI.24.A.1
# Mata Kuliah : Pemrograman Web
# Dosen : Agung Nugroho S.Kom, M.Kom

# Praktikum 11 & 12 – PHP OOP

Project ini merupakan gabungan **Praktikum 11 dan Praktikum 12** pada mata kuliah Pemrograman Web.  
Aplikasi dibuat menggunakan **PHP OOP tanpa framework** dengan konsep **routing, CRUD, autentikasi, dan session**.

## Struktur Folder
```

lab11_php_oop/
├── class/
├── module/
│   ├── artikel/
│   └── user/
├── template/
├── config.php
├── index.php
└── .htaccess

````

---

## Konfigurasi Database
```sql
CREATE DATABASE latihan_oop;
USE latihan_oop;

CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(50),
  password VARCHAR(255),
  nama VARCHAR(100)
);

CREATE TABLE artikel (
  id INT AUTO_INCREMENT PRIMARY KEY,
  judul VARCHAR(100),
  isi TEXT
);
````

---

## Akun Login

* **Username:** admin
* **Password:** admin123

---

## Cara Menjalankan

1. Aktifkan Apache dan MySQL (XAMPP)
2. Simpan project di folder `htdocs`
3. Akses:

   ```
   http://localhost/lab11_php_oop/user/login
   ```

---

## Kesimpulan

Project ini berhasil mengimplementasikan konsep **PHP OOP, routing, CRUD, autentikasi, dan session** sesuai dengan materi Praktikum 11 dan 12.

```

