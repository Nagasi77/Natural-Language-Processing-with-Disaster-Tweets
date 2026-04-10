# Natural-Language-Processing-with-Disaster-Tweets

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1OZ2Jr1-YStH95QwJnmh5gbc8Rw87ygWC/view?usp=sharing)

Natural Language Processing with Disaster Tweets
Deskripsi Proyek

Proyek ini berfokus pada klasifikasi teks untuk mendeteksi laporan bencana melalui tweet. Tantangan utamanya adalah membedakan antara penggunaan kata-kata bencana secara harfiah dengan penggunaan bahasa metafora. Proyek ini merupakan bagian dari kompetisi Kaggle.
Metodologi

Saya menerapkan metode P U L P untuk memproses data teks mentah menjadi fitur yang dapat dipahami oleh mesin. Pendekatan ini memastikan data bersih dari gangguan sebelum masuk ke tahap pemodelan.
Teknologi dan Algoritma

    Bahasa: Python.

    Manipulasi Data: Pandas.

    Ekstraksi Fitur: CountVectorizer dan TfidfVectorizer.

    Model Machine Learning:

        Logistic Regression (dengan data mentah dan data bersih).

        Multinomial Naive Bayes (menggunakan pembobotan TF-IDF).

Tahapan Kerja

    Analisis Data (EDA): Mengecek distribusi target dan menangani data yang hilang.

    Pembersihan Teks: Membuat fungsi kustom untuk mengubah teks menjadi huruf kecil, menghapus URL, serta menghapus karakter non-alfabet.

    Vektorisasi: Mengonversi teks menjadi representasi numerik menggunakan teknik Bag-of-Words dan TF-IDF.

    Pelatihan Model: Melatih beberapa model klasifikasi untuk mendapatkan prediksi terbaik.

    Evaluasi: Menghasilkan file submisi untuk pengujian performa akhir.

Hasil

Model akhir menggunakan kombinasi TF-IDF dan Naive Bayes untuk memberikan hasil klasifikasi yang efisien dan cepat dalam mendeteksi tweet bencana.
