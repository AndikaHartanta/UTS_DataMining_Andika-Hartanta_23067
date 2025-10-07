# 🚗 Used Cars Price Prediction - UTS Data Mining

Proyek ini dibuat untuk **UTS Praktikum Data Mining** oleh **Andika Hartanta - 5A Informatika**.  
Tujuan proyek ini adalah untuk melakukan **analisis dan prediksi harga mobil bekas** berdasarkan berbagai fitur seperti tahun produksi, jarak tempuh, kapasitas mesin, jenis bahan bakar, dan lainnya.

---

## 🧾 Deskripsi Singkat

Dataset yang digunakan adalah **Used Cars Price Prediction**.  
Seluruh tahapan analisis dilakukan menggunakan **Google Colab** dengan library *pandas*, *numpy*, *matplotlib*, *seaborn*, dan *scikit-learn*.

Berikut ringkasan tahapan utama proyek saya ini:

---

### 1. 🧮 Data Profiling dan Preparation
- Memuat dataset dan melihat struktur datanya menggunakan `.info()` dan `.describe()`
- Mengecek jumlah data, tipe data, serta nilai *missing*
- Menangani nilai kosong (*null values*) dengan mengganti menggunakan nilai rata-rata
- Menghapus data duplikat dan kolom ID yang tidak relevan
- Menghapus *outlier* menggunakan metode **IQR (Interquartile Range)**
- Melakukan *feature selection* dengan metode **VarianceThreshold**

---

### 2. 📊 Exploratory Data Analysis (EDA)
- Menampilkan distribusi fitur numerik menggunakan **histogram**
- Menganalisis korelasi antar variabel numerik dengan **heatmap**
- Mengidentifikasi pola dan hubungan antar fitur terhadap target (*Price*)

---

### 3. 🧠 Modeling (Prediksi Harga Mobil)
- Menggunakan model **Linear Regression**
- Melakukan **encoding** pada fitur kategori menggunakan `LabelEncoder`
- Melakukan **feature scaling** menggunakan `StandardScaler`
- Melakukan **train-test split** untuk membagi data menjadi data latih dan data uji
- Melatih model dan menampilkan **intercept** serta **coefficient** dari regresi linear

---

### 4. 📈 Model Evaluation
Model dievaluasi menggunakan beberapa metrik regresi, yaitu:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**

Evaluasi ini digunakan untuk melihat seberapa baik model dalam memprediksi harga mobil bekas berdasarkan fitur-fitur yang telah diproses sebelumnya.

---

### 💾 Tools & Library yang Digunakan
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

### 📍 Kesimpulan
Setelah melalui tahap *data profiling*, *cleaning*, *EDA*, *feature selection*, dan *modeling*,  
diperoleh model regresi linear yang dapat memprediksi harga mobil bekas dengan cukup baik.  
Tahapan *data preprocessing* yang bersih dan rapi menjadi kunci agar model dapat bekerja secara optimal. ✅

---

🧑‍💻 **Nama - NPM:** Andika Hartanta - 2310631170067
📚 **Mata Kuliah:** UTS Data Mining Praktikum  
🏫 **Kelas:** 5A - Informatika
