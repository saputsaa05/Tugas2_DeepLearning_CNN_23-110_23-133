# Tugas2_DeepLearning_CNN_23-110_23-133
Perbandingan Performa Custom Convolutional Neural Network (CNN) dan Residual CNN untuk Klasifikasi Citra pada Dataset CIFAR-10

# Praktikum Deep Learning — Tugas 2: Studi Komparasi Arsitektur CNN


---

**Dataset:** CIFAR-10 | **Framework:** PyTorch | **Platform:** Google Colab


---

# 🔗 Tautan Akses Cepat (Google Colab)

🚀 **Google Colab (Notebook yang Telah Dijalankan):**

👉 [https://colab.research.google.com/drive/1zMfQ2S5kXI9PZLt_j2_Tl4ltr6sSvOaa?usp=sharing]


---


# 👥 Identitas Anggota Kelompok


| No. | Nama Lengkap | NIM | Program Studi | Kelas |
|---|---|---|---|---|
| 1 | Belia Eka Sukma Mentari 1 | 23-110 | Sistem Informasi | Deep Learning |
| 2 | Annisa Putri 2 | 23-133 | Sistem Informasi | Deep Learning |


---


# 📖 Deskripsi Proyek & Penjelasan Mendalam Arsitektur Model


Proyek ini membandingkan dua arsitektur 
Convolutional Neural Network (CNN) pada dataset CIFAR-10.

Eksperimen dilakukan menggunakan framework PyTorch 
dengan parameter yang sama untuk membandingkan performa 
kedua model secara objektif.


## Model A — Custom CNN Konvensional


Model A merupakan arsitektur CNN sederhana yang dibuat 
secara mandiri.


### Struktur Utama:

- 3 blok Conv-ReLU-MaxPool
- Flatten layer
- Fully Connected Layer
- Output klasifikasi 10 kelas CIFAR-10


---


## Model B — Residual CNN


Model B menggunakan konsep residual connection 
seperti pada arsitektur ResNet.


### Struktur Utama:

- Residual Block
- Shortcut Connection
- Convolution Layer
- Fully Connected Layer


Keuntungan residual connection:

- Membantu propagasi gradient
- Mengurangi vanishing gradient
- Meningkatkan stabilitas training


---
