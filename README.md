|   Rony Eltom Atibaman  |   TI.20.D.1   |
|------------------------|---------------|
|     Pemrograman Web    |  Praktikum 9  |

# Lab9Web
Disini saya akan membuat prpgram modular sederhana menggunakan PHP
# Langkah - langkah Praktikum

## Menjalankan XAMPP server
![xampp](scs/1.png)

## 1). Buat folder baru dengan nama lab9_php_modular pada docroot webserver
![folder](scs/2.png)

## 2). Buat file baru dengan nama header.php
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
<header>
    <h1>Modularisasi Menggunakan Require</h1>
</header>
    <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
</nav>
```
![gambar](scs/3.png)

## 3). Buat file baru dengan nama footer.php
```
<footer>
                <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```
![gambar](scs/4.png)

## 4). Buat file baru dengan nama home.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```
![home](scs/5.png)

## 5). Buat file baru dengan nama about.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```
![about](scs/6.png)

## 6). Hasil tampilan halaman home pada browser dengan menggunakan modular header dan footer
![hasil](scs/7.png)

## 7). Hasil tampilan halaman about pada browser dengan menggunakan modular header dan footer
![hasil](scs/8.png)

----------------------------------------------------

# Pertanyaan & Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.

# Hasil Run
## - Tampilan halaman home
![home](scs/9.png)

## - Tampilan halaman tambah barang
![tambah](scs/10.png)

# SEKIAN & TERIMA KASIH