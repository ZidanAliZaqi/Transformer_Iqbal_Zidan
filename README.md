# Transformer_Iqbal_Zidan

Kelompok Transformer yang beranggotakan `Ahmad Iqbal Ferdinand R NIM 2110018 dan Zidan Ali Zaqi NIM 2110026`. kali ini membahas capstone project Jaringan Saraf Tiruan `Transformer` dengan studi kasus `Membuat Ringkasan Sederhana`.

# Deskripsi Project

Proyek ini menggunakan model pretrained `BART (Bidirectional and Auto-Regressive Transformer)` yang dikembangkan oleh Facebook untuk meringkas dokumen teks. Dengan memanfaatkan arsitektur hybrid-nya, BART mampu memahami konteks secara menyeluruh dan menghasilkan ringkasan otomatis yang ringkas dan efisien. Proyek ini dirancang dengan tujuan untuk membantu pengguna yang membutuhkan analisis cepat dari dokumen atau artikel panjang, seperti laporan bisnis, novel, atau berita.

# NOTE!!!!!
Kode Hanya Bekerja Dengan Input File Berformat (.txt)

# Cara Kerja
Pertama, file dokumen diunggah melalui Google Colab menggunakan fungsi files.upload(). Setelah file diunggah, dokumen dibaca dari file tersebut, dengan mekanisme untuk menangani masalah format teks yang mungkin terjadi. Jika dokumen tidak bisa dibaca dalam format tertentu, program akan mencoba format lain.

Setelah dokumen berhasil dibaca, teksnya diproses agar siap untuk diringkas. Model BART, yang dirancang khusus untuk membuat ringkasan, digunakan dalam proses ini. Model ini sudah dilatih sebelumnya untuk memahami teks panjang dan menghasilkan ringkasan yang singkat namun tetap mewakili isi utama dokumen. Model diberi beberapa pengaturan, seperti panjang minimum dan maksimum ringkasan, agar hasilnya lebih sesuai kebutuhan.

Setelah ringkasan dibuat, hasilnya diterjemahkan kembali ke bentuk teks biasa, sehingga dapat dibaca dengan mudah. Akhirnya, program menampilkan isi dokumen asli dan ringkasannya. Dengan cara ini, kode ini membantu membuat versi singkat dari dokumen panjang tanpa kehilangan informasi penting.






