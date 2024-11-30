# dibimbing-33.0
## ANALISIS DATASET WINE UNTUK PORTOFOLIO PROYEK

Dataset wine merupakan kumpulan data yang digunakan untuk mengklasifikasikan jenis anggur berdasarkan hasil analisis kimia dari tiga jenis anggur yang berbeda. Dataset ini terdiri dari beberapa fitur seperti kandungan alkohol, asam, magnesium, fenol, dan lainnya yang digunakan untuk membedakan setiap kelas anggur. Saya menggunakan kumpulan data dari tautan ini: (https://scikit-learn.org/)

Dalam proyek ini, algoritma K-Nearest Neighbors (KNN) digunakan untuk membangun model klasifikasi guna memprediksi jenis anggur berdasarkan fitur-fitur tersebut. Implementasi ini bertujuan untuk menyalakan kinerja KNN dalam memproses dataset wine, dengan mengukur akurasi, sensitivitas, dan evaluasi parameter lainnya.

**Sasaran :**

Proyek ini bertujuan untuk:
1. Membangun model klasifikasi menggunakan algoritma K-Nearest Neighbors (KNN) untuk memprediksi jenis anggur berdasarkan fitur kimianya.
2. Menganalisis kinerja KNN dengan membandingkan akurasi model pada data latih dan data uji.
3. Mengeksplorasi dampak parameter KNN, seperti jumlah tetangga ( k ) dan metrik jarak ( distance metrics ), terhadap kinerja model.
   
**Wawasan :**

Dari analisis yang dilakukan, proyek ini menghasilkan beberapa wawasan berikut:
1. Fitur seperti kandungan alkohol dan fenol memiliki pengaruh besar dalam membedakan jenis anggur.
2. Nilai optimal untuk parameter k bergantung pada distribusi data, di mana nilai k yang terlalu kecil dapat menyebabkan model terlalu sensitif terhadap noise .
3. Penggunaan metrik jarak tertentu (misalnya, Euclidean atau Manhattan ) dapat mempengaruhi model akurasi pada dataset ini.
   
**Saran :**

1. Pastikan untuk melakukan penskalaan fitur (misalnya, normalisasi) karena KNN sensitif terhadap skala data.
2. Eksperimen dengan nilai k yang berbeda untuk menemukan parameter optimal yang memberikan keseimbangan terbaik antara bias dan variance.
3. Jika dataset memiliki dimensi yang tinggi, tergantung penggunaan teknik pengurangan dimensi seperti PCA sebelum menerapkan KNN untuk meningkatkan efisiensi model.

Jika Anda memiliki saran atau masukan, jangan ragu untuk menghubungi saya melalui pesan langsung di LinkedIn dan Email: ratunafasa151106@gmail.com dan https://www.linkedin.com/in/ratuaulianafasa
