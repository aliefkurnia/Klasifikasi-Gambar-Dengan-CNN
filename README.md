# Hi Everyone 👋
## About This Repository
Repository ini berisi tentang Proyek Akhir Saya untuk pembelajaran Machine Learning pada situs Dicoding.com 
dimana dengan menggunakan metode CNN Model Construction kita bisa mengetahui foto yang kita upload merupakan gunting, batu, ataupun kertas
Untuk membangun sebuah model Convolutional Neural Network (CNN) yang dapat mengenali apakah foto yang diunggah adalah gunting, batu, atau kertas, Anda dapat mengikuti langkah-langkah berikut. Langkah-langkah ini termasuk persiapan data, konstruksi model CNN, pelatihan model, dan evaluasi model. 
Berikut adalah panduan lengkapnya menggunakan Python dan pustaka Keras:

## Langkah-langkah:
### 1.Instal Library TensorFlow
```
import tensorflow as tf
```
###  2.Persiapan Data:
Kumpulkan dataset yang terdiri dari gambar gunting, batu, dan kertas.
Bagi dataset menjadi tiga bagian: training, validation, dan testing.
Lakukan preprocessing gambar seperti normalisasi dan augmentasi data jika diperlukan.

### 3.Konstruksi Model CNN:
Bangun arsitektur CNN yang sesuai untuk klasifikasi gambar.

### 4.Pelatihan Model:
Latih model dengan dataset yang sudah dipreproses.
Pantau performa model menggunakan validation set.
Evaluasi Model:

