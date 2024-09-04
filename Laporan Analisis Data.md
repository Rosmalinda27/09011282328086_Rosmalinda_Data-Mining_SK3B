<h1> LAPORAN EKSPLORASI DAN ANALISIS DATA </h1>
<h2>1. Deskripsi Dataset</h2>
<p> Dataset heart disease merupakan kumpukan data pasien penyakit jantung. Dataset heart disease terdiri dari beberapa kolom dan baris. Dataset ini berisi mengenai informasi yang terdiri dari data age, sex, dataset, cp, trestbps, chol, fbs, restecg, thalch, exang, oldpeak, slope, ca, thal, num. </p>

Identifikasi data: 
1. age : Usia pasien <br/>
2. sex : Jenis Kelamin <br/>
3. dataset : Lokasi pengumpulan data <br/>
4. cp : jenis nyeri dada <br/>
5. trestbps : tekanan darah istirahat <br/> 
6. chol : kolesterol <br/>
7. fbs :  gula darah puasa > 120 mg/dl <br/>
8. restecg : hasil elektrokardiografi saat istirahat <br/>
9. thalach : denyut jantung maksimum tercapai <br/>
10. exang : angina akibat olahraga <br/>
11. oldpeak : Depresi ST disebabkan oleh olahraga dibandingkan dengan istirahat <br/>
12. slope : kemiringan segmen ST latihan puncak <br/>
13. ca : jumlah pembuluh darah utama (0-3) <br/>
14. thal : (normal; cacat tetap; cacat yang dapat diperbaiki) <br/>
15. num : atribut yang diprediksi (tingkat keparahan penyakit) <br/>

<h2>2. Eksplorasi Data</h2>
Dataset heart disease terdiri dari 920 baris data dan 16 kolom data. Dataset ini memiliki tipe data integer, float, dan object(string). Berdasarkan hasil dari missing value diketahui bahwa terdapat beberapa data yang memiliki missing value yaitu : <br/>
1. trestbps : 59 missing value <br/>
2. chol : 30 missing value <br/>
3. fbs : 90 missing value <br/>
4. restecg : 2 missing value <br/>
5. thalch : 55 missing value <br/>
6. exang : 55 missing value <br/>
7. oldpeak : 62 missing value <br/>
8. slope : 309 missing value <br/>
9. ca : 611 missing value <br/>
10. thal : 486 missing value <br/>
Setelah menghitung nilai outliers pada variabel numeric didapatkan ada beberapa data yang memiliki outliers yaitu, trestbps, chol, thalch, oldpeak, dan ca. Data yang memiliki outliers terbanyak adalah chol sebesar 183 outliers.

<h2>3. Analisis Statistik Data</h2>
<p> Pada data Usia didapatkan rata-rata usia pasien adalah 53.51 tahun, dengan median dan modus nya hampir sama yaitu 54 tahun. Standar deviasi sebesar 9.42 menunjukkan bahwa sebagian besar usia berkisar di sekitar rata-rata, namun ada variasi dalam distribusi usia yaitu sebesar 88.82. </p>
<p> Pada data Tekanan darah saat istirahat didapatkan rata-rata 132.13 mmHg dan median 130 mmHg, ini menunjukkan bahwa sebagian besar orang memiliki tekanan darah yang cukup normal. Dengan modus 120 mmHg menunjukkan bahwa ini adalah tekanan darah yang terbanyak dari data. Namun, Dengan standar deviasi sebesar 19.07 menandakan adanya sampel dengan tekanan darah yang jauh lebih tinggi atau lebih rendah.</p>
<p> Pada data Kolestrol didapatkan rata-rata kadar kolesterol adalah 199.13 mg/dL, dengan median adalah 223 mg/dL,  Modus 0 mg/dL ini dapat terjadi jika nilai tidak valid atau data yang hilang (banyaknya missing value yang ada pada data chol). Standar deviasi yang tinggi (110.78) menunjukkan bahwa ada variasi besar dalam kadar kolesterol dengan beberapa individu memiliki kadar kolesterol yang sangat rendah atau sangat tinggi.</p>
<p> Pada data Denyut jantung maksimal didapatkan rata-ratanya adalah 137.55 bpm, dengan median yang 140 bpm. Dengan angka denyut jantung maksimal terbanyak di 150 bpm dalam dataset. Standar deviasi yang relatif tinggi (25.93 bpm) menandakan adanya variasi denyut jantung yang cukup besar di antara individu.</p>
<p> Pada data oldpeak (Nilai depresi ST) didapatkan rata-rata adalah 0.88, dengan median 0.5, menandakan bahwa sebagian besar individu memiliki nilai depresi ST yang rendah. Modus 0 menunjukkan bahwa sebagian besar sampel tidak mengalami depresi ST. Standar deviasi yang kecil (1.09) menandakan variasi kecil di antara nilai-nilai ini, dengan sebagian besar individu memiliki nilai yang mendekati rata-rata.</p>
<p> Pada data ca (jumlah pembuluh darah utama yang terlihat) adalah 0.68, dengan modus dan median memiliki nilai 0. Hal ini menunjukkan bahwa mayoritas individu tidak memiliki pembuluh darah yang terlihat melalui fluoroskopi. Ada sedikit variasi dalam data ini dengan standar deviasi 0.94.</p>
<p> Pada data num rata-ratanya adalah 0.9957 , dengan median sampel berada di 1. Dengan data terbanyak di 0 ini menunjukkan bahwa tingkat penyakit nya tidak terlalu parah.</p>
<p> Berdasarkan hitungan korelasi antar numerik didapatkan bahwa korelasi terbesar di dataset ini adalah pasangan oldpeak dengan num yaitu diangka 0.42 . Namun, angka 0,42 termasuk dalam kategori korelasi sedang bukan korelasi yang kuat. Hubungan ini berarti kedua variabel memiliki keterkaitan tetapi tidak terlalu erat.</p>

<h2>4. Visualisasi Data</h2>
<h3>Histogram dari data numeric</h3>
<img src="https://github.com/user-attachments/assets/78de800d-cfe6-42ec-9fa0-b75c57b75fbb"/>
<img src="https://github.com/user-attachments/assets/a40b67b6-6b3c-457c-ac14-bbf3ce671fc2" width=500/>
<img src="https://github.com/user-attachments/assets/0261663f-03de-4bcd-87d1-be55b5036445"  width=500/>
<img src="https://github.com/user-attachments/assets/fbfeeca1-c13e-49d0-b592-e58f3d3e0deb"  width=500/>
<img src="https://github.com/user-attachments/assets/4d912229-11dc-4ce2-bfaf-2b0553b81999"  width=500/>

<h3>Boxplot dari data numeric</h3>
<img src="https://github.com/user-attachments/assets/fe559360-bd42-4d84-81e1-4836bb54303f"/>

<h3>Scatter Plot</h3>
<img src="https://github.com/user-attachments/assets/baa36091-0647-403e-aedb-b284836e251c"/>
<img src="https://github.com/user-attachments/assets/afd184d3-098e-4bdc-819f-f08ff3b80661"/>

<h2> 5. Kesimpulan</h2>
<p> Berdasarkan hasil dari analisis, heart disease lebih banyak terjadi pada laki laki dengan usia 50 keatas, dengan lokasi pengumpulan data terbanyak yaitu dari VA Long Beach. Berdasarkan hasil dari skew dan kurtosis didapatkan bahwa nilai nya jauh dari 0 sehingga dapat disebut sebagai distribusi tidak normal. Pada data didalam dataset ini memiliki korelasi tertinggi pada pasangan oldpeak dan num di angka 0.42 tapi ini tidak termasuk ke korelasi yang tinggi, Sehingga dapat dinyatakan bahwa dari korelasi ini hubungan kedua variabel memiliki keterkaitan namun tidak terlalu erat. Berdasarkan hasil pengecekan dataset ini juga memilki missing value pada beberapa datanya. Dataset ini juga memiliki outliers yang dapat kita lihat di visualisasi data pada bagian boxplot ataupun melalui perhitungan IQR yang ada di jupyter, Outliers terbesar didataset ini berada di data chol.  </p>




