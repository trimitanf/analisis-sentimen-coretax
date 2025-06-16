# Analisis Sentimen Tanggapan Pengguna Media Sosial X terhadap Sistem Coretax Menggunakan Support Vector Machine (SVM)

## Deskripsi

Penelitian ini untuk menguji efektivitas algoritma Support Vector Machine (SVM) dalam menganalisis dan mengklasifikasikan sentimen dari tanggapan pengguna media sosial X terhadap sistem Coretax. Melalui pendekatan hybrid, yaitu pelabelan otomatis berbasis lexicon menggunakan TextBlob dan pengklasifikasian menggunakan SVM. Hasil analisis dapat menjadi masukan untuk mengetahui sentimen publik terhadap sistem Coretax, pemangku kebijakan yaitu DJP dapat mengambil langkah-langkah perbaikan yang diperlukan untuk meningkatkan pengalaman pengguna dan memperbaiki aspek teknis sistem ini.

## Spesifikasi

- **Dataset :** Cuitan/Tweet berbahasa Indonesia yang mengandung kata kunci "coretax". Data yang digunakan rentang waktu mulai dari 1 Januari 2025 – 9 Mei 2025 berjumlah 18.528 data mentah;
- **Metode :** Support Vector Machine (SVM)
- **Slang & Stop Words :** kamus_slangword.csv dan kamus_stopword.csv;
- **Lexicon :** TexBlob;
- **Ekstraksi Fitur :** TF-IDF;

## Prasyarat

- `pandas`: Pengolahan dan manipulasi data
- `re` dan `string`: Text cleaning
- `scikit-learn`: Support Vector Machine, TF-IDF, Evaluation (confusion matrix, precision, recall, F1-score, accuracy)
- `TextBlob` : Lexicon-Based, Translation, dan Sentimen label

## Coretax Sentimen Analytics Dashboard
Hasil analisis dapat dilihat pada dashboard Looker Studio berikut:
[**Lihat Dashboard**](https://lookerstudio.google.com/reporting/9e0d6b96-fcb8-494f-b0d0-cc8c330d8035)
