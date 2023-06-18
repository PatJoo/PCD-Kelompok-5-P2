# PCD-Kelompok-5-P2
# Proses Pengolahan Citra Digital dengan Metode ANN dalam Penentuan Kualitas Daging

Kebutuhan konsumsi daging sangat berkembang pesat dalam kalangan masyarakat. Tingginya tingkat konsumsi daging membuat sangat memungkinkan ditemukannya daging tidak berkualitas yang diperjualbelikan. Hal tersebut menyebabkan pentingnya identifikasi untuk menentukan layak atau tidaknya suatu daging dikonsumsi. Proses analisis identifikasi dibutuhkan dalam menentukan kualitas daging yang beredar di masyarakat. Proses penentuan kualitas daging dapat dilakukan dengan melakukan identifikasi citra daging. Salah satu metode yang umum digunakan dalam klasifikasi identifikasi citra digital adalah artificial neural network. Oleh karena itu, penulis memutuskan untuk melakukan penelitian “Proses Pengolahan Citra Digital dengan Metode ANN dalam Penentuan Kualitas Daging”. Hasil yang diharapkan dari penelitian ini adalah ditemukannya model yang dapat membantu masyarakat untuk melakukan klasifikasi kualitas daging.

## Instalasi

```python
# Contoh kode instalasi dependensi
!pip install numpy
!pip install pandas
...
pip install pandas numpy seaborn matplotlib tensorflow opencv-python keras scikit-learn lightgbm xgboost catboost
```

Pastikan untuk menginstal dependensi yang dibutuhkan sebelum menjalankan kode di Google Colab. Anda dapat menggunakan perintah berikut untuk menginstal dependensi:

## Panduan Penggunaan
1. Impor dataset ke Google Drive dan pastikan dapat diakses dari Google Colab.
2. Pastikan dependensi yang diperlukan telah diinstal.
3. Jalankan sel satu per satu secara berurutan, mengikuti urutan yang ditentukan.
4. Analisis output yang dihasilkan setelah menjalankan kode.

## Struktur Proyek
○ Notebook: File notebook Google Colab yang berisi kode dan penjelasan.
○ Dataset: Folder yang berisi dataset Meat Quality Assessment yang berupa file gambar dengan format jpg.

## Dataset
Data yang digunakan pada penelitian ini adalah Meat Quality Assessment Dataset yang bersumber dari Kaggle. Dataset ini terdiri dari 1898 foto dengan dua kategori yaitu fresh (948 foto) dan spoiled (948 foto). Seluruh foto tersebut akan digunakan dalam penelitian ini dan akan dipisahkan menjadi data latih (train data) dan data uji (test data) untuk implementasi algoritma.

Sumber: [Meat Quality Assessment Dataset on Kaggle](https://www.kaggle.com/datasets/crowww/meat-quality-assessment-based-on-deep-learning)

## Metode
Proses membangun model menggunakan algoritma Artificial Neural Network (ANN) dari dataset dilakukan melalui tahapan praproses dan pembuatan model. Berikut adalah langkah-langkah yang dilakukan:

Praproses:

Membuat objek series.
Visualisasi data.
Memisahkan data menjadi data latih dan data uji.
Normalisasi data.

Pembuatan Model
Setelah praproses selesai, model Artificial Neural Network (ANN) dapat dibangun dan dilatih menggunakan data latih. Pembuatan model dilakukan secara sequential dimana aliran data melalui layer input ke layer-layer tersembunyi dan terakhir ke layer output menggunakan fungsi sequential dalam tensorflow keras. 

## Hasil
Hasil dari penelitian ini adalah model yang dapat membantu dalam melakukan klasifikasi kualitas daging berdasarkan citra. Performa model dapat dilihat dalam visualisasi atau grafik yang dihasilkan. Berikut ini adalah contoh beberapa metrik evaluasi yang dapat digunakan untuk mengevaluasi model:

○ Akurasi (accuracy)

○ Confusion matrix (heatmap)

○ Laporan klasifikasi (classification report)

Contoh hasil prediksi : 
![image](https://github.com/PatJoo/PCD-Kelompok-5-P2/assets/86305950/adbb2731-9ae7-4220-aad2-6ce53ce2fb8c)


## Referensi
○ Ahmad A. 2017. "Mengenal Artificial Intelligence, Machine Learning, Neural Network, dan Deep Learning." Jurnal Teknologi Indonesia. 1(3):4.

○ Al-Jabbar H.M, Fitriyah H., Maulana R. 2021. "Sistem Klasifikasi Kesegaran Daging Sapi Berdasarkan Citra Menggunakan Metode Naive Bayes Berbasis Raspberry Pi." Jurnal Pengembangan Teknologi Informasi dan Ilmu Komputer. 5(4): 1646-1653.

○ Melangi S. 2020. "Klasifikasi Usia Berdasarkan Citra Wajah Menggunakan Algoritma Artificial Neural Network dan Gabor Filter." Jambura Journal of Elecronics Engineering (JJEEE). 2(2):61.

○ Nurhayati OD, Adi K, Pujiyanto S. 2020. "Perbandingan Metode Segmentasi Otomatis Region of Interest dan K-Means Clustering pada Aplikasi Deteksi Kualitas Daging Sapi Berbasis Mobile." Jurnal Sistem Komputer. 10(1):35-41.

○ Priyanto R, Fuah AM, Aditia EL, Baihaqi M, Ismail M. 2015. "Peningkatan Produksi dan Kualitas Daging Sapi Lokal Melalui Penggemukan Berbasis Serealia pada Taraf Energi yang Berbeda." Jurnal Ilmu Pertanian Indonesia. 20(2): 108-114.

○ Yanto M, Arlis S, Putra DM. 2022. "Multiple Linear Regression pada Fuzzy Neural Network (FNN) untuk Penentuan Kualitas Daging Sapi." Jurnal Sains & Teknologi Universitas Pendidikan Ganesha. 11(1):94.

○ Yuristiawan D. "Identifikasi Kualitas Daging Sapi Berbasis Android dengan Ekstraksi Fitur Warna dan Klasifikasi KNN." 2011. Eprints.dinus.ac.id. [diunduh 18 Juni 2023];1(1):2.

## Kontributor
- Bares Manggala Samhas
- Citra Regita Nurtalia Wahyu Santosa
- Joachim Patrick Sihotang
- Rozan Maulana
- Shabrina Basyasayah
