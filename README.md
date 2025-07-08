# 📊 Analisis Data COVID-19 Jawa Barat

Proyek ini bertujuan untuk memantau perkembangan kasus COVID-19 di Jawa Barat menggunakan data resmi pemerintah. Data diolah dan divisualisasikan dalam bentuk grafik harian dan mingguan agar memudahkan pemahaman tren kasus positif, sembuh, dan meninggal.

---

## 🎯 Tujuan Proyek

* Mengambil data COVID-19 Jawa Barat secara real-time dari API resmi.
* Membersihkan dan mentransformasi data untuk analisis lebih lanjut.
* Membuat visualisasi kasus harian positif, sembuh, dan meninggal.
* Membuat analisis kasus mingguan dengan indikator peningkatan atau penurunan kasus.

---

## 🛠️ Teknologi dan Library yang Digunakan

* **Bahasa Pemrograman:** R
* **Library Utama:**
    - `httr` — Pengambilan data dari API
    - `dplyr` — Manipulasi data
    - `ggplot2` — Visualisasi grafik
    - `hrbrthemes` — Tema visualisasi profesional
    - `lubridate` — Manipulasi tanggal dan waktu

---

## 🚀 Alur Analisis

1. **Pengambilan Data**
     - Mengambil data JSON dari URL resmi pemerintah.
     - Mengonfigurasi agar tidak terjadi masalah SSL saat pengambilan data.

2. **Pembersihan dan Transformasi Data**
     - Menghapus kolom yang tidak diperlukan.
     - Merubah nama kolom agar lebih mudah dipahami.
     - Mengkonversi timestamp menjadi format tanggal yang mudah dibaca.

3. **Visualisasi Data Harian**
     - Membuat grafik batang kasus harian positif, sembuh, dan meninggal.

4. **Analisis Mingguan**
     - Mengelompokkan data per minggu dan menghitung jumlah kasus baru.
     - Menambahkan indikator peningkatan atau penurunan kasus dibandingkan minggu sebelumnya.
     - Membuat grafik batang kasus mingguan dengan warna indikator.

---

## 📈 Visualisasi

* Grafik kasus harian positif, sembuh, dan meninggal dengan warna berbeda.
* Grafik kasus pekanan dengan indikasi penurunan (hijau) atau kenaikan (merah) kasus.

*Visualisasi dibuat menggunakan paket `ggplot2` dengan tema dari `hrbrthemes`.*

---

## 📂 Dataset

* **Sumber Data:** [DQLab Academy](https://dqlab.id)
* **URL Data:**
  `https://storage.googleapis.com/dqlab-dataset/prov_detail_JAWA_BARAT.json`

---

## ✅ Output Akhir

* Dataset bersih dengan kolom tanggal dan jumlah kasus harian.
* Visualisasi kasus harian positif, sembuh, meninggal.
* Grafik kasus pekanan dengan indikasi tren.

---

## ⚠️ Lisensi dan Hak Cipta

* Data ini merupakan milik **DQLab Academy**.
* Digunakan **hanya untuk keperluan edukasi dan pembelajaran**.
* Dilarang menyebarluaskan data atau menggunakan di luar konteks yang diizinkan oleh pemilik data.

---

## 👨‍💻 Tentang Pengembang

**Yoga Pratama**
📧 Email: [yp170090@gmail.com](mailto:yp170090@gmail.com)
🔗 LinkedIn: [linkedin.com/in/yoga-pratama-923202349](https://linkedin.com/in/yoga-pratama-923202349)
🐱 GitHub: [github.com/Yongsjasjos](https://github.com/Yongsjasjos)

---
