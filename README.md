# Rose & Lily Garden 🌹

Taman bunga mawar dan lily berwarna merah, pink, dan putih yang tumbuh dan mekar dengan animasi. Teksnya menyala saat didekati kursor (atau disentuh di layar HP), dan pesan kecil di bawah tombol warna berganti setiap warna dipilih.

**Demo:** https://USERNAME.github.io/rose-lily-garden/

![Tangkapan layar Rose & Lily Garden](roselily.jpg)

## Fitur

- Animasi tumbuh: batang memanjang, daun muncul, lalu bunga mekar dan bergoyang pelan
- Empat pilihan warna: Campur, Merah, Pink, Putih
- Teks menyala mengikuti kursor, juga bisa dengan sentuhan di HP
- Pesan tersirat yang berganti di setiap warna, terinspirasi bahasa bunga
- Kelopak yang jatuh pelan di latar belakang
- Responsif di HP dan desktop, serta menghormati pengaturan *reduced motion*

## Teknologi

- HTML5
- CSS3 (animasi `@keyframes`, CSS variables, `color-mix`)
- JavaScript (SVG dinamis, event pointer)
- Bootstrap 5.3 lewat CDN (navbar, grid, card, badge, button group, toast)

## Cara menjalankan

1. Unduh atau *clone* repo ini.
2. Ubah nama `rose-lily-garden.html` menjadi `index.html` (kalau mau dipakai di GitHub Pages).
3. Buka file di browser. Butuh koneksi internet untuk memuat Bootstrap dan font.

Untuk GitHub Pages: **Settings → Pages → Branch `main` → folder `/ (root)` → Save**.

## Struktur

```
rose-lily-garden/
├── index.html      # seluruh halaman (HTML, CSS, JS dalam satu file)
├── roselily.jpg    # tangkapan layar untuk README
└── README.md
```

## Mengubah tampilan

- **Warna bunga:** ubah nilai `R`, `P`, dan `W` di bagian JavaScript.
- **Susunan bunga:** ubah array `plan` (posisi, tinggi, jenis, ukuran).
- **Pesan tersirat:** ubah isi `msgs`.
- **Seberapa luas teks menyala:** ubah angka `130` pada fungsi `paint()`.

## Yang dipelajari

- Menggunakan komponen Bootstrap: navbar, grid, card, badge, toast
- Membuat bentuk bunga dengan SVG `<symbol>` dan memakai ulang lewat `<use>`
- Menganimasikan elemen SVG dengan CSS
- Membuat efek menyala mengikuti kursor dengan memecah teks menjadi huruf

## Lisensi

Bebas dipakai untuk belajar.
