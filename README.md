# Kalkulator Zakat Mal Pribadi

Prototipe web app untuk menghitung zakat mal bagi pekerja dan investor Muslim yang hartanya tersebar di banyak tempat.

## Cara pakai

Buka `index.html` langsung di browser. Tidak perlu instalasi, framework, atau database. Semua hitungan berjalan di browser dan tidak ada data yang dikirim atau disimpan.

## Fitur

1. Form 4 jenis harta (kas dan tabungan, emas dan perak simpanan, investasi, piutang lancar) dengan keterangan dan contoh
2. Pengurang: utang jatuh tempo 12 bulan, dan tabungan dari gaji yang sudah dipotong zakat penghasilan (aktif secara bawaan, bisa dimatikan)
3. Harga buyback emas Antam per gram + tanggal harga, nisab = 85 gram x harga
4. Konfirmasi haul
5. Hasil: status (wajib, belum haul, belum wajib), zakat 2,5%, rincian, dan kalimat alasan
6. Penghitung waktu pengisian untuk uji target di bawah 10 menit

## Asumsi perhitungan

- Nisab 85 gram emas dengan harga buyback Antam, mengikuti panduan zakat emas BAZNAS
- Perhiasan yang dipakai wajar, rumah tinggal, kendaraan pribadi, dan perabot tidak dihitung
- Utang yang dikurangkan hanya yang jatuh tempo dalam 12 bulan ke depan
- Tabungan dari gaji yang sudah dizakati dikurangkan secara bawaan untuk menghindari zakat ganda dalam setahun

## Ukuran keberhasilan

Pengguna selesai menghitung dalam waktu kurang dari 10 menit dan bisa menjelaskan ulang hasilnya. Diuji ke 3 sampai 5 orang.

## Belum dibuat

Harga emas otomatis, login dan riwayat, koneksi bank, pengingat haul, jenis harta lain (aset usaha, kripto, perhiasan dipakai).

---

Alat bantu hitung, bukan fatwa.
