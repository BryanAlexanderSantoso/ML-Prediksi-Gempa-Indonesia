# 🌏 Machine Learning Prediksi Gempa Bumi Indonesia 🇮🇩

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn%20%7C%20XGBoost-orange.svg" alt="ML Tool">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Status">
</p>

## 📌 Deskripsi Proyek
Proyek ini merupakan implementasi Machine Learning secara end-to-end untuk melakukan analisis dan prediksi terkait gempa bumi di kawasan Indonesia menggunakan data historis. 

Notebook **`prediksi_gempa_indonesia.ipynb`** memandu Anda mulai dari tahapan Eksplorasi Data (EDA), Preprocessing, Feature Engineering, hingga pembangunan Model Machine Learning.

> ⚠️ **Disclaimer Utama**: Model Machine Learning dalam proyek ini **tidak dirancang** untuk memprediksi kapan atau di mana tepatnya gempa bumi akan terjadi secara akurat. Teknologi saat ini belum bisa melakukan prediksi gempabumi secara absolut. Model ini lebih difokuskan untuk mempelajari pola historis, mengestimasi magnitudo berdasarkan fitur, serta mengidentifikasi zona risiko berbasis data riwayat gempa.

## 🎯 Fitur Utama / Objektif
1. 📈 **Prediksi Magnitudo**: Memprediksi angka magnitudo dari event seismik berdasarkan jarak, kedalaman, dan pola seismik sebelumnya.
2. 🚨 **Klasifikasi Risiko Gempa**: Mengklasifikasikan tingkat bahaya/risiko (Rendah / Sedang / Tinggi) suatu event gempa.
3. 🗺️ **Deteksi Zona Seismik (Clustering)**: Identifikasi dan pemetaan zona-zona rawan gempa menggunakan algoritma clustering.

## 📊 Dataset yang Digunakan
Dataset yang digunakan bersumber dari pencatatan historis gempa bumi di Indonesia:
- 📄 `katalog_gempa.csv` — Berisi 92.887 titik kejadian gempa dari tahun 2008 hingga saat ini.
- 📄 `katalog_gempa_v2.tsv` — Dataset tambahan dengan 131.833 event geologi yang mencakup data focal mechanism.
- 📍 `katalog_sensor.tsv` — Lokasi dari 1.320 sensor seismik (stasiun) milik BMKG di seluruh wilayah.

## 🛠️ Tech Stack & Library
Proyek ini mengandalkan library Python modern untuk data science:
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`, `folium` (untuk pemetaan interaktif)
- **Machine Learning**: `scikit-learn` (Random Forest, Gradient Boosting, KMeans, DBSCAN), `xgboost`, `lightgbm`

## 🚀 Cara Menjalankan

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/username-anda/ML-Prediksi-Gempa-2024.git
   cd ML-Prediksi-Gempa-2024
   ```

2. **Install dependensi (Package) yang dibutuhkan:**
   ```bash
   pip install scikit-learn xgboost lightgbm folium seaborn matplotlib pandas numpy jupyter
   ```

3. **Jalankan Jupyter Notebook:**
   ```bash
   jupyter notebook prediksi_gempa_indonesia.ipynb
   ```
   Atau Anda bisa menggunakan Google Colab, VS Code, maupun JupyterLab untuk membukanya.

4. **Eksekusi Cell:** Jalankan sel satu per satu untuk mereplikasi alur Preprocessing hingga Evaluasi Model.

## 🤝 Kontribusi
Jika Anda memiliki ide untuk meningkatkan akurasi, visualisasi, atau optimasi model, silakan lakukan fork pada repository ini dan buat pull request (PR).

---
*Dibuat untuk keperluan riset dan edukasi Machine Learning.* 🚀
