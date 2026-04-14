##🚖 NYC Yellow Taxi Trip Data Analysis

📌 Project Overview
Project ini bertujuan untuk melakukan analisis data perjalanan taksi NYC (Yellow Taxi) guna mengidentifikasi pola perjalanan, distribusi tarif, serta insight penting yang dapat digunakan untuk pengambilan keputusan berbasis data.
Analisis dilakukan menggunakan pendekatan:
1.Exploratory Data Analysis (EDA)
2.Data Preprocessing & Cleaning
3.Machine Learning (Clustering & Classification)


🎯 Objectives
1.Memahami karakteristik dataset perjalanan taksi
2.Mengidentifikasi pola distribusi jarak dan tarif perjalanan
3.Mendeteksi outlier dalam data
4.Mengelompokkan data menggunakan K-Means Clustering
5.Membangun model klasifikasi menggunakan Decision Tree

📊 Dataset Information
Dataset yang digunakan merupakan NYC Yellow Taxi Trip Records, yang berisi informasi seperti:
1.Pickup & Dropoff datetime
2.Trip distance
3.Passenger count
4.Fare amount
5.Payment type

⚙️ Project Workflow
1. Data Collection
Dataset diambil dari platform Kaggle
2. Data Preprocessing
Handling missing values
Filtering data tidak valid
Data type conversion
3. Exploratory Data Analysis (EDA)
Analisis distribusi data
Identifikasi pola dan anomali
Visualisasi menggunakan histogram, boxplot, dan density plot
4. Outlier Detection
Menggunakan boxplot untuk mendeteksi nilai ekstrem
5. Data Normalization
Scaling data untuk kebutuhan modeling
6. Machine Learning
K-Means Clustering untuk segmentasi data
Decision Tree untuk klasifikasi

📈 Data Visualization
1.Distribution of Trip Distance
2.Boxplot Trip Distance (Outlier Detection)
3.Fare Amount Distribution

🔍 Key Insights
1.Sebagian besar perjalanan memiliki jarak pendek (short-distance trips)
2.Terdapat outlier signifikan pada trip distance dan fare amount
3.Distribusi fare menunjukkan skewness (tidak merata)
4.Pola perjalanan menunjukkan potensi segmentasi pelanggan berdasarkan jarak & tarif

🧠 Technologies Used
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Scikit-learn
-Google Colab

📁 Project Structure
data-analysis-yellow-taxi-trip-record-NYC/
│
├── notebook/
│   └── analysis.ipynb
├── images/
│   ├── histogram_trip_distance.png
│   ├── boxplot_trip_distance.png
│   └── density_fare_amount.png
├── dataset/
├── README.md

🚀 Conclusion
Project ini berhasil menunjukkan bagaimana data perjalanan taksi dapat dianalisis untuk:
-Menemukan pola penggunaan
-Mengidentifikasi anomali data
-Mengelompokkan data berdasarkan karakteristik tertentu
Analisis ini dapat dikembangkan lebih lanjut untuk kebutuhan:
-Prediksi tarif
-Optimasi rute perjalanan
-Sistem rekomendasi transportasi

💼 Author
Muhammad Alvin Maulana
Mahasiswa Sistem Informasi | Data Analysis Enthusiast
