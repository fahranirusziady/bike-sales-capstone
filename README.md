#Capstone Project: Analisis Penjualan Sepeda  

## Latar Belakang Proyek  
Proyek ini menganalisis dataset penjualan sepeda untuk menemukan profil pelanggan, tren geografis, performa produk, serta pola pendapatan. Tujuannya adalah menghasilkan insight dan rekomendasi yang dapat digunakan untuk mendukung strategi bisnis, pemasaran, dan penjualan.  

## Tujuan  
- Melakukan pembersihan dan persiapan data untuk analisis.  
- Mengklasifikasikan kategori pendapatan (Tinggi / Sedang / Rendah).  
- Membuat visualisasi terkait demografi pelanggan, distribusi geografis, produk, serta tren finansial.  
- Menyimpulkan insight utama dan memberikan rekomendasi bisnis.  

## Dataset  
- **Sumber**: Dataset sampel publik (fiksi penjualan sepeda) via Kaggle.  
- **Periode**: 2011 – 2016  
- **Fitur Utama**: Demografi pelanggan, lokasi, informasi produk, pendapatan, biaya, dan profit.  

## Metodologi  
1. **Pembersihan Data**:  
   - Menghapus data duplikat & menangani nilai kosong.  
   - Konversi kolom tanggal ke format datetime.  
   - Normalisasi kolom numerik.  

2. **Klasifikasi**:  
   - Pendapatan dikelompokkan ke kategori: *Tinggi, Sedang, Rendah*.  

3. **Visualisasi**:  
   - Distribusi umur, gender, negara, kategori produk.  
   - Tren pendapatan bulanan.  
   - Analisis profit tahunan.  

4. **Ringkasan**:  
   - Menyajikan insight utama terkait pelanggan, lokasi, produk, dan tren finansial.  

## Insight Utama  
- Mayoritas pelanggan adalah **Adults (35–64)** dan **Young Adults (25–34)**.  
- Penjualan terkuat berasal dari **Australia & Canada**, disusul **USA**.  
- Hanya terdapat 1 produk: *Hitch Rack – 4-Bike* dengan harga $120 dan margin profit 62,5%.  
- Pendapatan musiman dengan puncak di **Mei** dan **Desember**.  
- Profit meningkat 2011–2015, menurun di 2016 (indikasi pasar mulai jenuh).  

## Rekomendasi  
1. **Targeted Marketing** → fokus ke segmen Adults (35–64) & Young Adults (25–34).  
2. **Strategi Geografis** → perkuat penetrasi di Australia & Canada, ekspansi lebih agresif ke USA.  
3. **Diversifikasi Produk** → kurangi ketergantungan pada satu produk dengan meluncurkan variasi baru.  
4. **Promosi Musiman** → tingkatkan stok & kampanye promosi di bulan dengan penjualan tertinggi.  
5. **Pantau Penurunan Profit** → investigasi penurunan tahun 2016 (kompetitor, demand, atau faktor eksternal).  

## Struktur Repository  
Capstone_Project_Bike_Sales/
│── README.md # Dokumentasi utama proyek
│── insights_summary.md # Ringkasan insight & rekomendasi
│── Capstone_Project.ipynb # Notebook analisis (Colab/Jupyter)
│── bike_data.csv # Dataset mentah (jika diperbolehkan publik)
│── bike_data_cleaned.csv # Dataset hasil pembersihan
│── images/ # Folder berisi grafik visualisasi

Link Dataset Bike Sales :
https://drive.google.com/drive/folders/1mQ1-0lJJkPA1Gl2KYdXsCNr-5DF_juKT?usp=sharing
https://www.kaggle.com/code/ahmedterry/bike-sales-analysis/notebook

## 🚀 Cara Menjalankan  
1. Clone repository:  
   ```bash
   git clone https://github.com/fahranirusziady/bike-sales-capstone.git
