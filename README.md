# 📘 Basis Data Part 8 – Data Cleansing dengan OpenRefine

> **README.md – Siap untuk GitHub**
> Mata Kuliah: Basis Data
> Pengampu: Khamarudin Syarif

---

## 📌 Pendahuluan

Pada **Basis Data Part 8**, pembahasan berfokus pada proses **Data Cleansing (Pembersihan Data)** menggunakan tools **OpenRefine**. Data cleansing merupakan tahap penting sebelum data dianalisis karena data mentah sering mengandung kesalahan seperti duplikasi, inkonsistensi penulisan, dan nilai kosong.

Dokumentasi ini disusun dalam format **Markdown** sehingga dapat langsung digunakan sebagai **README di GitHub**, serta telah dilengkapi dengan **quiz dan jawaban lengkap** sesuai materi Part 8.

---

## 🧹 Apa itu Data Cleansing?

**Data Cleansing** adalah proses memperbaiki atau menghapus data yang:

* Duplikat
* Tidak konsisten (huruf besar/kecil, salah ejaan)
* Tidak lengkap (NULL / kosong)
* Tidak sesuai format

Tujuan utama data cleansing adalah memastikan data **akurat, konsisten, dan siap dianalisis**.

---

## 🛠️ Pengenalan OpenRefine

**OpenRefine** adalah aplikasi open-source yang digunakan untuk:

* Membersihkan data
* Menyeragamkan format data
* Mendeteksi duplikasi
* Melakukan transformasi data

### 🔗 Website Resmi

[https://openrefine.org](https://openrefine.org)

---

## 📥 Import Data ke OpenRefine

### Langkah-langkah Import Data

1. Jalankan OpenRefine
2. Klik **Create Project**
3. Pilih file (CSV / Excel / TSV)
4. Klik **Next**
5. Klik **Create Project**

---

## 🔍 Facet & Filter

### Text Facet

Digunakan untuk melihat variasi nilai dalam satu kolom.

Contoh penggunaan:

* Mendeteksi perbedaan penulisan: `Jakarta`, `jakarta`, `JKT`

### Numeric Facet

Digunakan untuk memfilter data numerik berdasarkan rentang nilai.

---

## ✏️ Transformasi Data

Beberapa transformasi umum di OpenRefine:

* **To Uppercase** → mengubah teks ke huruf besar
* **To Lowercase** → mengubah teks ke huruf kecil
* **Trim leading and trailing whitespace** → menghapus spasi berlebih

---

## 🧩 Cluster & Edit

Fitur **Cluster & Edit** digunakan untuk:

* Mendeteksi data yang mirip
* Menggabungkan data dengan makna sama

Contoh:

* `Bandung`, `Bandung `, `BANDUNG`

---

## 📤 Export Data

Setelah proses cleansing selesai, data dapat diekspor kembali.

### Langkah Export Data

1. Klik **Export**
2. Pilih format (CSV / Excel)
3. Data siap digunakan

---

# 📝 QUIZ BASIS DATA PART 8

## Quiz 1

**Apa tujuan utama data cleansing sebelum analisis data?**

✅ **Jawaban:**
Untuk memastikan data bersih, konsisten, dan akurat sehingga hasil analisis lebih valid.

---

## Quiz 2

**Tools apa yang digunakan pada Part 8 untuk data cleansing?**

✅ **Jawaban:**
OpenRefine

---

## Quiz 3

**Fitur apa yang digunakan untuk melihat variasi data dalam satu kolom?**

✅ **Jawaban:**
Text Facet

---

## Quiz 4

**Bagaimana cara mengubah seluruh teks menjadi huruf kecil di OpenRefine?**

✅ **Jawaban:**
Edit cells → Common transforms → To lowercase

---

## Quiz 5

**Apa fungsi fitur Cluster & Edit?**

✅ **Jawaban:**
Untuk mendeteksi dan menggabungkan data yang memiliki makna sama tetapi penulisan berbeda.

---

## Quiz 6

**Sebutkan dua manfaat utama data cleansing.**

✅ **Jawaban:**

1. Meningkatkan kualitas dan akurasi data
2. Mengurangi kesalahan dalam analisis dan pengambilan keputusan

---

## Quiz 7

**Bagaimana cara mengekspor data hasil cleansing dari OpenRefine?**

✅ **Jawaban:**
Klik Export → pilih format file → data siap digunakan

---

## ✅ Penutup

Dengan memahami proses data cleansing menggunakan OpenRefine, pengguna dapat memastikan bahwa data yang digunakan untuk analisis sudah bersih, konsisten, dan siap digunakan. Materi ini melengkapi rangkaian pembelajaran Basis Data dari Part 1 hingga Part 8.

---

## 🔗 Referensi

* [https://docs.google.com/document/d/1d-D4jaue8dK8bc65MHFJfA59SpBcjn7gMapTeXlJPME/edit?usp=sharing]
* [https://openrefine.org](https://openrefine.org)
* [https://www.mysql.com](https://www.mysql.com)
* [https://learn.microsoft.com/sql](https://learn.microsoft.com/sql)
