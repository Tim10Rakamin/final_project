# Final Project Tim 10 Rakamin Data Science Batch 25

Code Python ini digunakan untuk mengolah Banking Dataset yang berasal dari website KAGGLE
https://www.kaggle.com/code/santhoshtsk/banking-dataset-analysis-and-prediction/data

### Summary Insights Stage 3
Berdasarkan exploratory data analysis dan yang telah dilakukan bahwa dapat direkomendasi hal-hal terkait strategi bisnis yang dapat dijalankan yaitu berupa :
1. Stage 3 kami melakukan beberapa langkah untuk dataset kami. Kami memisahkan data training dengan komposisi 70% untuk data training dan 30% data testing
2. Kami juga membuat modeling dengan berbagai macam metode/model Machine Learning seperti Gradient Boosting Classifier, Random Forest Classifier, Logistic Regression, XGBClassifier, Extra Trees Classifier, Linear SVC, KNeighbors Classifier, Gaussian NB, Decision Tree Classifier, SVC.
3. Dari semua model yang sudah diuji kelompok kami memilih model Machine Learning Logistic Regression dengan pertimbangan model ini cocok untuk memprediksi data dengan tipe categorical. Untuk perhitungan  accuracy model ini juga baik dalam memprediksi data training dan data testing dengan gap nilai paling kecil yaitu 0,002812 dari ketiga model Machine Learning teratas dan nilai Precission, Recal dan AUC cukup bagus.
4. kami juga melakukan tuning hyperparameter, akan tetapi kesimpulan Hyperparameter Tuning tidak meningkatkan performa model Machine Learning dikarenakan data target yang diprediksi oleh model masih banyak yang tidak sesuai.
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