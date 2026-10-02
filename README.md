# Data Cleansing Dataset Anak Putus Sekolah Karena Ekonomi Di Indonesia


## Deskripsi

Repository ini berisi proyek Data Cleansing yang dilakukan pada dataset anak putus sekolah karena ekonomi. Dataset awal merupakan dataset kotor yang memiliki beberapa permasalahan, seperti missing value, data duplikat, format tanggal yang tidak seragam, penulisan teks yang tidak konsisten, dan format angka yang perlu dikonversi.

Proses data cleansing dilakukan menggunakan Python melalui Google Colab dengan library Pandas dan Regular Expression (re).

## Tujuan

Tujuan dari proyek ini adalah:

- Mengidentifikasi permasalahan pada dataset.
- Membersihkan data yang tidak konsisten.
- Menangani missing value.
- Menyeragamkan format data.
- Menghapus data duplikat.
- Melakukan validasi terhadap data yang telah dibersihkan.
- Menyimpan dataset hasil cleansing dalam format Excel.

## Dataset

Dataset yang digunakan berjudul:

**Dataset Anak Putus Sekolah**

Dataset terdiri dari 14 kolom, yaitu:

- id
- nama
- usia
- jenis_kelamin
- jenjang
- kelas
- provinsi
- kabupaten_kota
- pekerjaan_orang_tua
- penghasilan_orang_tua
- jumlah_tanggungan
- alasan_putus
- tanggal_putus
- status_sekarang

Dataset awal terdiri dari 50 data.

## Permasalahan Data

Beberapa permasalahan yang ditemukan pada dataset antara lain:

- Terdapat missing value pada kolom jenis_kelamin dan alasan_putus.
- Penulisan data teks tidak seragam (kapitalisasi dan singkatan).
- Format tanggal berbeda-beda (YYYY-MM-DD dan DD/MM/YYYY).
- Format penghasilan berbeda-beda (1200000, 1.2jt, Rp 1.500.000, 900rb).
- Jenis kelamin tidak konsisten (L, l, Laki-laki, perempuan).
- Whitespace dan karakter khusus pada beberapa kolom.
- Data duplikat ditemukan dan perlu dihapus.

## Proses Data Cleansing

Tahapan data cleansing yang dilakukan meliputi:

1. Import library.
2. Koneksi Google Colab dengan Google Drive.
3. Membaca dataset Excel.
4. Eksplorasi dataset.
5. Pengecekan missing value.
6. Pengecekan data duplikat.
7. Membersihkan data teks.
8. Menstandarkan provinsi.
9. Membersihkan kabupaten/kota.
10. Membersihkan jenjang.
11. Membersihkan jenis kelamin.
12. Membersihkan alasan putus.
13. Membersihkan status sekarang.
14. Membersihkan tanggal putus.
15. Membersihkan penghasilan orang tua.
16. Menangani outlier usia.
17. Menghapus whitespace dan karakter khusus.
18. Menghapus data duplikat.
19. Melakukan validasi data bersih.
20. Menyimpan hasil cleansing dalam format Excel.

## Tools dan Library

Proyek ini menggunakan:

- Python
- Google Colab
- Google Drive
- Pandas
- Regular Expression (re)
- OpenPyXL

## Hasil

Setelah proses data cleansing dilakukan, dataset diperiksa kembali untuk memastikan:

- Data memiliki format yang lebih konsisten.
- Missing value telah ditangani.
- Data numerik telah dikonversi dengan benar.
- Format tanggal telah diseragamkan.
- Data duplikat telah dihapus.
- Nilai telah divalidasi sesuai rentang wajar.
- Dataset bersih berhasil disimpan dalam format Excel.

## Output

Hasil data cleansing disimpan dalam format:

- `data_anak_putus_sekolah_clean.xlsx`

File hasil berada pada folder:

`Google Drive/Datmin2418054/`

## Google Drive

Dataset dan file hasil data cleansing dapat diakses melalui folder Google Drive berikut:

[Folder Google Drive](https://docs.google.com/spreadsheets/d/1q7BgojMN5zxJAkCAeRyeBzOPuO2WKGIC/edit?usp=drive_link&ouid=116531442615651384995&rtpof=true&sd=true)

## Google Colab

Seluruh proses data cleansing dilakukan menggunakan Google Colab.

[Google Colab - Data Cleansing](https://colab.research.google.com/drive/1Atq8U8TRcdJ2ypNgxJlZUJuqWdVOJnLf?usp=sharing)]
