# Portofolio Data Science

**Nama:** Moch Faris Oldie  
**NIM:** 250401020048  
**Kelas:** IF401  
**Program Studi:** PJJ Informatika

## Deskripsi Repository

Repository ini berisi kumpulan hasil hands-on/praktikum mata kuliah Data Science dari Pertemuan 1 sampai Pertemuan 13. Tujuan repository ini adalah mendokumentasikan proses belajar saya dalam memahami dasar Python, pengolahan data, visualisasi, preprocessing, machine learning (klasifikasi, clustering, asosiasi), hingga pengenalan deep learning dan NLP.

Setiap notebook disusun dengan identitas, tujuan praktikum, kode yang dapat dijalankan, output, serta kesimpulan singkat. Beberapa dataset dibuat sintetis atau menggunakan fallback lokal agar notebook tetap bisa dijalankan dari awal sampai akhir tanpa bergantung penuh pada file eksternal.

## Daftar Pertemuan

| Pertemuan | Topik                                                            | Notebook                                                                                               |
| --------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| 1         | Pengenalan Data Science dan Python dasar                         | [pertemuan_01_pengenalan_data_science.ipynb](pertemuan_01_pengenalan_data_science.ipynb)               |
| 2         | Struktur data Python, NumPy, Pandas, dan eksplorasi Titanic      | [pertemuan_02_python_numpy_pandas.ipynb](pertemuan_02_python_numpy_pandas.ipynb)                       |
| 3         | Data cleaning, missing value, outlier, ekspor CSV, dan akses API | [pertemuan_03_data_cleaning_api.ipynb](pertemuan_03_data_cleaning_api.ipynb)                           |
| 4         | Statistik deskriptif, distribusi, korelasi, dan visualisasi Iris | [pertemuan_04_statistik_visualisasi.ipynb](pertemuan_04_statistik_visualisasi.ipynb)                   |
| 5         | Dashboard visualisasi data transaksi restoran                    | [pertemuan_05_dashboard_visualisasi.ipynb](pertemuan_05_dashboard_visualisasi.ipynb)                   |
| 6         | Preprocessing data untuk machine learning                        | [pertemuan_06_preprocessing_machine_learning.ipynb](pertemuan_06_preprocessing_machine_learning.ipynb) |
| 7         | Regresi linear untuk prediksi gaji sintetis                      | [pertemuan_07_regresi_linear.ipynb](pertemuan_07_regresi_linear.ipynb)                                 |
| 9         | Klasifikasi: Logistic Regression & Decision Tree                 | [pertemuan_09_klasifikasi_logistic_decision_tree.ipynb](pertemuan_09_klasifikasi_logistic_decision_tree.ipynb) |
| 10        | Klasifikasi: Random Forest & prediksi Customer Churn             | [pertemuan_10_random_forest_churn.ipynb](pertemuan_10_random_forest_churn.ipynb)                       |
| 11        | Unsupervised Learning: K-Means & Hierarchical Clustering         | [pertemuan_11_clustering_kmeans_hierarchical.ipynb](pertemuan_11_clustering_kmeans_hierarchical.ipynb) |
| 12        | Asosiasi (Apriori / Market Basket) & sistem rekomendasi          | [pertemuan_12_apriori_rekomendasi.ipynb](pertemuan_12_apriori_rekomendasi.ipynb)                       |
| 13        | Pengenalan Deep Learning (ANN) & NLP (analisis sentimen)         | [pertemuan_13_ann_nlp_sentimen.ipynb](pertemuan_13_ann_nlp_sentimen.ipynb)                             |

## Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- mlxtend (Apriori & association rules)
- SciPy
- TensorFlow / Keras
- Git dan GitHub

## Cara Menjalankan Notebook

1. Clone repository ini ke komputer lokal.
2. Buka folder repository menggunakan Jupyter Notebook, JupyterLab, VS Code, atau Google Colab.
3. Install library yang dibutuhkan jika belum tersedia:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn mlxtend scipy tensorflow jupyter
```

4. Buka notebook yang ingin dijalankan.
5. Jalankan semua sel dari awal sampai akhir menggunakan menu `Kernel -> Restart & Run All` atau fitur `Run All`.

## Kesimpulan Umum

Melalui praktikum Pertemuan 1 sampai 13, saya mempelajari alur Data Science secara utuh, dari pengolahan data hingga machine learning. Materi dimulai dari dasar Python, pengolahan data dengan NumPy dan Pandas, pembersihan data, visualisasi dan dashboard, preprocessing, hingga pelatihan model regresi linear.

Selanjutnya saya mempelajari klasifikasi dengan Logistic Regression dan Decision Tree serta mengevaluasinya dengan Confusion Matrix, Accuracy, Precision, Recall, dan F1-Score; Random Forest untuk menangani dataset tidak seimbang (imbalanced) seperti prediksi Customer Churn; clustering (K-Means dan Hierarchical) sebagai unsupervised learning untuk menemukan kelompok pelanggan; association rule (Apriori) untuk market basket analysis; sistem rekomendasi sederhana (content-based dan collaborative filtering); serta pengenalan deep learning (Artificial Neural Network) dan NLP dengan analisis sentimen menggunakan TF-IDF.

Hal paling penting yang saya pelajari adalah bahwa Data Science tidak hanya tentang membuat model, tetapi juga memahami data, membersihkan data, memilih fitur, menampilkan pola melalui visualisasi, dan mengevaluasi hasil secara terukur — termasuk memahami bahwa pada data yang tidak seimbang, accuracy saja bisa menyesatkan sehingga metrik seperti recall, precision, F1-score, dan ROC-AUC lebih relevan. Keterbatasan repository ini adalah beberapa contoh masih menggunakan dataset sintetis atau dataset kecil, sehingga tahap berikutnya adalah berlatih dengan dataset nyata yang lebih besar dan lebih kompleks.

## Catatan

Repository ini diperbarui bertahap setiap pertemuan dan setiap notebook siap dijalankan ulang dari awal menggunakan `Kernel -> Restart & Run All`.
