# Reset Password BIMA - UMKT

Form reset password untuk sistem BIMA Universitas Muhammadiyah Kalimantan Timur.

## Deskripsi

Halaman web statis untuk membantu pengguna mereset password BIMA mereka. Form terintegrasi dengan Google Forms untuk pengumpulan data.

## Fitur

- ✅ Form Nama Lengkap dan Email
- ✅ Validasi input
- ✅ Integrasi Google Forms
- ✅ Responsive design dengan Tailwind CSS
- ✅ Success message setelah submit

## Deploy

Halaman ini dideploy menggunakan GitHub Pages.

## Google Form Setup

Form ini terkoneksi ke Google Form dengan entry IDs:
- `entry.1669995092` - Nama Lengkap
- `entry.1839343147` - Email

### Catatan Penting

Untuk memastikan form berfungsi dengan baik, pastikan pengaturan Google Form:
1. Tidak dibatasi hanya untuk domain tertentu (atau sesuaikan dengan kebutuhan)
2. Menerima respons dari pengguna yang tidak login (jika diperlukan)
3. Google Form dikonfigurasi untuk menerima POST requests dari domain GitHub Pages

## Local Development

Untuk testing lokal:

```bash
python -m http.server 5500
```

Buka browser ke `http://127.0.0.1:5500/`

## Teknologi

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Google Forms API

## Deadline

Formulir ini aktif hingga: **28 November 2025**

---

© 2025 Universitas Muhammadiyah Kalimantan Timur
