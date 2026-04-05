# UK Fuel Price Prediction 🚗⛽

## 📌 Overview
Project ini bertujuan untuk memprediksi harga bahan bakar di UK menggunakan algoritma **Random Forest Regressor**. Dataset mencakup periode Februari hingga April 2026.

## 📊 Key Insights from EDA
* **Bimodal Distribution:** Ditemukan dua puncak harga utama (145 pence untuk E10 dan 180+ pence untuk Premium/Diesel).
* **Weekly Trend:** Harga cenderung turun di akhir pekan (Sabtu & Minggu).
* **Linear Trend:** Terjadi kenaikan harga yang konsisten secara linear selama periode observasi.

## 🤖 Modeling & Evaluation
* **Algorithm:** Random Forest Regressor (Ensemble Learning).
* **Features:** `day_of_week`, `month`, `days_since_start`, and `fuel_type`.
* **Results:** * MAE: 7.51 pence
    * R² Score: 0.68
* **Analysis:** Model berhasil menangkap tren umum, namun memiliki limitasi dalam **ekstrapolasi** harga di bulan April karena karakteristik algoritma berbasis pohon.

## 🛠️ How to Use
1. Clone repository ini.
2. Buka file `.ipynb` di Google Colab atau Jupyter Notebook.
3. Pastikan dataset `price_history.csv` berada di folder yang sama.
