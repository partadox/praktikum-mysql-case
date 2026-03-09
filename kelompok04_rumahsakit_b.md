# Studi Kasus Kelompok 04 — Sistem Informasi Rumah Sakit "RS Harapan Bunda" (Variasi: Ruangan & Hasil Lab)

## Narasi

RS Harapan Bunda adalah rumah sakit umum tipe B yang melayani pasien rawat jalan dan rawat inap di kawasan Jakarta. Setiap harinya, puluhan dokter dari berbagai departemen spesialis menangani ratusan pasien dengan beragam kondisi medis. Selama ini, proses pencatatan ketersediaan kamar rawat inap dan hasil pemeriksaan laboratorium masih dilakukan secara manual menggunakan buku besar dan formulir kertas, sehingga sering menimbulkan masalah seperti double-booking kamar, hasil lab yang tertukar, serta keterlambatan dalam pengambilan keputusan klinis oleh dokter.

Untuk mengatasi persoalan tersebut, pihak direksi RS Harapan Bunda memutuskan untuk membangun sistem informasi rumah sakit berbasis database relasional. Sistem ini dirancang untuk mengelola seluruh alur pelayanan pasien secara digital dan terintegrasi, mulai dari pendaftaran pasien, penjadwalan janji temu dengan dokter, pembuatan rekam medis, hingga pencatatan hasil pemeriksaan laboratorium. Kamar rawat inap dikelola secara terpusat sehingga status ketersediaan dan tarif per kamar dapat diketahui secara real-time oleh petugas administrasi.

Database yang dibangun terdiri dari tujuh entitas utama yang saling berelasi: departemen, dokter, pasien, janji temu (appointment), rekam medis, kamar rawat inap, dan hasil laboratorium. Setiap rekam medis dapat memiliki satu atau lebih hasil lab yang terhubung langsung, sehingga dokter dapat menelusuri riwayat pemeriksaan pasien secara lengkap dan akurat. Kamar rawat inap berdiri sebagai entitas mandiri yang digunakan secara konseptual dalam proses penerimaan pasien rawat inap, dengan ketersediaan kamar diperbarui setiap kali ada pasien masuk atau keluar.

