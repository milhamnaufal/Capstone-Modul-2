**Latar Belakang**

Projek ini bertujuan untuk menganalisis riwayat transportasi Transjakarta pada bulan April 2023. PT Transjakarta ingin memahami tren dan insight dari data riwayat transportasi untuk merumuskan program transportasi yang lebih nyaman bagi pengguna di masa depan.

**Prosedur Analisis**
1. Data Understanding: Mengidentifikasi informasi yang terdapat dalam dataset untuk memahami data dengan lebih baik.
2. Perumusan Masalah: Merumuskan permasalahan yang akan diteliti dalam analisis.
3. Data Cleaning: Melakukan pembersihan data untuk mengatasi noise yang dapat mengganggu analisis, termasuk penanganan missing value, outlier, whitespace, dan format data.
4. Data Analysis: Mengekstrak insight dan tren dari dataset sesuai dengan permasalahan yang telah ditentukan sebelumnya. Analisis akan disertai dengan visualisasi seperti Bar Plot, Line Plot, dan Scatter Plot. Setiap hasil analisis akan disertai rekomendasi yang dapat dijadikan acuan bagi PT Transjakarta.
5. Data Understanding
   
Dataset mengandung informasi berikut:

TransID: Kode unik setiap transaksi.

payCardID: Kode unik setiap kartu pembayaran pengguna.

payCardBank: Jenis transaksi pengguna.

payCardName: Nama pengguna dari setiap kartu pembayaran.

payCardSex: Gender pengguna dari setiap kartu pembayaran.

direction: Arah rute setiap pengguna (0 = pergi; 1 = kembali).

tapInStops: Kode unik terminal tempat pengguna mulai berangkat.

tapInStopsName: Nama terminal tempat pengguna mulai berangkat.

tapInStopsLat: Koordinat latitude terminal tempat pengguna berangkat.

tapInStopsLon: Koordinat longitude terminal tempat pengguna berangkat.

stopStartSeq: Urutan terminal tempat pengguna mulai berangkat dalam sebuah rute.

tapInTime: Waktu dalam bentuk tanggal beserta jam pengguna mulai berangkat.

tapOutStops: Kode unik terminal tempat pengguna turun.

tapOutStopsName: Nama terminal tempat pengguna turun.

tapOutStopsLat: Koordinat latitude terminal tempat pengguna turun.

tapOutStopsLon: Koordinat longitude terminal tempat pengguna turun.

stopEndSeq: Urutan terminal tempat pengguna turun dalam sebuah rute.

tapOutTime: Waktu dalam bentuk tanggal beserta jam pengguna turun.

payAmount: Biaya yang harus dikeluarkan pengguna.

**Poin Analisis**

1. Korelasi antar variabel
2. Jumlah transaksi berdasarkan waktu (harian dan jam).
3. Jumlah transaksi berdasarkan 5 lokasi terminal terbanyak.
4. Jumlah transaksi berdasarkan gender dan jenis pembayaran.
5. Statistika deskriptif pay amount berdasarkan gender.
