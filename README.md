# 💳 Bank Transaction Segmentation & Classification

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Proyek ini merupakan bagian dari submission kelas **Belajar Machine Learning untuk Pemula** di Dicoding.  
🎖️ **Rating Submission: 5/5 (Bintang Lima)**  
📁 Submission ID: `4128952`  
📅 Tanggal Kirim: `30 Maret 2025`

---

## 🧑‍💼 Peran dan Tanggung Jawab System Analyst

Sebagai System Analyst dalam proyek ini, saya bertanggung jawab untuk:

- 🧭 Menganalisis kebutuhan sistem segmentasi dan klasifikasi transaksi bank.
- 🔍 Menyusun pipeline *end-to-end* dari *data preprocessing*, *unsupervised clustering*, hingga *supervised classification*.
- 📑 Mendokumentasikan proses modeling, evaluasi, serta insight bisnis berdasarkan hasil klasterisasi.
- 📊 Mengevaluasi dan membandingkan performa algoritma klasifikasi berdasarkan akurasi dan F1-score.

---

## 🎯 Tujuan Proyek

1. Mengelompokkan pelanggan bank berdasarkan pola transaksinya (*unsupervised clustering*)
2. Membangun model klasifikasi untuk mengenali tipe pelanggan berdasarkan hasil klasterisasi
3. Menyediakan insight bagi pengambil keputusan untuk segmentasi pelanggan dan strategi marketing

---

## 🗂 Dataset

Dataset transaksi bank berisi ribuan baris data pengguna dengan fitur numerikal dan kategorikal.  
- `bank_transactions_clustering_dataset.csv`
- `bank_transactions_data.csv`

Kriteria:
- ≥ 2500 baris data
- ≥ 5 fitur campuran numerikal dan kategorikal
- Hasil clustering digunakan sebagai label klasifikasi

---

## 🔧 Tools dan Teknologi

- **Python** (v3.9)
- **Pandas**, **NumPy** – untuk *data wrangling*
- **Matplotlib**, **Seaborn** – visualisasi data
- **Scikit-learn** – untuk clustering, evaluasi, klasifikasi
- **Feature Selection** – SelectKBest / Mutual Information
- **Evaluation** – Silhouette Score, Accuracy, F1-Score

---

## 📊 Ringkasan Proses

### 🔹 Clustering

- Algoritma: KMeans
- Silhouette Score: **0.76** (dengan feature selection)
- Evaluasi klaster berdasarkan agregasi fitur
- Interpretasi deskriptif tiap klaster (karakteristik utama)

### 🔹 Klasifikasi

- Dataset dilabeli dari hasil klastering
- Dua model dibandingkan:
  - Random Forest Classifier
  - Logistic Regression
- Akurasi dan F1-score di atas **92%** untuk semua model

---

## 📝 Struktur Folder
```
bank-transaction-segmentation-classification/
├── README.md                                      # Dokumentasi proyek
└── LICENSE                                        # Lisensi (MIT)
├── bank_transactions_clustering_dataset.csv       # Dataset clustering (original)
├── bank_transactions_data.csv                     # Dataset hasil transformasi
├── clustering.ipynb                               # Notebook untuk unsupervised learning
├── klasifikasi.ipynb                              # Notebook untuk supervised learning
└── requirements.txt                               # Dependensi proyek
```


---

## 📦 Cara Menjalankan

### 1. Clone Repo
```bash
git clone https://github.com/username/bank-ml-project.git
cd bank-ml-project
```
### 2. Aktifkan Virtual Environment
```
python -m venv venv
source venv/bin/activate        # Linux/Mac
venv\Scripts\activate.bat       # Windows
```
### 3. Install Requirements
```
pip install -r requirements.txt
```
### 4. Jalankan Notebook
```
jupyter notebook
```
---
## 📌 Insight dan Saran Pengembangan
  - Perluasan fitur seperti frekuensi login, channel transaksi (ATM/Online)
  - Uji model pada data bank riil
  - Integrasi model ke dashboard manajemen pelanggan

---

## 👩‍💻 Tentang Pengembang

**Faizah Rizki Auliawati**  
Mahasiswa Informatika sekaligus seorang Data Enthusiast dengan minat mendalam pada bidang Machine Learning, System Analysis, dan pengembangan solusi berbasis data. Proyek ini merupakan bagian dari portofolio ilmiah dan praktikal untuk pengembangan sistem cerdas berbasis rekomendasi.

---

## 📄 Lisensi

Proyek ini berlisensi MIT. Lihat `LICENSE` untuk detail.
