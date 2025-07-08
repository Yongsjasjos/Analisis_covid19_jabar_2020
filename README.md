# 📊 Analisis Data COVID-19 Jawa Barat

Proyek ini bertujuan memantau perkembangan kasus COVID-19 di Jawa Barat menggunakan data resmi pemerintah. Data diolah dan divisualisasikan dalam bentuk grafik harian dan mingguan untuk memudahkan pemahaman tren kasus positif, sembuh, dan meninggal.

---

## 🎯 Tujuan Proyek

- Mengambil data COVID-19 Jawa Barat secara real-time dari API resmi.
- Membersihkan dan mentransformasi data untuk analisis lebih lanjut.
- Membuat visualisasi kasus harian positif, sembuh, dan meninggal.
- Melakukan analisis kasus mingguan dengan indikator tren peningkatan atau penurunan.

---

## 🛠️ Teknologi dan Library yang Digunakan

| Komponen             | Deskripsi                                     |
|----------------------|-----------------------------------------------|
| **Bahasa Pemrograman**| R                                             |
| **Library Utama**     | - `httr`: Pengambilan data dari API           |
|                      | - `dplyr`: Manipulasi dan transformasi data   |
|                      | - `ggplot2`: Visualisasi grafik                 |
|                      | - `hrbrthemes`: Tema visualisasi profesional   |
|                      | - `lubridate`: Manipulasi tanggal dan waktu    |

---

## 🚀 Alur Analisis

1. **Pengambilan Data**  
   - Mengunduh data JSON dari URL resmi pemerintah.  
   - Mengatasi potensi masalah SSL saat pengambilan data.

2. **Pembersihan dan Transformasi Data**  
   - Menghapus kolom-kolom yang tidak relevan.  
   - Mengganti nama kolom agar lebih mudah dipahami.  
   - Mengonversi timestamp ke format tanggal yang user-friendly.

3. **Visualisasi Data Harian**  
   - Membuat grafik batang kasus harian positif, sembuh, dan meninggal dengan warna berbeda.

4. **Analisis Mingguan**  
   - Mengelompokkan data berdasarkan minggu dan menghitung jumlah kasus baru.  
   - Menambahkan indikator tren peningkatan atau penurunan kasus dibandingkan minggu sebelumnya.  
   - Membuat grafik batang mingguan dengan pewarnaan indikator tren (merah untuk kenaikan, hijau untuk penurunan).

---

## 📈 Visualisasi

- Grafik kasus harian positif, sembuh, dan meninggal dengan warna yang kontras.  
- Grafik kasus pekanan yang menampilkan tren dengan indikator warna (merah/hijau).  

*Visualisasi dibuat menggunakan `ggplot2` dengan tema profesional dari `hrbrthemes`.*

---

## 📂 Dataset

- **Sumber Data:** [DQLab Academy](https://dqlab.id)  
- **URL Data:**  
  `https://storage.googleapis.com/dqlab-dataset/prov_detail_JAWA_BARAT.json`

---

## ✅ Output Akhir

- Dataset bersih dengan kolom tanggal dan jumlah kasus harian.  
- Visualisasi grafik kasus harian positif, sembuh, dan meninggal.  
- Grafik kasus pekanan dengan indikasi tren kenaikan atau penurunan.

---

## ⚠️ Lisensi dan Hak Cipta

- Data ini milik **DQLab Academy**.  
- Hanya digunakan untuk keperluan edukasi dan pembelajaran.  
- Dilarang menyebarluaskan atau menggunakan data di luar konteks yang diizinkan.

---

## 👨‍💻 Tentang Pengembang

**Yoga Pratama**  
📧 Email: [yp170090@gmail.com](mailto:yp170090@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/yoga-pratama-923202349](https://linkedin.com/in/yoga-pratama-923202349)  
🐱 GitHub: [github.com/Yongsjasjos](https://github.com/Yongsjasjos)
