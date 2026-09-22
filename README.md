# 🗺️ Indonesia Tourism Destination — Power BI Dashboard

Dashboard analisis 437 destinasi wisata di 5 kota besar Indonesia (Jakarta, Bandung, Semarang, Yogyakarta, Surabaya), dibangun dengan Power BI untuk melihat bagaimana jenis dan sebaran wisata terdistribusi di tiap kota.

**🔗 [Lihat versi web interaktif](https://claude.ai/artifact/6fUVzasfjsesSQsnPGwv7e)**
*(ganti link ini dengan versi yang sudah kamu host sendiri di GitHub Pages, lihat bagian "Cara menjalankan" di bawah)*

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
- **HTML/CSS/JS (Chart.js)** — versi web interaktif untuk portofolio

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
├── dashboard.pbix              # file Power BI (isi sendiri)
├── Tema_Wisata_Teal.json       # custom Power BI theme
├── dashboard.html              # versi web interaktif (portofolio)
└── screenshots/                # tangkapan layar dashboard
```

## ▶️ Cara menjalankan

**File Power BI:**
1. Download `dashboard.pbix`
2. Buka dengan Power BI Desktop (gratis di Microsoft Store)

**Versi web interaktif:**
1. File `dashboard.html` bersifat *self-contained* — tinggal buka langsung di browser
2. Untuk host publik gratis lewat GitHub Pages: masuk ke **Settings → Pages** di repo ini, pilih branch `main` dan folder root, lalu akses di `https://<username>.github.io/<nama-repo>/dashboard.html`

## 🙌 Kredit

Dataset oleh [aprabowo di Kaggle](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination). Dibuat oleh **[nama kamu]** sebagai bagian dari portofolio data analyst.
