# 📘 Penjelasan Kode Website Sederhana (Catatan Belajar)

## 📌 Tujuan

Dokumen ini dibuat untuk membantu memahami setiap bagian dari kode HTML, CSS, dan JavaScript dalam satu file website sederhana.

---

## 🧱 Struktur Awal HTML

### `<!DOCTYPE html>`

Digunakan untuk memberi tahu browser bahwa file ini menggunakan HTML versi terbaru (HTML5).

### `<html lang="id">`

Tag utama yang membungkus seluruh isi halaman.
Atribut `lang="id"` menandakan bahwa bahasa yang digunakan adalah Bahasa Indonesia.

---

## ⚙️ Bagian `<head>`

### `<head>`

Berisi pengaturan halaman yang tidak terlihat langsung oleh pengguna.

### `<meta charset="UTF-8">`

Digunakan agar semua karakter (huruf, simbol) bisa ditampilkan dengan benar.

### `<meta name="viewport">`

Digunakan agar tampilan website menyesuaikan ukuran layar (responsive), terutama di HP.

### `<title>`

Menentukan judul halaman yang muncul di tab browser.

---

## 🎨 Bagian CSS (`<style>`)

CSS digunakan untuk mengatur tampilan website.

### `body`

* Mengatur font utama (Arial)
* Menghilangkan margin bawaan browser
* Memberi warna background

### `header`

* Mengatur warna latar belakang (gelap)
* Mengatur warna teks jadi putih
* Memberi jarak (padding)
* Teks rata tengah

### `nav`

* Background warna abu-abu
* Jarak dalam navbar
* Teks di tengah

### `nav a`

* Warna teks putih
* Jarak antar link
* Menghilangkan garis bawah

### `nav a:hover`

* Memberi efek garis bawah saat kursor diarahkan

### `main`

* Memberi jarak isi konten utama

### `section`

* Memberi jarak antar bagian
* Background putih
* Sudut membulat
* Efek bayangan

### `footer`

* Background gelap
* Teks putih
* Posisi selalu di bawah layar (fixed)

### `button`

* Mengatur ukuran tombol
* Warna hijau
* Sudut membulat
* Cursor berubah saat diarahkan

---

## 🧩 Bagian `<body>`

### `<body>`

Berisi semua elemen yang ditampilkan ke pengguna.

---

## 🔝 `<header>`

Bagian atas website:

* `<h1>` → judul utama
* `<p>` → deskripsi singkat

---

## 🧭 `<nav>`

Menu navigasi:

* `<a href="#home">` → menuju bagian home
* `<a href="#about">` → menuju bagian about
* `<a href="#contact">` → menuju bagian contact

---

## 📄 `<main>`

Bagian utama isi website.

---

## 📦 `<section id="home">`

* Berisi judul dan teks
* Terdapat tombol

### `<button onclick="tampilkanPesan()">`

Saat tombol diklik, akan menjalankan fungsi JavaScript.

---

## 📦 `<section id="about">`

Berisi penjelasan tentang website.

---

## 📦 `<section id="contact">`

Berisi form input data.

### `<form onsubmit="kirimForm(event)">`

Saat form dikirim, akan menjalankan fungsi JavaScript.

### `<label>`

Digunakan sebagai penjelas input.

### `<input>`

* `type="text"` → untuk nama
* `type="email"` → untuk email

### `<button type="submit">`

Digunakan untuk mengirim data form.

---

## 🔚 `<footer>`

Bagian bawah website, biasanya berisi copyright.

---

## ⚡ JavaScript (`<script>`)

Digunakan untuk menambahkan interaksi.

### `tampilkanPesan()`

Menampilkan alert saat tombol diklik.

### `kirimForm(event)`

* `event.preventDefault()` → mencegah halaman reload
* Mengambil nilai input nama
* Menampilkan pesan ke user

---

## 🧠 Kesimpulan

* HTML → struktur website
* CSS → tampilan website
* JavaScript → interaksi website

Dengan memahami ini, kita bisa mulai membuat website sederhana sendiri dan mengembangkannya lebih lanjut.
