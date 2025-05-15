📚 Aplikasi Rekomendasi Buku - Streamlit
Aplikasi ini adalah sistem rekomendasi buku berbasis Streamlit yang memungkinkan pengguna untuk melihat, menambahkan, menandai, mencari, dan mendapatkan rekomendasi buku berdasarkan kategori atau judul. Aplikasi ini juga menyimpan informasi pengguna dan statistik bacaan.

🚀 Fitur Utama
🔍 Cari Buku berdasarkan kata kunci judul

📖 Lihat Daftar Buku yang tersedia

➕ Tambah Buku Baru ke dalam sistem

✅ Tandai Buku sebagai telah dibaca

📊 Statistik Bacaan: Total buku, yang sudah dan belum dibaca

🎯 Rekomendasi Berdasarkan Kategori

🧠 Rekomendasi Berdasarkan Judul (dengan saran serupa)

🎁 Surprise Me!: Rekomendasi acak dari buku yang belum dibaca

👤 Penyimpanan Informasi Pengguna (Nama dan Umur)

🗂 Struktur Data
📘 Dataset Buku (CSV)
File buku disimpan di path:

swift
Copy
Edit
C:/Users/ASUS/Downloads/data_tubes_fix_fix1.csv
Kolom-kolom penting:

category: Kategori buku

title: Judul buku

rating: Rating buku (0.0 - 5.0)

read: Status dibaca (True/False)

👥 Data Pengguna
Data pengguna disimpan dalam file users.csv dengan kolom:

Nama

Umur

💻 Cara Menjalankan
Pastikan Anda telah menginstal Streamlit:

bash
Copy
Edit
pip install streamlit pandas
Jalankan aplikasi:

bash
Copy
Edit
streamlit run nama_file.py
Gantilah nama_file.py dengan nama file Python Anda.

Akses melalui browser: Biasanya akan terbuka otomatis di http://localhost:8501
