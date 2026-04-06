# AnalisisSentimen-PurbayaSadewaPodcast
This project aims to analyze the sentiment and emotions of user comments on YouTube Podcast Purbaya videos. By leveraging Natural Language Processing (NLP) techniques and pretrained models from Hugging Face, the project classifies comments into specific sentiment.
## 📌 Deskripsi

Analisis ini bertujuan untuk melakukan analisis sentimen terhadap komentar penonton pada video YouTube:

<p align="center">
  <a href="https://www.youtube.com/watch?v=Ss6ud71pmvQ">
    <img src="https://img.youtube.com/vi/Ss6ud71pmvQ/maxresdefault.jpg" width="600">
  </a>
</p>

Video ini adalah episode podcast dari channel Endgame (Gita Wirjawan) dengan narasumber Purbaya Yudhi Sadewa. Video ini menekankan bahwa keberhasilan suatu negara sangat bergantung pada konsistensi dan keteguhan prinsip dalam pengambilan kebijakan. Purbaya Sadewa menjelaskan bahwa pembuat kebijakan tidak boleh mudah terpengaruh tekanan jangka pendek, melainkan harus berpegang pada tujuan jangka panjang yang jelas. Selain itu, pembangunan sumber daya manusia menjadi kunci utama kemajuan, sehingga diperlukan investasi besar dan berkelanjutan, termasuk melalui pendidikan dan program seperti beasiswa luar negeri. Peran institusi juga penting untuk memastikan kebijakan berjalan secara sistematis dan berdampak luas. Secara keseluruhan, video ini menyampaikan bahwa kombinasi antara prinsip yang kuat, keberanian mengambil keputusan strategis, dan fokus pada pengembangan manusia merupakan fondasi penting bagi kemajuan bangsa.


Analisis ini dilakukan untuk mengetahui opini publik yang tercermin dalam komentar YouTube, apakah bersifat positif, netral, atau negatif.


## 🎯 Tujuan

Mengidentifikasi sentimen publik terhadap topik yang dibahas dalam video

Mengukur persepsi masyarakat terhadap kebijakan dan pernyataan narasumber

Menerapkan metode machine learning dalam analisis teks bahasa Indonesia

Menjadi studi kasus implementasi NLP (Natural Language Processing)


## 🧠 Metodologi

### 1. Data Collection
Mengambil data komentar dari YouTube menggunakan API / scraping
Dataset berupa teks komentar
### 2. Data Preprocessing
1. Cleaning


2. Case folding


3. Normalization


4. Tokenizing


5. Filter token


6. Stopword removal


7. Stemming (menggunakan Sastrawi)


### 3. Feature Extraction
TF-IDF (Term Frequency–Inverse Document Frequency)
### 4. Modeling

Model yang digunakan:

Support Vector Machine (SVM) / LinearSVC
### 5. Evaluation
Accuracy

Precision

Recall

F1-score


## 📊 Label Sentimen

😊 Positif → komentar mendukung / apresiatif

😐 Netral → komentar informatif / tidak berpihak

😡 Negatif → kritik / ketidaksetujuan
