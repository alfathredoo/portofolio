# Template Portofolio Pribadi

Website portofolio statis dengan HTML, CSS, dan JavaScript. Tidak memerlukan instalasi package atau build step.

## Struktur

```text
main/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    ├── documents/
    └── images/
```

## Menjalankan

Buka `index.html` di browser. Untuk pengalaman pengembangan yang lebih nyaman, gunakan ekstensi Live Server di VS Code.

## Personalisasi

1. Di `index.html`, ganti `[Nama Anda]`, `[NA]`, profesi, kota, cerita tentang diri, statistik, dan deskripsi proyek.
2. Ganti `halo@contoh.com` dengan alamat email Anda. Perbarui juga tautan LinkedIn, Instagram, dan GitHub.
3. Ganti URL foto profil dan gambar proyek dengan gambar Anda. Anda juga dapat menyimpan gambar di `assets/images/` lalu mengubah `src` menjadi, misalnya, `assets/images/foto-profil.jpg`.
4. Tambahkan file CV Anda ke `assets/documents/` bila diperlukan, lalu tambahkan tautan unduh di halaman.
5. Ubah warna dan tipografi melalui variabel di bagian `:root` dalam `css/style.css`.

Gambar contoh dan Google Fonts membutuhkan koneksi internet. Simpan gambar sendiri di folder aset jika ingin situs tidak bergantung pada layanan eksternal.
