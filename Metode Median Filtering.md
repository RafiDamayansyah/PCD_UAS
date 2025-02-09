# Aplikasi Peningkatan Kualitas Citra Menggunakan Metode Median Filtering Untuk Menghilangkan Noise

## 1. Judul Proyek
**Aplikasi Peningkatan Kualitas Citra Menggunakan Metode Median Filtering Untuk Menghilangkan Noise**  
**Nama:** Rafi Damayansyah  
**NPM:** 2206146

[![DOI](https://zenodo.org/badge/929709613.svg)](https://doi.org/10.5281/zenodo.14839548)

## 2. Pendahuluan

### Latar Belakang
Citra digital memiliki peran penting dalam berbagai bidang, seperti keamanan, medis, dan industri. Namun, citra sering mengalami gangguan berupa noise, yang dapat menurunkan kualitas gambar dan menghambat analisis lebih lanjut. Salah satu metode yang digunakan untuk mengurangi noise adalah **median filtering**.

### Penelitian atau Teori Terkait
Menurut penelitian oleh Sadly Syamsuddin dalam prosiding *Seminar Ilmiah Sistem Informasi dan Teknologi Informasi* (2019), metode median filtering dapat menghilangkan noise seperti **salt and pepper noise** dengan akurasi tinggi, meningkatkan kejernihan gambar hingga lebih dari **80%**.

### Tujuan Tugas
- Mengimplementasikan algoritma **median filtering** untuk meningkatkan kualitas citra.
- Mengevaluasi efektivitas metode dalam menghilangkan noise pada berbagai jenis citra.
- Mendokumentasikan hasil pengolahan citra dalam laporan.

## 3. Metode

### Penjelasan Langkah-Langkah yang Dilakukan
1. **Pengumpulan Data**: Memilih citra yang mengandung noise, seperti gambar CCTV atau citra medis.
2. **Pra-Pemrosesan**: Mengonversi citra ke grayscale atau mempertahankan format RGB jika diperlukan.
3. **Implementasi Median Filtering**:
   - Mencari nilai tengah dari piksel dalam window matriks yang dievaluasi.
   - Mengganti nilai piksel pusat dengan median dari window tersebut.
   - Mengulangi proses hingga seluruh citra diproses.
4. **Evaluasi Hasil**: Membandingkan citra sebelum dan sesudah pemrosesan untuk menilai efektivitas metode.

### Visualisasi Model atau Metode yang Digunakan
- **Diagram Use Case**: Menunjukkan interaksi pengguna dengan sistem pengolahan citra.
- **Diagram Alur Data**: Mengilustrasikan proses input gambar, filtering, dan output hasil akhir.

## 4. Hasil

### Penjelasan Hasil Eksperimen Lengkap dengan Gambar dan Analisis
1. **Citra Awal**: Mengandung noise yang mengaburkan detail penting.
2. **Citra Setelah Median Filtering**:
   - Noise berkurang secara signifikan.
   - Detail gambar menjadi lebih jelas.
   - Tingkat kejernihan meningkat lebih dari **80%**.
3. **Analisis**:
   - Untuk citra grayscale, median filtering bekerja dengan sangat baik.
   - Untuk citra berwarna, metode ini dapat menyebabkan sedikit perubahan warna.
   - Metode ini lebih efektif dibandingkan **mean filtering** dalam mengatasi **noise salt and pepper**.

## 5. Kesimpulan

### Ringkasan Temuan
- **Median filtering** efektif dalam menghilangkan noise pada citra digital.
- Metode ini mempertahankan ketajaman gambar lebih baik dibandingkan metode lain seperti **mean filtering**.

### Batasan Pekerjaan
- Kurang optimal untuk noise dengan pola yang kompleks seperti **speckle noise**.
- Proses filtering dapat menyebabkan sedikit perubahan warna pada citra berwarna.

### Rekomendasi untuk Pekerjaan di Masa Depan
- Mengombinasikan **median filtering** dengan metode lain seperti **Gaussian filtering** untuk hasil yang lebih baik.
- Mengembangkan model berbasis **AI** untuk otomatisasi pemrosesan citra.

## 6. Referensi
- Syamsuddin, S. (2019). *Aplikasi Peningkatan Kualitas Citra Menggunakan Metode Median Filtering Untuk Menghilangkan Noise*. Prosiding *Seminar Ilmiah Sistem Informasi dan Teknologi Informasi*, 227-236.
- Gonzalez, R. C., & Woods, R. E. (2015). *Digital Image Processing* (3rd ed.). Pearson Prentice Hall.
- Yuwono, B. (2015). *Image Smoothing Menggunakan Mean Filtering, Median Filtering, Modus Filtering dan Gaussian Filtering*. Telematika, 7(1), 65-75.

---

