# Personal Web — Black Pink Futuristic

Ini adalah personal website **single-page** (HTML + CSS + JS) dengan tema **black–pink neon**.

## Cara menjalankan

- Buka file `index.html` langsung di browser (double click).
- Alternatif: pakai Live Server (VS Code/Cursor) supaya lebih nyaman.

## Cara ganti foto kamu

Saat ini website pakai placeholder SVG.

- **Foto profil (Home)**:
  - Ganti file `assets/profile.svg` dengan foto kamu.
  - Cara paling gampang:
    1. Simpan fotomu sebagai `assets/profile.jpg` (atau `.png`)
    2. Edit di `index.html` dan ubah:
       - dari `./assets/profile.svg`
       - jadi `./assets/profile.jpg`

- **Foto gallery**:
  - Ganti `assets/gallery-1.svg` … `assets/gallery-6.svg` dengan foto kamu.
  - Cara paling gampang:
    1. Simpan fotomu sebagai `assets/gallery-1.jpg` … dst
    2. Edit di `index.html` dan ubah semua `gallery-*.svg` jadi `gallery-*.jpg`

## Cara ganti nama & tagline (1 tempat saja)

Edit `main.js`, bagian ini:

- `const name = "Nama Kamu";`
- `const tagline = "Tagline kamu di sini — singkat, confident, dan keren.";`

Nama akan otomatis muncul di Home, Biodata, dan Footer.

## Cara ganti biodata, deskripsi, achievements, skills, favorites

Edit langsung di `index.html`:

- Section **About Me**: biodata + description
- Section **Achievements**
- Section **Skills** & **I’m enjoy with…**
- Section **Favorite Things** + Quote

## Cara ganti social media & email contact

- Link sosial ada di section **Social** pada `index.html` (ubah `href` dan username).
- Email tujuan tombol contact ada di `main.js`:
  - cari `const to = "you@email.com";` lalu ganti jadi email kamu.

