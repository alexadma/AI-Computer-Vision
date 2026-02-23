\# DETEKSI OBJEK UNTUK MEMANTAU KEAKURATAN TEMBAKAN DALAM LATIHAN INDIVIDU OLAHRAGA BASKET BERBASIS ALGORITMA YOLO



\## Deskripsi Singkat

Project ini merupakan hasil karya skripsi penulis tahun 2024 yang membahas pengembangan sistem Artificial Intelligence berbasis Computer Vision untuk mendeteksi objek bola dan ring basket, membandingkan performa model YOLOv8 dan YOLOv9, serta menganalisis akurasi tembakan pada latihan individu olahraga basket.  
Seluruh kode dan metodologi dalam repository ini merupakan hasil pengembangan penulis untuk keperluan akademik.

Video dapat di lihat pada link berikut https://drive.google.com/drive/folders/1PxoG4bvBoACMEFkCWtuGYbehxDX95saK?usp=sharing perhatikan Struktur Folder Project!

Hak cipta © 2024 Alexander Adma Karyadi.  
Dilarang menggunakan, memperbanyak, atau memodifikasi sebagian atau seluruh isi project ini untuk kepentingan komersial tanpa izin tertulis dari penulis.  
Untuk keperluan akademik atau penelitian, mohon cantumkan sumber dan referensi.


---



\## Tujuan Penelitian

\- Membangun sistem deteksi objek bola dan ring basket berbasis YOLOv8 dan YOLOv9  

\- Membandingkan performa YOLOv8 dan YOLOv9 pada kasus deteksi tembakan basket  

\- Melakukan \*tuning hyperparameter\* untuk meningkatkan performa model  

\- Menghitung keberhasilan tembakan berdasarkan lintasan bola menggunakan metode \*linear trendline\*



---



\## Metode \& Teknologi

\- OpenCV  

\- YOLOv8  

\- YOLOv9  

\- TensorFlow  

\- Roboflow  

\- Python  

\- Jupyter Notebook  



---



\## Struktur Folder Project

```text

Computer Vision/

│── OUTPUT FIX/                  # Hasil output final (visualisasi, video, gambar)

│── runs/                        # Hasil training \& inference dari YOLO

│── PERBANDINGAN.ipynb           # Notebook analisis perbandingan YOLOv8 vs YOLOv9

│── YOLO8m\_SGD\_lr0.0001\_m0.999.ipynb

│── YOLO8m\_SGD\_lr0.01\_m0.937.ipynb

│── YOLOv9m\_SGD\_lr0.01\_m0.937.ipynb

│── YOLOv9m\_SGD\_lr0.0001\_m0.999.ipynb

│── README.md

