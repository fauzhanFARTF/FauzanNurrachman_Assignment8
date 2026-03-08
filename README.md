# 🗺️ Peta Transportasi Jakarta

## Introduction

Website interaktif untuk menampilkan rute transportasi publik di **DKI Jakarta**, termasuk **Transjakarta (TJ), MRT, LRT, dan KRL Commuter Line** menggunakan peta interaktif.

Project ini dibuat sebagai bagian dari **tugas Web Development** yang berfokus pada penerapan **struktur HTML, penggunaan berbagai tag HTML, serta pembuatan website multi-halaman**.

---

## 📋 Ketentuan Tugas

Berdasarkan instruksi tugas, website harus memenuhi ketentuan berikut:

### 1. Menerapkan semua tag HTML yang telah diajarkan

Website harus menggunakan beberapa kategori tag HTML berikut:

#### a. Tag Text

Digunakan untuk menampilkan teks seperti:

- `<h1>` – `<h6>`
- `<p>`
- `<span>`
- `<br>`
- `<hr>`

#### b. Tag Text Style

Digunakan untuk memberi format pada teks:

- `<b>` / `<strong>`
- `<i>` / `<em>`
- `<u>`
- `<mark>`
- `<small>`

#### c. Tag Table

Digunakan untuk menampilkan data tabel:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

#### d. Tag List

Digunakan untuk membuat daftar:

- `<ul>`
- `<ol>`
- `<li>`

#### e. Tag Form Input

Digunakan untuk membuat input form:

- `<form>`
- `<input>`
- `<textarea>`
- `<button>`
- `<label>`

---

## 🌐 Struktur Website

Website terdiri dari **3 halaman utama**.

### 🏠 Home Page

Berisi:

- Judul website
- Informasi tentang proyek
- Penjelasan singkat mengenai sistem peta transportasi Jakarta

---

### 👤 About Page

Berisi informasi tentang developer:

- Pendidikan
- Latar belakang
- Informasi kontak

---

### 🗺️ Map Page

Berisi:

- Peta atau gambar map
- Visualisasi jalur transportasi Jakarta

---

## 🧱 Struktur HTML

Setiap halaman website menggunakan struktur HTML berikut:

- **Navbar** → navigasi antar halaman
- **Main** → konten utama halaman
- **Footer** → informasi tambahan dan copyright

Contoh struktur dasar HTML:

```html
<header>
  <nav>Menu Navigasi</nav>
</header>

<main>Konten halaman</main>

<footer>Informasi copyright</footer>
```

---

## ✨ Fitur Website

- 🗺️ Peta interaktif menggunakan **Leaflet.js**
- 🚌 Visualisasi 4 jenis transportasi Jakarta:
  - Transjakarta
  - MRT Jakarta
  - LRT Jakarta
  - KRL Commuter Line
- 🔍 Layer control untuk menampilkan / menyembunyikan jalur transportasi
- 📱 Responsive design untuk berbagai ukuran layar
- 🎯 Fokus area DKI Jakarta
- ♿ Menggunakan semantic HTML untuk aksesibilitas

---

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (ES6+)
- Leaflet.js 1.9.4
- OpenStreetMap
- ArcGIS REST API (BIG)

---

## 📁 Struktur Folder

```bash
project/
├── assets/
│ ├── jalur_transjakarta.geojson
│ ├── jalur_mrt.geojson
│ └── jalur_lrt_jakarta.geojson
│
├── css/
│ └── style.css
│
├── js/
│ └── script.js
│
├── home.html
├── about.html
├── maps.html
└── README.md
```

---

## 🚀 Instalasi

Clone repository:

```bash
# SSH
git clone git@github.com:fauzhanFARTF/FauzanNurrachman_assignment8.git

# HTTPS
git clone https://github.com/fauzhanFARTF/FauzanNurrachman_assignment8.git
```

Masuk ke folder project:

```bash
cd FauzanNurrachman_assignment8
```

Pastikan file GeoJSON tersedia di folder `assets/`:

```bash
assets/
├── jalur_transjakarta.geojson
├── jalur_mrt.geojson
└── jalur_lrt_jakarta.geojson
```

Buka project di browser dengan membuka file:

```bash
home.html
```

---

## 🖼️ Screenshots

### Home Page

![Home](assets/images/Home-Transportasi-Jakarta-02-21-2026_09_17_AM.png)

### About Page

![About](assets/images/About-Transportasi-Jakarta-02-21-2026_09_18_AM.png)

### Maps Page

![Maps](assets/images/Maps-Transportasi-Jakarta-02-21-2026_09_18_AM.png)

---

## 👤 Developer

**Fauzan Nurrachman**  
GIS Specialist & Developer

- 📷 Instagram: [https://www.instagram.com/fauzhan_nr/](https://www.instagram.com/fauzhan_nr/)
- 💼 LinkedIn: [https://www.linkedin.com/in/fauzan-nurrachman-75655b90/](https://www.linkedin.com/in/fauzan-nurrachman-75655b90/)

---

## 📄 License

© 2026 Fauzan Nurrachman  
All Rights Reserved
