# Portfolio Website - I Wayan Pius Wiprajana Samita

Sebuah website portfolio modern dan responsif yang menampilkan keahlian, pengalaman, dan proyek-proyek Anda.

## 🌟 Fitur

- **Design Responsif**: Bekerja optimal di semua perangkat
- **Animasi Menarik**: Smooth scrolling, fade-in effects, dan hover animations
- **Color Palette Kustom**: Menggunakan palet warna yang Anda tentukan
- **Gallery Interaktif**: Setiap proyek memiliki 3 gambar yang dapat diklik
- **Social Media Links**: Instagram, LinkedIn, dan GitHub
- **Single File**: Mudah di-hosting di GitHub Pages

## 🎨 Color Palette

- Primary Dark: `#3E5F44`
- Primary Medium: `#5E936C`
- Primary Light: `#93DA97`
- Primary Lightest: `#E8FFD7`

## 📁 Struktur Project

```
profile/
├── index.html          # File utama website
└── README.md          # Dokumentasi ini
```

## 🚀 Cara Deploy ke GitHub Pages

1. **Upload ke GitHub Repository**:

   - Buat repository baru di GitHub
   - Upload file `index.html` ke repository
   - Pastikan file bernama `index.html` (bukan `index.htm` atau nama lain)

2. **Aktifkan GitHub Pages**:

   - Pergi ke Settings repository
   - Scroll ke bagian "Pages"
   - Pilih source: "Deploy from a branch"
   - Pilih branch: "main" atau "master"
   - Pilih folder: "/ (root)"
   - Klik Save

3. **Akses Website**:
   - Website akan tersedia di: `https://username.github.io/repository-name`

## 📸 Penempatan Gambar Project

Saat ini website menggunakan placeholder images. Untuk mengganti dengan gambar project Anda:

### 📁 Project Images Structure

Place your project images in the following directories:

#### Project 1 - CARENSY Camera Rental System

- `images/project1/` - CARENSY camera rental platform screenshots (Laravel 11 + TailwindCSS)
  - `carensy_1.png` - CARENSY homepage/landing page
  - `carensy_2.png` - Camera catalog/product listing
  - `carensy_3.png` - Rental dashboard/admin interface

#### Project 2 - TESA Tourism Platform

- `images/project2/` - TESA sustainable tourism platform screenshots (Vue.js + Django)
  - `tesa_1.png` - TESA homepage/landing page
  - `tesa_2.png` - Cultural experiences showcase
  - `tesa_3.png` - Local community features

#### Project 3 - Food Go Mobile App

- `images/project3/` - Food Go restaurant management app screenshots (Flutter + Dart)
  - `food_go_1.png` - App homepage/menu listing
  - `food_go_2.png` - Menu management/form interface
  - `food_go_3.png` - Restaurant map/location view

#### Certifications

- `images/certificate/` - Professional certifications and achievement certificates
  - `cert1.jpg` - BNSP Junior Web Developer certification
  - `cert2.jpg` - Programming Fundamentals certificate
  - `cert3.jpg` - Database Management certificate
  - `cert4.jpg` - Web Development certificate
  - (Add more certificates as needed)

**Recommended image specifications:**

- Format: PNG or JPG
- Resolution: 600x400 pixels (maintains 3:2 aspect ratio)
- File size: Under 500KB for optimal loading

### Opsi 1: Hosting Gambar di Repository (Recommended)

1. Buat folder `images` di repository yang sama
2. Upload gambar project ke folder tersebut
3. Ganti URL gambar di `index.html`:

   ```html
   <!-- Ganti dari -->
   <img
     src="https://via.placeholder.com/600x400/3E5F44/ffffff?text=E-Commerce+Home"
     alt="E-Commerce Home"
     class="project-image active"
   />

   <!-- Menjadi -->
   <img
     src="images/project1-image1.jpg"
     alt="E-Commerce Home"
     class="project-image active"
   />
   ```

### Opsi 2: Hosting Gambar Eksternal

1. Upload gambar ke layanan seperti:
   - GitHub (folder images di repository)
   - Imgur
   - Cloudinary
   - Google Drive (dengan sharing public)
2. Salin URL gambar
3. Ganti URL di `index.html`

## ✏️ Customization

### Mengganti Informasi Personal

1. **Nama**: Edit di bagian `<h1>` dan `<title>`
2. **Deskripsi**: Edit di bagian "About Me"
3. **Social Media Links**:
   ```html
   <a
     href="https://instagram.com/your_username"
     target="_blank"
     title="Instagram"
   >
     <a
       href="https://linkedin.com/in/your_username"
       target="_blank"
       title="LinkedIn"
     >
       <a
         href="https://github.com/your_username"
         target="_blank"
         title="GitHub"
       ></a></a
   ></a>
   ```
4. **Contact Info**: Edit email, phone, dan location di bagian contact

### Mengganti Project

1. Edit informasi project di section `#projects`
2. Ganti judul, deskripsi, teknologi yang digunakan
3. Update links demo dan source code
4. Ganti gambar sesuai petunjuk di atas

### Menambah Project

Salin struktur project card dan sesuaikan:

```html
<div class="project-card animate-on-scroll">
  <!-- Project info -->
  <!-- Project images -->
</div>
```

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3 (dengan CSS Grid dan Flexbox)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts

## 📱 Responsive Design

Website ini fully responsive dan akan terlihat bagus di:

- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🎯 Tips untuk Gambar Project

1. **Ukuran Optimal**: 600x400 pixels
2. **Format**: JPG atau PNG
3. **Ukuran File**: < 500KB per gambar untuk loading yang cepat
4. **Kualitas**: Gunakan gambar berkualitas tinggi yang menunjukkan fitur utama project

## 📞 Support

Jika ada pertanyaan atau butuh bantuan customization, silakan hubungi melalui:

- Email: your.email@example.com
- GitHub Issues di repository ini

---

Made with ❤️ for I Wayan Pius Wiprajana Samita
