# Klasifikasi Jenis Beras Berdasarkan Citra Digital

## Deskripsi

Proyek ini merupakan implementasi pengolahan citra untuk melakukan klasifikasi jenis beras berdasarkan citra digital.

Jenis beras yang digunakan dalam proyek ini terdiri dari:
- Beras Putih
- Beras Merah
- Beras Hitam

Pengolahan dilakukan menggunakan Python dan OpenCV melalui Google Colab.

## Tahapan Pengolahan Citra

Pipeline yang digunakan dalam proyek ini adalah:

1. Akuisisi Citra
2. Pre-processing
   - Resize
   - Grayscale
   - Gaussian Blur
3. Enhancement & Restoration
   - CLAHE
   - Sharpening
4. Segmentasi
   - Otsu Thresholding
   - Operasi Morfologi
5. Ekstraksi Fitur
   - Fitur warna RGB
   - Fitur warna HSV
   - Fitur bentuk
6. Klasifikasi
   - K-Nearest Neighbors (KNN)

## Dataset

Dataset terdiri dari tiga citra, masing-masing mewakili satu jenis beras:

| Jenis Beras | Jumlah Citra |
|---|---:|
| Beras Putih | 1 |
| Beras Merah | 1 |
| Beras Hitam | 1 |

Karena dataset yang digunakan masih terbatas, hasil klasifikasi pada proyek ini digunakan sebagai demonstrasi penerapan metode pengolahan citra dan belum dapat merepresentasikan performa klasifikasi pada dataset yang lebih besar.

## Tools & Library

- Python
- Google Colab
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Hasil

Model KNN berhasil mengidentifikasi ketiga citra referensi sesuai dengan label jenis berasnya:

- Citra 1 → Beras Putih
- Citra 2 → Beras Merah
- Citra 3 → Beras Hitam

## Author

**Sakti Attila Aulia Bintang**

## Google Colab

Notebook Google Colab untuk review:

[ Buka Notebook di Google Colab ](https://colab.research.google.com/drive/1pqlR7d-oJ9_1j2C_U3gLshLz9ekHEoqy?usp=sharing)
