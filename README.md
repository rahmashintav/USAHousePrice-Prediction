# USA House Price Prediction (Capstone Project)

Proyek ini merupakan bagian dari tugas akhir capstone dalam studi S2 Matematika, yang bertujuan untuk memprediksi harga rumah di Amerika Serikat menggunakan berbagai algoritma Machine Learning.

## Tujuan Proyek
Membangun model regresi prediktif yang mampu memperkirakan harga rumah berdasarkan karakteristik properti, lokasi, dan variabel lainnya dalam dataset publik dari Kaggle.

## Dataset
Dataset diambil dari Kaggle:
[USA House Prices Dataset by fratzcan](https://www.kaggle.com/datasets/fratzcan/usa-house-prices)

## Metodologi
1. Eksplorasi Data dan Pra-pemrosesan
2. Feature Engineering
3. Pemilihan Model (Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM)
4. Pelatihan & Evaluasi Model (MAE, MSE, RMSE, R² Score)
5. Hyperparameter Tuning (GridSearchCV, RandomizedSearchCV)
6. Visualisasi Hasil & Interpretasi Error
7. Deployment Model (joblib)

## Hasil Model Terbaik
Setelah dilakukan hyperparameter tuning, model **Gradient Boosting Regressor (GBR)** memberikan hasil terbaik dengan metrik:

- MAE: ±11.574
- RMSE: ±23.594
- R² Score: **0.9957**

## Visualisasi
- Scatter plot antara harga aktual vs prediksi
- Residual plot
- Histogram residual
- Bar plot feature importance
- Boxplot distribusi error per segmen harga
- Tabel evaluasi seluruh model

## Tools & Libraries
- Python 3.11
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn
- XGBoost, LightGBM
- Google Colab

## Struktur File
- USAHousePrice.ipynb # Notebook utama
- README.md # Dokumentasi proyek
- requirements.txt # Kebutuhan dependensi
- best_model.datsci # Model hasil pelatihan terbaik


## Catatan Tambahan
- Log transformasi sempat dipertimbangkan, namun hasil terbaik dicapai **tanpa log** pada target variabel.
- Model XGBoost dan LightGBM juga diujikan namun tidak melebihi performa GBR dalam konfigurasi saat ini.

## Author
Rahma Shinta V. – Master of Mathematics, Universitas Sebelas Maret

