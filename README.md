# 📊 Analisis Sentimen Ulasan Pelanggan  
**Final Project – Big Data and Data Mining**

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **analisis sentimen terhadap ulasan pelanggan berbahasa Indonesia** menggunakan pendekatan **text mining dan machine learning**. Analisis sentimen dilakukan untuk mengklasifikasikan ulasan pelanggan ke dalam kategori **positif** dan **negatif**, sehingga dapat digunakan sebagai **pendukung pengambilan keputusan operasional dan manajemen**.

Seiring meningkatnya jumlah ulasan pelanggan pada platform digital dan e-commerce, analisis manual menjadi tidak efisien. Oleh karena itu, proyek ini menerapkan **metode klasifikasi** untuk mengotomatisasi proses analisis sentimen dan mengekstraksi insight dari data teks.

---

## 🎯 Tujuan
- Menerapkan tahapan **data mining** secara lengkap  
- Membangun model **klasifikasi sentimen** berbasis teks  
- Mengevaluasi performa model menggunakan metrik evaluasi yang sesuai  
- Memberikan insight berbasis data untuk mendukung keputusan manajerial  

---

## 📂 Dataset
- **Nama Dataset**: Indonesian Sentiment Analysis Dataset  
- **Sumber**: IndoNLU / Indobenchmark (Public Dataset)  
- **Link Dataset**:  
  https://github.com/indobenchmark/indonlu  

Dataset berisi teks ulasan pelanggan berbahasa Indonesia yang telah diberi label sentimen.

---

## ⚙️ Metodologi
Proyek ini mengikuti tahapan **Knowledge Discovery in Databases (KDD)**:
1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Extraction & Selection (TF-IDF)  
5. Modeling (Naive Bayes Classifier)  
6. Model Evaluation  

---

## 🧠 Algoritma & Tools
- **Algoritma**: Multinomial Naive Bayes  
- **Feature Extraction**: TF-IDF  
- **Bahasa Pemrograman**: Python  
- **Library**:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - NLTK  
  - Sastrawi  
  - Matplotlib  
  - Seaborn  
- **Platform**: Google Colab  

---

## 📈 Evaluasi Model
Evaluasi dilakukan menggunakan:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

Hasil evaluasi menunjukkan bahwa model memiliki performa yang cukup baik dalam mengklasifikasikan sentimen ulasan pelanggan.

---

## 📁 Struktur Folder
```text
├── dataset/
├── model/
│   └── sentiment_model.pkl
├── notebook/
│   └── analisis_sentimen.ipynb
├── README.md
