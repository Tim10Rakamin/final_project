# Final Project Tim 10 Rakamin Data Science Batch 25

Code Python ini digunakan untuk mengolah Banking Dataset yang berasal dari website KAGGLE
https://www.kaggle.com/code/santhoshtsk/banking-dataset-analysis-and-prediction/data

### Summary Insights Stage 2
Berdasarkan Data Prepareation yang telah dilakukan bahwa kami mengindentifikasi berbagai hal berikut:
1. Outliers pada dataset dibersihkan menggunakan metode Z-Score. Penggunaan Z-Score dipilih dengan pertimbangan bahwa metode ini masih mempertahankan sebagian besar data dan hanya melakukan drop outliers pada value yang dilakukan handling.
2. Berdasarkan value Counting categorical sebelumnya pada stage 1 didapatkan bahwa terdapat feature yang memiliki value unknown yaitu feature Job, Education, Contact, dan poutcome sehingga perlu dilakukan drop pada unknown value tersebut dikarenakan unknown value menyebabkan dataset yang dimiliki menjadi bias dan tidak mewakili scope category yang ada pada suatu features. Sehingga dapat dipertimbangkan bahwa unknown value tersebut dapat di-drop sehingga dapat menyisihkan dataset yang bersih.
3. Kami menggunakan 2 Feature Encoding, yaitu Label Encoding untuk mengubah menjadi feature numerical dan One Hot Encoding untuk mengubah menjadi feature kategorik.
4. Berdasarkan Feature Correlation dan divisualisasikan melalui heatmap didapatkan bahwa hampir keseluruhan feature memiliki korelasi < 0,70. Hanya pada 2 feature yaitu marital_married & marital single memiliki korelasi 0,79 dan contact_cellular & contact_telephone memiliki korelasi 1.00
5. Kami juga menemukan bahwa Hasil output yang ditunjukkan melalui sebaran pada target menunjukkan hasil yang imbalance karena jumlah user yang membuka dan tidak membuka deposito berbeda signifikan, sehingga hal tersebut dapat mempengaruhi proses pembuatan model. Hkami menggnakan metide F1-Score dan K-fold



### Tim 10 
1. Novia Hananingrum
2. Ciptya Rahma A
3. Cakra Tri
4. Izzaudin Afif
5. Jully Ermisa
6. Hafiidh Alfian
7. Mufti Ikhsan Kamil
8. Yuda Arifianto