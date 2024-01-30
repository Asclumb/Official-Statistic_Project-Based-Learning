# LAPORAN TUGAS BESAR MATA KULIAH *OFFICIAL STATISTICS*
### “Analisis Statistik Imunisasi, Gizi Bayi di Indonesia pada tahun 2016-2018”
<p align="center">
  <img width="300" height="auto" src="itk.png">
</p>

#### Disusun oleh :
1. Eden Gideon Harefa(16221001)
2. Joabri Sihombing(16221002)
3. Fachlevi Asclumb(16221026)
4. Muhammad Atha Arrafi(16221031)
5. Andy Patra Virgiawan(16221037)
 
### INSTITUT TEKNOLOGI KALIMANTAN 
### BALIKPAPAN 
### 2023

<!-- Ini adalah page break dari css -->
<div style="page-break-before:always">&nbsp;</div>

### Abstrak

Penelitian ini bertujuan untuk mengidentifikasi dan memahami tingkat cakupan imunisasi di Indonesia pada tahun 2016, 2017, dan 2018, serta untuk mengkaji kondisi gizi bayi selama periode yang sama. Metode penelitian melibatkan analisis data dari laporan statistik BPS, yang mencakup persentase kabupaten/kota yang mencapai 80% imunisasi dasar lengkap pada bayi dan prevalensi gizi kurang pada balita menurut provinsi.

Hasil analisis statistik menunjukkan adanya perbedaan signifikan dalam tingkat gizi kurang pada balita (0-23 bulan dan 0-59 bulan) selama periode 2016–2018. Meskipun tingkat gizi kurang rata-rata meningkat dari kelompok usia 0-23 bulan hingga 0-59 bulan, distribusi data masih bervariasi, dengan nilai standar deviasi yang cukup signifikan. Meskipun variasi data menurun, terutama pada kelompok usia 0-23 bulan, kelompok usia 0-59 bulan pada tahun 2018 menunjukkan sedikit ekor positif, dengan parameter kurtosis dan skewness yang menunjukkan distribusi data cenderung normal. Rentang data menurun sepanjang waktu, menunjukkan bahwa variasi antara nilai maksimum dan minimum semakin terbatas.

***Kata Kunci**: Imunisasi, BPS (Badan Pusat Statistik), Balita (0-23 bulan dan 0-59 bulan).*

---

### Abstract

This research aims to identify and understand the immunization coverage levels in Indonesia for the years 2016, 2017, and 2018, as well as to examine the nutritional status of infants during the same period. The research method involves data analysis from BPS statistical reports, encompassing the percentage of districts/cities achieving 80% full basic immunization coverage in infants and the prevalence of malnutrition in toddlers by province.

Statistical analysis results indicate significant differences in malnutrition rates among toddlers (0-23 months and 0-59 months) during the period 2016–2018. Although the average malnutrition rates increased from the age group of 0-23 months to 0-59 months, the data distribution still varied, with a sufficiently significant standard deviation. Despite a decrease in data variability, especially in the age group of 0-23 months, the 0-59 months age group in 2018 exhibited a slight positive skewness, with kurtosis and skewness parameters suggesting a tendency toward a normal data distribution. The data range decreased over time, indicating a narrowing variation between maximum and minimum values.

***Keywords** : Immunization, BPS (Badan Pusat Statistik), Toddlers (0-23 months and 0-59 months).*

<div style="page-break-before:always">&nbsp;</div>


### Daftar Tabel

**Tabel 4.1.1** Gizi Kurang Balita (0-23 bulan)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;9

**Tabel 4.1.2** Gizi Kurang Balita (0-59 bulan)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;10

<div style="page-break-before:always">&nbsp;</div>

### Bab 1
### Pendahuluan

#### 1.1 &emsp;Latar Belakang

&emsp;&emsp;&emsp;Analisis statistik terkait imunisasi dan gizi di Indonesia memainkan peran sentral dalam pemahaman kondisi kesehatan masyarakat. Dua aspek utama ini, yaitu imunisasi dan gizi, memiliki dampak langsung pada tingkat kesehatan individu dan kolektif di negara ini.

&emsp;&emsp;&emsp;Pertama-tama, imunisasi berperan sebagai garda pertahanan utama melawan penyakit yang dapat menyebabkan dampak serius pada kesehatan masyarakat. Program imunisasi yang efektif dapat secara signifikan mengurangi angka kesakitan dan kematian akibat penyakit menular seperti campak, polio, dan hepatitis. Oleh karena itu, pemantauan statistik terkait cakupan imunisasi di berbagai wilayah Indonesia menjadi penting untuk mengevaluasi efektivitas program-program ini dan mengidentifikasi area di mana perlu ditingkatkan.

&emsp;&emsp;&emsp;Di sisi lain, aspek gizi juga memiliki peran krusial dalam membentuk kondisi kesehatan masyarakat. Gizi yang baik tidak hanya memastikan pertumbuhan dan perkembangan yang optimal pada anak-anak, tetapi juga meningkatkan daya tahan tubuh terhadap penyakit. Analisis statistik terkait status gizi penduduk Indonesia akan memberikan gambaran mendalam tentang sejauh mana kebutuhan gizi terpenuhi di berbagai kelompok usia dan lapisan masyarakat. Hal ini dapat membantu pemerintah dan lembaga kesehatan untuk merancang program-program nutrisi yang lebih tepat sasaran.

&emsp;&emsp;&emsp;Selain itu, integrasi data imunisasi dan gizi dalam analisis statistik dapat memberikan pemahaman yang lebih holistik tentang kesehatan masyarakat. Misalnya, apakah daerah dengan cakupan imunisasi yang rendah juga memiliki masalah gizi yang signifikan? Atau sebaliknya, apakah ada keterkaitan antara tingkat gizi dan respons tubuh terhadap vaksinasi?

&emsp;&emsp;&emsp;Dengan menyelidiki pertanyaan-pertanyaan ini melalui analisis statistik yang komprehensif, kita dapat mengidentifikasi pola-pola kesehatan yang mungkin terlewatkan dan merancang intervensi yang lebih terarah dan berkelanjutan. Oleh karena itu, upaya terus-menerus dalam pengumpulan dan analisis data terkait imunisasi dan gizi menjadi pondasi penting dalam membangun sistem kesehatan yang tangguh dan responsif terhadap kebutuhan masyarakat Indonesia.

#### 1.2 Rumusan Masalah

&emsp;&emsp;&emsp;Pada penelitian ini, kita akan membahas tentang analisis statistik terkait imunisasi dan gizi di Indonesia pada tahun 2016, 2017, dan 2018. Beberapa rumusan masalah yang akan dibahas antara lain:
- Bagaimana tingkat cakupan imunisasi di Indonesia pada tahun 2016, 2017, dan 2018?
- Bagaimana kondisi gizi masyarakat Indonesia pada tahun 2016, 2017, dan 2018?
- Apakah ada perbedaan signifikan antara tingkat cakupan imunisasi dan kondisi gizi di Indonesia pada tahun 2016, 2017, dan 2018?

#### 1.3 Tujuan
&emsp;&emsp;&emsp;Dari rumusan masalah didapatkan tujuan dari analisis ini sebagai berikut :

- Mengidentifikasi dan memahami tingkat cakupan imunisasi di Indonesia pada tahun 2016, 2017, dan 2018.
- Mengkaji kondisi gizi bayi di Indonesia pada tahun 2016, 2017, dan 2018.
- Menentukan apakah terdapat perbedaan signifikan antara tingkat cakupan imunisasi bayi di Indonesia pada tahun 2016, 2017, dan 2018.

&emsp;&emsp;&emsp;Dengan tujuan-tujuan tersebut, analisis statistik ini diharapkan dapat memberikan pemahaman yang mendalam tentang hubungan antara tingkat cakupan imunisasi dan kondisi gizi bayi di Indonesia selama tahun 2016, 2017, dan 2018 serta memberikan dasar bagi perbaikan kebijakan dan intervensi kesehatan.

#### 1.4 Manfaat

&emsp;&emsp;&emsp;Manfaat dari penelitian ini adalah untuk memperoleh informasi yang lebih detail dan akurat tentang kondisi imunisasi dan gizi di Indonesia pada tahun 2016, 2017, dan 2018. Informasi ini dapat bermanfaat bagi berbagai pihak, seperti pemerintah, lembaga kesehatan, dan masyarakat umum untuk melakukan perbaikan dan pengembangan program-program terkait kesehatan.

#### 1.5 Batasan Masalah
&emsp;&emsp;&emsp;Penelitian ini akan membatasi analisis statistik terkait imunisasi dan gizi di Indonesia pada tahun 2016, 2017, dan 2018. Analisis tidak akan membahas aspek-aspek kesehatan lainnya yang tidak berhubungan dengan imunisasi dan gizi.

<div style="page-break-before:always">&nbsp;</div>v


### Bab 2
### Tinjauan Pustaka

#### 2.1 Statistika Deskriptif
&emsp;&emsp;&emsp;Menganalisis data, kita pada dasarnya sedang melakukan tindakan atau perlakuan terhadap data dengan tujuan tertentu, entah itu untuk menyajikan gambaran menyeluruh mengenai data atau untuk menarik kesimpulan terkait dengan kondisi atau kejadian di mana data tersebut diambil. Pentingnya alat analisis yang dipilih menjadi faktor krusial dalam menentukan kebijakan berdasarkan data yang telah terkumpul seperti, sampel, rata-rata, varians, standar deviasi, standar error, minimum dan maksimum (Martias, 2021). 

#### 2.2 Penyebaran Data
&emsp;&emsp;&emsp;Pengertian Dispersi Data Penyebaran atau dispersi adalah pergerakan dari nilai observasi terhadap nilai rata-ratanya. Rata-rata dari serangkaian nilai observasi tidak dapat diinterpretasikan secara terpisah dari hasil dispersi nilai-nilai tersebut sekitar rata ratanya. Makin besar variasi nilai xi , makin kurang representatif rata-rata distribusinya. Ukuran penyebaran suatu kelompok data terhadap pusat data disebut dispersi atau variasi atau keragaman data. Dispersi data digunakan untuk membandingkan penyebaran dua distribusi data atau lebih.

Beberapa jenis pengukuran adalah penyebaran data sebagai berikut: 
1. Jangkauan (Range) Selisih antara batas atas dari kelas tertinggi dengan batas bawah dari kelas terendah. 
2. Simpangan Rata-Rata (Mean Deviation) Jumlah nilai mutlak dari selisih semua nilai dengan nilai rata-rata dibagi banyaknya data. 
3. Varians (Variance) Rata-rata hitung deviasi kuadrat setiap data terhadap rata-rata hitungnya.
4. Standar Deviasi Akar kuadrat dari varians dan menunjukkan standar penyimpangan data terhadap nilai rata-ratanya.

#### 2.3 Imunisasi
&emsp;&emsp;&emsp;Imunisasi adalah upaya untuk menimbulkan atau meningkatkan kekebalan seseorang terhadap suatu penyakit tertentu dengan cara memasukkan vaksin ke dalam tubuh. Vaksin merupakan suatu produk biologi yang mengandung antigen yang dapat merangsang sistem kekebalan tubuh untuk menghasilkan antibodi. Antibodi ini akan melindungi tubuh dari infeksi penyakit yang disebabkan oleh antigen tersebut (Darmin, 2023).

#### 2.4 Gizi
&emsp;&emsp;&emsp; Gizi merupakan salah satu penentu kualitas sumber daya manusia. Makanan yang diberikan sehari-hari harus mengandung zat gizi sesuai kebutuhan, sehingga menunjang pertumbuhan yang optimal dan dapat mencegah penyakit - penyakit defisiensi, mencegah keracunan, dan juga membantu mencegah timbulnya penyakit-penyakit yang dapat mengganggu kelangsungan hidup anak (Hidayati, 2015).

<div style="page-break-before:always">&nbsp;</div>

### BAB III
### METODOLOGI

#### 3.1 Sumber Data
&emsp;&emsp;&emsp;Data dalam penelitian ini diperoleh dari Badan Pusat Statistik (BPS). BPS merupakan sumber data utama yang menyediakan informasi mengenai karakteristik mahasiswa ITK yang bekerja. Data yang diperoleh melibatkan variabel-variabel seperti persentase bayi yang mendapatkan imunisasi lengkap (80%) dan prevalensi balita kurang gizi.
#### 3.2 Metode Pengumpulan Data
#### 3.2.1 Sampling
- Pengambilan sampel dilakukan dengan menggunakan metode purposive sampling, yaitu pemilihan sampel dengan tujuan tertentu berdasarkan kriteria tertentu.
- Jumlah sampel yang diambil mencakup sejumlah N responden untuk mendapatkan representasi yang memadai.
#### 3.2.2 Data BPS
- Data diambil dari laporan statistik yang diterbitkan oleh BPS yang mencakup informasi relevan mengenai persentase kabupaten kota yang mencapai 80 % imunisasi dasar lengkap pada bayi dan prevalensi balita gizi kurang menurut provinsi di Indonesia (PSG)	
- Data yang digunakan merupakan data sekunder yang telah ada dan diolah untuk keperluan penelitian ini.

#### 3.3 Langkah Analisis
- Mengumpulkan data/informasi
- Mengolah data hasil pengumpulan.
- Menyajikan data hasil pengolahan.
- Menganalisis data.

<div style="page-break-before:always">&nbsp;</div>

### BAB IV
### ANALISIS DAN PEMBAHASAN

#### 4. Analisis Hasil

#### 4.1 Analisis Statistika Deskriptif

**Tabel 4.1.1** Gizi Kurang Balita (0-23 bulan)

|                   | 2016     | 2017     | 2018     |
|-------------------|----------|----------|----------|
| Mean              | 11.994   | 12.256   | 12.285   |
| Standard Error    | 0.552    | 0.420    | 0.432    |
| Median            | 12.330   | 11.900   | 12.300   |
| Mode              | 17.870   | 15.700   | 14.400   |
| Standard Deviation| 3.220    | 2.451    | 2.517    |
| Sample Variance   | 10.370   | 6.005    | 6.335    |
| Kurtosis          | -0.313   | -0.461   | -0.560   |
| Skewness          | -0.361   | -0.198   | -0.094   |
| Range             | 12.680   | 9.900    | 10.200   |
| Minimum           | 5.190    | 6.300    | 7.400    |
| Maximum           | 17.870   | 16.200   | 17.600   |
| Sum               | 407.810  | 416.700  | 417.700  |
| Count             | 34.000   | 34.000   | 34.000   |
| Largest(1)        | 17.870   | 16.200   | 17.600   |
| Smallest(1)       | 5.190    | 6.300    | 7.400    |
| Confidence Level(95%) | 1.124 | 0.855    | 0.878   |

Pada tabel 4.1.1 didapatkan rata-rata tingkat gizi kurang menunjukkan peningkatan dari 11.994 pada tahun 2016 menjadi 12.256 pada tahun 2017, dan sedikit lebih tinggi pada tahun 2018 dengan nilai 12.285. Standar deviasi yang menurun dari tahun ke tahun menunjukkan bahwa data lebih mendekati nilai rata-rata, dan demikian juga dengan rentang yang menyusut dari 12.680 pada tahun 2016 menjadi 9.900 pada tahun 2017 dan 10.200 pada tahun 2018. Median yang bervariasi menunjukkan variasi dalam distribusi data, sementara modus memberikan gambaran nilai yang paling sering muncul. Selain itu, informasi mengenai kurtosis dan skewness memberikan wawasan tentang bentuk distribusi data. Interval kepercayaan 95% memberikan perkiraan rentang yang mungkin berisi rata-rata populasi, dan jumlah data yang konsisten sepanjang tahun menambah keandalan analisis statistik tersebut. Sebagai tambahan, informasi tentang jumlah total, nilai maksimum dan minimum, serta jumlah keseluruhan memberikan konteks yang lebih lengkap untuk interpretasi data gizi kurang pada balita selama periode tersebut.

**Tabel 4.1.2** Gizi Kurang Balita (0-59 bulan)

|                   | 2016     | 2017     | 2018     |
|-------------------|----------|----------|----------|
| Mean              | 14.551   | 14.862   | 14.768   |
| Standard Error    | 0.668    | 0.579    | 0.560    |
| Median            | 13.970   | 14.550   | 14.050   |
| Mode              | 17.730   | 19.900   | 18.600   |
| Standard Deviation| 3.893    | 3.377    | 3.263    |
| Sample Variance   | 15.157   | 11.405   | 10.650   |
| Kurtosis          | -0.394   | -0.425   | -0.784   |
| Skewness          | -0.223   | -0.175   | 0.448    |
| Range             | 15.480   | 14.300   | 12.400   |
| Minimum           | 5.860    | 6.600    | 9.800    |
| Maximum           | 21.340   | 20.900   | 22.200   |
| Sum               | 494.750  | 505.300  | 502.100  |
| Count             | 34.000   | 34.000   | 34.000   |
| Largest(1)        | 21.340   | 20.900   | 22.200   |
| Smallest(1)       | 5.860    | 6.600    | 9.800    |
| Confidence Level(95%) | 1.358 | 1.178    | 1.139    |

Pada tabel 4.1.2 didapatkan rata-rata tingkat gizi kurang mengalami kenaikan berturut-turut dari 14.551 pada tahun 2016, 14.862 pada tahun 2017, hingga 14.768 pada tahun 2018. Standar deviasi yang cukup tinggi menunjukkan variasi yang signifikan dalam data, dan rentang yang menurun dari 15.480 pada tahun 2016 menjadi 14.300 pada tahun 2017, dan 12.400 pada tahun 2018 menunjukkan pengurangan variasi antara nilai maksimum dan minimum. Meskipun median menunjukkan variasi, modus yang berbeda dari median menunjukkan kemungkinan adanya distribusi yang condong. Indikator kurtosis yang menurun dari tahun ke tahun menandakan bahwa distribusi data cenderung mendekati distribusi normal. Skewness yang mendekati nol pada tahun 2017 dan 2018 menunjukkan simetri yang relatif, sementara nilai yang sedikit positif pada tahun 2018 mungkin menandakan ekor distribusi yang lebih panjang di sisi kanan. Interval kepercayaan 95% memberikan perkiraan sejauh mana kita dapat yakin bahwa interval tersebut berisi nilai rata-rata populasi. Data jumlah total, nilai maksimum dan minimum, serta jumlah data yang konsisten sepanjang tahun memberikan konteks penting untuk interpretasi lebih lanjut terkait status gizi kurang pada balita dalam rentang usia tersebut.

<div style="page-break-before:always">&nbsp;</div>

### BAB V
### KESIMPULAN DAN SARAN

#### 5.1 Kesimpulan
&emsp;&emsp;&emsp;Analisis statistik terhadap data gizi kurang pada balita (0-23 bulan dan 0-59 bulan) selama periode 2016–2018 menunjukkan beberapa temuan signifikan. Di kelompok usia 0-23 bulan hingga kelompok usia 0-59 bulan, tingkat gizi kurang rata-rata meningkat. Distribusi data masih bervariasi, dengan nilai standar deviasi yang cukup signifikan. Ini terjadi meskipun variasi data menurun, terutama pada kelompok usia 0-23 bulan. Kelompok usia 0-59 bulan pada tahun 2018 menunjukkan sedikit ekor positif, tetapi parameter kurtosis dan skewness menunjukkan distribusi data cenderung normal. Rentang data menurun sepanjang waktu, yang menunjukkan bahwa variasi antara nilai maksimum dan minimum semakin terbatas.

#### 5.2 Saran
&emsp;&emsp;&emsp;Dari analisis tersebut, beberapa tindakan diperlukan untuk meningkatkan status gizi balita. Pertama, program gizi balita harus dimonitor dan dievaluasi secara teratur untuk mengidentifikasi tren dan kelompok risiko. Intervensi gizi harus disesuaikan dengan kelompok usia, dengan memberikan perhatian khusus pada balita usia 0-59 bulan pada tahun 2018, yang menunjukkan status gizi yang lebih buruk. Selain itu, orang tua dan penyedia layanan kesehatan harus dididik lebih baik tentang nutrisi balita. Salah satu langkah penting dalam mengatasi masalah gizi balita secara menyeluruh adalah meningkatkan sistem pemantauan gizi nasional bersama dengan kerja sama antar sektor. Penelitian tambahan juga diperlukan untuk memahami variabel yang mungkin mempengaruhi perbedaan status gizi kurang pada kelompok usia tersebut.

<div style="page-break-before:always">&nbsp;</div>

**Daftar Pustaka**
- Martias. (2021). "Statistika deskriptif sebagai kumpulan informasi."
- Darmin, dkk. (2023). "Pentingnya Imunisasi Dasar Lengkap Pada Bayi dan Balita."
- Hidayati, dkk. (2015). "Hubungan Pengetahuan Ibu Tentang Infeksi Kecacingan dengan Status Gizi Balita di Wilayah Kerja Puskesmas Gambut Kabupaten Banjar Tahun 2015."

**Lampiran**

[Data imunisasi dan gizi]("https://docs.google.com/spreadsheets/d/1N9-F1GyqexDGFFCDEvh6wRwadFWV27UR7gF735P1aWk/edit?usp=sharing")