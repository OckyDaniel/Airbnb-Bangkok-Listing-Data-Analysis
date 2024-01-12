Distrik Bangkok Geojson -> [link](https://github.com/pcrete/gsvloader-demo/blob/master/geojson/Bangkok-districts.geojson)

# Latar Belakang
Airbnb adalah sebuah platform yang menawarkan suatu tempat online yang memungkinkan para pengguna ("Anggota") untuk mempublikasikan, menawarkan, mencari, dan memesan layanan. Pada Capstone project ini akan melakukan analisis dari data listing airbnb bangkok.

# Pernyataan Masalah
Berdasarkan fokus business problemnya perlu diketahui karakteristik dari data penginapan yang telah dikumpulkan(listing) untuk selanjutnya bisa merekomendasikan beberapa hal yang berpotensi meningkatkan revenue dan efisiensi pada program dan target marketing.

# Data Understanding & Cleaning
Menganalisis data dan menghapus data yang tidak relevan kepada kebutuhan analisis. Termasuk menangani missing values dan penanganan anomali outliers. Setelah data dibersihkan dan menangani data duplikat serta menangani outliers kemudian data siap digunakan untuk analisis berikutnya. 

1. id = id unik untuk nama hunian
1. name = nama hunian
1. host_id = id unik untuk nama host
1. host_name = nama host
1. neighbourhood = daerah tempat airbnb (distrik)
1. latitude = lokasi neighbourhood (WGS84)
1. longitude = lokasi neighbourhood (WGS84)
1. room_type = tipe airbnb, terdapat 4 tipe
    * Entire home
    * Private room
    * Shared room
    * Hotel
1. price = harga sewa (baht)
1. minimum_nights = kuantitas minimal untuk menginap 
1. number_of_reviews = total jumlah riview yang dimiliki 
1. last_reviws = tanggal review terakhir 
1. reviews_per_month = jumlah review per bulan
1. calculated_host_listing_count = jumlah kalkulasi airbnb yang dimiliki host
1. availability_365 = ketersedian hari yang dapat disewa
1. number_of_reviews_ltm = jumlah review dalam 12 bulan terakhir

# Data Analysis
Proses data analisis ini menggunakan beberapa pendekatan dari variabel yang ada pada data listing airbnb bangkok yang memfokuskan pada jenis kamar berdasarkan review yaitu:
1. Pendekatan Lokasi
2. Pendekatan Host
3. Pendekatan Harga
4. Pendekatan Ketersediaan
5. Pendekatan Sewa Minimum (Minimum Nights)

 # Kesimpulan dan Rekomendasi
 Adapun insight yang dirangkum dengan kesimpulan dari analisis ini dan beberapa rekomendasi adalah sebagai berikut:
 Kesimpulan dan Rekomendasi

Kesimpulan :

Dari analisis yang telah dilakukan dari berbagai pendekatan yang fokus kepada jenis kamar berdasarkan review untuk melihat overview dan karakteristik airbnb bangkok yang bertujuan memberi kesimpulan (insight) dan rekomendasi peningkatan transaksi atau revenue. Berikut rangkuman kesimpulan, antara lain:

Penginapan Airbnb sudah ada di seluruh distrik Bangkok.
Lokasi memiliki peranan penting dalam popularitas listing.
Host yang memiliki banyak listing cenderung memiliki review yang banyak, tetapi bukan menjadi satu-satunya faktor.
Jenis Kamar juga memiliki peranan penting dalam popularitas listing
Secara korelasi harga kurang mempengaruhi popularitas listing secara keseluruhan, tetapi tetap mempengaruhi preferensi guest.
Berdasarkan median harga jenis kamar Entire home/apt lebih dominan dibandingkan tipe lainnya.
Ketersediaan dapat memperlihatkan popularitas listing (korelasi negatif), tetapi tidak secara signifikan
Ketersediaan jenis kamar Entire home/apt memiliki ketersediaan paling rendah berdasarkan review terbanyak dari host, mengindikasikan Entire home/apt paling diminati diantara jenis kamar lainnya.
Lama sewa minimum kurang mempengaruhi popularitas listing, tetapi tetap mempengaruhi preferensi guest karena tidak berkorelasi kuat positif.
Karakteristik listing yang populer dengan guest antara lain:

Berada di lokasi yang memiliki destinasi wisata yang terkenal di Bangkok seperti market, pusat perbelanjaan, bangunan bersejarah, pusat kota bangkok dan sebagainya.
Jenis Kamar Entire home/apt, dimana seluruh rumah/bangunan host disewakan pada guest merupakan yang paling dominan di top 10 lokasi paling banyak di review yang umumnya berada di pusat kota bangkok.
Memiliki harga di bawah rata-rata, tetapi bukan merupakan fokus utama guest (korelasi sangat rendah)
Lama sewa minimum cukup bervariasi tiap jenis kamar dan lebih baik lama sewa minimum tidak terlalu lama sehingga fleksibel untuk guest, terutama yang gemar bepergian dan tidak tinggal di daerah yang sama dalam jangka waktu yang lama.
Ketersediaan jenis kamar Entire home/apt cukup dominan dibandingkan jenis kamar lainnya.
Rekomendasi :

Utamakan listing yang berada di dekat lokasi wisata potensial. Lakukan riset tempat-tempat wisata di Bangkok yang banyak menarik wisatawan. Kemungkinan besar para wisatawan tersebut akan mencari tempat menginap menggunakan jasa aplikasi Airbnb.

Membuat program kepada utamakan yang memiliki banyak listing di daerah wisata Bangkok yaitu host untuk host membantu meningkatkan review di listing mereka dengan mengingatkan guest, karena terbukti menghasilkan keuntungan yang besar. Dapat juga dibuat promosi bagi pemiliki properti di daerah wisata Bangkok untuk bergabung dengan Airbnb sehingga semakin banyak host yang mau membuka listing di daerah tersebut.

Membuat program promosi yang menargetkan utamanya tipe listing entire home/apt di luar top 10 lokasi, karena merupakan yang paling populer di kalangan guest, baik secara keseluruhan dan dalam 12 bulan terakhir (trend konsisten)

Fokus kepada harga listing yang terjangkau (kurang dari sama dengan rata-rata) sebagai daya tarik konsumen. Walaupun harga memiliki korelasi yang lemah terkait popularitas, tetapi listing teramai adalah yang memiliki harga di bawah rata-rata karena mampu mengundang traffic guest.

Menawarkan program promosi kepada listing yang yang mempunyai waktu sewa minimum tidak terlalu lama agar menarik perhatian kepada listing yang memiliki waktu sewa minimum yang lama, karena sebaiknya tidak terlalu lama, terutama untuk tipe listing entire home/apt, sehingga memberikan kemudahan dan fleksibilitas bagi guest.

Listing yang populer cenderung akan memiliki ketersediaan yang terbatas dalam beberapa hari kedepan (akibat ramai booking). Pastikan host memiliki rencana dalam mengelola ketersediaan listing (salah satunya lewat kebijakan jumlah minimum penyewaan, atau dapat juga menampung lebih dari 1 guest dalam waktu yang bersamaan), sehingga dapat menampung sebanyak mungkin guest.

Membuat strategi point experience (XP) misalkan 50 exp dapat potongan/voucher gratis untuk bookingan berikutnya untuk setiap review yang ditulis. Soalnya review itu cukup penting karena bisa membantu mengenali behaviour dan sentimen dari guest ataupun potensial customer.

karena secara sistem airbnb tidak mewajibkan tamu memberikan ulasan ataupun menyelesaikan survei seperti yang ditulis pada ketentuan platform airbnb, bisa dicek dengan link berikut https://www.airbnb.co.id/help/article/2908#12

Diharapkan analisis ini dapat membantu melihat gambaran dan karakteristik serta rekomendasi yang diberikan membantu bisnis airbnb khususnya pada area bangkok.




