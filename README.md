# API Backend Repository

**Status: Serverless / Local Architecture**

Untuk tugas akhir ini, aplikasi Android yang dikembangkan menggunakan pendekatan **Offline-First** dengan **Room Database (SQLite)**.

Keputusan ini diambil untuk memaksimalkan performa fitur utama aplikasi, yaitu **Real-time OCR (Optical Character Recognition)** menggunakan CameraX dan ML Kit. Penggunaan database lokal memastikan data hasil scan dapat diproses dan disimpan secara instan tanpa ketergantungan pada latensi jaringan/internet.

Oleh karena itu, seluruh logika manipulasi data (CRUD) dan penyimpanan sudah terintegrasi langsung di dalam Repository Android Utama.

**Link Repository Android:**
https://github.com/Aestrick/PAM2025_105.git
