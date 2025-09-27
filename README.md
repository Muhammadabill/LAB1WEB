## 📘 README.md — Praktikum 1 HTML Dasar

* Nama :Muhammad Nabil Satria Suntara
* NIM : 312410365
* Kelas : TI.24.A.4
* Mata Kuliah : Pemograman Web 1
* Praktikum 1 : HTML Dasar
* Dosen : Agung Nugroho, S.Kom., M.Kom.

---

## **Tugas nya**
![WhatsApp Image 2025-09-27 at 09 42 39](https://github.com/user-attachments/assets/c4f90dca-033a-4a1b-a8bc-2fbb3aefb4c8)


### **Langkah-langkah Praktikum**

#### 1. Membuat Struktur Dasar HTML

Pertama membuat file `lab1_tag_dasar.html` berisi struktur dasar HTML.


```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="author" content="Mahasiswa UPB">
    <meta name="keywords" content="HTML, Pemrograman Web, UPB">
    <meta name="description" content="Praktikum HTML Dasar">
    <title>Praktikum 1 - HTML Dasar</title>
</head>
<body>

    <!-- Link Navigasi -->
    <nav>
        <a href="lab1_tag_dasar.html" target="_self">Dasar HTML</a> |
        <a href="lab1_halaman2.html" target="_self">Halaman 2</a> |
        <a href="http://www.google.com" target="_blank">Google</a>
    </nav>
    <hr>

    <!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya ZAENAL MAULANA RIZKI dengan <b> NIM 312410332 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>

    <!-- Sub Judul Gambar -->
    <h3>Universitas Pelita Bangsa</h3>
    <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-768x584.png" width="200" alt="Logo UPB" title="Logo Universitas Pelita Bangsa">

</body>
</html>
```

<img width="2180" height="2192" alt="code" src="https://github.com/user-attachments/assets/4cff0091-57d6-4e01-9d2f-92e9df70be89" />

---

#### 2. Membuat Paragraf

Menambahkan tag `<p>` untuk membuat paragraf.

```html
<p alig="center">
        Nama saya Muhammad Nabil Satriya Suntara dengan <b> NIM 312410 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>
```

<img width="907" height="110" alt="code" src="https://github.com/user-attachments/assets/0d67ad27-342d-481b-be1c-57bf12e8dd1d" />


---

#### 3. Menambahkan Judul (Heading)

Menambahkan heading `<h1>` dan `<h2>` sebelum paragraf.

```html
<!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya Muhammad Nabil Satriya Suntara dengan <b> NIM 312410365 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>
```

<img width="3250" height="862" alt="code1" src="https://github.com/user-attachments/assets/f5227cd3-525b-4f1b-89e1-88c22b647244" />


---

#### 4. Memformat Teks

Menggunakan tag `<b>`, `<i>`, `<sub>`, `<sup>` untuk memformat teks.

```html
<!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya Muhammad Nabil Satriya Suntara dengan <b> NIM 312410365 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>

<img width="922" height="154" alt="image" src="https://github.com/user-attachments/assets/618a36ba-ffce-4b33-9a46-82b061ec3efe" />


---

#### 5. Menyisipkan Gambar

Menggunakan tag `<img>` dengan atribut `src`, `title`, dan `alt`.

```html
<h3>Universitas Pelita Bangsa</h3>
<img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-768x584.png" width="200" alt="Logo UPB" title="Logo Universitas Pelita Bangsa">
```

<img width="156" height="140" alt="image" src="https://github.com/user-attachments/assets/fc060233-6880-44f7-af03-4f5699a7bf3d" />


---

#### 6. Menambahkan Hyperlink

Menambahkan navigasi link menggunakan tag `<a>` dengan berbagai target.

```html
<nav>
    <a href="lab1_tag_dasar.html" target="_self">Dasar HTML</a> |
    <a href="lab1_halaman2.html" target="_blank">Halaman 2</a> |
    <a href="http://www.google.com" target="_top">Google</a>
</nav>

<img width="1296" height="482" alt="code2" src="https://github.com/user-attachments/assets/0e05c7a1-62bd-4444-a959-38cb75b49838" />

---

### **Jawaban Pertanyaan Praktikum**

```
![WhatsApp Image 2025-09-27 at 10 25 11 (1)](https://github.com/user-attachments/assets/4c4358dc-86e9-422a-8796-8c84cfea93e6)
```


1. Jika ada salah penulisan tag, HTML tetap ditampilkan tetapi hasilnya bisa berantakan atau tidak sesuai (tidak error fatal).
2. `<p>` membuat paragraf baru dengan spasi otomatis, sedangkan `<br>` hanya pindah baris.
3. `alt` menampilkan teks pengganti gambar (aksesibilitas), `title` menampilkan tooltip saat kursor diarahkan.
4. Untuk menjaga proporsional, cukup isi salah satu (width atau height), jangan keduanya dengan nilai sembarangan.
5. `target="_blank"` buka tab baru, `_self` di halaman sama, `_top` di jendela penuh, `_parent` di frame induk.

---

### **Kesimpulan**

Dalam praktikum ini saya belajar:

* Struktur dasar HTML
* Tag heading, paragraf, pemformatan teks
* Penyisipan gambar
* Penggunaan hyperlink dengan atribut `target`

---
