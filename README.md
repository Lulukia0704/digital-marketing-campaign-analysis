# Analisis Performa Kampanye Digital Marketing dan Efisiensi Anggaran

## 📌 Gambaran Proyek

Proyek ini bertujuan untuk mengevaluasi performa kampanye digital marketing dan menganalisis efisiensi penggunaan anggaran iklan pada berbagai kanal pemasaran.

Dengan memanfaatkan data kampanye iklan, proyek ini berfokus pada analisis interaksi audiens, perbandingan efisiensi antar-channel, tren performa kampanye, serta penggunaan anggaran untuk membantu perusahaan mengambil keputusan bisnis berbasis data.

Proses analisis meliputi pembersihan data menggunakan Python dan Pandas di Google Colab, kemudian visualisasi hasil analisis menggunakan Google Looker Studio.

## 🎯 Tujuan Analisis

1. Mengevaluasi efektivitas kampanye digital marketing berdasarkan impresi, klik, dan rasio klik.
2. Membandingkan efisiensi biaya iklan antar-kanal pemasaran.
3. Menganalisis perbedaan performa kampanye antara hari kerja dan akhir pekan.
4. Memantau penggunaan anggaran melalui perbandingan anggaran yang dialokasikan, pengeluaran aktual, dan sisa anggaran.
5. Menyediakan informasi yang dapat mendukung optimasi kampanye dan alokasi anggaran iklan.

## ❓ Pertanyaan Bisnis

### 1. Apakah kampanye marketing berjalan efektif?

- Bagaimana tren impresi dan klik iklan dari waktu ke waktu?
- Kanal pemasaran mana yang memiliki Click-Through Rate (CTR) lebih tinggi?
- Apakah performa kampanye berbeda antara hari kerja dan akhir pekan?

### 2. Apakah anggaran iklan sudah digunakan secara efisien?

- Berapa total biaya yang dikeluarkan untuk kampanye iklan?
- Kanal pemasaran mana yang memiliki Cost Per Click (CPC) lebih rendah?
- Bagaimana perbandingan anggaran yang dialokasikan dengan pengeluaran aktual?
- Kampanye mana yang memiliki sisa anggaran paling besar?

## 🛠️ Tools dan Teknologi

- **Python** — Pengolahan dan persiapan data.
- **Pandas** — Manipulasi dan pembersihan data.
- **Google Colab** — Lingkungan untuk menjalankan kode Python.
- **Google Looker Studio** — Visualisasi data dan pembuatan dashboard interaktif.

## 📊 Dashboard

Dashboard interaktif dibuat menggunakan Google Looker Studio untuk menyajikan indikator performa kampanye dan efisiensi anggaran dalam bentuk visualisasi yang mudah dipahami.

### Pratinjau Dashboard

![Digital Marketing Campaign Dashboard](dashboard/dashboard_preview.png)

🔗 **[Lihat Dashboard Interaktif di Google Looker Studio](https://datastudio.google.com/reporting/e8f28b3c-1ea1-4a8f-9975-ddd778578032)**

## 📈 Metrik yang Dianalisis

| Metrik | Penjelasan |
|---|---|
| Total Spend | Total biaya iklan yang dikeluarkan. |
| Total Clicks | Total klik yang dihasilkan oleh kampanye. |
| Click-Through Rate (CTR) | Persentase impresi yang menghasilkan klik. |
| Cost Per Click (CPC) | Rata-rata biaya untuk memperoleh satu klik. |
| Cost Per Mille (CPM) | Biaya per 1.000 impresi. |
| Allocated Budget | Anggaran yang dialokasikan untuk kampanye. |
| Actual Spend | Pengeluaran aktual kampanye. |
| Remaining Budget | Sisa anggaran setelah dikurangi pengeluaran aktual. |

## 💡 Temuan Utama

Berdasarkan hasil yang ditampilkan pada dashboard:

- **Efisiensi kanal:** Kanal Display tercatat sebagai kanal dengan efisiensi biaya terbaik pada dashboard.
- **Tren performa:** Kampanye menunjukkan performa yang lebih kuat pada hari kerja dibandingkan akhir pekan.
- **Penggunaan anggaran:** Sebagian besar kampanye masih berada di bawah anggaran yang telah dialokasikan.

Temuan tersebut dapat digunakan sebagai dasar evaluasi awal untuk menentukan kanal pemasaran yang perlu dioptimalkan dan kampanye yang membutuhkan peninjauan anggaran lebih lanjut.

## ⚠️ Batasan Analisis

Analisis ini berfokus pada performa interaksi iklan, efisiensi biaya, dan penggunaan anggaran.

Dataset yang ditampilkan belum menyediakan metrik konversi dan pendapatan penjualan. Oleh karena itu, analisis ini belum dapat memastikan efektivitas kampanye dalam menghasilkan penjualan, Return on Advertising Spend (ROAS), atau profitabilitas secara keseluruhan.

## 📁 Struktur Proyek

```text
digital-marketing-campaign-analysis/
├── README.md
├── notebooks/
│   └── marketing_data_cleaning.ipynb
├── dashboard/
│   └── dashboard_preview.png
└── data/
    └── README.md
```

*Struktur di atas merupakan rekomendasi. Sesuaikan nama dan lokasi file dengan isi repository yang sebenarnya.*

## 👩‍💻 Tentang Penulis

**Luluk Asti**

Proyek ini merupakan bagian dari portofolio analisis data yang berfokus pada pengolahan data, visualisasi, dan penerapan analisis untuk mendukung pengambilan keputusan bisnis.
