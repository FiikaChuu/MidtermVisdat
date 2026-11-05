# Paket Tugas Besar Visualisasi Data

Isi sebelum pengumpulan: identitas mahasiswa/kelompok dalam notebook, report, dan slides. Sumber input Kaggle disitasi sesuai tautan pengguna; periode pengukuran, lisensi, dan atribusi pengumpulan primer belum diverifikasi.

## Berkas
- EDA_Kualitas_Udara_Asia_Tenggara.ipynb: notebook tereksekusi dengan analisis univariate, bivariate, dan multivariate.
- Report_EDA_Kualitas_Udara.pdf: laporan analisis.
- Slides_EDA_Kualitas_Udara.pptx: 12 slide presentasi yang dapat diedit.
- data/global_air_pollution_dataset.csv: CSV asli.
- data/asia_tenggara_aqi.csv: subset regional 1.227 baris, nama negara disamakan.
- data/audit_kategori.csv: 12 label batas yang berbeda dari audit interval numerik.
- data/ringkasan_negara.csv, hasil_ringkas.json: ringkasan hasil.
- figures/: tujuh visualisasi hasil notebook.
- requirements.txt: versi dependensi yang digunakan.

## Jalankan ulang
Gunakan Python 3.12 dan instal requirements.txt dalam virtual environment. Dari folder ini, jalankan seluruh sel notebook dengan kernel Python yang memuat dependensi tersebut. Untuk kernel standar di mesin lain, pilih Python 3 pada menu kernel (nama kernel Visdat khusus lingkungan ini). Tidak diperlukan internet saat notebook berjalan.

Dataset tidak memuat tanggal pengukuran, sehingga hasil bukan informasi kualitas udara terkini. Temuan bersifat deskriptif dan bukan bukti sebab-akibat atau peringkat nasional representatif. Grafik kategori mempertahankan label asli; persentase AQI >100 dihitung dari angka dan dapat berbeda dari kategori karena inkonsistensi batas.
