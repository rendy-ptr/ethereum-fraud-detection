# 🛡️ Model Machine Learning untuk Deteksi Penipuan Ethereum

Proyek ini menguji berbagai model machine learning untuk mendeteksi penipuan pada transaksi Ethereum, menggunakan dataset dari Kaggle.

---

## 📋 Deskripsi

Repositori ini berfokus pada eksplorasi, pelatihan, dan evaluasi beberapa algoritma machine learning untuk klasifikasi penipuan transaksi Ethereum. Proyek ini mencakup proses preprocessing data, pelatihan model, evaluasi performa menggunakan berbagai metrik, serta visualisasi hasil.

---

## ✨ Fitur

- ✅ Implementasi berbagai model ML (SVM, Gaussian Naive Bayes, Extra Trees, LightGBM, CatBoost)
- 🧹 Preprocessing dan scaling data khusus tiap model
- 📈 Evaluasi dan visualisasi metrik (akurasi, presisi, recall, F1)
- 📊 Perbandingan performa model secara komprehensif
- 🔍 Pengujian dengan Ethereum Fraud Detection Dataset dari Kaggle

---

## 🚀 Cara Menjalankan

1. **Clone repositori**
   
   ```bash
   https://github.com/rendy-ptr/ethereum-fraud-detection.git
   cd ethereum-fraud-detection
   
2. **Install dependensi**
   
     ```bash
    pip install scikit-learn numpy pandas matplotlib joblib catboost

3. **Jalankan notebook**

   ```bash
    jupyter notebook Src/pengujian-model/default-model.ipynb

---

## 🗂️ Struktur Proyek

```text
├── Src/
│   └── pengujian-model/
│       └── default-model.ipynb
├── picture/
│   └── visualisasi dan grafik evaluasi
├── catboost_info/
│   └── log dan metadata CatBoost
```

---

## 🧠 Model yang Diimplementasikan

- Support Vector Machine (SVM)

- Gaussian Naive Bayes (GNB)

- CatBoost

- Extra Trees Classfier (ETC)

- Light Gradient Boosting Machine (LGBM)

---

## 📝 Proses Pengujian

1. Membagi data menjadi training dan testing

2. Melakukan scaling tergantung model:

   - MinMaxScaler → SVM

   - PowerTransformer → GNB

3. Melatih model pada data training

4. Melakukan prediksi pada data testing

5. Menghitung metrik: Akurasi, Presisi, Recall, dan F1-Score

---

## 📊 Dataset
Ethereum Fraud Detection Dataset (Kaggle) mencakup:

   - Transaksi Ethereum yang diberi label (sah/penipuan)

   - Fitur seperti nilai transaksi, waktu, dan pola aktivitas

   - Cocok untuk klasifikasi biner dan studi keamanan blockchain

sumber : https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset

---

## 📈 Hasil Evaluasi

Model dievaluasi menggunakan:

   - Accuracy – Rasio prediksi benar dari semua prediksi

   - Precision – Rasio prediksi positif yang benar

   - Recall – Rasio deteksi terhadap kasus positif sebenarnya

   - F1-Score – Harmonik dari precision dan recall

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

## 🙏 Terima Kasih

Terima kasih kepada:

   - Kaggle atas dataset Ethereum Fraud Detection

   - Komunitas open-source yang mendukung riset deteksi penipuan blockchain

---

Dibuat dengan ❤️ untuk penelitian deteksi penipuan dalam transaksi Ethereum.
