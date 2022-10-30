# Final Project Tim 10 Rakamin Data Science Batch 25

Code Python ini digunakan untuk mengolah Banking Dataset yang berasal dari website KAGGLE
https://www.kaggle.com/code/santhoshtsk/banking-dataset-analysis-and-prediction/data

### Summary Insights Stage 3
Berdasarkan exploratory data analysis dan yang telah dilakukan bahwa dapat direkomendasi hal-hal terkait strategi bisnis yang dapat dijalankan yaitu berupa :
1. Stage 3 kami melakukan beberapa langkah untuk dataset kami. Kami memisahkan data training dengan komposisi 70% untuk data training dan 30% data testing
2. Kami juga membuat modeling dengan berbagai macam metode/model Machine Learning seperti Gradient Boosting Classifier, Random Forest Classifier, Logistic Regression, XGBClassifier, Extra Trees Classifier, Linear SVC, KNeighbors Classifier, Gaussian NB, Decision Tree Classifier, SVC.
3. Dari semua model yang sudah diuji coba diperoleh hasil modeling yang paling baik dengan urutan pertama yaitu Gradient Boosting Classifier, Random Forest Classifier diurutan kedua dan Logistic Regression diurutan ketiga. Dari tiga urutan diatas kelompok kami memilih model Machine Learning GradientBoostingClassifier dengan pertimbangan model ini cocok sesuai hasil accuracy train dan test yang mendekati satu sama lain. Untuk perhitungan  accuracy model ini juga baik dalam memprediksi data training dan data testing dengan gap nilai paling kecil yaitu 0,002119 dari hasil accuracy training - accuracy test.
4. Setelah melewati tahap pemilihan model Machine Learning yang akan digunakan, tahap selanjutnya adalah tahap Hyperparameter Tuning metode yang digunakan adalah dengan Grid Search CV. Dari Classification Report dapat dilihat seperti gambar diatas terdapat penurunan score untuk precision, recall dan f1-score dari data y_training kepada data y_test.
5. Dari hasil model Machine Learning akurasi data training sebesar 0,8596% dan data testing sebesar 0,8496%. Dari percobaan kedua data diatas dapat disimpulkan model Machine Learning memiliki accuracy memprediksi data training dan testing yang bagus dikarenakan gap accuracy antara kedua data tersebut sangat kecil.


### Tim 10 
1. Novia Hananingrum
2. Ciptya Rahma A
3. Cakra Tri
4. Izzaudin Afif
5. Jully Ermisa
6. Hafiidh Alfian
7. Mufti Ikhsan Kamil
8. Yuda Arifianto