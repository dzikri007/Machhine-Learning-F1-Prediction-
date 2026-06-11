# 🏎️ F1 Race Prediction Model

Machine Learning project untuk memprediksi hasil balapan Formula 1 menggunakan data historis pembalap, lap time, dan kondisi ban.

## Features

- Analisis konsistensi pembalap dengan fitur `Driver_Stability`
- Prediksi kebutuhan pit stop berdasarkan degradasi ban (`Is_Worn_Out`)
- Prediksi pemenang balapan menggunakan algoritma XGBoost
- Evaluasi model menggunakan ROC-AUC

## Methodology

- Exploratory Data Analysis (EDA)
- Feature Engineering
  - Driver_Stability
  - Cumulative_Degradation
  - Is_Worn_Out
- Model Training menggunakan XGBoost Classifier
- Model Evaluation

## Results

Model berhasil mencapai **ROC-AUC Score sebesar 0.89**.

Berdasarkan hasil prediksi, **Driver ID 875** menjadi kandidat pemenang utama dengan probabilitas kemenangan **92.4%**, didukung oleh konsistensi lap time yang tinggi dan strategi pit stop yang efisien.
