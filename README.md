# Analisis Pergerakan Harga Saham

Repositori ini berisi program, data, hasil simulasi, dan visualisasi terkait analisis pergerakan harga saham (contoh: UNVR).

---

## 📂 Struktur Folder

### `program/`
- **Pergerakan Harga Saham.ipynb** → Notebook utama untuk analisis dan simulasi pergerakan harga saham.
- **UNVR_close_price.csv** → Data harga penutupan saham UNVR yang digunakan sebagai input training/analisis.

### `visualisasi/`
- **analisis_komprehensif.png** → Grafik hasil analisis komprehensif.
- **data_overview.png** → Visualisasi overview data harga saham.
- **pohon_binomial_visualisasi.png** → Visualisasi pohon binomial untuk simulasi harga saham.

### `hasil/`
- **hasil_simulasi_detail.csv** → Hasil simulasi detail per langkah.
- **hasil_simulasi_harian.csv** → Ringkasan hasil simulasi per hari.
- **hasil_simulasi_lengkap.csv** → Output lengkap simulasi.
- **distribusi_harga_akhir.csv** → Distribusi harga akhir dari simulasi.
- **parameter_model.csv** → Parameter model yang digunakan dalam simulasi.
- **pohon_binomial_data.csv** → Data pohon binomial hasil perhitungan.
- **ringkasan_parameter.csv** → Ringkasan parameter simulasi.

### `README.md`
- Dokumentasi repositori, penjelasan struktur folder, dan deskripsi singkat isi file.

---

## 🚀 Cara Menggunakan
1. Buka notebook di folder `program/` untuk menjalankan analisis.
2. Pastikan file `UNVR_close_price.csv` tersedia sebagai input data.
3. Jalankan notebook → hasil simulasi akan tersimpan di folder `hasil/`.
4. Visualisasi hasil dapat dilihat di folder `visualisasi/`.

---

## 📌 Catatan
- Semua file CSV di folder `hasil/` adalah output simulasi, bukan data mentah.
- Folder `program/` berisi kode dan data input utama.
- Folder `visualisasi/` berisi gambar hasil analisis untuk interpretasi lebih mudah.
