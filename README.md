# 📈 Forecasting Harga Saham ISAT & EXCL dengan ARIMA

Proyek ini membahas analisis deret waktu (time series analysis) untuk memprediksi harga saham **Indosat Ooredoo Hutchison (ISAT.JK)** dan **XL Axiata (EXCL.JK)** menggunakan metode **ARIMA (AutoRegressive Integrated Moving Average)**.

## 🚀 Tujuan
Proyek ini bertujuan untuk:
- Membandingkan performa prediksi harga saham **ISAT vs EXCL**.  
- Memberikan gambaran penggunaan ARIMA dalam forecasting keuangan, khususnya sektor telekomunikasi di Indonesia.  

## 📊 Dataset
- `ISAT.JK` → Indosat Ooredoo Hutchison  
- `EXCL.JK` → XL Axiata
Sumber: *Yahoo Finance*

## 🔎 Tahapan Analisis
1. **Pengambilan Data**
   - Data harga saham diunduh dari *Yahoo Finance* dengan periode **Maret 2024 – Maret 2025**.
   - Kolom yang digunakan: harga penutupan (closing price).

2. **Preprocessing**
   - Mengatur frekuensi data ke hari kerja (business days).
   - Mengatasi missing values dengan interpolasi.

3. **Eksplorasi Data**
   - Visualisasi tren harga saham ISAT & EXCL.
   - Statistik deskriptif untuk memahami distribusi harga.

4. **Pemodelan ARIMA**
   - Pemisahan data menjadi **train (80%)** dan **test (20%)**.
   - Penerapan model **ARIMA (5,1,0)** untuk masing-masing saham.
   - Evaluasi model menggunakan **MAE, MSE, dan RMSE**.

5. **Visualisasi Hasil**
   - Plot perbandingan antara **data training, data aktual, dan hasil prediksi**. 

## 🛠️ Tools & Library
- Python 3  
- pandas, numpy, matplotlib  
- yfinance (pengambilan data saham)  
- statsmodels (ARIMA)  
- scikit-learn (evaluasi model)  

---
