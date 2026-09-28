# Laporan Praktikum 2: HTML Lanjutan

## Langkah-Langkah Praktikum
### 1. Membuat Tabel Data Mahasiswa
* **Penjelasan**: Langkah ini bertujuan untuk menyajikan data dalam bentuk baris dan kolom menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`. Data mahasiswa berhasil ditampilkan dengan struktur tabel dasar.
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 10-52-58" src="https://github.com/user-attachments/assets/b30730a4-fbae-4275-b008-6aeb68eea3e7" />)*
### 2. Mengembangkan Tabel dengan thead, tbody, dan tfoot
* **Penjelasan**: Membuat struktur tabel yang lebih teratur dan komunikatif menggunakan `<thead>` untuk header, `<tbody>` untuk isi data, dan `<tfoot>` untuk baris ringkasan (menggunakan atribut `colspan` untuk menggabungkan kolom).
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 10-59-56" src="https://github.com/user-attachments/assets/4e895792-e3b0-4889-91c0-895554418115" />
)*

### 3. Membuat Form Registrasi Mahasiswa
* **Penjelasan**: Membuat elemen `<form>` untuk menerima input dari pengguna menggunakan jenis input dasar seperti `text`, `email`, `password`, `date`, serta tombol `submit` dan `reset`.
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 11-04-19" src="https://github.com/user-attachments/assets/db8a8a39-0cd7-46fa-9edf-970ba37e5869" />
)*

### 4. Radio Button dan Checkbox
* **Penjelasan**: Menerapkan `<input type="radio">` untuk opsi pilihan tunggal (seperti Jenis Kelamin) dan `<input type="checkbox">` untuk pilihan ganda (seperti Keahlian).
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 11-06-23" src="https://github.com/user-attachments/assets/8abaf682-695a-40e4-a1db-a02f5201ba31" />
)*

### 5. Select dan Textarea
* **Penjelasan**: Menggunakan elemen `<select>` dan `<option>` untuk membuat pilihan drop-down (Program Studi) serta `<textarea>` untuk bidang input teks multibaris (Alamat).
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 11-09-05" src="https://github.com/user-attachments/assets/c0cdd0e8-931a-4fc7-9a41-87a00fe66355" />
)*

### 6. Validasi Form Dasar
* **Penjelasan**: Menerapkan atribut validasi bawaan HTML seperti `required`, `min`, `max`, dan `minlength` untuk memastikan input terisi sesuai ketentuan sebelum dikirimkan.
* **Screenshot**:
  *(<img width="667" height="99" alt="Screenshot from 2026-09-28 12-58-49" src="https://github.com/user-attachments/assets/ff1a7412-f541-4d6f-9e2a-6ae44a62e62c" />
)*

### 7. Membuat Halaman Semantic HTML
* **Penjelasan**: Menyusun struktur dokumen web menggunakan elemen semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>` agar struktur halaman lebih rapi dan memiliki makna yang jelas.
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 13-05-52" src="https://github.com/user-attachments/assets/83a8a02c-7e95-42eb-bdfd-39cf7268fc37" />
)*

### 8. Menambahkan Multimedia
* **Penjelasan**: Menyisipkan elemen multimedia berupa pemutar audio (`<audio controls>`) dan pemutar video (`<video controls>`) pada halaman web.
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 13-20-45" src="https://github.com/user-attachments/assets/2ea66fd9-a708-49e2-bcbb-e68fbee7d3ab" />
)*

### 9. Proyek Mini — Form Biodata Mahasiswa
* **Penjelasan**: Menggabungkan seluruh konsep HTML Lanjutan yang telah dipelajari (Semantic HTML, Tabel Data, Form dengan Validasi Dasar, dan Multimedia) menjadi satu halaman utuh Biodata Mahasiswa.
* **Screenshot**:
  *(<img width="1366" height="738" alt="Screenshot from 2026-09-28 13-31-37" src="https://github.com/user-attachments/assets/728ef41e-8b9b-4337-bb01-6551ced3afdf" />
)*

---

## Jawaban Pertanyaan

1. **Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?**
   * **`<table>`**: Membuat/membungkus kontainer tabel.
   * **`<tr>` (Table Row)**: Membuat baris baru dalam tabel.
   * **`<th>` (Table Header)**: Membuat sel judul/header kolom (teks dicetak tebal dan rata tengah secara default).
   * **`<td>` (Table Data)**: Membuat sel isi data biasa.

2. **Apa perbedaan `<th>` dan `<td>`?**
   * Sel `<th>` digunakan khusus untuk baris header (secara bawaan teks tebal dan di tengah), sedangkan `<td>` digunakan untuk isi data biasa (secara bawaan teks rata kiri dan berat normal).

3. **Apa fungsi `colspan` pada tabel?**
   * Atribut `colspan` digunakan untuk menggabungkan beberapa kolom menjadi satu sel secara horizontal.

4. **Apa fungsi `<form>` dalam HTML?**
   * Elemen `<form>` berfungsi sebagai kontainer penampung elemen-elemen input yang digunakan untuk mengumpulkan data dari pengguna dan mengirimkannya ke server.

5. **Apa perbedaan radio button dan checkbox?**
   * **Radio Button (`<input type="radio">`)**: Pengguna hanya dapat memilih **satu** opsi dari kelompok pilihan yang ada.
   * **Checkbox (`<input type="checkbox">`)**: Pengguna dapat memilih **satu, lebih dari satu, atau tidak memilih** opsi sama sekali.

6. **Mengapa `<label>` sebaiknya terhubung dengan id input melalui atribut `for`?**
   * Agar ketika teks pada label diklik, fokus kursor atau status pilihan otomatis berpindah ke elemen input yang bersangkutan, sehingga meningkatkan kenyamanan pengguna (*user experience*) dan keteraksesan (*accessibility*).

7. **Apa perbedaan `<textarea>` dengan input type text?**
   * `input type="text"` hanya menerima input teks **satu baris**, sedangkan `<textarea>` menerima input teks **multibaris** (panjang) seperti alamat atau deskripsi.

8. **Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?**
   * Memberikan makna (*semantic*) yang jelas pada bagian-bagian halaman web sehingga memudahkan pembacaan struktur kode oleh developer, browser, maupun mesin pencari (*SEO*).

9. **Apa fungsi `required`, `min`, `max`, dan `minlength`?**
   * **`required`**: Memaksa input wajib diisi sebelum form dikirim.
   * **`min` / `max`**: Menentukan batas nilai numerik minimum/maksimum yang diperbolehkan.
   * **`minlength`**: Menentukan batas jumlah karakter minimum pada teks input.

10. **Apa perbedaan elemen `<audio>` dan `<video>`?**
    * Elemen `<audio>` digunakan untuk memutar berkas suara saja (tanpa visual/layar), sedangkan elemen `<video>` digunakan untuk memutar berkas video lengkap dengan tampilan visual dan audio.
