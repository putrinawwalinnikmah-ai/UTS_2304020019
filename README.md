**WINE QUALITY**
---
**PENDAHULUAN**
Data mining merupakan proses penggalian informasi atau pola penting dari sekumpulan data menggunakan teknik statistik, machine learning, dan kecerdasan buatan. Salah satu penerapan data mining adalah klasifikasi, yaitu metode untuk mengelompokkan data ke dalam kelas tertentu berdasarkan karakteristik yang dimiliki. Pada bidang industri makanan dan minuman, khususnya industri anggur, klasifikasi dapat digunakan untuk memprediksi kualitas anggur berdasarkan kandungan kimiawi yang terdapat di dalamnya.

Data Mining ini digunakan dataset Wine Quality yang berisi berbagai fitur kimiawi anggur merah dan putih, seperti kadar alkohol, keasaman, kandungan gula, pH, dan variabel lainnya. Variabel target yang diprediksi adalah quality, yaitu tingkat kualitas anggur dengan skala tertentu. Dataset terdiri dari data training yang memiliki label kualitas serta data testing yang belum memiliki label sehingga perlu dilakukan prediksi menggunakan model klasifikasi.

Dalam pengerjaan proyek ini dilakukan beberapa tahapan, yaitu persiapan data, pembersihan data, eksplorasi data, pembuatan model klasifikasi, evaluasi model, hingga prediksi data uji. Model klasifikasi yang digunakan dalam analisis ini meliputi K-Nearest Neighbors (KNN), Decision Tree, dan Random Forest. Setelah dilakukan evaluasi performa model menggunakan metrik akurasi dan classification report, dipilih model terbaik untuk melakukan prediksi kualitas anggur pada data testing.

Melalui proses ini diharapkan dapat diperoleh model klasifikasi yang mampu memprediksi kualitas anggur dengan baik berdasarkan karakteristik kimiawi yang dimiliki setiap sampel anggur.

**TUJUAN**

Tujuan dari praktikum dan analisis data mining ini adalah sebagai berikut:
1. Melakukan proses persiapan dan pembersihan dataset Wine Quality agar siap digunakan dalam pemodelan.
2. Menganalisis karakteristik data serta hubungan antarvariabel pada dataset kualitas anggur.
3. Membangun model klasifikasi menggunakan algoritma K-Nearest Neighbors (KNN), Decision Tree, dan Random Forest untuk memprediksi kualitas anggur.
4. Mengevaluasi performa masing-masing model klasifikasi menggunakan metrik akurasi, classification report, dan confusion matrix.
5. Menentukan model terbaik berdasarkan hasil evaluasi performa model.
6. Menggunakan model terbaik untuk memprediksi nilai quality pada dataset testing.
7. Menyimpan hasil prediksi ke dalam file CSV sesuai format yang telah ditentukan, yaitu hanya memuat kolom Id dan quality.
