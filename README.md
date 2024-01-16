# 202131060_MUHAMMAD-KHATAMI_UAS_PEMSIS_B

PENGELOMPOKAN K-MEANS DENGAN PYTHON MENGGUNAKAN DATASETS PENJUAL FACEBOOK LIVE DI THAILAND, UCI ML REPO
Penelitian ini bertujuan untuk menerapkan algoritma K-Means Clustering pada dataset penjualan Facebook Live di Thailand yang disediakan oleh UCI Machine Learning Repository. Dataset ini mencakup informasi tentang status penjualan, waktu publikasi, dan jenis status pada setiap penjualan. Metode K-Means digunakan untuk mengelompokkan data penjualan menjadi beberapa cluster berdasarkan pola dan karakteristik yang mungkin ada. Langkah-langkah yang diambil melibatkan impor dataset, pra-pemrosesan data untuk mengatasi nilai yang hilang atau anomali, dan penskalaan fitur menggunakan Min-Max Scaler. Selanjutnya, dilakukan eksplorasi data untuk memahami distribusi variabel. Proses clustering menggunakan K-Means dilakukan dengan variasi jumlah cluster untuk menentukan jumlah optimal. Metode siku (elbow method) digunakan untuk membantu menentukan jumlah cluster yang paling sesuai. Hasil penelitian ini memberikan wawasan tentang pola dan kelompok yang mungkin ada dalam penjualan Facebook Live di Thailand. Hasil clustering dapat digunakan untuk memahami perilaku penjualan, memetakan kelompok pelanggan potensial, dan merancang strategi pemasaran yang lebih efektif. Studi ini menunjukkan potensi penggunaan K-Means Clustering sebagai alat analisis yang berguna dalam konteks penjualan online, khususnya pada platform sosial seperti Facebook Live.
Kata Kunci — K-Means Clustering, dataset penjualan Facebook Live, UCI Machine Learning Repository, analisis pola penjualan, strategi pemasaran.

Kesimpulan
1.	Dalam proyek ini, saya telah mengimplementasikan teknik pengelompokan tanpa pengawasan yang paling populer yang disebut K-Means Clustering.
2.	Saya telah menerapkan metode siku dan menemukan bahwa k=2 (k adalah jumlah cluster) dapat dianggap sebagai jumlah cluster yang baik untuk mengelompokkan data ini.
3.	Saya menemukan bahwa model memiliki inersia atau WCSS rendah sebesar 32.52165670978738. Jadi, ini adalah model yang cocok dengan baik untuk data tersebut.
4.	Saya berhasil mencapai akurasi klasifikasi rendah sebesar 1% dengan k=2 menggunakan model tanpa pengawasan kita.
5.	Oleh karena itu, saya mengubah nilai k dan menemukan akurasi klasifikasi yang relatif lebih tinggi sebesar 60% dengan k=4.
6.	Dengan demikian, kita dapat menyimpulkan bahwa k=4 merupakan jumlah cluster yang optimal.
