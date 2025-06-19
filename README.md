# Submission Akhir Belajar Machine Learning by DICODING
-- Dataset yang digunakan:  bank_transactions_data_edited --

# Tujuan Project
Tujuan dari project ini adalah untuk mengelompokkan nasabah berdasarkan pola transaksi keuangan mereka menggunakan algoritma K-Means Clustering, lalumembangun model klasifikasi (Decision Tree) yang mampu memprediksi cluster nasabah baru berdasarkan fitur-fitur seperti jumlah transaksi, saldo akun, durasi transaksi, dan lainnya. Project ini berhasil diselesaikan dan diterima oleh tim reviewer Dicoding, serta saya memperoleh sertifikat resmi sebagai bukti kelulusan.

# Insight yang di dapat
Cluster 0:
Rata-rata (TransactionAmount) : 0.1478 → (Jumlah transaksi kecil)
Rata-rata (TransactionDate) : 943.7 → (Pertengahan waktu, tidak terlalu baru atau lama)
Rata-rata (TransactionDuration) : 0.9931 → (Durasi transaksi sangat panjang)
Rata-rata (AccountBalance) : 0.3303 → (Saldo cukup rendah)
Rata-rata (LoginAttempts) : 0.0270 → (Usaha login rendah)
Analisis: Cluster ini mencakup pengguna dengan aktivitas transaksi rendah dan saldo akun yang relatif rendah. Durasi transaksi cukup panjang, namun pengguna jarang melakukan login. Hal ini menunjukkan bahwa pengguna dalam klaster ini mungkin tidak terlalu aktif atau hanya menggunakan layanan tertentu secara berkala. Mereka mungkin cocok ditargetkan dengan edukasi keuangan atau promosi produk ringan untuk meningkatkan interaksi.

Cluster 1:
Rata-rata (TransactionAmount) : 0.1670 → (Jumlah transaksi cukup tinggi)
Rata-rata (TransactionDate) : 1577.1 → (Pengguna pertengahan waktu – cenderung aktif lebih lama)
Rata-rata (TransactionDuration) : 0.9965 → (Durasi transaksi sangat panjang)
Rata-rata (AccountBalance) : 0.3301 → (Saldo hampir sama dengan Cluster 0, cukup rendah)
Rata-rata (LoginAttempts) : 0.0232 → (Usaha login rendah)
Analisis: pengguna cluster 1 memiliki aktivitas transaksi yang lebih besar di banding cluster 0, dengan durassi teransaksi panjang dan saldo yang stabil. mereka tampak cukup aktif namun tidak terlalu sering login. mereka adalah pengguna yang loyal tapi pasif pada teknologi digital. stategi yang cocok dengan memberikan penawaran berbasis tarnsaksi yang otomatis.

Cluster 2:
Rata-rata (TransactionAmount) : 0.1516 → (Jumlah transaksi sedang)
Rata-rata (TransactionDate) : 2204.2 → (Pengguna paling baru)
Rata-rata (TransactionDuration) : 1.0000 → (Durasi transaksi maksimum)
Rata-rata (AccountBalance) : 0.3453 → (Saldo akun paling tinggi)
Rata-rata (LoginAttempts) : 0.0321 → (Login cukup sering)
Analisis: Cluster ini diisi oleh pengguna yang baru, tetapi sangat aktif dan memiliki saldo akun tertinggi. Mereka juga cenderung sering login. Hal ini menunjukkan bahwa mereka adalah pengguna baru yang sangat aktif secara digital maupun finansial. Rekomendasi untuk cluster ini adalah memberikan fitur premium, onboarding interaktif, atau program promosi agar loyalitas tetap terjaga.

Cluster 3:
Rata-rata (TransactionAmount) : 0.1531 → (Jumlah transaksi sedang)
Rata-rata (TransactionDate) : 314.3 → (Pengguna paling lama)
Rata-rata (TransactionDuration) : 0.9966 → (Durasi transaksi sangat panjang)
Rata-rata (AccountBalance) : 0.3349 → (Saldo cukup tinggi)
Rata-rata (LoginAttempts) : 0.0367 → (Login paling sering)
Analisis: Cluster ini berisi pengguna lama yang aktif, sering login, dan memiliki saldo akun stabil. Mereka memiliki kebiasaan penggunaan yang konsisten dan durasi transaksi yang panjang. Pengguna ini tampaknya adalah pelanggan setia yang telah lama menggunakan layanan dan terus berinteraksi. Rekomendasi untuk mereka adalah program loyalitas eksklusif, promosi penghargaan, atau fitur baru lebih awal (early access).
