# Analisis Kualitas Air Minum Menggunakan Machine Learning 💧

Repository ini merupakan hasil pengerjaan **Final Project Mata Kuliah Big Data & Data Mining**.  
Proyek ini bertujuan untuk menganalisis dan mengklasifikasikan kualitas air minum (layak atau tidak layak dikonsumsi) menggunakan beberapa algoritma **Machine Learning** berdasarkan dataset *Water Potability* dari Kaggle.

---

## 📌 Latar Belakang
Kualitas air minum merupakan faktor penting yang berpengaruh langsung terhadap kesehatan manusia. Air yang tidak memenuhi standar kualitas dapat menyebabkan berbagai penyakit. Oleh karena itu, diperlukan metode analisis yang efektif untuk membantu menentukan kelayakan air minum secara cepat dan akurat.

Dataset *Water Potability* memiliki beberapa tantangan, seperti **missing values** dan distribusi kelas yang tidak seimbang. Dalam proyek ini, dilakukan tahapan **preprocessing data** serta penerapan beberapa algoritma Machine Learning untuk membandingkan performa model dalam melakukan klasifikasi kualitas air minum.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 📊 Tahapan Pengerjaan
- **Data Loading:** Mengambil dataset *Water Potability* dari Kaggle.  
- **Preprocessing Data:**
  - Handling Missing Values.
  - Feature Scaling menggunakan StandardScaler.
- **Modeling:**
  - Logistic Regression
  - K-Nearest Neighbor (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- **Evaluasi Model:**
  - Akurasi
  - Confusion Matrix
  - Classification Report
- **Perbandingan Model:** Menentukan model dengan performa terbaik.

---

## 📈 Hasil Evaluasi
Berdasarkan pengujian pada data testing, beberapa model Machine Learning berhasil melakukan klasifikasi kualitas air minum dengan performa yang cukup baik.

Model dengan akurasi terbaik diperoleh dari **Random Forest / SVM** *(sesuai hasil pada notebook)*.  
Detail hasil evaluasi seperti **Confusion Matrix** dan **Classification Report** dapat dilihat langsung pada notebook.

---

## 📂 Struktur File
- `UAS_Big_Data_&_Mining_23_11_5733.ipynb` : Source code utama (Jupyter Notebook).
- `README.md` : Dokumentasi proyek.

---

## 🚀 Cara Menjalankan
1. Clone repository ini.
2. Buka file `.ipynb` menggunakan Google Colab atau Jupyter Notebook.
3. Pastikan dataset sudah diunduh dan disesuaikan dengan path yang digunakan.
4. Jalankan seluruh cell secara berurutan.

---

## 🔗 Link Dataset
https://www.kaggle.com/datasets/adityakadiwal/water-potability

---

Disusun oleh: **Redo Mas – 23.11.5733**
