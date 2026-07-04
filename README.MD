📖 Deskripsi
BayarYuk! adalah aplikasi web simulasi pembayaran tagihan dan top-up yang dirancang dengan antarmuka modern dan responsif. Aplikasi ini memungkinkan pengguna untuk melakukan simulasi pembayaran berbagai jenis tagihan seperti:

⚡ Listrik PLN (Pasca & Prabayar)

💧 Air PDAM

🌐 Internet / TV Kabel

🎓 Biaya Kuliah / SPP

📱 Pulsa & Paket Data

Dibangun dengan HTML5, CSS3, JavaScript Vanilla, dan Tailwind CSS, aplikasi ini sepenuhnya berjalan di sisi klien (client-side) dengan penyimpanan data menggunakan LocalStorage.

🚀 Cara Menjalankan
Prasyarat
Browser modern (Chrome, Firefox, Edge, Safari)

Koneksi internet (untuk CDN dan library eksternal)

Langkah-langkah
Download file index.html dari repository ini

Buka file tersebut dengan browser favorit Anda (cukup double-click)

Aplikasi siap digunakan! 🎉

Catatan: Tidak perlu server web atau instalasi tambahan. Semua berjalan langsung di browser Anda.

Cara Penggunaan Cepat
Top Up Saldo - Klik tombol "Top Up Saldo" di dashboard untuk menambah saldo simulasi

Bayar Tagihan - Pilih kategori (PLN/PDAM/Internet), masukkan ID pelanggan, klik "Cek Tagihan"

Bayar SPP - Masukkan NIM (contoh: 202310000001), klik "Lihat Tagihan Semester"

Isi Pulsa - Masukkan nomor HP, pilih nominal, konfirmasi pembelian

Lihat Riwayat - Semua transaksi tersimpan di tab Riwayat

✨ Fitur yang Diimplementasikan
🏠 Dashboard
Saldo Simulasi - Tampilan saldo dengan fitur top-up instan

Statistik Pengeluaran - Grafik batang interaktif menggunakan Chart.js

Riwayat Terakhir - 3 transaksi terbaru dengan navigasi cepat

Kategori Layanan Cepat - Tombol akses langsung ke setiap layanan

Promo Banner - Informasi promo dengan tombol salin kode

💳 Bayar Tagihan
3 Kategori - PLN, PDAM, Internet

Validasi Input - Format ID pelanggan sesuai masing-masing kategori

Demo Data - Tombol "Gunakan Demo" untuk mengisi ID secara acak

Daftar ID Demo - List ID pelanggan yang bisa diklik langsung

Rincian Tagihan - Menampilkan nama, periode, pokok, denda, dan jatuh tempo

4 Metode Pembayaran:

BayarYuk-Pay (saldo)

Virtual Account (BCA)

QRIS (dengan countdown timer)

Teller / Retail

🎓 Biaya Kuliah / SPP
Validasi NIM - Format 12 digit angka

Demo NIM - 50+ NIM dengan data mahasiswa berbeda

Cek via Invoice - Cari tagihan langsung dengan kode invoice

Multi-pilih Tagihan - Pilih beberapa cicilan sekaligus

Total Otomatis - Jumlah tagihan terpilih terupdate real-time

2 Metode Pembayaran - BayarYuk-Pay & Virtual Account

📱 Pulsa & Data
Deteksi Provider Otomatis - Berdasarkan prefix nomor HP (Telkomsel, Indosat, XL, Tri, Smartfren)

2 Kategori Produk - Pulsa Nominal & Paket Internet

Grid Produk - Tampilan kartu produk yang informatif

Checkout Ringkasan - Detail pembelian di panel terpisah

2 Metode Pembayaran - BayarYuk-Pay & Virtual Account

📊 Riwayat Transaksi
Tabel Lengkap - ID, waktu, layanan, pelanggan, metode, total, status

Pencarian - Cari berdasarkan ID, nama, atau deskripsi

Filter Kategori - Filter berdasarkan jenis layanan

Filter Metode - Filter berdasarkan metode pembayaran

Export CSV - Unduh riwayat ke file Excel

Lihat Struk - Tampilkan ulang bukti transaksi

🧾 Struk & Cetak
Struk Digital - Tampilan struk yang rapi dengan font mono

Cetak Struk - Cetak langsung ke printer

Download PDF - Unduh struk sebagai file PDF menggunakan jsPDF

👤 Profil Pengguna
Klik untuk Edit - Klik area profil di header

Ubah Nama & Email - Simpan perubahan ke LocalStorage

Avatar Dinamis - Inisial nama tampil di avatar

💾 Penyimpanan Data
LocalStorage - Semua data (saldo, transaksi, profil) tersimpan di browser

Persistent - Data tetap ada meskipun browser ditutup

Reset Data - Tombol reset untuk menghapus semua data simulasi

🎨 UI/UX
Responsif - Tampilan optimal di desktop, tablet, dan mobile

Full Width - Halaman utama (tagihan & SPP) memenuhi layar

Animasi - Efek fade-in dan transisi halus

Toast Notifikasi - Feedback visual untuk setiap aksi pengguna

Dark Gradient - Desain modern dengan gradien hijau-teal