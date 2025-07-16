# 🧠 Latent Dirichlet Allocation (LDA) – Pemodelan Topik Ulasan Aplikasi SatuSehat

Proyek ini merupakan implementasi **Latent Dirichlet Allocation (LDA)** untuk melakukan **pemodelan topik** pada kumpulan ulasan pengguna aplikasi **SatuSehat**. Model ini bertujuan menemukan pola tersembunyi (topik dominan) yang muncul dari kumpulan teks besar dengan cara **probabilistik dan tidak terawasi** (unsupervised learning).

---

## 🎯 Tujuan Proyek

- Mengidentifikasi isu-isu utama yang sering muncul pada ulasan aplikasi layanan kesehatan (SatuSehat).
- Mengelompokkan dokumen berdasarkan kemiripan tema/topik.
- Menerapkan metode **NLP dan LDA** untuk topik modelling.
- Mengevaluasi kualitas topik menggunakan **coherence score**.
- Menyajikan hasil dalam bentuk visual yang informatif.

---

## 🔧 Teknologi dan Tools

- **Python** (Jupyter Notebook)
- **Gensim** – Model LDA
- **NLTK, Sastrawi** – Text preprocessing
- **pyLDAvis** – Visualisasi interaktif topik
- **Matplotlib, Seaborn** – Visualisasi pendukung

---

## 🔎 Tahapan Analisis

1. **Praproses Teks**
   - Case folding, tokenizing, stopword removal, stemming (Sastrawi)
   - Pembentukan korpus dan dictionary

2. **Pelatihan Model LDA**
   - Uji coba jumlah topik dari 2–10
   - Evaluasi model berdasarkan nilai **coherence score**
   - Pemilihan model terbaik

3. **Visualisasi**
   - Distribusi topik per dokumen
   - Kata-kata kunci tiap topik
   - Plot interaktif (pyLDAvis)

4. **Interpretasi Hasil**
   - Analisis topik-topik utama seperti: login gagal, akses sertifikat vaksin, performa aplikasi

---

## 📈 Hasil & Insight

- Model terbaik ditemukan pada **jumlah topik = 4** dengan **coherence score sebesar 0.4557**.
- Topik dominan mencerminkan **isu utama yang dirasakan pengguna**:  
  1. Masalah login  
  2. Akses dan sertifikat vaksin  
  3. Keluhan performa  
  4. Fitur tidak berfungsi

