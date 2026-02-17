#  Analisis Efisiensi FCR Broiler

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0.3-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-orange)
![License](https://img.shields.io/badge/License-MIT-green)

##  Ringkasan Proyek

Proyek ini menganalisis **efisiensi pakan (FCR)** pada peternakan broiler dengan **100 kandang** di **5 lokasi berbeda** selama periode **1 tahun** (10.000 data).

**Latar Belakang:**
- FCR adalah metrik utama efisiensi broiler
- Target FCR ideal: **1.60**
- FCR > 1.8 = boros, perlu intervensi

##  Temuan Utama

| Metrik | Nilai | Status |
|--------|-------|--------|
| Rata-rata FCR | **2.03** | ❌ Boros |
| Lokasi Terbaik | A (1.58) | ✅ Efisien |
| Lokasi Terburuk | D (2.15) | ❌ Boros |
| Kerugian per Tahun | **Rp 248 Milyar** | ⚠️ Serius |

## Insight Penting

1. **Lokasi D** perlu intervensi segera (FCR tertinggi)
2. **Suhu tinggi** berkorelasi kuat dengan FCR boros (r = 0.78)
3. **Kualitas air (WQI)** faktor penting efisiensi (r = -0.65)
4. Potensi hemat **Rp 92 M** jika FCR turun ke 1.8

##  Teknologi yang Digunakan

- Python 3.14
- Pandas (manipulasi data)
- Matplotlib & Seaborn (visualisasi)
- Jupyter Notebook

## 📁 Struktur File
📁 broiler-analisis2025/
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 LICENSE
├── 📁 data/
│ └── 📄 dataset_broiler2025.csv
├── 📁 notebooks/
│ └── 📄 analisis_fcr.ipynb
└── 📁 visualisasi/
├── 📄 Distribusi FCR.png
├── 📄 Outlier dan Sebaran Data FCR.png
├── 📄 Perbandingan FCR per Lokasi.png

## Cara Menjalankan

1. Clone repository:
```bash
git clone https://github.com/username/broiler-analisis2025.git
cd broiler-analisis2025

pip install -r requirements.txt

jupyter notebook notebooks/analisis_fcr.ipynb

Hasil Visualisasi
Distribusi FCR
https://visualisasi/Distribusi FCR.png

Perbandingan per Lokasi
https://visualisasi/Outlier dan Sebaran Data FCR.png

Komposisi Performance
https://visualisasi/Perbandingan FCR per Lokasi.png

Lisensi
MIT License - Silakan gunakan dan modifikasi sesuai kebutuhan.

Kontak
Nama: [alfius jefirel]
Email: [jefirel.alfius@gmail.com]
LinkedIn: linkedin.com/in/alfius-jefirel-purba-38737b3b1


