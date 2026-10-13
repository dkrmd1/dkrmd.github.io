# Diki Ramdani — Personal Portfolio

Portfolio pribadi statis untuk **Diki Ramdani**, dibuat dengan HTML, CSS, dan JavaScript murni agar bisa di-host gratis menggunakan GitHub Pages.

## Fitur

- Desain minimalis putih dengan aksen hijau.
- Responsive untuk desktop, tablet, dan smartphone.
- Navigasi mobile.
- Bagian profil, keahlian, project, cara kerja, dan kontak.
- Metadata SEO dasar dan favicon SVG.
- Tidak membutuhkan Node.js, Composer, database, atau backend.
- Tidak menggunakan framework atau build step.

## Struktur file

```text
portfolio-diki-ramdani/
├── index.html
├── style.css
├── script.js
├── .nojekyll
├── README.md
└── assets/
    └── favicon.svg
```

## Cara deploy ke GitHub Pages

### 1. Buat repository

Untuk website utama akun GitHub, nama repository harus persis sama dengan username GitHub diikuti `.github.io`.

Contoh untuk username `dkrmd1`:

`dkrmd1.github.io`

Buat repository di https://github.com/new, pilih **Public**, lalu klik **Create repository**. Boleh centang Add a README file; jika sudah ada README, timpa atau gabungkan dengan README ini.

### 2. Upload file portfolio

1. Extract ZIP ini di komputer.
2. Buka repository `dkrmd1.github.io` di GitHub.
3. Pilih **Add file → Upload files**.
4. Upload isi folder portfolio, bukan folder induknya. Pastikan `index.html` terlihat di root repository.
5. Klik **Commit changes**.

File `index.html`, `style.css`, `script.js`, dan `.nojekyll` harus berada di root repository, bukan di dalam folder tambahan.

### 3. Aktifkan GitHub Pages

1. Buka tab **Settings** pada repository.
2. Pilih **Pages** di sidebar.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`.
5. Klik **Save**.

Tunggu proses publikasi selesai. Biasanya hanya beberapa menit, tetapi dapat memerlukan hingga sekitar 10 menit. Setelah aktif, buka:

https://dkrmd1.github.io

Dokumentasi resmi: https://docs.github.com/en/pages/quickstart

## Cara mengganti isi portfolio

Buka file `index.html`, klik ikon pensil untuk mengedit, lalu cari bagian yang ingin diganti:

- **Nama dan deskripsi:** cari `Diki Ramdani` atau `hero-lead`.
- **Project:** cari `PROJECT PILIHAN` dan edit kartu project.
- **Email:** cari `mailto:dikiramdani009@gmail.com`.
- **GitHub:** cari `https://github.com/dkrmd1`.
- **Tahun:** diperbarui otomatis melalui `script.js`.

Setelah mengedit di GitHub, klik **Commit changes**. GitHub Pages akan menerbitkan pembaruan otomatis.

## Catatan sebelum dipublikasikan

- Periksa kembali alamat email dan tautan repository.
- Deskripsi project adalah ringkasan singkat; pastikan sesuai dengan fitur yang memang boleh dipublikasikan.
- Tambahkan foto profil asli jika diinginkan; jangan unggah informasi rahasia, kredensial, token API, atau data perusahaan.
- Link project yang belum tersedia sebaiknya tidak ditambahkan sebagai tautan palsu.
- Email ditampilkan secara publik di halaman kontak. Ganti bila ingin menggunakan alamat khusus untuk freelance.

## Teknologi

HTML5 · CSS3 · JavaScript · GitHub Pages
