# Studi Kasus Kelompok 03 — Sistem Informasi Klinik "RS Sehat Sentosa" (Variasi: Obat & Resep)

## Narasi

RS Sehat Sentosa adalah rumah sakit umum swasta yang telah berdiri sejak tahun 1998 di Jakarta Selatan. Selama lebih dari dua dekade beroperasi, seluruh proses administrasi rumah sakit masih dijalankan secara manual: data pasien dicatat di buku besar, jadwal dokter ditempel di papan pengumuman, dan stok obat di bagian farmasi hanya dilacak menggunakan spreadsheet yang sering tidak sinkron antar bagian. Kondisi ini menyebabkan berbagai masalah operasional, mulai dari duplikasi data pasien, kesalahan penjadwalan dokter, hingga resep yang tidak dapat dipenuhi karena stok obat habis tanpa peringatan sebelumnya.

Manajemen RS Sehat Sentosa akhirnya memutuskan untuk melakukan digitalisasi sistem informasi rumah sakit secara menyeluruh. Program digitalisasi ini mencakup empat area utama: pertama, manajemen data pasien yang terintegrasi dengan nomor identitas unik; kedua, pengelolaan jadwal dokter per departemen beserta sistem appointment yang terstruktur; ketiga, rekam medis elektronik yang terhubung langsung dengan setiap sesi pemeriksaan; dan keempat, manajemen obat dan resep yang memungkinkan farmasi memantau stok secara real-time dan mendapatkan peringatan otomatis ketika stok mendekati batas minimum.

Sistem informasi yang akan dibangun dirancang dengan basis data relasional MySQL. Setiap pasien yang mendaftar akan mendapatkan nomor rekam medis permanen. Ketika pasien membuat janji temu (appointment) dengan dokter, data keluhan awal langsung tersimpan. Setelah pemeriksaan selesai, dokter mengisi rekam medis berisi diagnosis dan tindakan, kemudian menerbitkan resep obat yang secara otomatis terhubung ke sistem inventaris farmasi. Dengan demikian, seluruh alur pelayanan dari pendaftaran pasien hingga pengeluaran obat dapat terlacak, teraudit, dan dilaporkan secara akurat.

