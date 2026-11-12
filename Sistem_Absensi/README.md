# Sistem Absensi Siswa - GitHub Pages

Aplikasi statis HTML, CSS, dan JavaScript untuk GitHub Pages.

## Fitur
- Dashboard ringkasan absensi
- CRUD data siswa (tambah, edit, hapus, cari)
- Input absensi Hadir, Izin, Sakit, dan Alpa
- Rekap berdasarkan rentang tanggal dan kelas
- Cetak laporan dan unduh CSV

## Cara publikasi
1. Buat repository GitHub, misalnya `sistem-absensi-siswa`.
2. Upload `index.html`, `README.md`, dan `.nojekyll` ke root repository.
3. Buka **Settings > Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu beberapa menit. Alamat website akan tampil pada bagian GitHub Pages.

## Penyimpanan data
Aplikasi ini menggunakan `localStorage` pada browser. Data tersimpan pada browser/perangkat yang digunakan, bukan database online. Data tidak otomatis tersinkron ke perangkat lain dan dapat hilang jika data situs/browser dibersihkan. Unduh CSV laporan secara berkala sebagai salinan.
