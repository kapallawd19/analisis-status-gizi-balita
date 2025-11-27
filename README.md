# analisis-status-gizi-balita
Proyek analisis data balita menggunakan machine learning untuk memprediksi status gizi.
# Analisis Status Gizi Balita Menggunakan Machine Learning

Proyek ini bertujuan untuk menganalisis data balita berdasarkan umur, jenis kelamin, dan tinggi badan untuk menentukan status gizi menggunakan metode klasifikasi machine learning.

#Tujuan Penelitian
- Menganalisis pola status gizi balita.
- Mengidentifikasi faktor yang berpengaruh pada status gizi.
- Membangun model prediksi status gizi menggunakan Random Forest.
- Menyediakan insight untuk pemantauan tumbuh kembang anak.
- Menjadi portofolio data analysis yang profesional.

#Dataset
Dataset berisi:
- Umur (bulan)
- Jenis Kelamin
- Tinggi Badan (cm)
- Status Gizi (label)

#Tools & Library
- Python
- Pandas
- Matplotlib
- Scikit-Learn
- Google Colab / Jupyter Notebook

#Tahapan Proyek
1. Import data
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Modeling (Random Forest Classifier)
5. Evaluasi model
6. Visualisasi insight

#Cara Menjalankan
Upload file `data_balita.csv` ke Google Colab lalu jalankan script di notebook:

```python
df = pd.read_csv('data_balita.csv')
