## 📊 Analisis Data Bencana Banjir 10 Tahun di Indonesia
Proyek ini bertujuan untuk menganalisis pola bencana banjir di Indonesia selama 10 tahun terakhir menggunakan data resmi dari BNPB. Kami melakukan eksplorasi data (EDA), visualisasi interaktif menggunakan Looker Studio, dan menerapkan algoritma Dynamic Time Warping (DTW) untuk mengukur kemiripan pola kejadian banjir antar provinsi.

## 🔗 Dashboard Insight (Looker Studio):
👉 [[Lihat Dashboard]](https://lookerstudio.google.com/reporting/935bd1f3-fb5a-4d73-853f-98be0621366b)

## 🗂️ Overview
Sumber Data: Badan Nasional Penanggulangan Bencana (BNPB)
Periode Data: Tahun 2014 – 2024
Wilayah Cakupan: Seluruh provinsi di Indonesia

## ⚙️ Langkah-langkah Analisis
1. Pengumpulan Data
Data dikumpulkan dari situs resmi BNPB yang berisi jumlah kejadian banjir per provinsi dari tahun 2014 hingga 2024.
2. Pra-pemrosesan Data
Pengubahan format tanggal
Agregasi jumlah kejadian banjir per bulan dan per provinsi
Penanganan missing values dan validasi konsistensi data

3. Eksplorasi Data (EDA)
Visualisasi jumlah kejadian banjir tahunan nasional dan per provinsi
Pemetaan daerah dengan frekuensi kejadian tinggi
Tren musiman

4. Dynamic Time Warping (DTW)
Menghitung jarak kemiripan pola kejadian banjir antar provinsi
Membandingkan pola waktu per bulan selama 10 tahun
Menemukan provinsi dengan pola bencana serupa (berbasis DTW)

5. Visualisasi Looker Studio
Dashboard interaktif menyajikan:
Jumlah kejadian banjir per tahun dan per wilayah
Diagram batang dan peta interaktif
Tren waktu dan pola bulanan

## 🔍 Insight Utama
Tren Nasional: Terjadi peningkatan jumlah kejadian banjir pada tahun-tahun tertentu yang berkorelasi dengan musim hujan ekstrem
Provinsi Rawan: Provinsi seperti Jawa Tengah, Jawa Barat, dan Kalimantan Selatan secara konsisten mencatat jumlah banjir tertinggi.
Pola Waktu: Bulan Januari dan Februari menjadi periode paling sering terjadi banjir.
Hasil DTW: Provinsi dengan pola banjir yang mirip (misalnya Jawa Barat dan Jawa Tengah) dapat dikelompokkan, memberikan potensi kolaborasi mitigasi regional.

## 🚀 Teknologi yang Digunakan
Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)
Looker Studio (Google Data Studio)
Google Colab
DTW from dtaidistance / custom implementation
