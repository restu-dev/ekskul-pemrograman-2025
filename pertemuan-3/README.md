
# 📅 Pertemuan 3 – 10 September 2025  

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

## Contoh sederhana (HTML + CSS External):
- style.css
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

