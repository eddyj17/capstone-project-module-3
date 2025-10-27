# capstone-project-module-3
Capstone Project Module 3 - Bank Marketing Campaign

Dalam github link ini terdapat 2 file yang perlu di download agar model dapat berjalan dengan baik.
1. Module 3 Capstone Project Bank Marketing Campaign.ipynb (Jupyter Notebook File)
2. Gradient_Boosting_pipeline.pkl (Pickle File)

Project Introduction:

### Business Problem ###

Context

Sebuah bank ingin meluncurkan produk finansial baru dengan menggunakan strategi baru marketing campaign. Salah satu produk finansial yang akan dluncurkan berupa term-deposit (atau yang kita kenal sebagai deposito). Deposito tersebut berupa produk yang memberikan bunga (fix interest) yang akan dibayarkan pada tempo-tempo tertentu dengan bunga yang berbeda-beda berdasarkan jangka waktu tempo yang ditetapkan.

Bank tersebut ingin menganalisa data-data yang terkumpul sewaktu berlangsungnya marketing campaign dan ingin memfokuskan target-target customer berdasarkan profil dan marketing data yang di collect dari campaign tersebut. Sehingga dengan adanya analisa tambahan terserbut diharapkan biaya marketing akan bisa lebih ditekan dengan fokus terhadap demographic target customernya.

Target:
- 0 : Tidak membuka Deposito
- 1 : Membuka Deposito


Problem Statement:

Biaya untuk marketing campaign adalah suatu resources yang terbatas, tentu bank ingin meningkatkan efisiensi dalam pembiayaan ke demographic calon-calon customer yang berpotensi membuka deposito. Jika tanpa melakukan perdiksi dengan machine learning dan biaya marketing campaign di gunakan tanpa sasaran yang jelas, maka resources terbatas tersebut akan terbuang dengan percuma.

Goals:

Untuk mengatasi masalah tersebut, bank ingin memiliki kemampuan untuk memperediksi sektor-sektor atau sasaran mana yang jelas dimana biaya marketing campaign akan diinvestikasikan.

Sektor-sektor / Sasaran calon potensi customer yang akan membuka deposito (term deposits) dapat lihat profil customer eg. age (umur), job (pekerjaan), balance (saldo tabungan), housing (memiliki rumah), loan (adanya pinjaman). 

Diharapkan juga Marketing data yang dicollect dari campaign ini juga dapat membantu machine learning algorithm untuk mengidentifikasikan pola dan melakukan prediksi. Data-data tersebut antara lain: contact (tipe kontak), month (bulan kontak terakhir), campaign (jumlah kontak yang dilakukan terhadap customer tersebut), pdays (jumlah hari dari kontak terakhir), poutcome (previous outcome - hasil dari marketing campaign sebelumnya), deposit (pembukaan deposito).

Analytic Approach:

Project ini akan terbagi dalam tahap-tahap berikut:
- Load & Explore Data
- Data Understanding
- Data Cleaning (EDA)
- Split Train/Test
- Preprocessing
- Modelling
- Evaluation
- Hyperparameter Tuning
- Confusion Matrix
- Feature Importance
- Model Deployment

Sangat diharapkan model yang telah dibuat dapat meminimalisasi False Positive (Menekan biaya marketing yang terbuang sia-sia) dan False Negative (Kehilangan sumber deposito). Metric yang akan digunakan antara lain roc_auc/ pr_auc.



