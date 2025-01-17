# Min-Wo : Chatbot Desa Wonorejo

## Domain Proyek

Min-Wo merupakan fitur chatbot yang merupakan karya di masa Kuliah Kerja Nyata (KKN) saya untuk desa Wonorejo, Sukoharjo. Dalam rangka meningkatkan ketersediaan akses informasi mengenai desa, baik dalam hal administratif, non-administratif, maupun informasi umum, dibutuhkan adanya suatu terobosan untuk memaksimalkan ketersediaan akses informasi agar mudah didapat dan diakses dimana saja oleh masyarakat Desa Wonorejo. Chatbot Sistem Aplikasi Desa hadir sebagai solusi ketersediaan informasi berbasis digital yang enerapkan teknologi kecerdasan buatan (AI) yang mampu melakukan pertukaran informasi dari pengguna dengan sistem secara otomatis sebagai implementasi Desa Digital menuju pemerintahan pintar. Pembuatan aplikasi ini bertujuan untuk mempermudah akses informasi mengenai Desa Wonorejo untuk masyarakat lokal maupun masyarakat di luar Desa Wonorejo.Tingkat resign atau perputaran karyawan yang tinggi merupakan masalah serius yang dihadapi banyak perusahaan. Kondisi ini dapat mengakibatkan kerugian finansial yang signifikan, hilangnya produktivitas, dan penurunan moral karyawan. Oleh karena itu, penting bagi perusahaan untuk memahami faktor-faktor yang berkontribusi terhadap resign dan mengembangkan strategi untuk mengurangi tingkat resign.

Chatbot Sistem Aplikasi Desa dibuat dengan tujuan untuk memudahkan akses informasi Desa Wonorejo baik dalam hal administratif, non-administratif, maupun informasi umum. Fitur chatbot ini mampu melakukan pertukaran informasi mengenai informasi umum Desa, informasi pengurusan dokumen / surat, informasi administratif, maupun non-administratif dari Desa Wonorejo. Model chatbot ini kemudian diserahkan kepada pihak desa dan kelompok KKN selanjutnya untuk keperluan pengembangan lebih lanjut ataupun proses deployment ke website desa ataupun sistem chatbot di aplikasi whatsapp


## Data Understanding
Dataset yang digunakan untuk pembuatan chatbot didapat melalui proses wawancara kepada Kepala Desa Wonorejo, dan beberapa warga desa. Data yang diperoleh dari wawancara kemudian dibuat dalam format JSON yang kemudian digunakan untuk pembuatan chatbot.

## Data Preparation
Untuk pemrosesan data, dilakukan 5 tahap diantaranya : 
1. Data cleaning : data teks yang berupa kalimat atau pertanyaan dari pengguna (input) dibersihkan dari tanda baca dan diubah menjadi huruf kecil dengan tujuam untuk menyeragamkan data dan mengurangi kompleksitas.
2. Lematisasi : mengubah kata-kata dalam data menjadi bentuk dasarnya (kata dasar). Proses ini membantu dalam mengurangi redundansi dan meningkatkan akurasi model.
3. Tokenisasi : data  teks dipecah menjadi unit-unit yang lebih kecil yang membantu dalam mengubah teks menjadi representasi numerik yang dapat diproses dengan machine learning.
4. Padding : digunakan untuk menyeragamkan panjang kalimat dengan menambahkan token khusus (misalnya, 0) di awal atau akhir kalimat.
5. Label Encoding : mengubah label pada data menjadi bentuk numerik.

## Modeling
Algoritma Machine Learning yang digunakan yaitu Neural Network dengan embedding dan LSTM.

## Evaluation
Model chatbot yang dibuat yang dibuat menunjukkan tren akurasi yang meningkat seiring bertambahnya epoch yang berarti model semakin baik dalam mempelajari pola dari data, dan akurasi yang tinggi (mendekati 1)  menunjukkan model memiliki performa yang baik dalam memprediksi label yang benar. Sedangkan untuk grafik loss, model menunjukkan nilai loss yang semakin rendah seiring bertambahnya epoch model semakin baik dalam mengurangi kesalahan prediksi.
