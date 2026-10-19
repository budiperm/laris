---
title: Kebijakan Privasi Laris — Kasir & Cicilan
permalink: /privacy/
---

# Kebijakan Privasi — Laris: Kasir & Cicilan

_Berlaku sejak: 19 Oktober 2026 (diperbarui untuk Laris Pro)_

Laris ("aplikasi") adalah aplikasi Android untuk mencatat penjualan, pembelian, stok, dan cicilan
pembayaran barang bagi usaha kecil. Kebijakan ini menjelaskan data apa yang diolah aplikasi dan ke mana data itu pergi.

**Ringkasnya: semua data Anda disimpan di HP Anda sendiri. Pengembang tidak punya server dan tidak
menerima, melihat, atau menyimpan data Anda.**

## 1. Data yang Anda catat

Data yang Anda masukkan ke aplikasi, misalnya:

- nama, nomor HP, dan alamat customer serta toko/supplier;
- produk, barcode, satuan, harga modal, harga jual dan grosir, stok, dan foto produk;
- transaksi penjualan dan pembelian, retur, buka/tutup kasir, DP, jadwal cicilan, pembayaran, biaya operasional;
- pengaturan aplikasi (nama toko, dan sebagainya).

Data ini disimpan di **penyimpanan internal HP Anda** (database aplikasi). Aplikasi berjalan penuh tanpa internet.

## 2. Backup ke Google Drive milik Anda (opsional)

Jika Anda memilih **Hubungkan Google Drive**, aplikasi membuat file backup (`.zip`) dan mengunggahnya
ke **Google Drive akun Anda sendiri**, di folder **Laris Backup**, langsung dari HP Anda ke Google.

- Aplikasi hanya meminta izin `drive.file`: aplikasi hanya bisa melihat file yang dibuatnya sendiri,
  tidak bisa membuka file lain di Drive Anda.
- Pengembang **tidak** punya akses ke Drive Anda atau ke file backup tersebut.
- Pengiriman memakai koneksi terenkripsi (HTTPS). Penyimpanan di Drive tunduk pada
  [Kebijakan Privasi Google](https://policies.google.com/privacy).
- Anda bisa memutus koneksi kapan saja di **Lainnya → Pengaturan & backup**, dan menghapus file backup
  langsung dari Google Drive. Akses aplikasi juga bisa dicabut di
  [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

## 3. Berbagi lewat WhatsApp dan aplikasi lain

Kwitansi, nota, jadwal cicilan, pengingat, dan laporan hanya dikirim ketika **Anda sendiri** menekan
tombol bagikan. Aplikasi membuka WhatsApp (atau aplikasi pilihan Anda) dengan teks/gambar yang sudah
disiapkan; Anda yang memutuskan mengirimnya. Pengembang tidak menerima salinannya.

## 4. Kamera dan printer Bluetooth

- **Kamera** hanya dipakai saat Anda menekan tombol scan barcode di kasir atau form produk. Gambar diolah
  langsung di HP untuk membaca barcode, tidak disimpan, dan tidak dikirim ke pengembang. Pembaca barcode
  memakai Google ML Kit, yang mengirim data diagnostik ke Google (jenis dan versi perangkat, versi aplikasi,
  ID per instalasi, kecepatan dan error fitur; bukan gambar kamera dan bukan data transaksi Anda), sesuai
  [ketentuan ML Kit](https://developers.google.com/ml-kit/android-data-disclosure).
- **Bluetooth** hanya dipakai untuk mengirim struk ke printer thermal yang sudah Anda pasangkan di HP.
  Aplikasi tidak memindai perangkat di sekitar dan tidak memakai lokasi.

## 5. Backup manual ke file

**Simpan ke file** membuat file backup yang Anda simpan atau bagikan sendiri. File itu berisi seluruh
data aplikasi; simpan di tempat yang aman.

## 6. Laris Pro (pembelian dalam aplikasi)

Laris Pro dijual sebagai langganan bulanan atau pembelian sekali bayar lewat **Google Play**.

- Pembayaran diproses sepenuhnya oleh Google Play sesuai [Kebijakan Privasi Google](https://policies.google.com/privacy)
  dan [Persyaratan Layanan Google Play](https://play.google.com/about/play-terms/). Aplikasi dan pengembang tidak
  menerima nomor kartu, rekening, atau data pembayaran Anda.
- Aplikasi hanya membaca status pembelian dari Google Play Store di HP (produk apa yang dibeli dan kode
  pembeliannya) untuk membuka fitur Pro. Status itu disimpan di HP dan tidak dikirim ke server pengembang.
- Pengembang hanya melihat laporan penjualan agregat yang disediakan Google Play Console untuk semua penjual aplikasi.
- Langganan bisa dihentikan kapan saja di Google Play Store → Profil → Pembayaran & langganan.

## 7. Yang tidak dilakukan aplikasi

- Tidak ada akun/registrasi di server pengembang.
- Tidak ada iklan, analitik, atau pelacak pihak ketiga (selain data diagnostik ML Kit untuk pembaca barcode, lihat bagian 4).
- Tidak mengakses kontak, lokasi, log panggilan, atau galeri foto di luar foto yang Anda pilih sendiri untuk produk.
- Tidak menjual atau membagikan data kepada siapa pun.
- Aplikasi **tidak menyediakan atau menyalurkan pinjaman uang**. Aplikasi ini hanya alat pencatatan
  penjualan barang secara tunai maupun cicilan antara Anda dan customer Anda.

## 8. Data customer Anda

Anda bertanggung jawab atas data customer yang Anda catat. Kami menyarankan hanya mencatat data yang
diperlukan untuk transaksi dan menghapus data yang tidak dipakai lagi.

## 9. Menghapus data

- Hapus data tertentu langsung di aplikasi (customer, produk, transaksi).
- Hapus semua data: **Pengaturan Android → Aplikasi → Laris → Penyimpanan → Hapus data**, atau uninstall aplikasi.
- Hapus backup di Drive: buka Google Drive, hapus folder **Laris Backup**.

## 10. Anak-anak

Aplikasi ditujukan untuk pelaku usaha dewasa dan tidak ditujukan untuk anak-anak.

## 11. Perubahan kebijakan

Jika kebijakan ini berubah, versi terbaru dipasang di halaman ini dengan tanggal berlaku yang baru.

## 12. Kontak

Pertanyaan tentang privasi: [budipermadi@fiznet.web.id](mailto:budipermadi@fiznet.web.id)
