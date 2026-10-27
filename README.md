<div align="center">

# 📊 Pertemuan 9 — Nilai Aktual vs. Prediksi
**Multiple Linear Regression with Python**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](./Pertemuan9.ipynb)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](./Pertemuan9.ipynb)
[![Google Colab](https://img.shields.io/badge/Open%20in-Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/dzuraihandy/Pertemuan-9.-Aktual-V-Prediksi/blob/main/Pertemuan9.ipynb)

*Latihan membangun model regresi linear berganda, membuat prediksi, mengevaluasi hasil, dan membandingkan nilai aktual dengan nilai prediksi.*

</div>

## 🎯 Tentang Proyek

Notebook ini menggunakan **data sintetis** untuk mempelajari cara memprediksi variabel target (Y) berdasarkan dua variabel prediktor, yaitu (X1) dan (X2).

Persamaan yang digunakan untuk membentuk data:

[
y = 5 + 2.5 * X1 - 2 * X2 + noise
]

- **X1 dan X2:** variabel prediktor yang digunakan model.
- **Y:** nilai target yang ingin diprediksi.
- **Noise:** variasi acak yang ditambahkan pada data.

Data dibuat dengan Python sebanyak 700 baris, sehingga latihan dapat dilakukan tanpa memerlukan dataset eksternal.

## 📂 File Utama

| File | Keterangan |
|---|---|
| [📓 Pertemuan9.ipynb](./Pertemuan9.ipynb) | Notebook berisi pembuatan data, pelatihan model, prediksi, evaluasi, dan visualisasi. |

## 🧪 Alur Analisis

1. **Import library** — menggunakan NumPy, pandas, Matplotlib, Seaborn, dan scikit-learn.
2. **Membuat data sintetis** — menghasilkan 700 observasi dengan variabel X1, X2, dan Y.
3. **Membagi data** — 80% untuk pelatihan (*training*) dan 20% untuk pengujian (*testing*).
4. **Melatih model** — menggunakan `LinearRegression` untuk mempelajari hubungan antara X1, X2, dan Y.
5. **Membuat prediksi** — menghitung nilai prediksi untuk data pengujian.
6. **Mengevaluasi model** — menggunakan Mean Squared Error (MSE) dan R-squared (R²).
7. **Membuat visualisasi** — membandingkan nilai aktual dengan nilai prediksi melalui scatter plot.

## 📈 Cara Membaca Hasil

- **Intercept:** perkiraan nilai Y ketika X1 dan X2 bernilai nol.
- **Koefisien X1:** menunjukkan perubahan prediksi Y untuk kenaikan satu unit X1, dengan X2 tetap.
- **Koefisien X2:** menunjukkan perubahan prediksi Y untuk kenaikan satu unit X2, dengan X1 tetap.
- **MSE:** mengukur rata-rata kuadrat selisih antara nilai aktual dan prediksi; semakin kecil umumnya semakin baik.
- **R²:** menunjukkan seberapa besar variasi nilai target yang dapat dijelaskan model pada data evaluasi; nilai yang lebih mendekati 1 umumnya menunjukkan kecocokan yang lebih baik.

Pada grafik, titik yang mendekati garis diagonal menunjukkan prediksi yang lebih dekat dengan nilai aktual. Gunakan nilai output yang muncul saat notebook dijalankan untuk menyusun kesimpulan akhir.

## 🚀 Cara Menjalankan

**Opsi 1 — Google Colab**
1. Klik tombol **Open in Google Colab** di bagian atas.
2. Jalankan setiap cell secara berurutan dengan tombol **Run**.
3. Amati koefisien, nilai evaluasi, dan grafik yang dihasilkan.

**Opsi 2 — Jupyter Notebook**
1. Unduh `Pertemuan9.ipynb`.
2. Pastikan Python dan library yang digunakan telah tersedia.
3. Buka notebook di Jupyter Notebook dan jalankan setiap cell secara berurutan.

## 🛠️ Tools

- Python
- NumPy dan pandas
- Matplotlib dan Seaborn
- scikit-learn
- Jupyter Notebook / Google Colab

---

**Learn from the data, evaluate the model, and interpret the results.** 📈
