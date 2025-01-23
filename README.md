## Ajwa vs Medjool Classification
Merupakan implementasi algoritma K-Nearest Neighbors (KNN) untuk mengklasifikasikan jenis kurma, yaitu Ajwa dan Medjool, berdasarkan karakteristik fisik dan nilai gizinya. Proyek ini juga memanfaatkan teknik K-Fold Cross Validation untuk meningkatkan performa model dengan validasi data yang optimal.

## Fitur Utama
- **Preprocessing Data:** Melakukan encoding terhadap atribut kategorikal, normalisasi data, dan pemeriksaan nilai kosong (missing value).
- **Visualisasi Data:** Menyediakan visualisasi distribusi data sebelum dan setelah normalisasi untuk setiap skala.
- **Model KNN:** Mengimplementasikan KNN dengan parameter jumlah tetangga (`n_neighbors`) yang dapat disesuaikan.
- **Tuning Hyperparameter:** Mengevaluasi performa model dengan berbagai nilai `n_neighbors` dan mengukur akurasi serta skor F1.
- **Validasi K-Fold:** Membagi dataset menjadi beberapa lipatan (fold) untuk melatih dan menguji model secara bergantian.
- **Evaluasi Model:** Menggunakan metrik akurasi, skor F1, dan confusion matrix untuk mengevaluasi performa model.

## Dataset
Dataset yang digunakan mencakup atribut-atribut berikut:
- Panjang kurma (cm)
- Diameter kurma (cm)
- Berat kurma (g)
- Panjang biji kurma (cm)
- Kalori (Kcal)
- Warna (Hitam atau Coklat)
- Kelas (Ajwa atau Medjool)

## Teknologi yang Digunakan
- Python
- Pandas, NumPy
- Matplotlib untuk visualisasi

## Cara Penggunaan
1. Unduh dan instal dependensi Python yang diperlukan.
2. Pastikan dataset tersedia dan terhubung dengan program.
3. Jalankan script untuk memproses data, melatih model, dan mengevaluasi performanya.
