# Machine-Learning-Logistic-Regression

Regresi logistik adalah teknik pemodelan yang digunakan untuk memprediksi probabilitas terjadinya suatu kejadian dengan menggunakan data masa lalu. Algoritma ini sering digunakan dalam pengklasifikasian (memprediksi apakah sesuatu termasuk dalam kelompok yang satu atau kelompok yang lain) dan sangat berguna dalam berbagai aplikasi, seperti pemasaran, keuangan, dan kedokteran.

Pada latihan ini, kita akan membuat model regresi logistik untuk memprediksi apakah seorang siswa diterima di universitas. Pengklasifikasi regresi logistik yang kami lakukan disini memprediksi dengan benar apakah seorang siswa diterima pada ujian masuk universitas sebesar 89%.

Berikut ini adalah langkah-langkah yang harus dilakukan untuk melakukan prediksi menggunakan Logistik Regression
1. import library yang dibutuhkan
2. import data set lalu load datanya
3. ploting data menjadi positif dan negatif
4. Buat fungsi sigmod untuk mengconvert nilai input menjadi rentang 0-1.
5. Hitung cost function
6. Tambahkan satu kolom guna mempermudah perkalian matriks
7. Set Training data sebagai variabel X dan Y sebagai target variabel
8. convert nilai X dan Y menjadi array dan inisialisasi Theta
9. Periksa bentuk dari array
10. Hitung initial cost
11. Hitung gradient 
13. Gunakan implementasi truncated newton (TNC) dari SciPy untuk menemukan parameter yang optimal.
14. Hitung cost resultnya
15. Buatlah fungsi yang akan mengeluarkan prediksi 
16. Hitunglah tingkat akurasi dari suatu model prediksi.

