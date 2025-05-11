# 📰 Web Scraping Berita: Le Sserafim dari X

Proyek ini bertujuan untuk mengambil data dari **X** (sebelumnya Twitter) yang membahas tentang grup K-pop **Le Sserafim**, khususnya terkait penampilan mereka di **Coachella 2024**.  
Data yang diperoleh disimpan dalam bentuk dataset untuk dianalisis lebih lanjut.

---

## 🧰 Tools / Library yang Digunakan

- **Python** — Bahasa pemrograman utama  
- **requests** — Mengambil data (jika scraping manual dilakukan)  
- **BeautifulSoup (bs4)** — Parsing HTML (jika ada scraping web)  
- **pandas** — Menyimpan data dalam DataFrame dan ekspor ke `.csv`  
- **matplotlib** — Visualisasi data dari hasil scraping  
- **re, collections.Counter** — Analisis kata

---

## 📈 Output

- Dataset berisi teks cuitan (tweet) yang menyebut *Le Sserafim*  
- Visualisasi 10 kata yang paling sering muncul dalam isi tweet  
- File `.csv` berisi data hasil scraping yang siap dianalisis

---

## 📌 Kesimpulan

Proyek ini menunjukkan bagaimana data dari X dapat diambil secara otomatis menggunakan teknik **web scraping**.  
Hasil analisis menunjukkan bahwa topik-topik seperti konser dan kontroversi cukup dominan.  
Dengan analisis kata, kita juga dapat mengidentifikasi kata-kata yang paling sering muncul dalam tweet tentang Le Sserafim.  
Proyek ini dapat dikembangkan lebih lanjut dengan menambahkan sumber data lain, melakukan analisis sentimen, atau mengklasifikasikan topik tweet.

---

## 🧑‍💻 Author

Proyek ini dikerjakan oleh **Ardhea Oktaviany** sebagai latihan portofolio dalam bidang *data analysis* dan *web scraping*.
