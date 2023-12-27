# Klasifikasi_Gambar_fashionmnist
Proyek yang telah saya kerjakan ini merupakan model deep learning untuk memprediksi kelas gambar pakaian dari dataset Fashion MNIST menggunakan model yang telah dilatih sebelumnya. 

Pertama, kode ini mendefinisikan kamus `dict_label` yang memetakan indeks kelas ke label kelas yang sesuai. 

Kemudian, fungsi `predict` dibuat. Fungsi ini memilih empat gambar secara acak dari set data uji. Gambar-gambar ini kemudian diprediksi oleh model. 
Prediksi ini adalah vektor probabilitas 10-dimensi (karena ada 10 kelas), jadi fungsi `np.argmax` digunakan untuk mengambil indeks dari probabilitas tertinggi, yang merupakan prediksi kelas model. 

Label sebenarnya untuk gambar-gambar ini juga diambil dengan cara yang sama dari label one-hot. 

Setelah itu, gambar dan prediksi ditampilkan dalam plot 2x2. Untuk setiap gambar, judul subplot adalah label sebenarnya dan prediksi. 

Akhirnya, fungsi `predict` dipanggil untuk menjalankan proses prediksi dan visualisasi ini. 

Jadi, kode ini memberikan cara untuk memvisualisasikan kinerja model pada sampel acak dari set data uji. Anda dapat melihat gambar asli dan membandingkan prediksi model dengan label sebenarnya.
