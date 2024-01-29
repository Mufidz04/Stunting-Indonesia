# Laporan Proyek Machine Learning - Tsaqif Mutashim Mufid

## Domain Proyek

*Stunting* telah menjadi program nasional di Indonesia karena masih melibatkan sebagian besar penduduk. Upaya pencegahan *stunting* memerlukan pemahaman mendalam terhadap faktor-faktor yang menjadi determinan, baik dari pihak ibu maupun anak. Faktor ibu yang menjadi determinan *stunting* melibatkan pendidikan ibu, kesadaran dalam mengonsumsi tablet tambah darah, menjaga kualitas makanan, serta kemampuan dalam mencari informasi gizi baik dari sumber-sumber terpercaya [1]. Selain itu, faktor anak yang juga determinan *stunting* melibatkan kurangnya asupan ASI dan MPASI, terutama ketika ibu mengalami kekurangan gizi. Dengan kondisi tersebut, tumbuh kembang anak menjadi terhambat, menyebabkan kejadian *stunting* [2]. *Stunting* merupakan masalah gizi utama di negara-negara berkembang, termasuk Indonesia. *Stunting* dapat terjadi pada anak setelah usia 6 bulan, dan semua anak membutuhkan makanan lunak yang bergizi, umumnya dikenal sebagai makanan pendamping ASI (MP-ASI), selain ASI. Ada berbagai faktor yang dapat menyebabkan *stunting*, seperti kurangnya pemberian ASI eksklusif, rendahnya kadar kalsium dalam ASI, dan gumoh yang berlebihan setelah menyusui. *Stunting* merupakan kondisi gagal tumbuh pada anak balita akibat kekurangan gizi kronis terutama dalam 1.000 hari pertama kehidupan sehingga anak terlalu pendek untuk usianya [3]. Penelitian telah menunjukkan bahwa pemberian ASI eksklusif secara signifikan berhubungan dengan risiko stunting yang lebih rendah [4] [2]. Dalam upaya menurunkan angka *stunting*, khususnya praktik malnutrisi pada anak telah banyak dilakukan seminar yang bertujuan untuk mendiskusikan peran penting pertumbuhan ekonomi keluarga [5]. Faktor ekonomi merupakan jumlah pendapatan yang diperoleh keluarga untuk memenuhi keperluan rumah tangga [3]. Selain itu, *stunting* masih menjadi masalah yang serius di Indonesia, dengan prevalensi *stunting* pada tahun 2022 sebesar 21,6% [6]. Hal ini berbeda dengan target WHO, yang harus di bawah 20% [7]. Oleh karena itu, pemanfaatan pembelajaran mesin diharapkan dapat membantu memprediksi dan mencegah malnutrisi pada anak.

**References**:
> [1]	I. R. Putri and M. Anas, “Hubungan Faktor Ibu Dan Anak Terhadap Kejadian Stunting Pada Balita,” J. Multidisiplin Indones., vol. 2, no. 7, pp. 1450–1469, Jul. 2023, doi: 10.58344/jmi.v2i7.304.

> [2]	A. K. S. Lebuan, M. Syafar, and N. Hartati, “Hubungan Pola Pemberian Makan Pada Balita Stunting di Puskesmas di Flores Timur”.

> [3]	E. M. Yanti, “HUBUNGAN FAKTOR EKONOMI DAN POLA ASUH ORANG TUA DENGANKEJADIAN STUNTING PADA BALITA DI DESA KEMBANG KERANG DAYA,” vol. 4, no. 8, 2023.

> [4]	R. S. Putra Pratama, M. S. Dasuki, T. Agustina, and S. Soekiswati, “ASI Eksklusif Sebagai Faktor Protektif Terhadap Kejadian Stunting Pada Balita 24-59 Bulan,” J. Ilm. Kesehat. Sandi Husada, vol. 11, no. 1, pp. 262–270, Jun. 2022, doi: 10.35816/jiskh.v11i1.748.

> [5]	E. Endraria and P. Susilo, “Edukasi Mengenai Pertumbuhan Ekonomi Keluarga Yang Efektif Dapat Menurunkan Angka Stunting Khususnya Praktik Malnutrisi Pada Anak,” J. Pengabdi. Masy. Bangsa, vol. 1, no. 8, pp. 1580–1588, Oct. 2023, doi: 10.59837/jpmba.v1i8.390.

> [6]	H. T. Sinaga, N. Achmad, M. Manalu, S. Perangin-Angin, and L. G. Doloksaribu, “Length Attainment and Stunting Prevalence of Children aged 0–24 Months Living in the Area of Clay Brick Kilns in Pagar Merbau Sub District, Indonesia,” Open Access Maced. J. Med. Sci., vol. 10, no. E, pp. 155–160, Jan. 2022, doi: 10.3889/oamjms.2022.7969.

> [7]	A. J. Pitoyo, A. Saputri, R. E. Agustina, and T. Handayani, “Analysis of Determinan of Stunting Prevalence among Stunted Toddlers in Indonesia,” Populasi, vol. 30, no. 1, p. 36, Jun. 2022, doi: 10.22146/jp.75796.

## Business Understanding

Hakikatnya, generasi muda membutuhkan pemahaman mendalam mengenai faktor-faktor yang dapat menyebabkan *stunting* pada anak sebagai bekal penting dalam menghadapi kehidupan mendatang. Generasi Z, sering disebut sebagai anak-anak muda, masih memiliki pengetahuan terbatas mengenai *stunting*. Beberapa mulai menyadari masalah ini karena menjadi perbincangan umum di televisi. Hal ini menjadi motivasi bagi penulis untuk membantu calon orang tua agar lebih memperhatikan aspek gizi anak-anak mereka, termasuk pemahaman tentang faktor-faktor yang dapat memicu *stunting*.

Harapannya dengan adanya pemahaman faktor - faktor tersebut dapat meningkatkan kesejahteraan masyarakat secara menyeluruh dan dapat mengurangi angka kasus *stunting* di kalanagan anak - anak. Hal ini akan memberikan dampak positif pada generasi masa depan untuk meningkatkan kualitas hidup dan membentuk masyarakat yang lebih sehat secara keseluruhan. Selain itu juga, mengurangi tingkat *stunting* dapat berkontribusi pada penurunan beban kesehatan masyarakat dan peningkatan produktivitas di masa mendatang. 

Pemanfaatan teknologi pembelajaran mesin menjadi bagian penting dari solusi ini. Dengan menerapkan teknologi ini, kita dapat menganalisis data yang kompleks terkait stunting pada anak. Pembelajaran mesin membantu dalam memprediksi risiko stunting dan menciptakan sistem yang mendukung orang tua serta tenaga kesehatan. Semua ini diharapkan tidak hanya meningkatkan pemahaman, tetapi juga membantu mengurangi kasus *stunting* sebesar 3,8% setiap tahunnya.

### Problem Statements

Dengan latar belakang permasalahan yang diungkapkan, muncul pertanyaan-pertanyaan yang relevan terkait aspek penting dalam perawatan kehamilan, terutama berkaitan dengan pengaturan pola makan ibu hamil untuk memastikan asupan gizi yang optimal. Beberapa pertanyaan yang diajukan untuk merumuskan pemahaman lebih mendalam melibatkan:
> **Bagaimana hubungan antara pola makan seorang ibu hamil dan risiko stunting pada anak yang dikandungnya?**

> **Apakah ada korelasi antara faktor-faktor terkait gizi dalam makanan ibu hamil dan kemungkinan terjadinya stunting pada anak?**

> **Adakah metode atau langkah-langkah yang dapat diambil untuk memastikan pemenuhan gizi yang optimal selama kehamilan, dengan tujuan mencegah kasus stunting pada anak yang dilahirkan?**

### Goals

Untuk menjawab dari permasalahan sebelumnya, penulis mencoba membuat predictive analysis dengan tujuan atau goals sebagai berikut:
> **Mengidentifikasi dan menganalisis hubungan antara pola makan ibu hamil dengan risiko stunting pada anak yang sedang dikandungnya**

> **Mengetahui korelasi antara faktor-faktor gizi dalam makanan ibu hamil dan potensi terjadinya stunting pada anak yang dilahirkan.**

> **Membuat model predictive analysis yang dapat memprediksi tingkat risiko stunting pada anak berdasarkan faktor-faktor gizi dalam makanan ibu hamil, dengan tingkat akurasi yang tinggi.**

## Data Understanding
Pada kasus ini saya mengarahkan langsung kepada dataset resmi keluaran dari UNICEF yang berisikan data - data yang beririsan dengan kasus stunting. [UNICEF](https://sdmx.data.unicef.org/databrowser/index.html?q=UNICEF:NUTRITION(1.0)).

Didalamnya banyak sekali variabel - variabel yang bisa dipakai namun saya hanya berfokus kedalam beberapa variabel dibawah ini untuk mengetahui scope batasan persebaran datanya.  

### Variabel-variabel pada UNICEF Nutrion dataset adalah sebagai berikut:
- 'REF_AREA:Geographic area' : Merupakan data geografis yang disajikan pada dataset dalam kasus ini area 'Indonesia' menjadi target.
- 'INDICATOR:Indicator' : Merupakan data yang mencakup sejumlah indikator yang beragam terkait dengan status gizi anak, mencakup aspek-aspek seperti pemberian ASI, pertumbuhan fisik, pola makan, dan cakupan suplementasi. Indikator ini melibatkan kategorisasi seperti tingkat stunting, wasting, overweight, serta informasi terkait dengan praktik pemberian makanan dan gizi sejak lahir.
- 'SEX:Sex' : Merupakan data yang mengidentifikasi jenis kelamin individu dan mencakup tiga kategori: 'Male', 'Female', dan 'Total'. Kategori 'Total' mungkin merujuk pada total keseluruhan populasi atau total dari suatu kelompok tertentu.
- 'AGE:Current age' : Merupaan data yang mencerminkan informasi tentang usia individu dalam dataset. Variabel ini dirancang untuk menggambarkan variasi usia di antara subjek data. Analisis terhadap variabel ini dapat memberikan wawasan tentang distribusi usia dalam dataset, memungkinkan identifikasi tren atau pola yang mungkin berkaitan dengan kelompok usia tertentu
- 'WEALTH_QUINTILE:Wealth Quintile' : Merupakan data yang mencakup informasi tentang klasifikasi kekayaan individu atau rumah tangga dalam dataset. Kelompok kekayaan ini dibagi menjadi beberapa kategori atau quintile, mencerminkan tingkat kekayaan yang berbeda.
- 'RESIDENCE:Residence' : Merupakan data yang mencakup informasi tentang lokasi tempat tinggal individu atau rumah tangga dalam dataset. Variabel ini mungkin menggambarkan beragam tipe tempat tinggal atau wilayah geografis tanpa merinci setiap kategori secara spesifik.
- 'MATERNAL_EDU_LVL:Mother\'s Education Level' : Merupakan data yang memuat informasi mengenai tingkat pendidikan ibu dari individu atau anak dalam dataset. Variabel ini mungkin mengelompokkan tingkat pendidikan menjadi beberapa kategori umum.
- 'TIME_PERIOD:Time period' : Merupakan data yang mencakup informasi tentang periode waktu yang terkait dengan data dalam dataset. Variabel ini mungkin mencerminkan rentang waktu atau tanggal pengumpulan data tanpa merinci periode waktu secara spesifik.
- 'OBS_VALUE:Observation Value' : Merupakan data yang memuat informasi tentang nilai observasi yang terkait dengan data dalam dataset. Variabel ini mungkin mencakup beragam nilai dari 0-100.

#### Data Wragling

Dikarenakan hasil dataset yang didapatkan berisikan data yang raw atau kotor. Kita harus mempersiapkan terlebih dahulu agar dataset yang akan kita pakai sudah bersih tahap ini adalah mengolah data yang kotor menjadi bersih.

- Sebelumnya kita akan memuat dataset yang sudah kita peroleh menggunakkan library pandas
![Data Loading](assets/DataLoading.png)
- Setelah dimuat maka terlihat bahwa data yang diperoleh dari UNICEF masih berbentuk kondisi yang tidak kita inginkan, selanjutnya maka kita coba telusuri dengan menggunakan fungsi info().
![Data Info](assets/DataInfo.png)
- Dikarenakan banyaknya feature variabel maka sesuai dengan kondisi di atas, kita hanya akan menggunakan variabel tertentu agar scope yang kita telusuri sesuai dan tida melabar kemana - mana. Dalam penentuan variabel yang akan diekstraksi, saya menggunakan fungsi parameter dari pandas yaitu chunksize yang merupakan kondisi yang paling cocok dari kasus ini dikarenakan dataset kita yang cukup besar dan complex sehingga kita memerlukan potongan - potongan kecil untuk dalam pemrosesan.
![Chunk](assets/Chunk.png)
- Setelah di define menggunakan chunk, selanjutnya kita akan mencoba mengambil variabel yang akan kita pakai sesuai dengan diatas.
![Ekstraksi Kolom](assets/EkstraksiKolom.png)
- Tidak lupa juga karena penggambaran data seperti yang dilihat pada Data Loading sangat berantakan, maka disini saya juga mencoba untuk string manipulation agar terlihat agar rapih. Prosesnya seperti berikut ini
![String Manipulation](assets/StringManipulation.png)
- Maka akan hasilnya seperti ini, terlihat bukan datanya lebih readable?
![Result String](assets/ResultString.png)
- Karena data setelah ekstraksi masih dalam bentuk string, sekarang kita rubah menjadi dataframe agar terlihat perbedaannya
![DataFrame](assets/DataFrame.png)
- Setelah datanya mudah dibaca, sekarang saatnya kita memeriksa apakah dataset yang telah kita bersihkan memiliki nilai duplikat dengan menggunakan fungsi df.duplicated().sum(). Setelah itu melihat apakah data memiliki nilai null dengan fungsi isnull().
![Cek Dataset](assets/CekDataset.png)
![Cek Info Data](assets/CekInfoData.png)
- Berikutnya, kita akan menelusuri lebih jauh terhadap variabel Indicator. Dikarenakan banyak juga feature yang akan diambil maka saya memutuskan untuk mengambil variabel berelevansi atas literatur yang telah dilampirkan pada data diatas. Selebihnya bisa cek pada notebook.
![Indicator Value](assets/DataIndicator.png)
- Selanjutnya kita coba seleksi fitur variabel yang ada pada di Indicator.
![Fitur Seleksi Indicator](assets/SeleksiFitur.png)
- Setelah kita coba seleksi fitur, sekarang kita akan coba gabungkan beberapa tabel lainnya ke dalam dataframe baru.
![Gabungan DataFrame](assets/GabunganDF.png)
![Nutrisi Indonesia](assets/NutriIndo.png)
- Berikutnya, mencari informasi tentang dataset mengenai jumlah baris data,kolom data terhadap DataFrame baru. Saya menggunakan fungsi shape().
![Jumlah Data](assets/JumlahData.png)
- Selanjutnya kita coba manipulasi string kembali terhadap variabel - variabel diatas agar mudah dibaca.
Residence:
![Residence](assets/Residence.png)
Education:
![Education](assets/Pendidikan.png)
Poverty:
![Poverty](assets/Kekayaan.png)
![Datafrane Info Terbaru](assets/DataInfoNew.png)

#### Exploratory Data Analysis and Vizualizations

Pada tahap ini saya mencoba mencari tahu apakah tedapat Outliers pada data yang setelah melakukan aksi yang diatas, serta mencari korelasi yang antar variable, dan juga melakukan coba analisis sederhana yang mencakup Univariate, Bivariate dan Multivariate. 

Sebelum masuk lebih jauh, kita akan mencoba untuk melihat persebaran datanya terlebih dahulu. Dari hasil yang bisa didapatkan bahwa data yang diperoleh pendistribusiannya tidak normal lebih mengarah Right-Skewed or Positive-Skewed. 
![Distribusi Data](assets/DistribusiData.png)
Dari gambar diatas didapati bahwa tidak adanya outliers yang menandakan bahwa data kita tidak masuk ke step khusus untuk menangani outliers. Dilakukan juga Univariate analysis terhadap feature yang ada lebih lengkapnya bisa di cek pada collab EDA

Selanjutnya setelah diketahui distribusi data tidak adanya outliers, maka kita bisa lanjutkan step berikutnya yaitu Bivariate analysis Indicator terhadap Maternal Education. Fokus utamanya terhadap kasus stunting.
![HeatMap Pendidikan](assets/HeatMapPendidikan.png)
Diketahui dari heatmap tersebut bahwa korelasi kasus stunting dipengaruhi oleh beberapa faktor diantaranya Underweight, Wasting, Severve_Wasting, Overweight. Selain itu pemberian ASI pada rentang waktu 12 - 15 Bulan ke bayi mempunyai pengaruh juga terhadap Stunting. Turut serta bepengaruh juga terhadap ASI yang diberikan oleh batita hal ini bisa dilihat pada indikator BMI_Age.
![Bar Chart Pendidikan](assets/BarChartPendidikan.png)
Dari grafik bar diatas juga bahwa Stunting sendiri terjadi di kalangan masyarakat yang tidak mempunyai latar belakang pendidikan yang bagus. Hal ini dikuatkan berdasarkan literatur yang terlampir bahwa seseorang yang memiliki pendidikan yang cukup baik telah diberikan sosialisasi dan pengetahuan mengenai tumbuh kembang anak.

Berikutnya, kita akan mencoba Bivariate analysis Indicator terhadap Poverty_Rating atau kekayaan. Pada analisis kali ini juga didapatkan data bahwa ternyata rata - rata yang mengalami Stunting berada pada masyarakat yang berekonomi rendah. Bisa dilihat pada gambar dibawah:
![Bar Chart Kekayaan](assets/BarChartKekayaan.png)
Dari situ bisa disimpulkan bahwa masyarakat yang berekonomi rendah berpengaruh juga kedalam kasus pendidikan juga Stunting.

## Data Preparation
Sebelum kita masuk ke dalam modeling tentunya ada yang harus dilakukan terlebih dahulu yaitu mengkonversi data yang kita punya kedalam numeric. Tujuannya adalah agar mesin dapat mengenali mengenai data kita, pada laporan proyek ini dibuat saya membuat persebaran data train sebesar 80% dan 20% sebagai data test.

Berikutnya, step yang akan dilakukan adalah melabeli data yang kita punya dengan library bawaan dari sckit-learn yaitu LabelEncoder. LabelEncoder dipilih dikarenakan banyaknya data yang bersifat categorical sehingga akan memudahkan dalam pre-procesing data dalam sekali jalan.
![Label Encoder](assets/LabelEncoder.png)
Pada gambar diatas, feature column data yang telah di pre-processing antara lain Maternal_Education, Indicator, dan sebagainya yang bisa dilihat pada notebook.

Setelah dilakukan pelabelan, selanjutnya kita akan masuk ke dalam Feature Selection. Feature selection dilakukan agar model dari yang kita bangun berasal dari data yang paling penting yang harus ada.
![Feature Selection](assets/FeatureSelection.png)
Pada data diatas terlihat bahwa, variabel 'Indicator', 'Gender', 'Maternal_Education' memiliki fitur yang penting untuk permodelan. Oleh karena itu, maka feature selection yang dipilih adalah semua hal yang berkaitan dengan 'Indicator'.

Selepas telah mengetahui fitur mana yang penting untuk di masukkan, sekarang saatnya menyiapkan data untuk digunakan terhadap model yang akan dibuat seperti yang telah saya bicarakan diatas bahwa data yang saya siapkan meliputi 80% data train dan 20% data test.
![Pembagian Data](assets/PembagianData.png)

## Modeling
Modeling merupakan tahap yang akan menentukan apakah pembelajaran mesin ini dapat memberikan hasil prediksi yang baik. Dalam kasus Stunting ini saya menggunakan 5 Algoritma, yaitu:
1. Linear Regression
   ![Linear Regression](assets/LinearRegression.png)
2. Decision Tree Regression
   ![Decision Tree Regression](assets/DecisionTreeRegres.png)
3. Random Forest Regression
   ![Random Forest Regression](assets/RandomForestRegress.png)
4. Support Vector Regression
   ![SVR](assets/SVR.png)
5. Gradient Boosting Regression
   ![Gradient Boosting Regression](assets/GradientBoost.png)

## Evaluation
Setelah model dilakukan pelatihan, adapun metrik evaluasi yang akan saya gunakan pada kasus Stunting ini adalah MAE, MSE. Serta ada tambahan aksi yaitu menentukan r2_score agar kita bisa lebih dapat memahami berapa ukuran sebuah metrik akurasi. Berikut hasil MAE, MSE kelima model yang sudah di evaluasi:
![Alt text](assets/MAExMSE.png)
Dari gambar diatas dapat disimpulkan bahwa kandidat terkuat dimiliki oleh algoritma Random Forest Regression and Gradient Boosting Regression. Indikator dikatakan model yang dihasilkan merupakan pilihan terbaik dikarenakan MAE serta MSE nya paling kecil diantara lainnya dikatakan jika MAE serta MSE didapati valuenya kecil maka bisa dikatakan model yang mempunyai performa yang bagus. Selanjutnya untuk penambahan aksi yang biasanya bertemu dengan metrik akurasi, disini saya menggunakan r2_score agar bisa mendapatkan nilai yang bisa dipahami oleh beberapa mayoritas, berikut hasil setelah dilakukannya r2_score:
![R-Squared](assets/R-Squared.png)
Hasil yang didapati mulai terlihat bahwa model terbaik dimiliki oleh algoritma Random Forest Regression and Gradient Boosting Regression karena nilai yang dihasilkan cukup identik. Namun jika bener - bener ditentukan mana yang terbaik yaitu Gradient Boosting Regression.
Berikutnya, kita akan mencoba visualisasi hasil dari evaluasi yang kita lakukan agar semuanya terjasi dalam bentuk informasi.
![Evaluasi Model Terbaik](assets/EvaluteModel.png)

Sekian laporan yang bisa saya sajikan, dari keseluruhan proses yang dilakukan pertanyaan yang dilontarkan pada problem statement telah terjawab.
