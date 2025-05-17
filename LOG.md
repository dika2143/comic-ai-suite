### Day-3
- Tambah virtual environment `.venv`
- Tambah `requirements.txt` hasil pip freeze
- Tambah konfigurasi VSCode di `.vscode/settings.json`
### Day-4
✅ Buat folder `scripts` dan file `main.py`
✅ Isi `main.py` dengan kode sederhana
✅ Jalankan dan cek output pakai terminal: `python scripts/main.py`
### ✅ Day-5
- Install Pillow: `pip install pillow`
- Tambah file `scripts/load_image.py`
- Load gambar `images/contoh.png` dan tampilkan:
  - Ukuran
  - Format
  - Mode
### ✅ Day-6: Ubah & Simpan Gambar
- Buat file `scripts/process_image.py`
- Resize gambar `contoh.png` ke 512x512
- Convert ke grayscale (mode L)
- Simpan hasil ke `output/hasil_resize.png` dan `output/hasil_gray.png`
### ✅ Day-7
- Tambah file `scripts/show_image.py`
- Buka gambar `images/contoh.png`
- Tampilkan gambar ke layar dengan `img.show()`
### Day-8 – Colab Free GPU

Sun May 11 12:47:57 2025       
+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 550.54.15              Driver Version: 550.54.15      CUDA Version: 12.4     |
|-----------------------------------------+------------------------+----------------------+
| GPU  Name                 Persistence-M | Bus-Id          Disp.A | Volatile Uncorr. ECC |
| Fan  Temp   Perf          Pwr:Usage/Cap |           Memory-Usage | GPU-Util  Compute M. |
|                                         |                        |               MIG M. |
|=========================================+========================+======================|
|   0  Tesla T4                       Off |   00000000:00:04.0 Off |                    0 |
| N/A   35C    P8              9W /   70W |       0MiB /  15360MiB |      0%      Default |
|                                         |                        |                  N/A |
+-----------------------------------------+------------------------+----------------------+
Day 11: Commit notebook & dokumentasi setup selesai
