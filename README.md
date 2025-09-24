# Blackout-X-Performance ☠️

![Blackout-X-Performance Banner](https://raw.githubusercontent.com/blackoutnextproject/Blackout-Project-Banner/main/Blackout-banner.jpg)

### 📄 Deskripsi

**Blackout-X-Performance** adalah Module Magisk/KernelSU yang dirancang untuk mengoptimalkan performa perangkat Android secara otomatis. Modul ini mendeteksi saat sebuah game sedang berjalan dan mengaktifkan serangkaian *tweak* performa agresif. Saat game ditutup, semua pengaturan akan dikembalikan ke kondisi normal untuk menghemat baterai dan menjaga stabilitas sistem.

---

### ✨ Fitur Utama

* **Deteksi Game Otomatis**: Secara cerdas mendeteksi game yang sedang berjalan menggunakan Game Manager Service Android. Tidak perlu lagi memasukkan nama *package* secara manual.
* **Optimalisasi Grafis (SkiaVulkan)**: Mengubah *renderer* grafis ke **SkiaVulkan** untuk potensi peningkatan FPS dan responsivitas UI.
* **Downscale Resolusi**: Menurunkan resolusi layar saat bermain game untuk mengurangi beban kerja GPU, yang menghasilkan *frame rate* yang lebih stabil dan tinggi.
* **Tweak I/O Scheduler**: Mengatur I/O *scheduler* ke **Kyber** saat bermain game untuk mengurangi latensi disk, mempercepat waktu *loading*, dan mencegah *stuttering*.
* **Mode Seimbang**: Mengembalikan semua pengaturan ke mode seimbang (`bfq` I/O, resolusi normal) setelah game ditutup.
* **Kompatibilitas Luas**: Mendukung Magisk, Kitsune, KernelSU, KernelSUNext, dan Apatch.

---

### 🚀 Cara Menginstal

1.  Unduh modul **Blackout-X-Performance** dari [tautan rilis](link_ke_rilis_github_mu).
2.  Buka aplikasi Magisk Manager atau KernelSU Manager.
3.  Pergi ke bagian **Modul** dan pilih **Instal dari penyimpanan**.
4.  Pilih file `.zip` dari modul yang sudah kamu unduh.
5.  Tunggu hingga proses instalasi selesai. Kamu akan melihat laporan instalasi di layar.
6.  **Reboot** perangkatmu untuk mengaktifkan modul.

---

### ⚙️ Cara Menggunakan

Setelah modul terinstal, kamu tidak perlu melakukan apa pun. **Blackout-X-Performance** akan berjalan secara otomatis di *background*.

* Saat kamu membuka game, modul akan mengaktifkan **Mode Blackout** dengan semua *tweak* performa.
* Saat kamu keluar dari game, modul akan kembali ke **Mode Seimbang** secara otomatis.

---

### ⚠️ Peringatan

* **Risiko *Tweak***: Modul ini menggunakan *tweak* yang bersifat agresif dan mungkin tidak cocok untuk semua perangkat. Beberapa fitur, seperti **SkiaVulkan**, bergantung pada dukungan *driver* perangkatmu.
* **Laporkan *Bug***: Jika kamu mengalami masalah (misalnya, *glitch* grafis atau aplikasi *crash*), silakan laporkan masalah tersebut di halaman GitHub proyek ini.

---

### 🤝 Kontribusi

Proyek ini bersifat *open-source*. Kontribusi dan saran sangat terbuka. Jika kamu ingin berkontribusi, silakan buat *pull request* di [https://github.com/blackoutnextproject/Blackout-X-Perf](https://github.com/blackoutnextproject).

---

### 📜 Lisensi

Modul ini dirilis di bawah lisensi [MIT License](https://opensource.org/licenses/MIT).
