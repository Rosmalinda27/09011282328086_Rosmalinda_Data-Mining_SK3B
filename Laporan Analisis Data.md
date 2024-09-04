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
14. thal : [normal; cacat tetap; cacat yang dapat diperbaiki] <br/>
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

<h2> Analisis Statistik Data</h2>
<p> Berdasarkan hasil </p>
