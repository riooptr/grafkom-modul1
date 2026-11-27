# Lampiran dan status kegiatan lab

Input yang digunakan adalah data sintetis dari `make data`, bukan foto
pribadi. Karena itu tidak ada pengaturan kamera atau rasio kompresi kamera
yang dapat diklaim. Manifest mencakup citra uji sintetis, bukan 15 foto
warisan budaya dari berbagai sudut.

## Simpan atau screenshot

1. Lab 1: `toolchain.md`, `../data/manifest.csv`, dan `budget.md`.
   Screenshot output `make data` dan bagian tabel budget di `report.html`.
2. Lab 2: `hasil_test.txt` untuk hasil histogram, blur, resampling, luma,
   dan uji lain; `diagnosis_awal.txt` untuk angka sebelum perbaikan; dan
   `hasil_report.txt` untuk hasil perbandingan downscale. Screenshot tiga
   citra naive, linear-correct, dan difference pada `report.html`.
3. Lab 3: `prediksi_format.md`, `formats_crop_smooth.md`,
   `formats_crop_hifreq.md`, dan `hasil_report.txt`. Screenshot kedua tabel
   perbandingan format dan bagian CVD di `report.html`.
4. Simpan `report.html` sebagai lampiran mandiri, bersama kode sumber dan
   manifest. Untuk bukti reproduksi, screenshot terminal yang menunjukkan
   pemasangan requirements dan perintah `make data`, `make test`, serta
   `make report` setelah benar-benar dijalankan di lingkungan bersih.

## Yang masih perlu dikerjakan

- Perhitungan manual untuk set, perbandingan tiga citra dan penjelasan
  rasio; bacaan serta refleksi Lab 1. Dataset PPM sintetis tidak mempunyai
  kompresi kamera.
- Diagnosis tertulis pribadi sebelum melihat perbaikan, perubahan satu
  baris pada bug yang disediakan, histogram pergeseran, dan PSNR setelah
  perbaikan. Script bawaan sudah mempunyai jalur yang benar dan menghasilkan
  perbandingan, tetapi itu belum membuktikan perubahan kode oleh praktikan.
- Pengukuran banding 8-bit/5-bit, dithering, demonstrasi sapuan frekuensi
  dan alias, serta satu perbaikan pitfall yang terukur sebelum/sesudah.
- Perbandingan Pillow BOX dan linear-correct dengan PSNR/SSIM, kebijakan
  format, refleksi, dan laporan HTML yang memuat histogram serta tabel format.
- Uji reproduksi pada mesin atau clone bersih belum dilakukan. Prediksi format
  adalah hipotesis yang dicatat sebelum pengukuran pada sesi ini; bandingkan
  dengan tabel hasil dan tulis rekonsiliasi Anda sendiri.

Jangan menyatakan bagian yang belum dilakukan sebagai selesai; pengukuran dan
refleksi pribadi harus sesuai pekerjaan yang benar-benar dilakukan.
