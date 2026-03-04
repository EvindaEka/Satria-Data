# Dashboard Angka Partisipasi Sekolah

---

## 📌 Deskripsi Proyek
Dashboard Angka Partisipasi Sekolah adalah platform analitik interaktif berbasis Streamlit yang digunakan untuk menganalisis Angka Partisipasi Sekolah (APS) di Indonesia periode 2020–2024. Dashboard ini menyajikan visualisasi tren, perbandingan antar provinsi, serta hubungan APS dengan Indeks Pembangunan Manusia (IPM) dan tingkat pengangguran untuk mendukung evaluasi kebijakan pendidikan berbasis data.

---

## Fitur Utama
### 1. Halaman Home (Ringkasan Nasional)
* Filter berdasarkan **Tahun** dan **Provinsi**
* Score card
* Tren rata-rata APS nasional per jenjang (2020–2024)
* Scatter plot APS rata-rata vs Tingkat Pengangguran
* Top 5 Provinsi APS Tertinggi & Terendah

---

### 2. Halaman per Jenjang Pendidikan
Dashboard dibagi menjadi 4 halaman analisis:
* SD
* SMP
* SMA/SMK
* Perguruan Tinggi

Setiap halaman menampilkan:

#### 🔹 KPI Jenjang
* Total Sekolah
* Total Siswa
* Total Tenaga Pendidik
* Rata-rata APS

#### 🔹 Visualisasi
* Jumlah Sekolah per Provinsi
* Jumlah Siswa per Provinsi
* Jumlah Tenaga Pendidik per Provinsi
* Tren APS Nasional 2020–2024
* Scatter Plot APS vs IPM per Provinsi

---

## Insight yang Dihasilkan
* Identifikasi provinsi dengan APS tertinggi & terendah
* Tren peningkatan/penurunan APS per jenjang
* Hubungan antara APS dan IPM
* Hubungan antara APS rata-rata dan tingkat pengangguran
* Gambaran distribusi fasilitas pendidikan dan tenaga pendidik

---

## 🛠️ Teknologi yang Digunakan
* Python
* Streamlit
* Pandas
* Plotly Express
* Matplotlib

---

## ▶️ Cara Menjalankan
```bash
git clone https://github.com/EvindaEka/Satria-Data
cd Satria-Data
pip install -r requirements.txt
streamlit run app.py
```

Pastikan file `ESC.xlsx` berada di folder yang sama dengan `app.py`.

---

## 📁 Struktur Proyek
```
Satria-Data/
│
├── app.py
├── ESC.xlsx
├── requirements.txt
└── README.md
```
