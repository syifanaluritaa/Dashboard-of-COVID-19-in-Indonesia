# Analisis Tren Perkembangan dan Distribusi Spasial Kasus COVID-19 di Indonesia
Berkas ini berisi dokumentasi Dashboard Analisis COVID-19 Indonesia berbasis Excel dan Tableau dengan tema "Slate &amp; Teal". Dilengkapi visualisasi kartu KPI otomatis, tabel agregat 10 provinsi terpapar tertinggi menggunakan formula dinamis di Excel, serta interaktivitas drill-down grafik tren berkala yang dioptimalkan untuk Tableau Dashboard.

---

## 📝 Deskripsi Proyek (Project Description)

Proyek ini bertujuan untuk mengolah, meringkas, dan memvisualisasikan data deret waktu (*time-series*) penyebaran virus COVID-19 di Indonesia dari periode awal pandemi hingga fase pemulihan. Dengan memanfaatkan dataset publik tingkat nasional dan provinsi, analisis ini difokuskan pada identifikasi lonjakan gelombang penularan, perbandingan rasio kesembuhan terhadap fatalitas (*Case Fatality Rate - CFR*), serta pemetaan wilayah episentrum penyebaran tertinggi di tingkat provinsi.

Pendekatan yang digunakan dalam proyek ini menerapkan metode integrasi alat analitik multi-platform untuk memenuhi kebutuhan pelaporan yang berbeda:
1. **Microsoft Excel**: Digunakan sebagai fondasi utama pengolahan data mentah, proses pembersihan, manipulasi struktur tabel waktu (agregasi bulanan), serta pembuatan ringkasan dasbor eksekutif berbasis formula dinamis yang siap cetak.
2. **Tableau**: Digunakan untuk mentransformasikan data agregat menjadi sebuah sistem *dashboard* visual interaktif berskala korporat. Melalui Tableau, pengguna dapat melakukan eksplorasi data secara mandiri melalui filter wilayah (*drill-down*) dan melihat korelasi tren penularan harian secara *real-time*.

Keseluruhan visualisasi pada kedua platform dirancang secara konsisten menggunakan skema warna profesional **"Slate & Teal"**. Pemilihan palet ini sengaja diterapkan untuk menonjolkan indikator kinerja utama (*Key Performance Indicators - BANs*) secara tegas tanpa mengurangi kenyamanan visual bagi para pemangku kepentingan saat membaca data dalam volume besar.

---

## 🔗 Tautan Publik (Live Dashboard Link)
Untuk melihat dan berinteraksi langsung dengan grafik dinamis, filter wilayah, dan visualisasi penuh, silakan akses tautan Tableau Public berikut:
👉 [https://public.tableau.com/app/profile/syifa.nalurita.azahra/viz/DashboardofCOVID-19_17798711955490/InteractiveDashboard?publish=yes] 

---

## 📋 Struktur Lembar Kerja Excel
Proyek ini mengadopsi alur pemrosesan data terstruktur (data pipeline) di dalam lingkungan Excel yang dibagi ke dalam 4 lembar kerja utama:
1. **Raw Data (Data_Nasional & Data_Provinsi)**: Lembar kerja yang menampung basis data mentah historis penularan COVID-19 harian tanpa modifikasi, menjaga integritas sumber data asli.
2. **Filter Data**: Lembar kerja khusus proses pembersihan (*data cleansing*), pemilahan variabel relevan, dan eliminasi baris kosong atau data anomali agar siap diolah lebih lanjut.
3. **Pivot (Data_Aggregates)**: Lembar kerja yang memanfaatkan fitur *Pivot Table* untuk melakukan kompilasi dan agregasi data dari skala harian menjadi tren bulanan, yang juga berfungsi sebagai jembatan *Data Source* utama menuju Tableau.
4. **Dashboard**: Antarmuka visual akhir (*executive summary*) yang bersih tanpa *gridlines*, menampilkan 4 kartu KPI dinamis, tabel interaktif Top 10 Provinsi, serta grafik tren laju kasus.

---

## 🖥️ Pratinjau Antarmuka (Dashboard Screenshots)

### Tampilan Dashboard Microsoft Excel
<p align="center">
  <img src="Images/screenshot_excel.png" alt="Dashboard Excel Summary" width="100%" style="border-radius: 8px; border: 1px solid #334155;">
  <br>
  <em>Gambar 1.1: Tampilan Utama Eksekutif Dashboard pada Lembar Kerja Microsoft Excel.</em>
</p>

### Tampilan Dashboard Tableau
<p align="center">
  <img src="Images/screenshot_tableau.png" alt="Dashboard Tableau Interactive" width="100%" style="border-radius: 8px; border: 1px solid #334155;">
  <br>
  <em>Gambar 1.2: Visualisasi Interaktif dan Analisis Tren Berkala pada Platform Tableau.</em>
</p>

---
*Dibuat untuk keperluan visualisasi data multi-platform, portofolio analitik, dan pelaporan berkala dampak COVID-19 di Indonesia.*
