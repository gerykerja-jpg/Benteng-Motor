# Aplikasi HP Benteng Motor

Versi HP dibuat sebagai **PWA (Progressive Web App)**. Aplikasi dapat dibuka dari GitHub Pages dan dipasang ke layar utama Android tanpa Play Store.

## Mengaktifkan hosting GitHub Pages dari HP

1. Buka repository **Benteng-Motor**.
2. Tekan **Settings**. Pada tampilan HP, menu ini biasanya berada di **More**.
3. Pilih **Pages**.
4. Pada **Build and deployment**, ubah **Source** menjadi **Deploy from a branch**.
5. Pilih branch **main**.
6. Pilih folder **/ (root)**.
7. Tekan **Save**.
8. Tunggu sekitar 1–3 menit sampai GitHub menampilkan alamat situs.

## Alamat aplikasi

`https://gerykerja-jpg.github.io/Benteng-Motor/app.html`

## Memasang di Android

1. Buka alamat aplikasi menggunakan Google Chrome.
2. Tekan tombol **Pasang Aplikasi** yang muncul di kanan bawah.
3. Bila tombol belum muncul, tekan menu Chrome **⋮** lalu pilih **Tambahkan ke layar utama** atau **Instal aplikasi**.

## Berkas PWA

- `app.html` — tampilan aplikasi HP dan tombol instalasi.
- `manifest.webmanifest` — nama, warna, ikon, dan mode aplikasi.
- `sw.js` — penyimpanan cache agar aplikasi dapat tetap dibuka saat koneksi terputus.
- `icon.svg` — ikon Benteng Motor.

> Data MobilKu saat ini disimpan secara lokal di perangkat melalui browser. Data di satu HP tidak otomatis tersinkron ke HP lain. Gunakan fitur Backup pada aplikasi secara rutin.
