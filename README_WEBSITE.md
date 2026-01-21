# Wedding Invitation Website

Undangan pernikahan satu halaman (single page) responsif yang modern dan elegan.

## Fitur

✅ **Hero Section** dengan nama mempelai dan countdown timer ke hari pernikahan
✅ **Personalized Greeting** - Sapaan personal yang diambil dari URL query parameter `?to=`
✅ **Galeri Foto** - Grid galeri foto responsif dengan efek hover
✅ **Detail Acara** - Informasi waktu dan lokasi acara dengan tombol Google Maps
✅ **Form RSVP** - Form konfirmasi kehadiran sederhana
✅ **Floating Music Player** - Toggle player musik yang melayang

## Teknologi

- **HTML5** - Struktur semantik
- **Tailwind CSS** - Framework CSS utility-first via CDN
- **Alpine.js** - Framework JavaScript reaktif untuk interaktivitas
- **AOS.js** - Animasi scroll yang halus
- **Google Fonts** - Font serif elegan (Playfair Display & Cormorant Garamond)

## Cara Menggunakan

1. **Buka website**: Akses `index.html` melalui browser
   ```
   http://example.com/index.html
   ```

2. **Personalisasi undangan**: Tambahkan parameter `?to=` di URL untuk menampilkan nama tamu
   ```
   http://example.com/index.html?to=Ahmad%20Budi
   ```

3. **Kustomisasi konten**:
   - Ubah nama mempelai di bagian Hero Section
   - Sesuaikan tanggal pernikahan di JavaScript (line 360+)
   - Ganti gambar galeri dengan foto asli
   - Update detail lokasi dan link Google Maps
   - Sesuaikan warna tema di class Tailwind CSS

## Struktur File

```
.
├── index.html          # File utama website
└── README_WEBSITE.md   # Dokumentasi ini
```

## Fitur Detail

### 1. Hero Section & Countdown
Menampilkan nama mempelai, tanggal pernikahan, dan countdown timer real-time yang update setiap detik.

### 2. Personalized Greeting
Menampilkan sapaan khusus untuk tamu dengan mengambil nama dari URL:
- Format: `?to=Nama%20Tamu`
- Contoh: `index.html?to=Budi%20Santoso`

### 3. Galeri Foto
Grid responsif 2-4 kolom (tergantung ukuran layar) dengan efek zoom saat hover.

### 4. Detail Acara
Dua card untuk Akad Nikah dan Resepsi dengan:
- Ikon yang menarik
- Informasi waktu dan lokasi
- Tombol Google Maps yang membuka lokasi di tab baru

### 5. Form RSVP
Form konfirmasi kehadiran dengan field:
- Nama lengkap
- Status kehadiran (radio button)
- Jumlah tamu
- Pesan & ucapan
- Submit dengan animasi sukses

### 6. Floating Music Player
Tombol melayang di kanan bawah untuk play/pause musik latar.

## Responsif

Website ini responsif dan teroptimasi untuk:
- 📱 Mobile (< 768px)
- 📱 Tablet (768px - 1024px)
- 💻 Desktop (> 1024px)

## Animasi

Menggunakan AOS.js untuk animasi scroll:
- Fade up/down
- Zoom in
- Fade left/right
- Smooth scroll behavior

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## Kustomisasi Warna

Website menggunakan gradient purple-pink. Untuk mengubah warna:
1. Cari class `bg-purple-*` dan `bg-pink-*` di HTML
2. Ganti dengan warna Tailwind CSS lainnya
3. Update gradient di `.hero-bg` di section `<style>`

## Lisensi

Free to use and modify.
