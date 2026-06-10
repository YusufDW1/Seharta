# 🚀 Cara Clone Repository (Penting!)

Repository Seharta ini menggunakan arsitektur **Git Submodule** untuk menghubungkan repository `Frontend` dan `Backend`. 

⚠️ **PERHATIAN:** Perintah `git clone` biasa hanya akan mengunduh repository utama dan membiarkan folder submodule (`Frontend` dan `Backend`) dalam keadaan **kosong**.

Untuk mengunduh keseluruhan *source code*, gunakan salah satu metode di bawah ini:

### 🌟 Opsi 1: Clone Sekaligus (Sangat Direkomendasikan)
Tambahkan *flag* `--recursive` saat melakukan clone agar Git otomatis mengunduh seluruh isi submodule.

```bash
git clone --recursive https://github.com/YusufDW1/Seharta
