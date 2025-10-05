## v0.2.5 [INCURSION] 〄 [HOs]

### ✨ Fitur dan Peningkatan Utama

* **Peningkatan Performa Inti**:
    * **Optimalisasi Vsync Agresif**: Menghilangkan *input latency* dengan mengatur fase *timing* Vsync ke nilai minimal pada SurfaceFlinger (untuk *early/late app duration* dan *sf duration*).
    * **Tweak VM**: Mengurangi `dirty_ratio` dan `dirty_background_ratio` (10/5) untuk memaksa data *buffer* ditulis lebih cepat ke disk, meminimalkan *stutter* mendadak.
    * **Tweak Jaringan Latensi Rendah**: Mengaktifkan `tcp_low_latency=1` untuk memprioritaskan latensi daripada *throughput*, sangat penting untuk game *online*.
    * **Tweak CPU Responsiveness**: Mengaktifkan `sem_enhanced_cpu_responsiveness` saat *Game Mode* aktif untuk responsivitas CPU yang lebih cepat.

* **Peningkatan Stabilitas dan Pengembalian**:
    * **Pembersihan Proses**: Menambahkan `pkill -f` yang lebih ketat saat transisi mode untuk menghentikan proses *tweak* lama.
    * **Pengembalian Vsync Lengkap**: Semua *tweak* Vsync dan *timing* yang baru ditambahkan dikembalikan ke nilai default di **Mode Seimbang**.

* **Peningkatan Instalasi**:
    * **Deteksi Perangkat Komprehensif**: Menambahkan deteksi otomatis **Codename** dan **Jenis ROM** (MIUI & HyperOS) saat *flashing*.

* **UI Elements**
    * **Mengubah tampilan UI agar lebih** **fresh & smooth**