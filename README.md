# 📘 Analisis Sentimen X Pasca Pertandingan Piala AFC 23
### Deskripsi Singkat
Proyek ini melakukan analisis sentimen dari data media sosial (X/Twitter) yang berfokus pada reaksi pasca pertandingan Indonesia vs Uzbekistan Piala AFC 2023. Menggunakan teknik Natural Language Processing (NLP) untuk mengklasifikasi sentimen sebagai positif, netral, atau negatif.

## 🚀 Fitur
- Scraping data tweet relevan tentang pertandingan Piala AFC 2023.
- Pre-processing teks: tokenisasi, pembersihan, stopword removal.
- Training model klasifikasi menggunakan SVM dan evaluasi menggunakan confusion matrix dan classification report.
- Visualisasi hasil prediksi (bar chart, wordcloud, dsb).

## 📈 Hasil Analisis
- Total Data yang diperoleh sebanyak 503 baris data
- Total sentimen positif sebanyak 183
- Total sentimen negatif sebanyak 61
- Total sentimen netral sebanyak 259

## 🛠️ Teknologi
- Python
- pandas, scikit-learn, matplotlib, seaborn, nltk (stopwords, tokenizer)
- Tweepy atau snscrape untuk scraping tweet
- Jupyter Notebook
