# Analisis Performa Bike Sharing Dataset (2011-2012)

## Performa Peminjaman Sepeda

Performa peminjaman sepeda selama tahun 2011 hingga 2012 menunjukkan tren peningkatan yang signifikan:
- * Tahun 2011: Peminjaman sepeda mengalami peningkatan stabil pada kuartal pertama, puncak lonjakan terjadi pada kuartal kedua dan ketiga, kemudian terjadi penurunan bertahap hingga kuartal keempat dengan penurunan tajam di akhir tahun.
- * Tahun 2012: Peningkatan besar terjadi di akhir kuartal pertama dan terus berlanjut hingga puncaknya pada kuartal ketiga. Penurunan kembali terjadi pada kuartal keempat, meskipun performanya tetap lebih baik dibandingkan tahun 2011.
-  Secara keseluruhan, grafik peminjaman menunjukkan performa yang positif dengan tren kenaikan dari tahun ke tahun.


## Situasi dan Kondisi dengan Peminjaman Tertinggi

Hasil analisis menunjukkan situasi dan kondisi tertentu memiliki pengaruh besar terhadap jumlah peminjaman sepeda:

1. Musim:
- **Musim gugur (Fall)** mencatat total peminjaman tertinggi, yaitu 1.061.129 peminjaman, diikuti musim panas (Summer) dengan 918.589 peminjaman.
2. Cuaca:
- **Cuaca cerah (Clear)** memiliki kontribusi tertinggi terhadap jumlah peminjaman dengan 2.338.173 peminjaman, sedangkan cuaca berawan (Cloudy) mencatat 795.952 peminjaman.
3. Waktu:
- **Jam sibuk** antara pukul 8 pagi dan 5–6 sore menunjukkan lonjakan peminjaman tertinggi pada hari kerja (Senin–Jumat).
- **Pada akhir pekan** (Sabtu dan Minggu), peminjaman tertinggi terjadi antara pukul 12 siang hingga 3 sore.
4. Hari:
- Hari kerja (Senin–Jumat) memiliki tingkat peminjaman lebih tinggi dibandingkan akhir pekan.

## Statistik Peminjam Sepeda

- **Peminjam Terdaftar (Registered):**
  Total pelanggan terdaftar mencapai 2.245.440 peminjaman (68% dari total peminjaman).
- **Peminjam Tidak Terdaftar (Casual):**
  Peminjam kasual atau tidak terdaftar mencatat 1.043.618 peminjaman (32% dari total peminjaman).

**Catatan:** Mayoritas peminjaman dilakukan oleh pelanggan terdaftar. Strategi pemasaran perlu difokuskan untuk menarik lebih banyak peminjam kasual agar meningkatkan jumlah total pelanggan dan peluang konversi.

## Kesimpulan dan Rekomendasi

Berdasarkan analisis data peminjaman sepeda dari tahun 2011 hingga 2012, terdapat pola musiman, cuaca, dan waktu yang sangat memengaruhi performa peminjaman sepeda.

1. **Kesimpulan:**
    - Puncak peminjaman terjadi pada kuartal kedua hingga ketiga setiap tahun.
    - Faktor cuaca cerah dan waktu sibuk di pagi dan sore hari menjadi momen dengan tingkat peminjaman tertinggi.
    - Musim gugur dan musim panas adalah periode dengan kontribusi besar terhadap jumlah peminjaman.
    - Mayoritas pelanggan berasal dari kategori terdaftar, sementara kontribusi peminjam kasual masih relatif kecil.

2. **Rekomendasi:**
    - Fokus Pemasaran: Tingkatkan upaya untuk menarik lebih banyak peminjam kasual dengan kampanye yang menarik, seperti diskon atau promosi khusus.
    - Optimalisasi Operasional: Tingkatkan ketersediaan sepeda pada jam sibuk (8 pagi dan 5–6 sore) dan pada musim dengan permintaan tinggi (musim gugur dan musim panas).
    - Diversifikasi Pelanggan: Lakukan strategi untuk meningkatkan loyalitas pelanggan terdaftar sekaligus memperluas basis pelanggan baru.

Dengan menerapkan rekomendasi ini, bisnis dapat meningkatkan performa, efisiensi, dan skala operasional untuk mendukung pertumbuhan yang berkelanjutan.

# Dashboard Bike Sharing Dataset (2011-2012)

Untuk menjalankan dashboard ini di _local_ ada beberapa langkah yang perlu dilakukan

## Instal _Dependencies_

Untuk menginstall dependencies, anda dapat menjalankan code ini

### Anaconda

```
conda create --name main-ds python=3.11.9
conda activate main-ds
pip install -r requirements.txt
```

### Shell/Terminal

```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run Dashboard di Local

```
cd dashboard
streamlit run dashboard.py
```
# BikeSharingDataset-Dicoding
