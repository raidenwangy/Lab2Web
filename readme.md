<!-- Pembuatan Tabel Data Mahasiswa, Tabel Nilai Praktikum, dan Form Registrasi -->
# Praktikum 2 - Pemrograman Web

Pada tahap ini, dilakukan pembuatan tabel data mahasiswa menggunakan tag `<table>` dengan garis tepi `border="1"`, di mana struktur judul kolom ditentukan oleh tag `<th>` dan baris data diisi menggunakan tag `<tr>` serta `<td>`. Selanjutnya, tabel dikembangkan lebih terstruktur menggunakan tag `<caption>` untuk judul tabel, `<thead>` untuk bagian kepala tabel, `<tbody>` untuk bagian isi data, serta `<tfoot>` untuk bagian kaki tabel yang dilengkapi dengan atribut `colspan="2"` untuk menggabungkan dua kolom pada baris rata-rata. 

Selain tabel, dibuat pula formulir pendaftaran menggunakan elemen `<form>` yang berisi bidang isian teks (`type="text"`), email (`type="email"`), kata sandi (`type="password"`), dan pemilih tanggal (`type="date"`) yang masing-masing dilengkapi dengan `<label>`, serta tombol aksi untuk pendaftaran (`type="submit"`) dan pembatalan (`type="reset"`).

### Hasil dan Codingan (Bagian 1):
* **Codingan 1:**  
  ![codingan 1](<media/Screenshot/1 codingan.png>)
* **Hasil 1:**  
  ![hasil 1](<media/Screenshot/1 hasil.png>)
* **Codingan 1.2:**  
  ![codingan 1.2](<media/Screenshot/1.2 codingan.png>)

---

<!-- Pembuatan Elemen Form Lanjutan (Radio, Checkbox, Select, dan Textarea) -->
## Pembuatan Elemen Form Lanjutan

Pada tahap ini, dilakukan penambahan elemen-elemen isian formulir tingkat lanjut pada file `index.html` dengan rincian sebagai berikut:

* **Radio Button (Jenis Kelamin)**  
  Dibuat menggunakan elemen `<input type="radio">` dengan atribut `name="jk"` yang sama. Hal ini bertujuan agar pengguna hanya dapat memilih satu dari beberapa opsi pilihan tunggal yang tersedia, yaitu laki-laki atau perempuan.
  
* **Checkbox (Keahlian)**  
  Dibuat menggunakan elemen `<input type="checkbox">` untuk bagian daftar keahlian. Pilihan ini memungkinkan pengguna untuk memilih lebih dari satu opsi sekaligus, seperti HTML, CSS, dan JavaScript.
  
* **Select dan Option (Program Studi)**  
  Dibuat menggunakan tag `<select>` yang berisi beberapa tag `<option>` di dalamnya untuk menampilkan menu pilihan turun (*dropdown menu*). Pilihan mencakup Teknik Informatika dan Sistem Informasi.
  
* **Textarea (Alamat)**  
  Dibuat menggunakan tag `<textarea>` dengan atribut `rows="5"` dan `cols="40"`. Tag ini digunakan untuk menyediakan kotak isian teks berukuran besar yang dapat menampung teks banyak baris, seperti alamat lengkap.

### Hasil dan Codingan (Bagian 2):
* **Codingan 2:**  
 ![Codingan 2](<media/Screenshot/2 codingan.png>)
* **Hasil 2:**  
  ![hasil 2](<media/Screenshot/2 hasil.png>)

---

<!-- Penerapan Validasi Form, Semantic HTML, dan Elemen Multimedia -->
## Validasi Form, Semantic HTML, dan Elemen Multimedia

Pada tahap ini, dilakukan penerapan fitur validasi input, struktur tata letak Semantic HTML, serta penyisipan media audio dan video pada file `index.html` dengan rincian sebagai berikut:

### 1. Validasi Form Dasar
Menerapkan atribut validasi bawaan HTML pada elemen isian formulir. Atribut `required` digunakan agar bidang isian nama, email, dan umur wajib diisi. Selain itu, diterapkan aturan `minlength="3"` pada bidang nama serta `min="17"` dan `max="60"` pada bidang umur untuk membatasi rentang nilai input.

### 2. Struktur Semantic HTML
Menyusun struktur halaman web yang lebih bermakna menggunakan tag semantik. Struktur ini terdiri dari:
* `<nav>` untuk menu navigasi utama
* `<main>` sebagai area konten utama
* `<section>` dan `<article>` untuk mengelompokkan topik serta artikel informasi akademik
* `<aside>` untuk informasi tambahan
* `<footer>` untuk catatan hak cipta di bagian bawah

### 3. Menambahkan Multimedia (Audio dan Video)
Menyisipkan media interaktif menggunakan tag pemutar bawaan HTML:
* Tag `<audio controls>` dengan `<source src="media/plankton.mp3">` digunakan untuk memutar file suara.
* Tag `<video controls width="480">` dengan `<source src="media/haruka.mp4">` digunakan untuk menampilkan pemutar video. 
* Atribut `controls` ditambahkan agar pengguna dapat memutar, menghentikan, dan mengatur volume media.

### Hasil dan Codingan (Bagian 3):
* **Codingan 3:**  
 ![Codingan 3](<media/Screenshot/3 codingan.png>)
* **Hasil 3:**  
  ![hasil 3](<media/Screenshot/3 hasil.png>)
* **Codingan 3.2:**  
  ![codingan 3.2](<media/Screenshot/3.2 codingan.png>)
* **Hasil 3.2:**  
 ![hasil 3.2](<media/Screenshot/3.2 hasil.png>)
* **Hasil Akhirkeseluruhan:**  
  ![Hasil](<media/Screenshot/Screenshot (254).png>)
