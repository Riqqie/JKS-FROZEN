# Penyusun JKS Frozen RDI

Web app untuk menyusun JKS (jalur kunjungan salesman) frozen RDI dari file Excel toko. Hasilnya: wilayah per salesman, hari dan pekan kunjungan (M1, M2C13, M2C24, 4 pekan sekali), urutan rute, jam check-in, peta, dan ekspor Excel.

- Semua data diproses di browser pemakai. File toko dan omset tidak dikirim ke server mana pun, termasuk GitHub.
- Tidak perlu login. Cukup buka link GitHub Pages repo ini.

## Cara pakai singkat
1. Unduh template di aplikasi, isi kode toko, nama, titik (lat/long atau link Google Maps), omset, kelas, dan rata-rata EC (opsional).
2. Upload file, cek pengaturan (titik depo, jumlah salesman, jam kerja, kapasitas), lalu tekan **Susun JKS**.
3. Supervisor menilai di peta, menukar area di matriks atau mengedit toko, lalu **Ekspor Excel**. File ekspor bisa dibuka lagi untuk diedit lanjut.

## Memperbarui aplikasi
Ganti file `index.html` dengan versi baru (Add file → Upload files), lalu commit. GitHub Pages memperbarui link dalam 1–2 menit.
