# CLIPR — Browser-Native Video Editor

**CLIPR** adalah alat pemotong dan pengolah video berbasis web yang dirancang untuk kecepatan, privasi, dan kemudahan penggunaan. Seluruh pemrosesan video dilakukan secara **lokal di dalam browser Anda** tanpa pernah mengunggah file ke server.

## 🚀 Fitur Utama

- **Privasi Total:** Tidak ada data yang diunggah ke server. Video diproses di memori perangkat Anda.
- **Batch Export (Antrean):** Anda dapat menentukan hingga 5 potongan video yang berbeda dan mengekspornya sekaligus dalam satu kali antrean.
- **Crop & Resize:** Ubah rasio video dengan mudah (TikTok 9:16, Square 1:1, IG 4:5, YouTube 16:9) menggunakan *overlay* interaktif yang bisa digeser.
- **Format Output Fleksibel:** Mendukung format `.webm` (optimal) dan `.mp4` (didukung browser tertentu).
- **Kontrol Audio:** Opsi *Mute Audio* untuk membuat video tanpa suara (cocok untuk B-Roll).
- **Shortcut Editor:** Kontrol layaknya software profesional untuk efisiensi tinggi.

## ⌨️ Shortcut Keyboard

Gunakan tombol berikut untuk mempercepat proses editing:

| Tombol | Fungsi |
| :--- | :--- |
| `Space` | Play / Pause Video |
| `Panah Kiri` | Mundur 1 detik |
| `Panah Kanan` | Maju 1 detik |
| `I` | Set waktu mulai (Start) |
| `O` | Set waktu akhir (End) |

## 🛠️ Cara Penggunaan

1. **Upload Video:** Seret (*drag & drop*) file video Anda ke area "Upload Video".
2. **Atur Durasi:** Gunakan *slider* pada timeline atau masukkan waktu di kolom "Start" dan "End".
3. **Atur Rasio (Opsional):** Pilih rasio pada dropdown "Format Asli", lalu geser kotak oranye pada video untuk menentukan area yang ingin dipotong.
4. **Tambah ke Antrean:** Klik "Tambah ke Antrean Potongan" untuk menyimpan konfigurasi (Maksimal 5 clip).
5. **Export:** Pilih format output dan tekan "Potong & Export". Aplikasi akan memproses semua antrean dan mengunduh file secara otomatis.

## 💻 Spesifikasi Teknis

- **Core:** Web Audio API & MediaRecorder API.
- **Processing:** Canvas API (Client-side rendering).
- **Responsiveness:** Desain adaptif (Mobile & Desktop).
- **Zero Server dependency:** 100% Client-side.

---

*Dibuat untuk kreator konten yang mengutamakan keamanan dan kecepatan.*
