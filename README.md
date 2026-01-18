📘 Basis Data Part 8 – Clean and Transform Data dengan OpenRefine
README.md – Siap untuk GitHub
Mata Kuliah: Basis Data
Pengampu: Khamarudin Syarif

📌 Pendahuluan
Pada Basis Data Part 8, kita akan mempelajari cara membersihkan dan mengubah data menggunakan OpenRefine, sebuah alat open-source yang sangat powerful untuk bekerja dengan data yang “berantakan” (messy data). Setelah data dibersihkan, kita akan mengonversinya ke dalam format SQL untuk disimpan dalam basis data.

Dokumentasi ini disusun dalam format Markdown dan siap digunakan sebagai README di GitHub, dilengkapi dengan penjelasan langkah-langkah dan panduan praktis.

🧼 Apa itu OpenRefine?
OpenRefine adalah alat berbasis web yang digunakan untuk:

Membersihkan data yang tidak konsisten

Mengubah format data

Menghubungkan dan menggabungkan dataset

Menyiapkan data untuk analisis lebih lanjut atau import ke basis data

🚀 Langkah 1: Memulai OpenRefine
Instalasi & Menjalankan
Download OpenRefine dari openrefine.org

Ekstrak dan jalankan file openrefine.exe (Windows) atau openrefine (Mac/Linux)

Buka browser dan akses http://127.0.0.1:3333

📂 Langkah 2: Import Data ke OpenRefine
Jenis File yang Didukung:
CSV, TSV, Excel (.xls, .xlsx)

JSON, XML, RDF

Data dari Clipboard, URL, atau Database

Cara Import:
Klik Create Project

Pilih sumber data:

This Computer → upload file dari komputer

Clipboard → tempel data langsung

URL → impor dari alamat web

Konfigurasi format data (pemisah kolom, encoding, dll.)

Klik Create Project

🧹 Langkah 3: Membersihkan Data
Operasi Umum dalam OpenRefine:
Text Facet → melihat distribusi nilai unik

Cluster and Edit → menggabungkan nilai yang mirip

Transform → ubah format teks, tanggal, angka

Split Column → memisahkan kolom berdasarkan delimiter

Fill Down → mengisi nilai kosong dengan nilai di atasnya

Contoh Transformasi:
json
value.trim().toUpperCase()
digunakan untuk menghapus spasi dan mengubah teks menjadi huruf besar.

📤 Langkah 4: Export Data ke SQL
Setelah data bersih, kita dapat mengekspornya ke dalam format SQL untuk dibuat tabel di basis data.

Contoh Membuat Tabel Customer:
sql
CREATE TABLE Customer (
    id INT PRIMARY KEY,
    Name VARCHAR(100),
    address TEXT,
    Gender CHAR(1),
    phone VARCHAR(20),
    email VARCHAR(100),
    DOB DATE
);
📝 Quiz: Clean & Transform Data
Soal:
Bersihkan dan transformasikan file berikut dengan OpenRefine:

Customer.txt

Invoice.txt

Payment.txt

Product.txt

Subscription.txt

Kemudian import data tersebut ke dalam SQL dengan nama tabel sesuai nama file.

✅ Tugas:
Import masing-masing file ke OpenRefine

Lakukan pembersihan data (hilangkan duplikat, format konsisten, dll.)

Export data bersih ke format CSV atau SQL

Buat tabel SQL sesuai struktur data

Masukkan nama dan NIM pada kolom kedua setiap tabel

Screenshot setiap tabel (total 5 screenshot)

🧠 Tips & Best Practices
Selalu backup data sebelum transformasi besar

Gunakan Undo/Redo history di OpenRefine

Simpan project OpenRefine untuk revisi

Validasi data sebelum import ke SQL

✅ Penutup
Dengan OpenRefine, proses pembersihan dan transformasi data menjadi lebih terstruktur, efisien, dan dapat dilacak. Data yang bersih adalah fondasi penting untuk analisis yang akurat dan pengambilan keputusan yang baik.

🔗 Referensi
OpenRefine Documentation

MySQL Documentation

Data Cleaning Best Practices

