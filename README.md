# Employee Profile Validator 🐍

 Program ini dirancang untuk memvalidasi data profil karyawan, memeriksa format email, nomor telepon, kode unik, serta memformat teks input yang tidak beraturan.

---

## 🚀 Fitur Utama & Konsep Python
* **Pencarian & Ekstraksi Teks**: Menggunakan metode `.find()` dan *string slicing* untuk mengekstrak *username* dari alamat email.
* **Validasi Keberadaan Karakter**: Memeriksa keberadaan karakter khusus seperti `@` dan domain `.com` menggunakan operator `in`.
* **Pembersihan Teks (*Sanitization*)**: Membersihkan spasi berlebih dan merapikan kapitalisasi teks menggunakan `.strip()`, `.lower()`, `.title()`, dan `.upper()`.
* **Penggantian & Pemecahan String**: Memanipulasi nomor telepon dengan `.replace()`, serta memecah serta menggabungkan kembali data alamat menggunakan `.split()` dan `'.join()'`.
* **Validasi Awalan & Akhiran**: Memeriksa format kode karyawan dan email menggunakan `.startswith()` dan `.endswith()`.
* **Penghitungan Karakter**: Menghitung jumlah kemunculan karakter tertentu menggunakan metode `.count()`.

---

## 🛠️ Teknologi yang Digunakan
* **Bahasa**: Python 3.x
* **Editor**: Visual Studio Code
* **Kontrol Versi**: Git & GitHub

---

## 💻 Cara Menjalankan Program
1. Pastikan Python sudah terinstal di perangkatmu.
2. Clone repository ini atau unduh file `main.py`.
3. Jalankan perintah berikut di terminal:
   ```bash
   python main.py