# Capstone Module 2 menggunakan Data Transjakarta 

** Dataset:**
Data Pelanggan Transjakarta di Bulan April 2023 yang terdiri dari  37.900 baris data dan 22 kolo (sebelum dibersihkan) dan 36.556 an 17 kolom (setelah dibersihkan).
Adapun data yang diperoleh ada beberapa yaitu:
kode kartu, jenis metode pembayaran, nama pelanggan, gender, tahun kelahiran, nama koridor, direction, nama perhentian dan koordinatnya, waktu tap in dan tap out, dan tarif 

**Teknik analisis:**
Satistik deskriptif dan statistik inferensial yang menggunakan pengujian korelasi spearman (untuk data kategorikal). 

**Key point analisis:** 
Dari data Transjakarta ini, ada beberapa yang ingi diperoleh insight yang dapat diperoleh adalah:

1. Analisis pola perjalanan penumpang Transjakarta dengan melihat pola tap-in (masuk) dan tap-out (keluar) di koridor (koridor terbanyak dan jam sibuk)
2. Frekuensi Penggunaan kartu untuk transaksi (payCardID)
3. Demografi pelanggan yang menggunakan layanan Transjakarta (gender, usia, tempat tinggal)
4. Informasi tentang lokasi halte (berdasarkan data tapInStopsLat/tapInStopsLon dan tapOutStopsLat/tapOutStopsLon) 
7. Jam sibuk rata-rata pelanggan TransJakarta berdasarkan data tap dan tap out time

**Kesimpulan dan saran:**
Dari analisis yang telah dilakukan, maka dibisa ditarik kesimpulan bahwa:

Layanan Transjakarta saat ini:
* Halte teramai adalah halte penjaringan dan BKN. 
* Koridor teramai adalah Cibubur - Balaikota, yang mana koridor ini merupakan layanan Royaltrans. 
* Waktu perjalanan penumpang saat ini bisa mencapai 3 jam. 
* Beberapa koridor, perlu ada evaluasi untuk mengurangi waktu perjalanan 

Karakteristik pelanggan Transjakarta:
* Mayoritas pelanggan adalah dengan jenis kelamin perempuan. 
* Metode transaksi yang banyak digunakan adalah bank DKI. 
* Pelanggan Transjakarta juga didominasi oleh penumpang dewasa dengan rentang umur 26-60 tahun
* Waktu yang paling sering digunakan oleh pelanggan untuk melakukan perjalanan di pagi pada 06.00 dan di sore pukul 17.00 dan di hari weekday saja → berangkat dan pulang kerja. 
* Mayoritas layanan yang paling banyak diminati pelanggan adalah layanan Reguler.

**Rekomendasi**

Cara meningkatkan jumlah pelanggan Transjakarta dan meningkatkan kepuasan pelanggan saat menggunakan layanan Transjakarta:

1. Penambahan petugas halte terutama di halte ramai pelanggan dan di jam sibuk agar dapat mengatur penumpang.
2. Penambahan bus untuk rute dengan jumlah pelanggan terbanyak dan mempersempit headway bus dan juga memperbanyak frekuensi bus terutama pada jam-jam sibuk agar waktu tunggu bus tidak terlalu lama.  
3. Untuk meningkatkan efisiensi waktu perjalanan, Transjakarta dapat mempertimbangkan rekomendasi berikut:
   * Evaluasi dan sesuaikan rute bus untuk meminimalkan kemungkinan macet atau jalan yang lambat.
   * Tingkatkan frekuensi layanan bus pada rute yang sering mengalami kemacetan untuk mengurangi waktu tunggu penumpang.
   * Perbarui sistem informasi penumpang untuk memberikan estimasi waktu perjalanan yang lebih akurat dan informasi terkini mengenai kondisi lalu lintas melalui aplikasi yang informasinya bisa diakses secara realtime oleh penumpang.
4. Dengan jumlah pelanggan yang didominasi oleh perempuan dan didominasi oleh orang dewasa maka perlu adanya penambahan bus dan ruang khusus perempuan di setiap bus layanan Transjakarta. Saat ini, Transjakarta memiliki bus pink yang hanya ada di beberapa koridor tertentu saja yaitu koridor 2, koridor 3, koridor 9, koridor 13 dan koridor 5. Maka bisa dilakukan penambahan di semua koridor dan layanan khususnya di koridor ramai pelanggan. 
5. Mayoritas metode pembayaran pelanggan adalah bank DKI, hal ini menunjukkan bahwa mayoritas pelanggan Transjakarta adalah pengguna bank DKI. Di halte Transjakarta ada vending machine yang menjual kartu. Transjakarta harus menyediakan kartu bank DKI lebih banyak dibandingkan dengan jenis kartu lainnya atau lebih mempromosikan metode pembayaran lainnya kepada pelanggan. 
6. Layanan yang sering digunakan oleh pelanggan adalah layanan reguler, layanan reguler juga harus disediakan armada yang banyak karena minatnya banyak dibandingkan layanan lainnya agar waktu tunggu penumpang tidak lama dan load factor bus tidak melebihi kapasitas.
7. Dari visualisasi origin-destination di Tableau pun bahwa Layanan Transjakarta sudah mencakup seluruh wilayah DKI Jakarta, maka perlu adanya peningkatan promosi mengenai layanan dan peningkatan layanan untuk menarik minat masyarakat untuk menggunakan layananan Transjakarta. 


Visualisasi data dapat dilihat di tableau public berikut:
https://bit.ly/PelangganTransjakartaApril2023
