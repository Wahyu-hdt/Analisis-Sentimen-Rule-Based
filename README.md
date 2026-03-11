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
<h1>Insight</h1>
Sentimen Negatif Menunjukkan Perlu Dilakukan Pembenahan Pada Area Berikut:
<br>
Kebersihan: Kata "sampah" dan "kotor". Ini adalah keluhan nomor satu pengunjung Pantai Labuhan Jukung.
<br>
Fasilitas: Kata "fasilitas" dan "rusak" mengindikasikan adanya penurunan kualitas pada fasilitas yang diberikan kepada pengunjung.
<br>
Kekecewaan: Kata "sayang" menunjukkan ekspektasi pengunjung yang tidak terpenuhi karena faktor berbagai macam faktor, salah satunya Kebersihan.

<br>
Sentimen Positif Menunjukkan Faktor Yang Disukai Pengunjung Pantai Labuhan Jukung:
<br>
Keindahan Alam: Kata "indah", "sunset", "pemandang", dan "ombak" adalah nilai jual utama pantai ini.
<br>
Aktivitas Yang Bisa Dilakukan:  Kata "surfing" dan "labuh jukung", menunjukkan aktivitas surfing merupakan andalan dipantai ini.
<br>
Wisata Ramah Keluarga: Kata "keluarga", "ramah", dan "murah" mengungkapkan bahwa pantai ini adalah wisata yang ramah keluarga.
