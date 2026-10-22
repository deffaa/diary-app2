Nama: Deffa Haidar Darmansyah
NIM: 2430511035
Kelas: 5C Teknik Informatika

Fitur yang Diselesaikan
Pada tugas ini, aplikasi telah dipecah menjadi beberapa komponen terstruktur:
* **Manajemen State Terpusat:** State utama (`entries`, `query`, `likedIds`) dikelola di komponen induk (`DiaryListScreen`).
* **Presentational Component:** Komponen `DiaryCard` menerima data dan interaksi (tombol Like & tekan) melalui *props*.
* **Fitur Pencarian:** `SearchBar` menggunakan *local state* untuk menyaring daftar catatan yang tampil secara *real-time*.
* **Controlled Form:** `EntryForm` menangkap input pengguna untuk menambahkan entri catatan baru ke daftar secara instan tanpa perlu memuat ulang (*reload*) aplikasi.
* **Aset Lokal:** Menggunakan file gambar lokal yang tersimpan di dalam folder `assets/moods/`.

Cara Menjalankan Aplikasi
1. Buka terminal di dalam folder `diary-app`.
2. Jalankan perintah `npm install` untuk menginstal dependensi.
3. Jalankan perintah `npx expo start` untuk memulai server.
4. Buka aplikasi **Expo Go** di smartphone, lalu *scan* QR Code yang muncul di terminal.
