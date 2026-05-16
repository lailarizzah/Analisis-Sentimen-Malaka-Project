# Klasifikasi Sentimen Komentar YouTube Malaka Project Menggunakan Algoritma Support Vector Machine (SVM)

Repositori ini berisi source code, dataset, serta file pendukung yang digunakan dalam penelitian skripsi berjudul:

“Klasifikasi Sentimen Komentar YouTube Malaka Project Menggunakan Algoritma Support Vector Machine (SVM)”

## Deskripsi Penelitian

Penelitian ini bertujuan untuk membandingkan performa kernel Linear, Polinomial, dan Radial Basis Function (RBF) pada algoritma Support Vector Machine (SVM) dalam mengklasifikasikan sentimen komentar YouTube ke dalam tiga kelas, yaitu positif, negatif, dan netral.

Dataset diperoleh melalui proses scraping menggunakan YouTube Data API v3 pada video:
“Bisnis Gelap Dokter & Perusahaan Farmasi”.

## Struktur Repository

## Isi Repository

Repository ini memuat file yang digunakan dalam penelitian, meliputi:

- `komentar_yt.csv` : dataset hasil scraping komentar YouTube
- `komentar_df.xlsx` : dataset hasil preprocessing
- `kamus_slang.csv` : kamus slangword untuk normalisasi kata
- `tfidf_result.csv` : hasil ekstraksi fitur TF-IDF
- notebook/source code klasifikasi sentimen menggunakan SVM

## Tahapan yang Dilakukan

- Data Preprocessing
- Pelabelan Sentimen berbasis InSet Lexicon
- Data Split dengan rasio 80:20
- Ekstraksi Fitur TF-IDF
- Support Vector Machine (SVM)
- One-Against-All (OvR)
- Perbandingan Kernel:
  - Linear
  - Polinomial
  - RBF

## Evaluasi Model

Evaluasi model dilakukan menggunakan:
- Akurasi
- Presisi
- Recall
- F1-Score
- Confusion Matrix

## Penulis

Laila Rohmatul I’zzah  
Program Studi Matematika
