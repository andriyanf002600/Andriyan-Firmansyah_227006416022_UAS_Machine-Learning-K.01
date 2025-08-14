# Andriyan-Firmansyah_227006416022_UAS_Machine-Learning-K.01
Online Retail II — End-to-End Analysis (EDA, RFM, Segmentation, Association Rules, Cohort)
1. Judul Proyek

Online Retail II — End-to-End Analysis (EDA, RFM, Segmentation, Association Rules, Cohort)

# Analisis Market Basket Dataset Online Retail II

2. Deskripsi Singkat

Jelaskan tujuan dan ringkasan singkat.

Proyek ini bertujuan untuk melakukan analisis Market Basket menggunakan algoritma Apriori pada dataset Online Retail II. 
Hasil analisis ini dapat digunakan untuk menemukan pola pembelian konsumen dan rekomendasi produk.

3. Tujuan Analisis

Tulis tujuan utama yang ingin dicapai.

## 🎯 Tujuan
- Mengidentifikasi item yang sering dibeli bersamaan.
- Menemukan aturan asosiasi (association rules) yang bermanfaat.
- Memberikan wawasan untuk strategi promosi atau bundling produk.

4. Dataset

Jelaskan asal, format, dan isi dataset.

## 📂 Dataset
- **Nama File:** online_retail_II.xlsx
- **Sumber:** https://archive.ics.uci.edu/dataset/502/online+retail+ii
- **Deskripsi:** Berisi data transaksi retail online antara tahun 2009–2011.
- **Kolom Penting:**
  - Invoice: Nomor transaksi
  - Description: Nama produk
  - Quantity: Jumlah barang
  - InvoiceDate: Tanggal transaksi
  - Country: Negara pembeli

5. Algoritma yang Digunakan

Jelaskan algoritma yang dipakai dan alasan pemilihannya.

## 🧠 Algoritma
- **Algoritma Apriori**
  - Digunakan untuk menemukan frequent itemsets.
  - Cocok untuk analisis Market Basket karena dapat mengidentifikasi kombinasi barang yang sering dibeli bersama.
- **Library:** mlxtend

6. Instalasi & Cara Menjalankan

Berikan petunjuk supaya orang lain bisa menjalankan kode.

## ⚙️ Instalasi & Menjalankan Program
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/nama-repo.git


Masuk ke folder proyek:

cd nama-repo


Buka file .ipynb di Google Colab atau Jupyter Notebook.

Jalankan sel kode secara berurutan.


---

### **7. Output**
Tampilkan contoh hasil (screenshot atau link).
```md
## 📊 Output
- `frequent_itemsets.csv` → Daftar itemset yang sering muncul.
- `association_rules.csv` → Aturan asosiasi berdasarkan support, confidence, dan lift.
- `rules_scatter.png` → Visualisasi hubungan support vs lift.

Contoh Visualisasi:
![Scatter Plot](rules_scatter.png)

8. Struktur Folder

Tunjukkan susunan file di repo.

## 📁 Struktur Folder
.
├── outputs/
│   ├── frequent_itemsets.csv
│   ├── association_rules.csv
│   └── rules_scatter.png
├── online_retail_II.xlsx
├── analisis_market_basket.ipynb
└── README.md
