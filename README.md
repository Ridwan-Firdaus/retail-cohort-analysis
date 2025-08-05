# Retail Cohort Analysis

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis **perilaku retensi pelanggan** berdasarkan data transaksi dari sebuah toko retail menggunakan teknik **Cohort Analysis**. Dengan analisis ini, kita dapat memahami seberapa lama pelanggan bertahan sejak pembelian pertama dan kapan mereka cenderung kembali berbelanja.

## Tujuan Analisis

- Mengidentifikasi kelompok pelanggan berdasarkan waktu pertama kali mereka berbelanja (*cohort*).
- Melihat tren retensi pelanggan dari waktu ke waktu.
- Memberikan insight strategis untuk meningkatkan loyalitas dan pembelian ulang pelanggan.

## Dataset

- Nama file: `Online Retail.xlsx`
- Sumber: Transaksi toko retail online
- Informasi yang digunakan:
  - Tanggal transaksi
  - ID pelanggan
  - Nomor faktur
  - Jumlah dan nilai pembelian

## Tools & Library

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Hasil Utama

- Pelanggan yang pertama kali berbelanja pada **Desember 2010** memiliki retensi tertinggi, mencapai **50%** pada bulan berikutnya.
- Setelah 2–3 bulan sejak pembelian pertama, retensi pelanggan menurun secara signifikan.
- Retensi yang tinggi di akhir tahun kemungkinan besar dipengaruhi oleh promosi musiman dan perilaku belanja liburan.

## Kesimpulan

- **Desember 2010** menjadi periode dengan loyalitas pelanggan tertinggi.
- Retensi pelanggan menurun tajam setelah bulan kedua pembelian.
- **Cohort analysis** sangat membantu dalam memahami pola loyalitas dan efektivitas waktu promosi.

## Rekomendasi

- Fokuskan promosi besar-besaran di bulan **Desember**.
- Maksimalkan strategi retensi dalam **3 bulan pertama** setelah pelanggan pertama kali berbelanja.
- Segmentasikan pelanggan berdasarkan cohort untuk pemasaran yang lebih relevan.
- Replikasi strategi promosi Desember di bulan lain untuk menguji efektivitasnya.
