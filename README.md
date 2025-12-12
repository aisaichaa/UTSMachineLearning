# UTSMachineLearning

1. Tujuan Repositori: Repositori ini dibuat untuk menghimpun seluruh pengerjaan Fraud detection, Regression, dan Clustering dalam satu tempat. Setiap tugas ditempatkan pada folder terpisah agar proses dokumentasi, pemeriksaan, dan navigasi menjadi lebih mudah
2. Gambaran Singkat Proyek
Repositori ini berisi tiga proyek machine learning dengan fokus dan metode berbeda, yaitu:
- Tugas 1: Deteksi fraud menggunakan supervised learning
- Tugas 2: Prediksi tahun rilis lagu menggunakan regresi
- Tugas 3: Segmentasi pelanggan menggunakan clustering
Setiap proyek memiliki pipeline lengkap meliputi IEDA, preprocessing, pemodelan, tuning, evaluasi, hingga output
3. Deskripsi Model dan Hasil Metrik
Setiap tugas menggunakan model berbeda sesuai tujuan analisis:
- Tugas 1: LightGBM dengan tuning, dievaluasi menggunakan ROC-AUC, PR-AUC, classification report, dan confusion matrix
- Tugas 2: Model regresi (Linear Regression, Ridge, RandomForest, LightGBM, XGBoost), dengan model terbaik adalah LightGBM; metrik evaluasi meliputi MSE, RMSE, MAE, dan R²
- Tugas 3: K-Means; dievaluasi menggunakan Silhouette Score dan interpretasi centroid
4. Navigasi repo/colab
Navigasi Repo:

Repositori terdiri dari tiga folder utama:

- Tugas-1 (Fraud Detection)
- Tugas-2 (Regression)
- Tugas-3 (Clustering)

Setiap folder memiliki:
- Notebook utama (Tugas1Fraud.ipynb, Tugas2Regression.ipynb, Tugas3Clustering.ipynb)
- README penjelasan per tugas
- File pendukung jika diperlukan
  
Navigasi Colab:
- Upload atau buka notebook melalui Google Colab
- Mount Google Drive
- Pastikan struktur folder Drive sesuai dengan masing-masing tugas drive saya->(fraud transaction, regresi dataset, machine learning)
- Jalankan notebook dari atas ke bawah sesuai urutan pipeline
5. Identitas
- Nama: Aisha Patricia Sekar Ayu
- Kelas: TK-46-02
- NIM: 1103223067
