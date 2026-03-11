<h1>Isi Repository</h1>
Repository ini bertujuan untuk menganalisis sentimen pengunjung terhadap Pantai Labuhan Jukung, Lampung, berdasarkan ulasan yang diambil dari Google Maps. Dengan pendekatan klasifikasi Rule-Based (lexicon-based (kamus kata)), ulasan diklasifikasikan menjadi sentimen Positif, Netral, atau Negatif untuk memahami aspek apa yang paling disukai atau dikeluhkan oleh wisatawan terhadap Pantai Labuhan Jukung, Lampung.


<br>
<br>
<h1>Alur Kerja Repository</h1>
1. Data Scraping: Pengambilan data ulasan secara real-time menggunakan teknik web scraping.<br>
2. Pre-processing: Pembersihan data teks meliputi: Case Folding, Filtering, Stopwords Removal.<br>
3. Penetapan Rule: Penyusunan kamus kata (lexicon) positif dan negatif.<br>
4. Klasifikasi Data: Pemberian label sentimen berdasarkan skor bobot kata yang muncul.<br>
5. Visualisasi: Untuk memudahkan proses pengambilan insight data.<br>

<br>
<br>
<h1>Hasil Visualisasi</h1>
Berdasarkan hasil analisis sentimen yang telah dilakukan pada dataset Pantai Labuhan Jukung, Lampung. Berikut adalah gambaran kata-kata yang paling sering muncul dalam ulasan pengunjung yang direpresentasikan melalui WordCloud:
<br>
<br>

<br>
<div align="center">
  <img src="visualisasi/statistik-sentimen.png" alt="Statistik Sentimen" width="700">
  <p><i>Gambar: Statistik Sentimen dan Analisis Topik Dominan Pantai Labuhan Jukung</i></p>
</div>


<br>
<div align="center">
  <img src="visualisasi/wc-positif.png" alt="Wordcloud positif" width="700">
  <p><i>Gambar: Wordcloud Positif Pantai Labuhan Jukung</i></p>
</div>


<br>
<div align="center">
  <img src="visualisasi/wc-negatif.png" alt="Wordcloud Negatif" width="700">
  <p><i>Gambar: Wordcloud Negatif Pantai Labuhan Jukung</i></p>
</div>


<br>
<div align="center">
  <img src="visualisasi/wc-netral.png" alt="Wordcloud Netral" width="700">
  <p><i>Gambar: Wordcloud NetralPantai Labuhan Jukung</i></p>
</div>


<br>
<br>
<h1>Insight</h1>

Analisis sentimen terhadap ulasan pengunjung Pantai Labuhan Jukung memberikan beberapa poin penting sebagai berikut:

---

### Fokus Pembenahan (Sentimen Negatif)
Berdasarkan data, area-area berikut memerlukan perhatian segera dari pihak pengelola:

* **Masalah Kebersihan:** Kata **"sampah"** dan **"kotor"** menjadi keluhan nomor satu. Hal ini menunjukkan bahwa isu kebersihan adalah penghambat utama kenyamanan pengunjung.
* **Kualitas Fasilitas:** Kemunculan kata **"fasilitas"** dan **"rusak"** mengindikasikan adanya penurunan kualitas sarana prasarana yang tersedia di area pantai.
* **Faktor Kekecewaan:** Kata **"sayang"** sering muncul, menggambarkan ekspektasi pengunjung yang tinggi  namun tidak terpenuhi karena faktor eksternal seperti kebersihan dan fasilitas tadi.

<br>

---

###  Keunggulan Utama (Sentimen Positif)
Faktor-faktor inilah yang menjadi daya tarik utama dan alasan mengapa pengunjung merekomendasikan pantai ini:

* **Pesona Alam:** Kata **"indah"**, **"sunset"**, **"pemandang"**, dan **"ombak"** mengukuhkan daya tarik visual Pantai Labuhan Jukung sebagai nilai jual utama.
* **Pusat Aktivitas:** Kata **"surfing"** dan **"labuh jukung"** menegaskan bahwa pantai ini merupakan destinasi unggulan bagi pecinta olahraga selancar.
* **Destinasi Keluarga:** Penggunaan kata **"keluarga"**, **"ramah"**, dan **"murah"** menunjukkan bahwa pantai ini dinilai sebagai tempat wisata yang aksesibel dan nyaman untuk segala usia.

---

<br>

###  Proyek Terkait
Lihat juga pengolahan data ulasan Pantai Labuhan Jukung dengan pendekatan lainnya disini:
* **Analisis Sentimen (Naive Bayes):** [Wahyu-hdt/Analisis-Sentimen-Naive-Bayes](https://github.com/Wahyu-hdt/Analisis-Sentimen-Naive-Bayes)
  > Pendekatan menggunakan algoritma Multinomial Naive Bayes untuk klasifikasi otomatis berdasarkan data training.
