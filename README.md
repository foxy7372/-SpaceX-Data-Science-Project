# -SpaceX-Data-Science-Project
Data Analysis and Prediction of Falcon 9 Rocket Landings using Python, SQL, and Machine Learning (IBM Data Science Capstone Project).

## 📋 Overview
Proyek ini bertujuan untuk memprediksi apakah roket Falcon 9 tahap pertama akan mendarat dengan sukses. SpaceX menghemat jutaan dolar dengan menggunakan kembali roket mereka; dengan memprediksi keberhasilan pendaratan, kita dapat menentukan biaya peluncuran dan memberikan wawasan kompetitif bagi perusahaan peluncuran roket alternatif.

## 🛠️ Tech Stack & Tools
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly Dash
- **Database:** SQL (SQLite)
- **Machine Learning:** Scikit-Learn (Logistic Regression, SVM, Decision Tree, KNN)
- **Environment:** Jupyter Notebook, GitHub

## 📊 Methodology

### 1. Data Acquisition & Wrangling
Ekstraksi data menggunakan **SpaceX API** dan teknik **Web Scraping** dari Wikipedia. Data dibersihkan (handling missing values) dan dikonversi menjadi format yang siap untuk analisis.

### 2. Exploratory Data Analysis (EDA)
- **SQL Analysis:** Menjalankan query kompleks untuk memahami hubungan antara lokasi peluncuran, berat muatan (payload), dan tingkat keberhasilan.
- **Data Visualization:** Menggunakan Seaborn dan Matplotlib untuk mengidentifikasi tren keberhasilan seiring bertambahnya jumlah penerbangan (Flight Number).

### 3. Interactive Visual Analytics
- **Folium:** Membangun peta interaktif untuk menganalisis kedekatan lokasi peluncuran dengan garis pantai dan jalur pendaratan.
- **Plotly Dash:** Membuat dashboard interaktif untuk memfilter data secara real-time berdasarkan lokasi dan berat muatan.

### 4. Predictive Modeling (Machine Learning)
Membangun dan membandingkan beberapa model klasifikasi. Menggunakan **GridSearchCV** untuk optimasi hyperparameter guna mendapatkan akurasi terbaik.

## 📈 Key Insights
- **Teknologi Matang:** Tingkat keberhasilan pendaratan meningkat secara signifikan pada misi-misi terbaru (Falcon 9 Block 5).
- **Fitur Krusial:** Kehadiran 'Grid Fins' dan 'Legs' adalah prediktor terkuat untuk keberhasilan pendaratan.
- **Lokasi Strategis:** Semua lokasi peluncuran utama berada di dekat pesisir untuk memfasilitasi pendaratan di *Drone Ship*.

## 🏆 Model Performance
| Model | Accuracy |
| :--- | :--- |
| **Decision Tree** | **83%** |
| Logistic Regression | 82% |
| SVM | 82% |
| KNN | 80% |

## 📂 Project Structure
- `SpaceX_Professional_Analysis.ipynb`: Jupyter Notebook utama berisi seluruh pipeline kode.
- `SpaceX_Presentation.pdf`: Laporan akhir proyek dalam format presentasi.
- `interactive_map.html`: Hasil visualisasi peta interaktif.

---
**Author:** [DimasMH]  
**Connect with me:** [www.linkedin.com/in/dimas-mutsaqoful-hidayat-1695bb356]
