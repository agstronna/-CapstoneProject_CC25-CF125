# TrashGu: Teknologi Cerdas untuk Identifikasi dan Klasifikasi Sampah Melalui Citra Digital

https://github.com/user-attachments/assets/29156258-d873-44fd-8e49-24d00904bf1b

# ♻️ Deskripsi TrashGu
TrashGu adalah aplikasi berbasis machine learning yang dapat mengklasifikasikan gambar sampah ke dalam beberapa kategori seperti organik, anorganik, dan residu berdasarkan 10 jenis sampah. Proyek ini bertujuan untuk membantu pengelolaan sampah dengan meningkatkan kesadaran masyarakat akan pentingnya memilah sampah. Selain itu, proyek ini juga menyediakan edukasi mengenai cara pengelolaan sampah yang baik dan benar.


# 🚀 Fitur Utama

1. Mengklasifikasikan sampah hanya dari gambar.
2. Model machine learning yang dilatih dengan dataset seimbang.
3. Antarmuka *user friendly* berbasis web.


# 🛠️ Teknologi yang Digunakan

- **Front-End**: HTML5, CSS3, Tailwind CSS, Webpack, dan JavaScript.
- **Back-End**: Flask, SQLite, dan Postman.
- **Machine Learning**: Python, Keras, Pandas, Numpy, Scikit-Learn, Matplotlib, dan Tensorflow.
- **Tools**: Visual Studio Code (IDE) dan Google Colab (training model).
- **Version Control**: GitHub.


# Dataset

Pada proyek ini, kami menggunakan tiga dataset klasifikasi sampah dari Kaggle yang memiliki kelas kategori yang sama, yaitu:

1. [Garbage Classification by Mostafa Abla](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)  
2. [Garbage Classification V2 by Sumn2u](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2)
3. [DSA_tugas_akhir](https://github.com/fannyahdita/DSA_tugas_akhir/)

Dataset ini kemudian **digabungkan** menjadi satu dataset yang lebih besar untuk meningkatkan variasi data dan performa model klasifikasi.

# Akses Website TrashGu

Website dapat di akses melalui tautan berikut:
[Website TrashGu](https://trash_gu.ivanrajwa.my.id/)

## Cara Penggunaan

### Cara Menjalankan Dashboard di Streamlit:

1. Install semua library yang diperlukan: Menggunakan pip install untuk menginstal library yang diperlukan. Anda bisa melakukannya secara manual:
`pip install numpy pandas matplotlib seaborn streamlit babel`
Atau menggunakan requirements.txt untuk menginstal semua library yang tercantum di dalamnya:
`pip install -r requirements.txt`
2. Masuk ke folder Dashbord: Mengubah direktori kerja ke folder dashboard tempat file dashboard.py berada:
`cd Trashgu-streamlit`
3. Jalankan file app.py dengan Streamlit: Menjalankan aplikasi dashboard menggunakan Streamlit dengan perintah:
`streamlit run app.py`


### Cara Menjalankan CapstoneTrashGu di Lokal:
### 1. Clone Repository

bash
git clone https://github.com/viapiyaaa/Capstone_CC25_CF125.git
cd trashguCapstone

### 2. Jalankan Backend (Flask API)

#### a. Masuk ke folder backend

bash
cd backend

#### b. Install dependensi backend

bash
pip install -r requirements.txt


#### c. Jalankan aplikasi Flask

bash
python app.py

Pastikan port yang digunakan cocok dengan konfigurasi CORS di app.py.

### 3. Jalankan Frontend (Vite/React + Tailwind)

#### a. Masuk ke folder frontend/src

bash
cd ../frontend/src

#### b. Install dependensi frontend

bash
npm install

#### c. Jalankan aplikasi frontend

bash
npm run dev

### 4. Akses Aplikasi

Setelah semua server berjalan:

* *Frontend:* http://localhost:57304 (saat development)
* *Backend API:* http://localhost:5000 *(atau sesuai yang diset di app.py)*

# Pengembang
Coding Camp 2025 Team CC25-CF125 
1. [Agistia Ronna Aniqa](https://www.linkedin.com/in/agistiaronna/) - MC299D5X1601 - Machine Learning
2. [Evi Afiyatus Solihah](https://www.linkedin.com/in/eviafiyatussolihah/) - MC299D5X1752 - Machine Learning
3. [Rahmah Fauziah](https://www.linkedin.com/in/rahmahf/) - MC299D5X1751 - Machine Learning
4. [Fajar Anugrah](https://www.linkedin.com/in/fajaranugrah29/) - FC265D5Y1786 - Front-End & Back-End
5. [M.Reza Pahlevi](http://www.linkedin.com/in/m-reza-pahlevi-26a21b255) - FC265D5Y1103 - Front-End & Back-End
6. [Pebri Andika](https://www.linkedin.com/in/pebri-andika-40386a356) - FC265D5Y1796 - Front-End & Back-End
