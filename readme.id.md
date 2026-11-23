# html-3d-template

English version: [README.md](README.md)

Template HTML mandiri dengan elemen 3D Three.js + CSS — titik awal untuk proyek web.

## Fitur

- Satu berkas `index.html` yang mandiri — tanpa build dan tanpa dependensi yang perlu dipasang
- Adegan Three.js selayar penuh (Three.js r128 melalui CDN): icosahedron beranimasi dengan pencahayaan ambient dan directional
- Elemen 3D CSS: kubus berputar (`.scene` / `.cube`) dengan animasi rotasi 12 detik
- Warna tema melalui variabel CSS di `:root`, dengan mode terang/gelap otomatis dari `prefers-color-scheme`

## Penggunaan

Buka `index.html` di peramban (diperlukan koneksi internet untuk memuat Three.js dari CDN).

Untuk memulai proyek baru dari template ini, salin `index.html` lalu ubah: ganti warna tema pada variabel CSS `:root`, ganti geometri/material Three.js, atau tambahkan konten Anda sendiri pada bagian 3D CSS.

## Struktur Proyek

```
index.html  # seluruh template: gaya, adegan Three.js, dan elemen 3D CSS
```

## Lisensi

Proyek ini dilisensikan di bawah MIT License. Lihat berkas [LICENSE](LICENSE).
