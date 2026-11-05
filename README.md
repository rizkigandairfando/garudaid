# BrandSmart AI — Versi Tanpa API

Aplikasi web sederhana untuk membantu branding UMKM. Versi ini **tidak menggunakan OpenAI API, API eksternal, Supabase, atau backend**. Generator bekerja dengan template dan aturan JavaScript lokal.

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser, atau unggah folder ini ke GitHub lalu import repository ke Vercel.
3. Tidak perlu memasukkan API key atau membuat file `.env`.

## Akun demo
- Admin: `admin@brandsmart.local` / `admin123`
- UMKM: `umkm@brandsmart.local` / `umkm123`
- Konsultan: `konsultan@brandsmart.local` / `konsultan123`

## Fitur yang tersedia
- Login demo dengan tiga peran: Admin, UMKM, Konsultan.
- Dashboard sesuai peran.
- Profil usaha UMKM.
- Generator identitas merek berbasis template.
- Brief desain logo dan visual (teks, bukan file logo).
- Analisis target pasar berbasis aturan/template.
- Perencanaan pemasaran dan konten media sosial.
- Asisten bisnis berbasis panduan/template.
- Katalog produk: tambah dan hapus produk.
- Learning Center dan penanda materi selesai.
- Permintaan konsultasi.
- Ringkasan aktivitas dan analitik dasar.
- Penyimpanan data menggunakan `localStorage` pada browser.

## Batasan penting
- Istilah “AI” pada nama modul adalah konsep produk. Tanpa model AI/API, hasil dibuat dari template dan aturan lokal, bukan jawaban generatif yang memahami konteks secara mendalam.
- Akun demo bukan autentikasi aman. Kata sandi tersimpan di browser; jangan gunakan untuk data bisnis rahasia.
- Data hanya ada di browser/perangkat yang digunakan. Tidak tersinkron antarperangkat dan dapat hilang jika data situs/browser dihapus.
- Role dan akses hanya simulasi antarmuka, bukan keamanan backend.
- Belum tersedia upload gambar, pembuatan file logo otomatis, QR katalog, ekspor PDF, integrasi WhatsApp/Instagram/TikTok, pembayaran, notifikasi real-time, atau database online.
- Google Fonts membutuhkan koneksi internet; jika offline, browser memakai font cadangan.
- Untuk penggunaan produksi dengan banyak pengguna, diperlukan backend/database dan autentikasi aman.

## Struktur folder
```text
brandsmart-ai-tanpa-api/
├── index.html
├── style.css
├── app.js
└── README.md
```
