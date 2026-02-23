  🏀 DETEKSI OBJEK UNTUK MEMANTAU KEAKURATAN TEMBAKAN DALAM LATIHAN INDIVIDU OLAHRAGA BASKET BERBASIS ALGORITMA YOLO

> Skripsi — Universitas Sanata Dharma Yogyakarta, 2025  
> **Alexander Adma Karyadi**

---

   🎬 Demo Video

[![Demo Video Sistem](https://img.shields.io/badge/▶%20Tonton%20Demo-Google%20Drive-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/16vKliuVBUTsyi2meQBs9kHF3WOxwoqhQ/view?usp=sharing)

> Klik badge di atas untuk menonton video demonstrasi sistem secara langsung.  
> Video lengkap lainnya tersedia di: [Google Drive Folder](https://drive.google.com/drive/folders/1PxoG4bvBoACMEFkCWtuGYbehxDX95saK?usp=sharing) *(perhatikan struktur folder)*

---

   📋 Deskripsi Singkat

Project ini merupakan hasil karya skripsi penulis tahun 2025 yang membahas pengembangan sistem **Artificial Intelligence** berbasis **Computer Vision** untuk:

- Mendeteksi objek bola dan ring basket secara real-time
- Membandingkan performa model **YOLOv8** dan **YOLOv9**
- Menganalisis akurasi tembakan pada latihan individu olahraga basket

Seluruh kode dan metodologi dalam repository ini merupakan hasil pengembangan penulis untuk keperluan akademik.

---

   🎯 Tujuan Penelitian

- Membangun sistem deteksi objek bola dan ring basket berbasis YOLOv8 dan YOLOv9
- Membandingkan performa YOLOv8 dan YOLOv9 pada kasus deteksi tembakan basket
- Melakukan *tuning hyperparameter* untuk meningkatkan performa model
- Menghitung keberhasilan tembakan berdasarkan lintasan bola menggunakan metode *linear trendline*

---

   🛠️ Metode & Teknologi

| Kategori | Tools |
|---|---|
| **Deteksi Objek** | YOLOv8, YOLOv9 |
| **Computer Vision** | OpenCV |
| **Deep Learning** | TensorFlow |
| **Dataset & Anotasi** | Roboflow |
| **Bahasa Pemrograman** | Python |
| **Environment** | Jupyter Notebook |

---

   📁 Struktur Folder Project

```text
Computer Vision/
│
├── OUTPUT FIX/                          # Hasil output final (visualisasi, video, gambar)
│
├── runs/                                # Hasil training & inference dari YOLO
│
├── PERBANDINGAN.ipynb                   # Notebook analisis perbandingan YOLOv8 vs YOLOv9
│
├── YOLO8m_SGD_lr0.0001_m0.999.ipynb    # Training YOLOv8 — lr=0.0001, momentum=0.999
├── YOLO8m_SGD_lr0.01_m0.937.ipynb      # Training YOLOv8 — lr=0.01, momentum=0.937
├── YOLOv9m_SGD_lr0.01_m0.937.ipynb     # Training YOLOv9 — lr=0.01, momentum=0.937
├── YOLOv9m_SGD_lr0.0001_m0.999.ipynb   # Training YOLOv9 — lr=0.0001, momentum=0.999
│
└── README.md
```

---

   ⚖️ Lisensi & Hak Cipta

**Hak Cipta © 2025 Alexander Adma Karyadi. All Rights Reserved.**

- ❌ Dilarang menggunakan, memperbanyak, atau memodifikasi sebagian atau seluruh isi project ini untuk kepentingan **komersial** tanpa izin tertulis dari penulis.
- ✅ Untuk keperluan **akademik atau penelitian**, mohon cantumkan sumber dan referensi yang sesuai.

---

<div align="center">
  <sub>Built with ❤️ for academic purpose · Universitas Sanata Dharma Yogyakarta · 2025</sub>
</div>
