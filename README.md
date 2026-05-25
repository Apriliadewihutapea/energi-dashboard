# EnergiData — Dashboard Transisi Energi 🌿

> **DARI DATA KE AKSI: MENDORONG LITERASI ENERGI RUMAH TANGGA URBAN**  

[![Live Dashboard](https://img.shields.io/badge/Dashboard-Live-brightgreen)](https://apriliadewihutapea.github.io/energi-dashboard/)
[![Responden](https://img.shields.io/badge/Responden-73-blue)]()
[![Proyeksi Reduksi](https://img.shields.io/badge/Reduksi%20CO₂e-15.7%20ton%2Ftahun-green)]()
[![SDG](https://img.shields.io/badge/SDG-7%20%7C%2010%20%7C%2013%20%7C%2017-orange)]()

---

## 📌 Tentang Proyek

**EnergiData** adalah platform literasi energi berbasis data yang dirancang untuk menjembatani kesenjangan antara data teknis konsumsi energi dengan tindakan nyata yang dapat dilakukan oleh rumah tangga urban di Indonesia.

Proyek ini lahir dari satu temuan lapangan yang mengejutkan: sebagian besar masyarakat tidak tahu cara menghitung jejak karbon rumah tangga mereka sendiri, bukan karena tidak peduli, tetapi karena informasi itu tidak pernah hadir dalam bahasa yang mereka mengerti, di platform yang mereka gunakan sehari-hari.

> *"Data adalah energi pertama yang harus kita sebarkan."*

---

## 🌐 Akses Dashboard

🔗 **[apriliadewihutapea.github.io/energi-dashboard](https://apriliadewihutapea.github.io/energi-dashboard/)**

Dashboard memiliki empat menu utama:

| Menu | Deskripsi |
|------|-----------|
| **Impact Overview** | Metrik dampak terukur secara real-time |
| **Data Primer LIVE** | Visualisasi hasil survei lapangan yang terus diperbarui |
| **Capaian SDG** | Keterkaitan temuan data dengan indikator SDG spesifik |
| **Roadmap** | Peta jalan pengembangan aksi secara transparan |

---

## 📊 Metodologi & Model Kalkulasi Emisi

Model emisi dibangun berdasarkan data resmi yang dapat diaudit secara terbuka:

```
Rata-rata konsumsi RT/bulan     : ~124 kWh
                                  (Statistik PLN 2022: 116.095 GWh ÷ 78,3 juta pelanggan)

Faktor emisi listrik PLN        : 0,85 kg CO₂e/kWh
                                  (Dirut PLN Darmawan Prasodjo, web.pln.co.id, Okt 2022)

Emisi baseline per RT/tahun     : 1.265 kg CO₂e
                                  (124 kWh × 0,85 kg × 12 bulan)

Potensi efisiensi energi RT     : 10–30% (rata-rata 17%)
                                  (Sumber: ESDM & IEA Energy Efficiency 2022)

Reduksi per RT/tahun            : ~215 kg CO₂e
                                  (1.265 kg × 17%)
```

### Proyeksi Dampak (Live)

| Indikator | Nilai |
|-----------|-------|
| Total responden survei | **73 orang** |
| Proyeksi reduksi CO₂e/tahun | **15,7 ton** |
| Responden bersedia hemat energi | **56%** |
| SDG yang didukung | **4 SDG** (7, 10, 13, 17) |

---

## 🗂️ Sumber Data

| Sumber | Digunakan untuk |
|--------|-----------------|
| Statistik PLN 2022 | Konsumsi RT, distribusi penjualan listrik per sektor |
| Kementerian ESDM 2023 | Capaian penurunan emisi GRK sektor energi 2019–2023 |
| DEN/ESDM 2023 | Capaian bauran EBT nasional vs target KEN 23% |
| IEA Energy Efficiency 2022 | Estimasi potensi efisiensi energi rumah tangga |
| BPS 2024 | Data demografis pendukung |
| Google Form (Live) | Data primer survei lapangan |

---

## 🗺️ Roadmap Pengembangan

### ✅ Tahap 1 — Fondasi (2024–2025) `Selesai`
- Penyusunan model analisis data konsumsi energi rumah tangga urban
- Survei Google Form kepada 250+ responden
- Integrasi data sekunder: PLN, ESDM, KLHK, BPS
- Validasi model dengan data aktual
- Peluncuran dashboard EnergiData v1.0 (live)

### ⏳ Tahap 2 — Pilot Project (2025–2026) `Berlangsung`
- Peluncuran dashboard publik sebagai media edukasi utama
- Sesi edukasi berbasis visualisasi dashboard (bukan presentasi konvensional)
- Dokumentasi metodologi untuk replikasi
- Evaluasi perubahan pengetahuan dan niat perilaku responden

### 📋 Tahap 3 — Replikasi & Integrasi Kebijakan (2026+) `Direncanakan`
- Adopsi model oleh universitas-universitas di kota berbeda (SDG 17)
- Integrasi dengan program efisiensi energi daerah
- Publikasi open-source kerangka model untuk komunitas nasional
- Target: **1.000+ rumah tangga teredukasi**
- Target reduksi emisi kolektif: **74 ton CO₂e/tahun**

---

## 🎯 Kontribusi terhadap SDGs

| SDG | Kontribusi |
|-----|-----------|
| **SDG 7** — Energi Bersih & Terjangkau | Peningkatan literasi konsumsi energi rumah tangga urban |
| **SDG 10** — Berkurangnya Kesenjangan | Distribusi informasi energi inklusif untuk kelompok menengah ke bawah |
| **SDG 13** — Penanganan Perubahan Iklim | Reduksi CO₂e melalui perubahan perilaku berbasis data |
| **SDG 17** — Kemitraan untuk Tujuan | Model modular open-source untuk replikasi komunitas nasional |

---

## 🔧 Teknologi

- **Frontend:** HTML, CSS, JavaScript
- **Visualisasi:** Chart.js
- **Data primer:** Google Forms (live integration)
- **Hosting:** GitHub Pages
- **Desain:** Responsif, dapat diakses tanpa latar belakang teknis

---

## 📁 Struktur Repositori

```
energi-dashboard/
├── index.html          # Dashboard utama
├── assets/
│   ├── css/            # Stylesheet
│   └── js/             # Logic & Chart.js config
├── data/
│   └── primer.json     # Cache data survei (diperbarui berkala)
└── README.md
```

---

## 📄 Lisensi

Model data dan kerangka metodologi bersifat **open-source**, bebas diadopsi oleh komunitas lain dengan menyesuaikan data input lokal.

---

*EnergiData Dashboard*  
*Data: BPS 2024 · PLN Statistics 2022 · KLHK GRK 2023 · Google Form Primer (Live)*
