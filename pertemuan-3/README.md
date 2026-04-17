# 📘 MODUL EKSKUL PEMROGRAMAN WEB

## HTML, CSS & Bootstrap Dasar

---

## 🏫 Identitas Kegiatan

* **Nama Kegiatan** : Ekskul Pemrograman Web
* **Sasaran** : Santri Ekskul Pemrograman
* **Fokus** : Dasar Web & Portfolio Diri
* **Output Akhir** : Website portfolio pribadi (multi halaman)

---

## 📅 Jadwal Pertemuan

* **Pertemuan 3 – 10 Oktober 2025**
  GitHub Dasar 1

* **Pertemuan 4 – 13 Oktober 2025**
  GitHub Dasar 2

* **Pertemuan 5 – 23 Januari 2026**
  HTML & CSS Dasar 1

* **Pertemuan 6 – 30 Januari 2026**
  HTML & CSS Dasar 2

* **Pertemuan 7 – 06 Februari 2026**
  CSS & Bootstrap Dasar : Pengenalan Boostrap

* **Pertemuan 8 – 17 April 2026**
  Bootstrap Dasar 2 : Layoting & Komponen

---

## 🎯 Tujuan Pembelajaran

Setelah mengikuti ekskul ini, santri diharapkan mampu:

* Memahami dasar HTML & CSS
* Menggunakan GitHub untuk kolaborasi
* Menggunakan Bootstrap untuk desain web
* Membuat website portfolio pribadi
* Memahami konsep multi halaman website

---

## 📘 Proyek Akhir Ekskul

### 🎓 Portfolio Diri Santri

Setiap santri membuat **website portfolio pribadi** menggunakan:

* HTML
* CSS
* Bootstrap
* GitHub

Isi minimal:

* Profil diri
* Skill / minat
* Halaman hubungi saya

---

## 🔗 Repository & Modul

**Modul Materi**
GitHub Kolaborasi + HTML & CSS Data Diri

---

## 🔄 Mekanisme Pull & Push GitHub (Kolaborasi 4 Orang)

### Alur Kerja Standar

1. **Pull sebelum mulai kerja**

```bash
git pull origin main
```

2. **Edit / Update kode**

3. **Simpan ke staging**

```bash
git add .
```

4. **Commit perubahan**

```bash
git commit -m "menambahkan data diri [Nama]"
```

5. **Push ke GitHub**

```bash
git push origin main
```

---

## 🧩 Apa itu HTML?

HTML (*HyperText Markup Language*) adalah bahasa dasar untuk membuat halaman web.
HTML berfungsi sebagai **kerangka utama** website.

Perumpamaan:

* HTML = rangka rumah 🧱
* CSS = cat & dekorasi 🎨
* JavaScript = listrik & tombol ⚡

---

## 🧱 Struktur Dasar HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Judul Halaman</title>
  </head>
  <body>
    <h1>Halo Dunia!</h1>
    <p>Ini paragraf pertama saya.</p>
  </body>
</html>
```

---

## 📖 Penjelasan Struktur HTML

* `<!DOCTYPE html>` → Penanda HTML5
* `<html>` → Pembungkus seluruh halaman
* `<head>` → Informasi halaman (judul, CSS)
* `<title>` → Judul tab browser
* `<body>` → Konten yang tampil di layar

---

## 🧠 Elemen Dasar HTML

### Judul

```html
<h1>Judul</h1>
```

### Paragraf

```html
<p>Ini paragraf</p>
```

### Gambar

```html
<img src="gambar.jpg" alt="deskripsi">
```

### Link

```html
<a href="https://google.com">Google</a>
```

### List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### Button

```html
<button>Klik Saya</button>
```

---

## 🎨 Apa itu CSS?

CSS (*Cascading Style Sheets*) digunakan untuk **mengatur tampilan** HTML.

```css
p {
  color: blue;
  font-size: 16px;
}
```

---

## 🧩 Class & ID

### ID (unik)

```html
<h1 id="judul">Halo Dunia</h1>
```

```css
#judul { color: blue; }
```

### Class (bisa banyak)

```html
<p class="merah">Teks Merah</p>
```

```css
.merah { color: red; }
```

---

## 🧵 Jenis CSS

### Inline CSS

```html
<p style="color:red">Merah</p>
```

### Internal CSS

```html
<style>
  p { color: blue; }
</style>
```

### External CSS

```html
<link rel="stylesheet" href="style.css">
```

---

## 🅱️ Apa itu Bootstrap?

Bootstrap adalah **framework CSS** yang menyediakan **class siap pakai** untuk desain web yang rapi dan responsif.

---

## 📦 Menggunakan Bootstrap (CDN)

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
```

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

## 🧱 Konsep Dasar Bootstrap

### Container

```html
<div class="container">Konten</div>
```

### Grid

```html
<div class="row">
  <div class="col-6">Kiri</div>
  <div class="col-6">Kanan</div>
</div>
```

---

## 🧩 Komponen Bootstrap

### Button

```html
<button class="btn btn-primary">Kirim</button>
```

### Card

```html
<div class="card">
  <div class="card-body">Isi Card</div>
</div>
```

### Navbar

```html
<nav class="navbar navbar-dark bg-dark">
  <a class="navbar-brand" href="index.html">Portfolio</a>
</nav>
```

### Form

```html
<input class="form-control" placeholder="Nama">
```

---

## 🔁 Konsep Multi Halaman

Struktur:

```
index.html
contact.html
```

```html
<a href="contact.html">Hubungi Saya</a>
```

---

## 🧪 Studi Kasus Proyek Akhir

### Halaman Profil

* Foto
* Nama
* Deskripsi
* Skill (Card)

### Halaman Hubungi Saya

* Google Maps
* Form Kontak

---

## 🪄 Penutup

Ekskul ini bertujuan membekali santri dengan:

* Skill dasar pemrograman web
* Etika kolaborasi GitHub
* Portfolio digital yang bermanfaat

> *Gunakan waktu untuk belajar hal yang bermanfaat dan bernilai ibadah.*

---

**Barakallahu fiikum** 🙏
