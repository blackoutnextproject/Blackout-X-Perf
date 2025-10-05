# Blackout-X-Performance ☠️

![Blackout-X-Performance Banner](https://raw.githubusercontent.com/blackoutnextproject/Blackout-Project-Banner/main/Blackout-banner.jpg)

### 📄 Deskripsi

**Blackout-X-Performance** adalah modul Magisk/KernelSU yang dirancang untuk mengoptimalkan performa perangkat Android secara otomatis. Modul ini mendeteksi saat sebuah game sedang berjalan dan mengaktifkan serangkaian *tweak* performa agresif. Saat game ditutup, semua pengaturan akan dikembalikan ke kondisi normal untuk menghemat baterai dan menjaga stabilitas sistem.

---

### ✨ Fitur Utama

* **Deteksi Game Otomatis**: Secara cerdas mendeteksi game yang sedang berjalan menggunakan Game Manager Service Android. Tidak perlu lagi memasukkan nama *package* secara manual.
* **Optimalisasi Grafis (SkiaVulkan)**: Mengubah *renderer* grafis ke **SkiaVulkan** untuk potensi peningkatan FPS dan responsivitas UI.
* **Downscale Resolusi Cerdas**: Menurunkan resolusi layar ke **1440x720 (atau sejenisnya)**. Fitur ini **hanya menargetkan aplikasi game yang aktif**, menjaga UI sistem tetap pada resolusi normal.
* **Tweak Latensi Ekstrem**:
    * **Vsync Timing**: Mengatur *timing* Vsync untuk meminimalkan *input latency* antara sentuhan dan gambar di layar.
    * **VM/I/O Buffer**: Menurunkan `dirty_ratio` untuk mengurangi *stutter* yang disebabkan oleh operasi I/O tertunda.
    * **Network Latency**: Mengaktifkan `tcp_low_latency` untuk prioritas *ping* stabil saat game *online*.
* **Mode Seimbang**: Mengembalikan semua pengaturan *tweak* ke kondisi default (termasuk Vsync, VM, dan *Network*) setelah game ditutup.
* **Informasi Lengkap**: Menampilkan informasi detail perangkat (termasuk **Codename** dan **Jenis ROM**) saat instalasi.
* **Kompatibilitas Luas**: Mendukung Magisk, Kitsune, KernelSU, KernelSUNext, dan Apatch.

---

### 🚀 Cara Menginstal

1.  Unduh modul **Blackout-X-Performance** dari [https://github.com/blackoutnextproject/Blackout-X-Perf](https://github.com/blackoutnextproject/Blackout-X-Perf/releases).
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
* **Only HyperOs & MIUI***

---

### 📜 Lisensi

Modul ini dirilis di bawah lisensi [MIT License](https://opensource.org/licenses/MIT).
