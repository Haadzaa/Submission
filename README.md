# 📊 E-Commerce Data Analysis Project

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis data pada dataset e-commerce guna memahami pola transaksi dan perilaku pelanggan. Analisis dilakukan menggunakan Python dengan pendekatan data analysis pipeline mulai dari data wrangling hingga pembuatan dashboard interaktif.

## 🎯 Pertanyaan Bisnis
1. Bagaimana tren jumlah order dan revenue dari waktu ke waktu?
2. Bagaimana segmentasi pelanggan berdasarkan RFM (Recency, Frequency, Monetary) Analysis?

## 📂 Dataset
Dataset yang digunakan merupakan dataset e-commerce publik yang terdiri dari beberapa tabel, di antaranya:
- orders_dataset
- customers_dataset
- order_items_dataset
- order_payments_dataset

## 🧠 Metode Analisis
Proses analisis yang dilakukan meliputi:
- Data Wrangling (Gathering & Cleaning Data)
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Data Visualization
- RFM Analysis (Recency, Frequency, Monetary)
- Customer Segmentation (Manual Clustering)

## 📊 Insight Utama
- Terdapat pola tren transaksi yang berubah dari waktu ke waktu
- Revenue dipengaruhi oleh frekuensi dan nilai pembelian pelanggan
- Segmentasi pelanggan menunjukkan adanya kelompok pelanggan bernilai tinggi yang berkontribusi besar terhadap total revenue

## 🖥️ Dashboard
Dashboard dibuat menggunakan Streamlit untuk menampilkan hasil analisis secara interaktif.

### Cara Menjalankan Dashboard
```bash
streamlit run dashboard/dashboard.py
