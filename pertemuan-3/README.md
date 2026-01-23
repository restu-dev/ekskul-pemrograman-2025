
# Pertemuan
## 📅 Pertemuan 3 – 10 Oktober 2025  
## 📅 Pertemuan 4 – 13 Oktober 2025 
## 📅 Pertemuan 5 – 23 January 2026

## 📘 Praktikum GitHub dengan Studi Kasus Data Diri

## Review Sebelumnya
- **Materi 1** → pengenalan pemrograman, algoritma, frontend.  
- **Materi 2** → pengenalan GitHub: repo, file, codespaces, commit, push.  

---

## Fokus Materi 3
- Belajar **kolaborasi 1 repo dengan 4 orang**.  
- Studi kasus: **membuat halaman Data Diri sederhana** dengan HTML + CSS.  
- Melatih alur kerja: `pull → add → commit → push`.

---

## 🔄 Mekanisme Pull & Push GitHub (Kolaborasi 4 Orang)

## Alur Kerja
1. **Pull dulu sebelum kerja**
  ```bash
   git pull origin main
  ```
2. **Update Kode**

3. **Simpan ke staging**
  ```bash
   git add .
  ```
4. **Buat commit (catatan perubahan)**
  ```bash
   git commit -m "menambahkan data diri [Nama]"
  ```
5. Push ke GitHub
  ```bash
  git push origin main
  ```

---

## 🧩 Apa itu HTML?

HTML (HyperText Markup Language) adalah bahasa dasar untuk membuat halaman web.
Bisa dibilang, HTML adalah kerangka (tulang) dari sebuah situs web — tempat kamu menulis teks, gambar, link, tombol, video, dan lainnya agar bisa tampil di browser (seperti Chrome, Firefox, Safari, dll).

Bayangkan seperti membangun rumah:

HTML = rangka dan dinding rumah 🧱

CSS = cat dan dekorasinya 🎨

JavaScript = listrik dan tombol-tombolnya ⚡

## 🧱 Struktur Dasar HTML
Sebuah file HTML biasanya punya bentuk seperti ini:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Judul Halaman</title>
  </head>
  <body>
    <h1>Halo Dunia!</h1>
    <p>Ini adalah paragraf pertama saya.</p>
  </body>
</html>
```

## 📖 Penjelasan Baris per Baris
```html 
<!DOCTYPE html>
```
#### Memberi tahu browser bahwa ini adalah dokumen HTML versi terbaru (HTML5).

```html 
<html> ... </html>
```
#### Tag utama yang membungkus seluruh isi halaman web.

```html
<head> ... </head>
```
#### Bagian “kepala” — berisi informasi tentang halaman (judul, CSS, meta data, link). Tidak tampil langsung di layar.

```html
<title> ... </title>
```
#### Menentukan judul halaman (yang muncul di tab browser).

```html
<body> ... </body>
```
#### Bagian “tubuh” — berisi semua konten yang terlihat oleh pengguna: teks, gambar, tombol, tabel, dsb.

## 🧠 Contoh Elemen Dasar di ```html <body> ```

### Judul
```html
<h1>Halo Dunia</h1>
```
#### Menampilkan teks besar sebagai judul. Ada dari ```<h1> sampai <h6>```

### Paragraf
```html
<p>Ini paragraf.</p>
```
#### Menampilkan teks paragraf.

### Gambar
```html
<img src="gambar.jpg" alt="Deskripsi">
```
#### Menampilkan gambar.

### Tautan
```html
<a href="https://google.com">Pergi ke Google</a>
```
#### Membuat link.

### Daftar
```html
<ul><li>Item 1</li><li>Item 2</li></ul>
```
#### Membuat daftar (bulleted list).

### Tombol
```html
<button>Klik Saya</button>
```
#### Menampilkan tombol yang bisa diklik.

## 🪄 Kesimpulan Singkat
 - HTML = bahasa untuk membuat struktur halaman web.
 - Disusun dari tag yang punya fungsi masing-masing.
 - Setiap tag punya pembuka dan penutup, misalnya ```<p> dan </p>```
 - Browser membaca HTML dari atas ke bawah untuk menampilkan konten di layar.

---

## 🎨 Apa itu CSS?
CSS (Cascading Style Sheets) adalah bahasa untuk mengatur tampilan (desain) dari halaman web.
Kalau HTML adalah kerangka rumah, maka CSS adalah cat, dekorasi, dan tata letak rumah itu.

## 🧩 Struktur Dasar CSS
CSS menggunakan “selector” untuk memilih elemen HTML, lalu memberi “property” dan “value” untuk mengubah tampilannya.

```css
p {
  color: blue;
  font-size: 16px;
}
```

Artinya:
Semua elemen <p> (paragraf) warnanya biru dan ukuran teksnya 16px.

## 💡 Contoh Properti CSS yang Sering Dipakai
| Properti           | Fungsi                | Contoh                         |
| :----------------- | :-------------------- | :----------------------------- |
| `color`            | warna teks            | `color: red;`                  |
| `background-color` | warna latar           | `background-color: yellow;`    |
| `font-size`        | ukuran huruf          | `font-size: 20px;`             |
| `text-align`       | posisi teks           | `text-align: center;`          |
| `margin`           | jarak luar elemen     | `margin: 10px;`                |
| `padding`          | jarak dalam elemen    | `padding: 5px;`                |
| `border`           | garis tepi            | `border: 1px solid black;`     |
| `width` & `height` | lebar & tinggi elemen | `width: 200px; height: 100px;` |

## 🪄 Kesimpulan
  - CSS = pengatur gaya & tampilan web.
  - Bisa ditulis di inline, internal, atau external file.
  - Menggunakan selector → property → value.
  - Membuat website jadi indah, rapi, dan profesional.

---

## 🧩 Classs dan Id

## 🎯 1. Apa itu id?

id adalah identitas unik dari satu elemen HTML.
Artinya, setiap halaman hanya boleh punya satu elemen dengan id yang sama.

```html
<h1 id="judul">Halo Dunia!</h1>
```

## ➕ Digunakan untuk:

Menandai elemen tertentu supaya bisa diubah lewat CSS atau JavaScript.
Misalnya kamu mau ubah warna teks dengan CSS:

```html
#judul {
  color: blue;
  text-align: center;
}
```

## 👥 2. Apa itu class?
class digunakan untuk memberi nama pada sekelompok elemen yang gayanya sama.
Berbeda dengan id, satu halaman boleh punya banyak elemen dengan class yang sama.

Contoh:

```html
<p class="teks-biru">Paragraf 1</p>
<p class="teks-biru">Paragraf 2</p>
<p class="teks-biru">Paragraf 3</p>
```

## ➕ Digunakan untuk:
Mengatur gaya semua elemen dengan class itu:

```css
.teks-biru {
  color: blue;
  font-size: 18px;
}
```
### 🔹 Di CSS, class ditulis dengan titik . (bukan #).

## ⚖️ Perbandingan Singkat

| Perbedaan        | `id`                           | `class`                           |
| :--------------- | :----------------------------- | :-------------------------------- |
| Sifat            | Unik (satu halaman hanya satu) | Bisa dipakai berkali-kali         |
| Penanda di CSS   | `#id`                          | `.class`                          |
| Contoh HTML      | `<div id="header"></div>`      | `<div class="menu"></div>`        |
| Contoh CSS       | `#header { ... }`              | `.menu { ... }`                   |
| Penggunaan di JS | `getElementById("id")`         | `getElementsByClassName("class")` |

---

## Studi Kasus: Data Diri
Setiap siswa membuat file HTML berisi biodata pribadi.  
Isi minimal:
- Nama  
- Kelas  
- Hobi  
- Foto (opsional)  

## Contoh sederhana (HTML + CSS inline):
```html
<h1 style="color:red">Andi</h1>
```

## Contoh sederhana (HTML + CSS internal):
```html
<head>
  <title>Data Diri Andi</title>
  <style>
    body { font-family: Arial; background: #f4f4f4; padding: 20px; }
    h1 { color: blue; }
    p { font-size: 14px; }
  </style>
</head>
```

## Contoh sederhana (HTML + CSS External): style.css
```css
body { font-family: Arial; background: #f4f4f4; }
h1 { color: blue; }
p { font-size: 14px; }
```

## ID → (unik, hanya untuk 1 elemen)
```html
<p id="judul">Halo Dunia</p>
```
- #judul { color: green; font-weight: bold; }

## Class → . (bisa dipakai banyak elemen)
```html
<p class="merah">Teks ini merah</p>
```
- .merah { color: red; }

## Cara Pemanggilan CSS

- Inline CSS
```css
<p style="color: red;">Teks Merah</p>
```

- Internal CSS
```css
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
```

- External CSS
```css
<link rel="stylesheet" href="style.css">
```


