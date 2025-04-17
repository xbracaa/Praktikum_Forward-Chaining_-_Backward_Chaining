# 🧠 Praktikum Forward Chaining & Backward Chaining

Repositori ini berisi implementasi sederhana sistem pakar untuk **diagnosis penyakit** menggunakan metode **Forward Chaining** dengan library Python [`experta`](https://github.com/noxdafox/experta).

## 📌 Deskripsi

Aplikasi ini akan menanyakan gejala-gejala kepada pengguna, kemudian berdasarkan fakta-fakta tersebut, sistem akan mencocokkan dengan rule (aturan) yang telah ditentukan untuk memberikan kemungkinan **diagnosa penyakit**.

Metode yang digunakan:  
✅ **Forward Chaining**  
✅ Library: `experta` (turunan dari CLIPS dalam bentuk Pythonic)

## 📁 Struktur File

- `diagnosis.py` – File utama yang berisi kode sistem pakar untuk diagnosa penyakit menggunakan `experta`.
- `diagnosis.ipynb` – Versi Notebook dari file `diagnosis.py` untuk kebutuhan praktikum / eksplorasi interaktif.
- `README.md` – Penjelasan dan dokumentasi repositori.

## 💉 Penyakit yang Dapat Dideteksi

Saat ini terdapat **8 jenis penyakit** yang dapat dikenali oleh sistem berdasarkan kombinasi gejala:

1. **Flu**
2. **Pneumonia**
3. **Common Cold**
4. **Throat Infection**
5. **Masuk Angin**
6. **Magh**
7. **Dengue Fever**
8. **Tonsillitis**
9. **COVID-19**

## 🧪 Contoh Gejala yang Ditanyakan

- Batuk (`cough`)
- Demam (`fever`)
- Kelelahan (`fatigue`)
- Sesak napas (`breathing_difficulty`)
- Bersin (`sneezing`)
- Hidung meler (`runny_nose`)
- Sakit tenggorokan (`sore_throat`)
- Mual (`nausea`)
- Kembung (`bloating`)
- Sakit perut (`stomach_pain`)
- Menggigil (`chills`)
- Sakit kepala (`headache`)

## ▶️ Cara Menjalankan

### Dengan Python CLI
1. Install dependencies:
   ```bash
   pip install experta
