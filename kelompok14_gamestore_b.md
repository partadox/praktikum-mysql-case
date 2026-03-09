# Studi Kasus Kelompok 14 — Toko Game Digital "PixelPlay" (Variasi: Achievement)

## Narasi

PixelPlay adalah platform toko game digital lokal yang memungkinkan pengguna membeli dan memainkan berbagai judul game secara langsung melalui platform. Berbeda dari toko game biasa, PixelPlay menempatkan sistem achievement sebagai fitur unggulan untuk meningkatkan keterlibatan dan loyalitas pengguna. Setiap game yang tersedia di platform memiliki daftar achievement tersendiri, mulai dari yang paling mudah diraih hingga yang sangat langka, dengan poin reward yang bervariasi sesuai tingkat kesulitannya.

Pengguna yang aktif bermain dapat membuka (unlock) achievement saat memenuhi syarat tertentu dalam game. Setiap achievement yang berhasil dibuka akan menambah poin ke profil pengguna, dan akumulasi poin tersebut menentukan level pengguna di platform. Sistem ini menciptakan motivasi berkelanjutan bagi pengguna untuk terus memainkan game dan mengeksplorasi seluruh konten yang tersedia.

Dari sisi arsitektur data, hubungan antara pengguna dan achievement merupakan contoh klasik relasi Many-to-Many: seorang pengguna dapat memiliki banyak achievement dari berbagai game, dan sebuah achievement dapat dimiliki oleh banyak pengguna. Relasi ini direpresentasikan melalui tabel junction `user_achievements`, yang mencatat detail kapan dan dalam kondisi apa seorang pengguna berhasil membuka sebuah achievement. Data pada tabel junction ini sangat berharga untuk analisis platform, seperti mengidentifikasi achievement yang paling sulit, pengguna paling aktif, serta tingkat penyelesaian achievement per game.

