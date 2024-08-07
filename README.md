## About This Project

Saya membuat proyek dashboard data analysis e-commerce dengan menggunakan streamlit dan beberapa library seperti : numpy pandas scipy matplotlib seaborn jupyter streamlit babel. Berikut beberapa step untuk menjalankan project ini.

## Melakukan unduh dataset

Untuk Dataset dan juga Data Dashboard dapat diunduh melalui link berikut

https://drive.google.com/drive/folders/1t8w9KRzC1TDFxZb8b9n1NwqsG8p46-WM?usp=sharing


## Melakukan setup environment

#### Pastikan sudah menginstall conda terlebih dahulu, untuk mengeceknya bisa mengetikkan 

conda --version (di terminal), saya sendiri saat ini menggunakan conda 23.7.4

conda create --name main-ds python=3.11
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

## Run steamlit app
Berikutnya untuk proses menjalankan dashboard di file dashboard.py

cd Dahboard
streamlit run Dashboard.py

## Melihat dashboard yang sudah di jalankan
Dashboard dapat dilihat melalui halaman berikut >> http://192.168.1.7:8501/
atau untuk local host di http://localhost:8501/#
