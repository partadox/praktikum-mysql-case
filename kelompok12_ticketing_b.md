# Studi Kasus Kelompok 12 — Platform Ticketing "EventHub" (Variasi: Seating & Booking)

## Narasi

EventHub adalah platform ticketing digital yang dirancang khusus untuk event dengan sistem kursi bernomor. Platform ini melayani berbagai jenis acara seperti konser musik, pertandingan olahraga, pertunjukan teater, dan festival berskala besar. Setiap event yang terdaftar di EventHub diselenggarakan di sebuah venue tertentu dan dikategorikan berdasarkan jenis acaranya, sehingga memudahkan pelanggan dalam menemukan event yang sesuai minat mereka.

Setiap event di EventHub memiliki beberapa seksi tempat duduk (seating sections) dengan karakteristik yang berbeda-beda, misalnya seksi VIP di barisan terdepan dengan harga premium, Tribune A dan Tribune B di sisi kiri-kanan panggung dengan harga menengah, serta area Festival untuk penonton berdiri dengan harga paling terjangkau. Setiap seksi memiliki kapasitas dan harga tersendiri, dan sistem secara otomatis memantau ketersediaan kursi agar tidak terjadi kelebihan pemesanan (overbooking).

Pelanggan yang telah terdaftar di EventHub dapat memesan kursi spesifik melalui sistem booking. Setiap pemesanan menghasilkan sebuah tiket dengan kode unik yang berfungsi sebagai barcode untuk masuk ke venue. Proses booking berstatus pending hingga pelanggan menyelesaikan pembayaran melalui salah satu metode yang tersedia: transfer bank, e-wallet, atau kartu kredit. Jika pembayaran tidak diselesaikan dalam batas waktu yang ditentukan, booking akan otomatis hangus dan kursi dikembalikan ke stok yang tersedia.

