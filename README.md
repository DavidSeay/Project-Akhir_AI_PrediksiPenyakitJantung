**Heart Disease Detection Using AI**

**Daftar Anggota**
  - 71220832 Yehezkiel Satya Nugroho <br />
  - 71220853 Matthew Alexander <br />
  - 71220909 David Delon Seay 

**Penjelasan singkat**
<br /> Aplikasi Heart Disease Detection yang kami buat menggunakan Artificial Intelligence (AI). Data yang kami gunakan merupakan data sekunder dari Kaggle. Data tersebut kami visualisasikan dalam bentuk Bar Plot. Implementasi model yang kami gunakan adalah model Klasifikasi dan menggunakan algoritma Logistic Regression.
Aplikasi ini kami buat untuk Orang yang rentan terhadap penyakit jantung untuk menghadapi masalah meningkatnya kasus penyakit jantung pada usia muda. Aplikasi tersebut digunakan ketika  pasien mengalami gejala-gejala penyakit jantung tetapi tidak mengetahui secarapasti apakah gejala yang di alami adalah tanda-tanda penyakit jantung. Dengan harapan, sistem AI ini dapat membantu mendeteksi penyakit dengan lebih cepat sehingga memungkinkan perawatan yang lebih awal dan meningkatkan peluang penyembuhan.

**Data Dictionary**
<br />Data Dictionary 
age: age in years
sex: sex
1 = male
0 = female
cp: chest pain type
Value 0: typical angina
Value 1: atypical angina
Value 2: non-anginal pain
Value 3: asymptomatic
trestbps: resting blood pressure (in mm Hg on admission to the hospital)
chol: serum cholestoral in mg/dl
fbs: (fasting blood sugar > 120 mg/dl)
1 = true;
0 = false
restecg: resting electrocardiographic results
Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach: maximum heart rate achieved
exang: exercise induced angina
1 = yes
0 = no
oldpeak = ST depression induced by exercise relative to rest
slope: the slope of the peak exercise ST segment
Value 0: upsloping
Value 1: flat
Value 2: downsloping
ca: number of major vessels (0-3) colored by flourosopy
thal:
0 = error (in the original dataset 0 maps to NaN's)
1 = fixed defect
2 = normal
3 = reversable defect
target (the lable):
0 = no disease,
1 = disease


**Eksplorasi Data** <br />
13 Parameter/Feature - Input
  - Umur = Numerik
  - Jenis Kelamin = Categorical
  - Jenis Nyeri Dada = Categorical
  - Tekanan Darah = Numerik
  - Nilai Kolesterol = Numerik
  - Gula Darah = Categorical
  - Hasil Elektrokadriografi
  - Detak Jantung Maximum = Numerik
  - Induksi Agina = Categorical
  - ST Deperesion = Numerik
  - Slope = Categorical
  - Nilai CA = Numerik
  - Nilai Thal = Categorical

1 Target - Output<br />
  Kondisi (Berupa 0 atau 1)
  0 adalah Tidak Terkena Penyakit Jantung dan 1 adalah Terkena Penyakit Jantung
  
**Modelling Logistic Regression** <br />
Algoritma tersebut kami gunakan karena cocok untuk melakukan pemodelan antara variabel dependen binary (Outcome yang berupa 0 atau 1) dengan beberapa variabel independen (13 parameter) <br />
