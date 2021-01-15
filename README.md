# titanic-prediction
Kaggle: Titanic - Machine Learning from Disaster (https://www.kaggle.com/c/titanic/overview)

Data ini berisi 12 variabel, termasuk di dalamnya adalah variabel personal seperti id dan nama, serta variabel target berupa "Survived" (bernilai 0 dan 1).
Tujuan yang ingin dicapai adalah memprediksi penumpang mana yang selamat (Survived = 1) dan penumpang mana saja yang tidak selamat (Survived = 0) dalam peristiwa kapal Titanic berdasarkan fitur yang ada.

Langkah-langkah yang saya lakukan adalah sebagai berikut:

1. Import library dasar yang diperlukan
2. Import dataset
3. Exploratory Data Analysis (EDA)
4. Feature Selection dengan menghapus beberapa fitur
5. Feature Engineering yaitu mengatasi missing value, mengatasi variabel kategorik, dan melakukan penskalaan data
6. Modelling dengan menggunakan K-Nearest Neighbors (K-NN) sekaligus evalusi model menggunakan nilai akurasi. Akan ada perbandingan beberapa model juga di sini

Terdapat artikel yang saya buat: https://wandalistathea.medium.com/prediksi-ketahanan-hidup-penumpang-kapal-titanic-menggunakan-k-nn-python-74862d03cd46

Score submission di Kaggle: 0.71531
