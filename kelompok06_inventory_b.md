# Studi Kasus Kelompok 06 — Sistem Inventory & Penjualan "PT Mitra Distribusi" (Variasi: Sales Order)

## Narasi

PT Mitra Distribusi adalah perusahaan distributor B2B yang bergerak di bidang penyaluran barang-barang industri dan kebutuhan komersial kepada pelanggan korporat di berbagai kota di Indonesia. Perusahaan mengelola beberapa gudang yang tersebar secara strategis, antara lain di Jakarta dan Surabaya, untuk memastikan kelancaran distribusi ke seluruh wilayah cakupan. Setiap gudang memiliki kapasitas dan pengelola tersendiri, serta bertanggung jawab atas pergerakan stok barang masuk maupun keluar.

Dalam kegiatan operasional sehari-hari, PT Mitra Distribusi menerima pesanan dari pelanggan korporat melalui mekanisme Sales Order (SO). Setiap SO mencatat detail pemesanan mulai dari identitas pelanggan, gudang pengirim, daftar produk beserta kuantitas dan harga, hingga tanggal jatuh tempo pembayaran. Pelanggan diberikan batas kredit (credit limit) yang menjadi acuan maksimum piutang yang boleh berjalan. Sistem juga memantau status pembayaran setiap SO agar tim keuangan dapat menindaklanjuti piutang yang melampaui batas atau telah jatuh tempo.

Untuk mendukung efisiensi operasional, perusahaan membutuhkan sistem database terpadu yang mampu mencatat pergerakan stok secara real-time, mengelola siklus hidup SO dari status draft hingga delivered, serta menghasilkan laporan analitik seperti rekap penjualan bulanan, margin keuntungan per produk, dan monitoring piutang pelanggan. Database ini dirancang dengan delapan tabel yang saling berelasi, mencakup data gudang, kategori produk, pemasok, produk, pergerakan stok, pelanggan, sales order, dan detail item per SO.

