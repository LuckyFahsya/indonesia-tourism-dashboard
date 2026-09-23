# 🗺️ Indonesia Tourism Destination — Power BI Dashboard

Dashboard analisis 437 destinasi wisata di 5 kota besar Indonesia (Jakarta, Bandung, Semarang, Yogyakarta, Surabaya), dibangun dengan Power BI untuk melihat bagaimana jenis dan sebaran wisata terdistribusi di tiap kota.

### 🎬 Demo interaktif

![Demo dashboard](screenshots/demo.gif)

*(rekaman singkat klik-klik filter, tabel, dan peta — lihat panduan bikinnya di bagian bawah README ini)*

---

## 📌 Ringkasan

| Metrik | Nilai |
|---|---|
| Total destinasi | 437 |
| Kota dianalisis | 5 |
| Kategori wisata | 6 |
| Kota dengan destinasi terbanyak | Yogyakarta (126) |
| Kategori terbesar | Taman Hiburan (135) |

## 📊 Dataset

- **Sumber:** [Indonesia Tourism Destination](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination) oleh aprabowo di Kaggle
- **Cakupan:** 437 destinasi wisata, 13 kolom (nama, kategori, kota, rating, harga, koordinat, dll)
- **Kota:** Jakarta, Bandung, Semarang, Yogyakarta, Surabaya
- **Kategori:** Bahari, Budaya, Cagar Alam, Pusat Perbelanjaan, Taman Hiburan, Tempat Ibadah

## 🛠️ Tools & proses

- **Power BI Desktop** — pemodelan data & pembuatan visual
- **DAX** — pengukuran (measures) untuk KPI dan agregasi
- **Custom theme JSON** — palet warna teal konsisten di seluruh dashboard (lihat `Tema_Wisata_Teal.json`)

## 🖼️ Tampilan dashboard

Tambahkan screenshot dashboard kamu di sini, contoh:

```markdown
![Overview](screenshots/overview.png)
![Detail per kota](screenshots/by-city.png)
```

## 💡 Insight utama

- **Taman Hiburan mendominasi** — 135 dari 437 destinasi (31%) masuk kategori Taman Hiburan, jauh di atas kategori lain.
- **Yogyakarta & Bandung memimpin** — kedua kota ini menyumbang 250 dari 437 destinasi (57%), jauh di atas Jakarta, Semarang, dan Surabaya.
- **Budaya & alam kuat di Jawa** — Budaya (117) dan Cagar Alam (106) jadi kategori terbesar kedua dan ketiga, sejalan dengan banyaknya candi dan situs alam di Jawa Tengah & DIY.

## 📁 Struktur repo

```
├── README.md
├── Portofolio Power BI.pbix    # file Power BI
├── Tema_Wisata_Teal.json       # custom Power BI theme
└── screenshots/                # tangkapan layar dashboard
```

## ▶️ Coba sendiri (opsional)

Video demo di atas sudah mencakup fitur utamanya. Kalau mau eksplor lebih dalam sendiri:

1. Download `Portofolio Power BI.pbix`
2. Buka dengan Power BI Desktop (gratis di Microsoft Store)
3. Kalau mau pakai theme warna yang sama: **View → Themes → Browse for themes** → pilih `Tema_Wisata_Teal.json`

## 🎥 Cara bikin demo GIF-nya (catatan pribadi)

1. Buka Power BI Desktop, tekan `Win + G` buat buka Xbox Game Bar (bawaan Windows)
2. Klik record, lalu klik-klik dashboard selama 10-15 detik (ganti filter, klik tabel, zoom map)
3. Stop recording, hasilnya .mp4 otomatis tersimpan di folder *Videos > Captures*
4. Convert ke .gif lewat [ezgif.com/video-to-gif](https://ezgif.com/video-to-gif) — upload video, compress kalau perlu (target di bawah 10MB biar cepat loading di GitHub)
5. Simpan hasilnya sebagai `screenshots/demo.gif`

## 🙌 Kredit

Dataset oleh [aprabowo di Kaggle](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination). Dibuat oleh **[nama kamu]** sebagai bagian dari portofolio data analyst.
