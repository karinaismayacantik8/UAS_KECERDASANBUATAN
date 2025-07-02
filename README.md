# UAS_KECERDASANBUATAN

## 📌 Judul Proyek
**Implementasi Klasifikasi Kanker Paru-paru Menggunakan Algoritma Random Forest**

## 👩‍💻 Disusun Oleh
- Karina Ismaya
- Kailla Salsabila  
- Kelas B - Kelompok 9  
- Institut Teknologi Garut

---

## 📁 Deskripsi Singkat
Proyek ini merupakan bagian dari tugas UAS mata kuliah *Kecerdasan Buatan* yang bertujuan untuk mengklasifikasikan jenis kanker paru-paru berdasarkan dataset klinis. Algoritma yang digunakan adalah **Random Forest** karena kemampuannya dalam menangani data yang kompleks dan menghasilkan akurasi yang tinggi.


## 📁 Struktur Folder

1. uas.pdf           # Laporan akhir UAS dalam bentuk dokumen PDF
   
Laporan ini membahas penerapan metode Random Forest untuk menyelesaikan studi kasus klasifikasi pada mata kuliah Kecerdasan Buatan. Algoritma Random Forest dipilih karena kemampuannya menghasilkan prediksi yang akurat melalui kombinasi beberapa pohon keputusan. Proses yang dijelaskan mencakup preprocessing data, pelatihan model, dan evaluasi menggunakan metrik seperti akurasi, presisi, dan f1-score. Laporan ini juga dilengkapi dengan referensi jurnal serta visualisasi hasil, sehingga menggambarkan penerapan Random Forest secara efektif dalam proyek berbasis data.

---

2. dataset/          # Data mentah dan olahan yang digunakan untuk pelatihan/pengujian model
   
Dataset ini berisi data hasil survei yang digunakan untuk memprediksi potensi penyakit kanker paru-paru. Terdapat beberapa fitur seperti usia, jenis kelamin, kebiasaan merokok, konsumsi alkohol, tingkat kecemasan, dan gejala-gejala lain yang relevan. Label target pada dataset ini adalah LUNG_CANCER, yang menunjukkan apakah seseorang berisiko terkena kanker paru-paru atau tidak. Dataset ini telah melalui tahap preprocessing sebelum digunakan dalam pemodelan menggunakan algoritma Random Forest.

---

3. jurnal/           # Artikel dan referensi pendukung (PDF dan ringkasan)
   
📚 Referensi Jurnal
- Prediksi Kanker Paru dengan Perbandingan Random Forest, Decision Tree, dan Naïve Bayes (DECODE Vol.4 No.3 (2024))
Membandingkan algoritma Random Forest, Decision Tree, dan Naïve Bayes untuk prediksi kanker paru. Random Forest dan Decision Tree mencapai akurasi 100%.

- Prediksi Kanker Paru Menggunakan Grid Search untuk Optimasi MLP dan Logistic Regression (ELKOMIKA Vol.12 No.3 (2024))
Menggunakan Grid Search untuk optimasi MLP dan Logistic Regression. Kedua model berhasil mencapai akurasi dan f1-score 100%.

- Penerapan Data Mining untuk Prediksi Kanker Paru Menggunakan Algoritma Random Forest (Infotekmesin Vol.14 No.1 (2023))
Menerapkan Random Forest dengan K-Fold Cross Validation dan SMOTE. Mencapai akurasi 98,4% dan AUC 1, lebih unggul dari Naïve Bayes.

---

4. notebook.ipynb    # Notebook Jupyter (Python) berisi implementasi Random Forest dan analisis data
   
Implementasi model prediksi kanker paru-paru menggunakan algoritma Random Forest. Proses dalam notebook mencakup pembersihan data duplikat, pembagian data latih dan uji, pelatihan model, serta evaluasi performa menggunakan metrik akurasi, precision, recall, dan f1-score. Selain itu, notebook juga menyertakan visualisasi seperti confusion matrix dan feature importance untuk mendukung analisis hasil model. 
