# Implementasi Machine Learning untuk Prediksi Median Nilai Rumah Menggunakan Linear Regression dan Random Forest

## Ringkasan

Proyek ini membangun dan membandingkan dua model regresi untuk memprediksi median nilai rumah berdasarkan karakteristik wilayah di California, Amerika Serikat. Proyek ini digunakan sebagai implementasi dasar tahapan machine learning mulai dari pemuatan data hingga evaluasi model.

## Dataset

- **Nama:** California Housing
- **Sumber resmi:** Scikit-learn
- **Dokumentasi:** https://scikit-learn.org/stable/datasets/real_world.html
- **Jumlah observasi:** 20.640 sampel
- **Fitur prediktif:** 8 fitur numerik
- **Target:** Median nilai rumah per kelompok wilayah sensus.
- **Satuan target:** Ratusan ribu dolar AS.

Dataset dimuat menggunakan fungsi `fetch_california_housing()` dari scikit-learn.

## Tujuan

1. Memuat dan memahami struktur dataset.
2. Melakukan eksplorasi data dan statistik deskriptif.
3. Membagi data menjadi data latih dan data uji.
4. Melatih model Linear Regression.
5. Melatih model Random Forest Regressor.
6. Membandingkan kinerja kedua model.
7. Memvisualisasikan nilai aktual dan nilai prediksi.

## Metode dan metrik

- Eksplorasi dan pemeriksaan data.
- Pembagian data train/test.
- Linear Regression sebagai model baseline.
- Random Forest Regressor sebagai model pembanding.
- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).
- Koefisien determinasi (R²).
- Grafik perbandingan nilai aktual dan prediksi.

## Batasan dan penggunaan yang bertanggung jawab

- Dataset berasal dari California, Amerika Serikat, bukan pasar properti Indonesia.
- Data menggambarkan kelompok wilayah sensus, bukan harga setiap rumah secara individual.
- Data historis berasal dari sensus Amerika Serikat tahun 1990.
- Hasil evaluasi pada data uji tidak menjamin performa model pada wilayah atau periode lain.
- Prediksi hanya digunakan untuk pembelajaran dan tidak dimaksudkan sebagai penilaian harga properti aktual.
