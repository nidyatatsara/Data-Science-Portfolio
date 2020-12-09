# Data-Science-Portfolio
Repository containing portfolio of data science projects completed by me for self learning and hobby purposes. It is updated regularly. The projects is written in Python (Jupyter Notebook). 

# Contents:
## Prediksi Churn di Perusahaan Telekomunikasi (Indonesia)
Churn merupakan dampak dari persaingan di dunia bisnis telekomunikasi. Churn adalah keadaan dimana seorang pelanggan berpindah dari suatu provider ke provider lainnya. Semakin tinggi tingkat churn maka pendapat perusahaan akan semakin kecil di masa depan. Oleh sebab itu, perusahaan telco berupaya untuk mencegah pelanggan mereka untuk churn dengan meningkatkan loyalitas pelanggan melalui Customer Relationship Management (CRM) dan prediksi churn.

Prediksi churn bertujuan untuk memprediksikan peluang seorang pelanggan untuk churn sebelum pelanggan tersebut benar-benar churn sehingga dapat dilakukan upaya seperti pemberian diskon atau peningkatan kepuasan pelanggan untuk meminimalisir kemungkinan churn. Riset pemasaran menunjukkan bahwa rata-rata nilai pelanggan yang churn adalah sekitar 2,2% per bulan. Keadaan ini mendorong perusahaan telekomunikasi untuk menambah biaya pemasaran guna mendapatkan pelaggan baru. Dimana biaya tersebut lebih tinggi dibandingkan dengan mempertahankan pelanggan lama.

Klasifikasi merupakan salah satu bagian dari supervised machine learning yang paling sering digunakan untuk memprediksikan data kategori. Data churn merupakan data kategorik (binary) oleh sebab itu untuk memprediksikan churn digunakan algoritma machine learning klasifikasi.

Dataset yang digunakan adalah data sebuah perusahaan telekommunikasi. Penjelasan dari variabel-variabel tersebut adalah sebagai berikut:
* __UpdatedAt__ : periode pengambilan data
* __customerID__ : ID pelanggan
* __gender__ : jenis kelamin (Male, Female)
* __SeniorCitizen__ : pelanggan berusia lebih dari 60 thn / pensiunan (1,0)
* __Partner__ : pelanggan memiliki pasangan (Yes, No)
* __Dependents__ : pelanggan memiliki tanggungan (Yes, No)
* __tenure__ : lamanya pelanggan berlangganan (month)
* __PhoneService__ : pelanggan memakai layanan telepon (Yes, No)
* __MultipleLines__ : pelanggan memakai layanan multiple lines (Yes, No, No phone service)
* __InternetService__ : penyedia layanan internet pelanggan (DSL, Fiber optic, No)
* __OnlineSecurity__ : pelanggan memakai layanan online security (Yes, No, No internet service)
* __OnlineBackup__ : pelanggan memakai layanan online backup (Yes, No, No internet service)
* __DeviceProtection__ : pelanggan memakai layanan device protection (Yes, No, No internet service)
* __TechSupport__ : pelanggan memakai layanan tech support (Yes, No, No internet service)
* __StreamingTV__ : pelanggan memakai layanan streaming TV (Yes, No, No internet service)
* __StreamingMovies__ : pelanggan memakai layanan streamming movies (Yes, No, No internet service)
* __Contract__ : kontrak pelanggan (Month-to-month, One year, Two year)
* __PaperlessBilling__ : pelanggan menggunakan paperless billling (Yes, No)
* __PaymentMethod__ : metode pembayaran (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* __MonthlyCharges__ : tagihan bulanan
* __TotalCharges__ : total tagihan
* __Churn__ : berhenti berlangganan (Yes, No)
