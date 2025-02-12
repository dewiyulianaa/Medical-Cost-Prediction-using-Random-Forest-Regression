# Medical-Cost-Prediction-using-Random-Forest-Regression
# 💡 Medical Cost Prediction

## 📌 Project Overview
Medical Cost Prediction adalah proyek machine learning yang bertujuan untuk memprediksi biaya medis seseorang berdasarkan berbagai faktor seperti usia, BMI, jumlah anak, status perokok, dan wilayah tempat tinggal. Model ini menggunakan **Random Forest Regressor** untuk melakukan prediksi dengan tingkat akurasi yang tinggi.

## 📂 Dataset
Dataset yang digunakan adalah **Medical Cost Personal Datasets**, yang terdiri dari beberapa fitur utama:
- **age**: Usia pasien
- **sex**: Jenis kelamin pasien
- **bmi**: Indeks Massa Tubuh (BMI)
- **children**: Jumlah anak yang ditanggung oleh pasien
- **smoker**: Apakah pasien perokok atau bukan
- **region**: Wilayah tempat tinggal pasien
- **charges**: Biaya medis yang harus dibayarkan (Target/Label)

Sumber dataset: [Medical Cost Dataset](https://www.kaggle.com/mirichoi0218/insurance)

## 🛠️ Tech Stack
- **Python** (pandas, numpy, seaborn, matplotlib, scikit-learn)
- **Machine Learning** (Random Forest Regression)
- **Jupyter Notebook / Google Colab**

## 🚀 Installation & Usage
1. Clone repository ini:
   ```bash
   git clone https://github.com/yourusername/medical-cost-prediction.git
   cd medical-cost-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook di Jupyter/Google Colab dan mulai eksplorasi data serta pelatihan model.

## 📊 Exploratory Data Analysis (EDA)
EDA dilakukan untuk memahami pola data dan korelasi antar fitur menggunakan visualisasi seperti:
- *Pairplot* untuk melihat hubungan antar variabel
- *Histogram* untuk distribusi data
- *Feature Correlation Matrix* untuk mengidentifikasi fitur yang paling berpengaruh

## 🔍 Model & Evaluation
Model **Random Forest Regressor** digunakan dengan **hyperparameter tuning**, dan evaluasi model dilakukan dengan metrik berikut:
- **MAE (Mean Absolute Error)**: Mengukur seberapa besar rata-rata kesalahan prediksi dalam satuan aslinya.
- **MSE (Mean Squared Error)**: Menghitung rata-rata kesalahan kuadrat untuk penalti yang lebih besar terhadap error besar.
- **R² Score**: Menunjukkan seberapa baik model dapat menjelaskan variabilitas data.

Hasil evaluasi model:
```
Train MAE: 2092.73
Train MSE: 14609368.23
Train R² Score: 0.8938
Test MAE: 2467.03
Test MSE: 19296935.80
Test R² Score: 0.8884
```

## 📌 Key Findings
- Status perokok memiliki dampak signifikan terhadap biaya medis, meningkatkan biaya hingga beberapa kali lipat dibandingkan non-perokok.
- BMI yang tinggi juga berkontribusi terhadap peningkatan biaya, menunjukkan hubungan antara obesitas dan risiko kesehatan.
- Model **Random Forest Regressor** menunjukkan performa yang baik dengan R² Score di atas 0.88.

## 📞 Contact
📧 Email: dewiyulianaa938@gmail.com  
🔗 LinkedIn: www.linkedin.com/in/dewiyuliana1507  
🐙 GitHub: https://github.com/dewiyulianaa

