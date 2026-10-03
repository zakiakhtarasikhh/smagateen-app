# SMAGATEEN (Sistem Manajemen Kantin SMAN 3 Jombang)

Aplikasi web interaktif yang dirancang khusus untuk mengelola aktivitas kantin dan pencatatan jajan harian siswa di SMAN 3 Jombang.

👥 Pembagian Tugas Kelompok
- **Ghoni Bayhaqi Arfinsyah:** Perancangan arsitektur awal aplikasi, pembuatan struktur dasar, & logika utama kantin.
- **Muhammad Zaki Akhtarasikh:** Penyempurnaan aplikasi, penambahan fitur-fitur baru, & pengelolaan dokumentasi GitHub.

## 💬 Riwayat Pengembangan & Spesifikasi Aplikasi SMAGATEEN

### 1. Deskripsi Proyek
**SMAGATEEN** (Sistem Manajemen Kantin dan Gizi SMAN 3 Jombang / SMAGAJO) adalah aplikasi web interaktif yang dirancang untuk membantu siswa mencatat pengeluaran harian, memantau asupan gizi harian (kalori, karbohidrat, protein, dan lemak), serta menyediakan rekomendasi makanan sehat yang disesuaikan dengan profil kesehatan masing-masing siswa.

### 2. Fitur Utama Aplikasi
- **Dashboard Harian & Indikator Visual:** Menampilkan ringkasan pengeluaran dalam Rupiah, progres kalori harian, grafik makronutrien, serta indikator visual (Progress Bar) untuk memantau batas anggaran dan target kalori.
- **AI Vision Food Scanner:** Fitur pemindai berbasis AI untuk mengenali foto makanan/minuman, mendeteksi harga, rincian gizi, kantin penjual (Kantin 1–8), alternatif tebakan menu, peringatan alergi, serta dukungan produk kemasan/Koperasi Siswa.
- **Analisis Grafik & Rekomendasi Gizi:** Grafik interaktif harian, mingguan, hingga bulanan, serta kalkulator BMR & TDEE untuk rekomendasi menu sehat otomatis.
- **Portal Khusus Pengelola Kantin (1–8):** Panel eksklusif untuk stan Kantin 1 sampai 8 guna menambah, mengedit, menghapus, serta mengatur status ketersediaan menu (Tersedia / Habis) secara *real-time*. Dilengkapi pustaka gizi standar (*Library Gizi*).
- **Sistem Autentikasi & Keamanan Ketat:** 
  - Akun Siswa dengan verifikasi email via EmailJS dan pemulihan sandi aman (Lupa Password).
  - Akun Pengelola Kantin dengan pemetaan email resmi (kantin1smagajo@gmail.com s.d. kantin8smaga@gmail.com) dan fitur "Ingat Saya" serta tombol lihat sandi (show/hide).

### 3. Contoh Ringkasan *Prompt* Perancangan Utama
1. **Inisialisasi & Arsitektur Sistem:**
   > *"Buatkan aplikasi web SMAGATEEN untuk SMAN 3 Jombang yang mencakup pencatatan keuangan harian siswa, kalkulator gizi, dan manajemen stan Kantin 1-8 dengan tema warna biru ceria khas SMAGAJO."*
2. **Integrasi AI Vision & Database Menu:**
   > *"Hubungkan pemindai foto makanan dengan daftar menu resmi kantin, lengkap dengan fitur deteksi alergi, rekomendasi gizi, dan label produk Koperasi Siswa."*
3. **Autentikasi & Keamanan (EmailJS):**
   > *"Terapkan sistem Lupa Password 2 langkah dengan pengiriman kode OTP 6 digit yang aman melalui EmailJS tanpa menampilkan kode di layar."*
