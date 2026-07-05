# Machine Predictive Maintenance Classification
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

Proyek ini merupakan pemenuhan tugas besar mata kuliah Dasar Ilmu Data yang bertujuan untuk membangun aplikasi machine learning berbasis web untuk melakukan klasifikasi potensi kegagalan mesin terhadap dataset **Predictive Maintenance**.

## Deskripsi Proyek
Tujuan utama dari proyek ini adalah memprediksi apakah sebuah mesin berpotensi mengalami kegagalan (*failure*) beroperasi berdasarkan parameter sensornya. Analisis ini sangat krusial bagi industri manufaktur dalam merencanakan pemeliharaan preventif dan meminimalisir *downtime* mesin.

Dalam proyek ini, kami melakukan:
- **Pra-pemrosesan Data**: Pembersihan, penanganan data yang hilang (*missing values*), dan *encoding* variabel.
- **Seleksi Fitur**: Memilih variabel sensor paling relevan untuk meningkatkan akurasi model.
- **Pemodelan**: Implementasi dan komparasi 4 metode machine learning untuk mendapatkan performa terbaik.
- **Optimasi Hyperparameter**: Melakukan *tuning* pada model untuk memaksimalkan hasil prediksi.
- **Deployment**: Integrasi model ke dalam aplikasi berbasis web untuk kemudahan penggunaan.

## Model Machine Learning
Dalam proyek ini, kami membandingkan performa dari 4 algoritma klasifikasi:
* **Random Forest (RF)**
* **k-Nearest Neighbors (k-NN)**
* **Support Vector Machine (SVM)**
* **Decision Tree (DT)**

## Teknologi yang Digunakan
* **Bahasa**: Python
* **Lingkungan Kerja**: Jupyter Notebook
* **Library ML**: Scikit-learn, Pandas, NumPy
* **Web Framework**: Streamlit
* **Dataset**: predictive_maintenance.csv
