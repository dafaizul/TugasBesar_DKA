# 🎓 Fuzzy Logic Student Performance Predictor

Sebuah Sistem Pakar interaktif berbasis web untuk memprediksi Indeks Performa Akademik Siswa. Proyek ini mendemonstrasikan implementasi algoritma **Fuzzy Logic (Mamdani & Sugeno)** yang dibangun sepenuhnya dari nol (*from scratch*) tanpa menggunakan *library* fuzzy pihak ketiga.

## ✨ Fitur Utama
* **Algoritma Murni**: Implementasi matematika fungsi keanggotaan (Segitiga & Trapesium), evaluasi 15 *Rule Base*, dan defuzzifikasi (Centroid & Weighted Average) menggunakan Python native dan NumPy.
* **Analisis Data**: *Jupyter Notebook* yang memuat komputasi vektorisasi untuk 10.000 baris data secara instan, lengkap dengan perbandingan metrik evaluasi MAE dan MSE.
* **Web Interaktif**: Antarmuka pengguna (*User Interface*) yang dibangun dengan Streamlit untuk memprediksi performa siswa secara *real-time* berdasarkan input interaktif.

## 🛠️ Teknologi yang Digunakan
* **Bahasa**: Python 3
* **Data Science**: Pandas, NumPy, Matplotlib
* **Frontend**: Streamlit

## 🚀 Cara Menjalankan Aplikasi Web
1. Pastikan Python sudah terinstal di sistem Anda.
2. *Clone* repositori ini: `git clone https://github.com/username-kamu/nama-repo.git`
3. Instal dependensi: `pip install -r requirements.txt`
4. Jalankan aplikasi Streamlit: `streamlit run app.py`

## 📊 Evaluasi Model
Berdasarkan pengujian pada 10.000 dataset:
* **Mamdani (Centroid)** menghasilkan transisi nilai yang lebih proporsional dan halus.
* **Sugeno (Orde-0)** memberikan komputasi yang jauh lebih cepat namun menggunakan konstanta *singleton* yang kaku.
