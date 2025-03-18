# PENGANTAR HTML
HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk membantu dalam pemnbuatan website, HTML menggambarkan struktur halaman web dan punya serangkaian elemen HTML yang bertujuan memberitahu browser cara untuk menampilkan konten.
chrome, Edge, Firefox dan Safari adalah web browser untuk membaca dokumen HTML dan menampilkannya dengan benar. Browser bukan untuk menampilkan tag HTML, tetapi digunakan untuk menentukan cara menampilkan dokumen.

# HTML EDITOR
Berikut ini langkah-langkah membuat halaman website menggunakan Notepad atau TextEdit:
1. Buka NotePad atau TextEdit
2. Salin kode HTML yang dibuat
3. Simpan Halaman HTML dengan nama file 'index.htm'
   ![image](https://github.com/user-attachments/assets/eeb3a744-d2c1-4f8e-8bfc-c4b008fd3412)
4. Lihat halaman HTML di browser dengan cara membuka file HTML yang sudah disimpan tadi
   ![image](https://github.com/user-attachments/assets/c0ca5cd6-c9b6-4f4a-802a-a8a0a61b507f)

# HTML BASIC
Dokumen HTML **WAJIB ADA** `<!DOCTYPE html>` untuk bagian awalnya (sebelum apapun dan hanya muncul satu kali di awal).  
Untuk **HTML5**, gunakan `<!DOCTYPE html>`.
Selanjutnya memulai dengan `<html>` dan diakhiri dengan `</html>`,  sedangkan untuk bagian yang terlihat berada di antara `<body>` dan `</body>`.
**Judul HTML** menggunakan tag `<h1>` sampai `<h6>`.  
**Paragraf HTML** menggunakan tag `<p>`.  
**Tautan HTML** menggunakan tag `<a>`.  
**Gambar HTML** didefinisikan dengan `<img>`, file sumber (`src`), teks alternatif (`alt`), lebar (`width`), tinggi (`height`).  
Tag `<br>` mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup.  
HTML tidak peka huruf besar/kecil, `<P>` artinya sama dengan `<p>`, tetapi lebih baik gunakan huruf kecil.


# ATRIBUT DALAM HTML
Atribut (href) mendefinisikan hyperlink dengan tag <a>  untuk menentukan URL halaman yang dituju tautan tersebut.
Atribut (src) dengan tag <img> untuk menyematkan gambar dan menentukan jalur ke gambar yang akan ditampilkan.
Atribut (width and height) memberikan tag <img> untuk informasi ukuran sebuah gambar.
Atribut (alt) tag <img> memerlukan alt untuk menentukan teks alternatif suatu gambar.
Atribut (style) digunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.
Atribut (lang) sertakan dalam <html> untuk mendeklarasikan bahasa halaman Web. Misal menentukan bahasa inggris <html lang="en"> dan untuk bahasa inggris sebagai bahasa dan negara <html lang="en-US"mg>.
Atribut (title) mendefinisikan beberapa informasi tambahan tentang suatu elemen.

# HTML HEADINGS
Judul HTML penting untuk mesin pencari mengindeks struktur dan konten halaman website. `<h1>` Judul harus digunakan untuk judul utama dengan ukuran besar, lalu `<h2>` hingga `<h6>` adalah subjudul karena akurannya akan mengecil. Untuk menentukan ukuran setiap judul bisa menggunakan atribut style dan properti CSS font-size:, contoh: `<h1 style="font-size:60px;">Heading 1</h1>`

# HTML PARAGRAPH
- Tag `<p>` mendefinisikan sebuah paragraf.
- Tag `<hr>` untuk memisahkan konten di halaman HTML dengan garis horizontal.
- Tag `<br>` untuk memberikan spasi, sebagai pemutus baris HTML.
- Tag `<p>` bisa diganti dengan `<pre>` untuk mempertahankan spasi yang kita beri sebelumnya.

# HTML STYLE
- `background-color`: Mengatur warna latar belakang elemen.
- `color`: Mengatur warna teks.
- `font-family`: Mengatur jenis font.
- `font-size`: Mengatur ukuran teks.
- `text-align`: Mengatur perataan teks (misalnya: kiri, tengah, kanan).

# HTML FORMATTING
- `<b>`: Membuat teks **tebal** tanpa makna khusus.
- `<strong>`: Membuat teks **tebal** dengan arti penting.
- `<i>`: Membuat teks *miring*, sering digunakan untuk istilah teknis atau bahasa asing.
- `<em>`: Menekankan teks (*dibaca dengan penekanan oleh screen reader*).
- `<mark>`: Menyoroti teks.
- `<small>`: Menampilkan teks lebih kecil.
- `<del>`: Menunjukkan teks yang dihapus (coretan).
- `<ins>`: Menunjukkan teks yang ditambahkan (garis bawah).
- `<sub>`: Menampilkan teks subscript (misalnya rumus kimia: H₂O).
- `<sup>`: Menampilkan teks superscript (misalnya pangkat: x²).

# HTML QUOTATIONS
- `<blockquote>`: Untuk mendefinisikan bagian yang dikutip dari sumber lain.
- `<q>`: Untuk mendefinisikan kutipan pendek (ada tanda kutip).
- `<abbr>`: Untuk mendefinisikan singkatan.
- `<address>`: Untuk mendefinisikan informasi penulis (*ditampilkan italic*).
- `<cite>`: Untuk mendefinisikan judul suatu karya (*ditampilkan italic*).
- `<bdo>`: Untuk mengganti arah teks saat ini.

# HTML COMMENTS
Tag Komentar HTML Untuk menambahkan komentar ke sumber HTML perlu menggunakan sintaks berikut:
<!-- Write your comments here -->
Dengan komentar kita dapat:
- menempatkan pemberitahuan dan pengingat dalam kode HTML
- menyembunyikan konten sementara
- menyembunyikan konten sebaris

# HTML COLOUR
- Tomato: merah
- Orange: orange
- DodgerBlue: biru
- MediumSeaGreen: hijau
- Gray: abu-abu
- SlateBlue: Ungu
- Violet: pink
- LightGray: abu-abu muda

Contoh penggunaan untuk warna teks:
`<h1 style="color:Tomato;">Hello World</h1>`

Contoh penggunaan untuk warna batas:
`<h1 style="border:2px solid Tomato;">Hello World</h1>`

Contoh penggunaan untuk nilai warna:
`<h1 style="background-color:rgb(255, 99, 71);">... </h1>`

# HTML CSS
CSS (Cascading Style Sheets) digunakan untuk memformat tata letak halamat web.

- Berikut adalah elemen CSS HTML:
`<style>` : untuk menentukan CSS internal
`<link>` : untuk merujuk ke file CSS eksternal
`<head>` : untuk menyimpan elemen `<style>` dan `<link>`
   
- Berikut adalah properti CSS HTML:
color : untuk warna teks
font-family : untuk font teks
font size : untuk ukuran teks
border : untuk batas
padding : untuk spasi di dalam perbatasan
margin : untuk spasi di laur batas

# HTML LINK
Ketika diklik tautannya dapat melompat ke dokumen lain. Tag yang digunakan <a> memiliki sintaks ini `<a href="url">Link text</a>`

Atribut Target (menentukan tempat untuk membuka dokumen yang ditautkan)
_self: Default. Membuka dokumen di jendela/tab yang sama saat diklik
_blank: Membuka dokumen di jendela atau tab baru
_parent: Membuka dokumen di bingkai induk
_top: Membuka dokumen di badan penuh jendela
URL Absolut vs. URL Relatif Menggunakan atribut href. Bedanya kalau Absolut (web lengkap), sedangkan relative (tanpa bagian "https://wwww")

# HTML IMAGE
Tag `<img>` memerlukan dua atribut:
src : Menentukan jalur ke gambar
alt : Menentukan teks alternatif untuk gambar

Berikut sintaksisnya,
`<img src="url" alt="alternatetext">`

Gunakan HTML width adn height untuk ukuran lebar dan tinggi gambar
Gunakan properti CSS float untuk membiarkan gambar melayang ke kanan dan ke kiri


# HTML FAVICON
Cara menambahkan favicon di HTML:
- simpan gambar favicon Anda ke direktori akar server web Anda, atau buat folder di direktori akar yang disebut gambar
- simpan gambar favicon Anda di folder ini. Nama umum untuk gambar favicon adalah "favicon.ico"
- tambahkan `<link>` elemen ke file "index.html" Anda, setelah `<title>` elemen
- simpan berkas "index.html" dan muat ulang di peramban

# HTML PAGE TITTLE
Elemen `<title>` mendefinisikan judul di bilah alat browser, memberikan judul untuk halaman saat ditambahkan ke favorit dan menampilkan judul halaman di hasil mesin pencari.

# HTML TABLE
Setiap sel tabel didefinisikan oleh tag `<td>` dan `</td>`
Berikut adalah tag yang dipakai dalam membuat tabel di HTML:
`<table>` : mendefinisikan sebuah tabel
`<th>` : mendefinisikan judul tabel
`<tr>` : mendefinisikan baris dalam tabel
`<td>` : mendefinisikan sel dalam tabel
`<caption>` : mendefinisikan keterangan tabel
`<colgroup>` : menentukan grup dari satu kolom atau lebih di sebuah tabel untuk pemformatan.
`<col>` : menentukan properti kolom untuk setiap kolom dalam elemen <colgroup>
`<thead>` : mengelompokkan konten header dalam sebuah tabel
`<tbody>` : mengelompokkan konten body dalam sebuah tabel
`<tfoot>` : mengelompokkan konten footer dalam sebuah tabel


# HTML LISTS
Daftar HTML Tidak Berurut (pakai dot)
Dimulai dengan tag `<ul>`, setiap item dalam daftar dimulai dengan `<li>`
Daftar HTML yang Diurutkan (pakai nomor) Dimulai dengan tag `<ol>`, setiap item dalam daftar dimulai dengan `<li>`
Daftar Deskripsi HTML
`<dl>` : untuk mendefinisikan daftar deskripsi
`<dt>` : untuk mendefinisikan istilah (nama)
`<dd>` : untuk mendeskripsikan setiap istilah

# HTML BLOCK & INLINE
Dua elemen blok yang umum digunakan adalah:
`<p>` : mendefinisikan paragraf dalam dokumen HTML
`<div>` : mendefinisikan divisi atau bagian dalam dokumen HTML
`<span>` digunakan untuk memborder kata yang dipilih saja. Jika digabungkan dengan CSS maka dapat memberi gaya pada bagian teks namun memerlukan atribut style, class, dan id.

# HTML DIV
Untuk Kalimat dengan menggunakan `<div>`
Untuk blok semua kalimat maka letakkan `<div>` sebelum menaruhkan elemen lainnya
Untuk blok rata tengah maka atur margin properti CSS ke auto
Untuk blok paragraf yang berbeda maka tambahkan beberapa <div> pada halaman yang sama.
Untuk blok berdampingan pakai properti CSS `<float>` ini hasilnya akan mepet, jika ingin ada celah maka pakai in-line block.

# HTML CLASSES
Atribut kelas digunakan untuk menunjuk ke nama kelas dalam style sheet.
Nama kelas peka pada huruf kecil dan besar
getElementsByClassName() digunakan JavaScript untuk mengakses elemen dengan nama kelas tertentu.

# HTML ID
Digunakan untuk menentukan id unik untuk elemen HTML. Nama id peka dengan huruf kecil dan besar. Setidaknya atribut id mengandung satu karakter, tidak dapat dimulai dengan angka, dan tidak boleh spasi.
- Atribut id
Nilai atribut id harus unik dalam dokumen HTML. Atribut ini iddigunakan untuk menunjuk ke deklarasi gaya tertentu dalam lembar gaya.
- Perbedaan antara kelas dan id
Kelas bisa digunakan oleh beberapa elemen HTML sedangkan nama id hanya boleh digunakan oleh satu elemen HTML saja.
- Bookmark HTML dengan ID dan Tautan
Untuk menggunakan bookmark, harus membuatnya terlebih dahulu, lalu menambahkan tautan ke dalamnya. Lalu, saat tautan diklik, halaman akan bergulir ke lokasi yang terdapat penanda halaman.
- Menggunakan atribut id di JavaScript
JavaScript dapat mengakses elemen dengan id tertentu dengan getElementById().

# HTML IFRAME
Digunakan untuk menampilkan halaman web di dalam halaman web. Sintaksisnya adalah sebagai berikut: `<iframe src="url" title="description"></iframe>`
- Mengatur tinggi dan lebar Iframe
Gunakan atribut height dan width.
- Hapus batasan
Dengan cara tambahkan style dan gunakan properti CSS border.
- Target untuk tautan
Atribut targettautan harus merujuk ke nameatribut iframe.

# HTML JAVASCRIPT
Ada 2 tag HTML yang digunakan yaitu:
`<script>` untuk mendefinisikan skrip sisi klien (JavaScript)
`<nonscript>` untuk mendefinisikan konten alternatif yang akan ditampilkan kepada pengguna yang telah menonaktifkan skrip di browser mereka.

# HTML FILE PATHS
1. Jalur Berkas HTML Jalur berkas menggambarkan lokasi berkas dalam struktur folder situs web. Jalur berkas digunakan saat menautkan ke berkas eksternal, seperti:
- Halaman web
- Gambar
- Lembar gaya
- JavaScript dalam bahasa Inggris
  
2. Jalur File Absolut
URL lengkap ke suatu berkas.

3. Jalur File Relatif
Menunjuk ke berkas yang relatif terhadap halaman saat ini.

# HTML HEAD
`<head>` : untuk metadata (data tentang data) diletakkan antara <html> dan <body>.
`<title>` : untuk menentukan judul dokumen.
`<style>` : untuk menentukan informasi gaya untuk satu halaman HTML.
`<link>` : untuk mendefinisikan hubungan antara dokumen saat ini dan sumber daya eksternal.
`<meta>` : untuk menentukan set karakter, deskripsi halaman, kata kunci, penulis dokumen, dan pengaturan viewport (area yang terlihat oleh pengguna di halaman web).
`<script>` : untuk mendefinisikan JavaScript sisi klien.
`<base>` : menentukan URL dasar dan/atau target untuk semua URL relatif di suatu halaman.

# HTML LAYOUT
`<header>` : Menentukan header untuk dokumen atau bagian
`<nav>` : Menentukan sekumpulan tautan navigasi
`<section>` : Menentukan bagian dalam dokumen
`<article>` : Mendefinisikan konten yang independen dan mandiri
`<aside>` : Mendefinisikan konten selain konten (seperti sidebar)
`<footer>` : Menentukan footer untuk dokumen atau bagian
`<details>` : Menentukan detail tambahan yang dapat dibuka dan ditutup oleh pengguna sesuai permintaan
`<summary>` : Menentukan judul untuk <details> elemen

Ada 4 teknik tata letak HTML
1. Kerangka kerja CSS: menggunakan kerangka kerja CSS, seperti W3.CSS atau Bootstrap .
2. Properti float CSS
3. Kotak fleksibel CSS: memastikan bahwa elemen berperilaku sesuai prediksi saat tata letak halaman harus mengakomodasi berbagai ukuran layar dan perangkat tampilan yang berbeda.
4. Jaringan CSS: dengan baris dan kolom, sehingga memudahkan dalam mendesain halaman web tanpa harus menggunakan float dan pemosisian.

# HTML RESPONSIVE
tentang penggunaan HTML dan CSS untuk secara otomatis mengubah ukuran, menyembunyikan, mengecilkan, atau memperbesar situs web, agar terlihat bagus di semua perangkat (desktop, tablet, dan ponsel).
- Mengatur viewport: dengan menambahkan `<meta>` ke semua halaman web.
- Gambar responsif: gambar yang skalanya dapat disesuaikan dengan ukuran browser apa pun. Kalau pakai width maka bisa di zoom, sedangkan kalau pakai max-width maka tidak bisa dizoom besar dari ukuran aslinya.
- Menampilkan Gambar Berbeda Tergantung pada Lebar Browser: `<picture>` untuk menentukan gambar yang berbeda untuk ukuran jendela browser yang berbeda.
- Ukuran Teks Responsif: Ukuran teks dapat diatur dengan satuan "vw", yang berarti "lebar tampilan".

# HTML COMPUTER CODE
`<kbd>` : mendefinisikan input keyboard
`<samp>` : mendefinisikan contoh keluaran dari program komputer
`<code>` : mendefinisikan sepotong kode komputer
`<var>` : mendefinisikan variabel dalam pemrograman atau dalam ekspresi matematika
`<pre>` : endefinisikan teks yang telah diformat sebelumnya

# HTML SEMANTIC ELEMENTS
`<article>` : mendefinisikan konten independen dan mandiri
`<aside>` : menentukan konten selain konten halaman
`<details>` : menentukan detail tambahan yang dapat dilihat atau disembunyikan oleh pengguna
`<figcaption>` : menentukan judul untuk elemen <figure>
`<figure>` : menentukan konten mandiri, seperti ilustrasi, diagram, foto, daftar kode, dll.
`<footer>` : menentukan footer untuk dokumen atau bagian
`<header>` : menentukan header untuk dokumen atau bagian
`<main>` : menentukan konetn utama suatu dokumen
`<mark>` : menentukan teks yang ditandai/disorot
`<nav>` : mendefinisikan tautan navigasi
`<section>` : menentukan bagian dalam dokumen
`<summary>` : menentukan judul yang terlihat untuk elemen <details>
`<time>` : menentukan tanggal/waktu

# HTML STYLE GUIDE
- Deklarasi Tipe Dokumen: Selalu mulai dokumen HTML dengan deklarasi tipe dokumen `<!DOCTYPE html>` untuk memastikan browser mengenali versi HTML yang digunakan.
- Penggunaan Huruf Kecil untuk Nama Elemen: Meskipun HTML tidak peka huruf besar-kecil, disarankan menggunakan huruf kecil untuk nama elemen agar konsisten dan mudah dibaca.
- Penutupan Semua Elemen HTML: Meskipun beberapa elemen HTML tidak wajib ditutup, sebaiknya tetap menutup semua elemen untuk menjaga struktur kode yang rapi dan mencegah kesalahan.
- Penggunaan Huruf Kecil untuk Nama Atribut: Seperti nama elemen, disarankan menggunakan huruf kecil untuk nama atribut demi konsistensi dan kemudahan pembacaan.
- Penggunaan Tanda Kutip untuk Nilai Atribut: Meskipun HTML mengizinkan nilai atribut tanpa tanda kutip, praktik terbaiknya adalah selalu menggunakan tanda kutip untuk menghindari potensi kesalahan.
- Inden dan Spasi: Gunakan indentasi dan spasi yang konsisten untuk membuat kode lebih mudah dibaca dan dipahami oleh pengembang lain.

# HTML ENTTITIES
1. Entitas Karakter HTML, Beberapa karakter seperti <, >, dan & punya makna khusus di HTML, jadi perlu ditulis dalam bentuk entitas agar tidak dianggap sebagai kode.
2. Ruang tanpa putus, Spasi yang tidak akan terputus menjadi baris baru. Tanda hubung tidak putus ( ‑ ) digunakan untuk menentukan karakter tanda hubung (‑) yang tidak putus pada baris baru.

# HTML SYMBOLS
![image](https://github.com/user-attachments/assets/8ed15aa9-091c-44f5-8b43-ba90c6fc1bc1)
![image](https://github.com/user-attachments/assets/05d5bc09-67b1-419b-8043-4e6628cfe5a2)
![image](https://github.com/user-attachments/assets/28c26812-f8bd-4c77-8fec-2d515acbbbd5)

# HTML EMOJI
![image](https://github.com/user-attachments/assets/08f7b3ce-889d-4503-bad2-b46656007a0a)

# HTML CHARSETS
HTML Character Encoding adalah cara menentukan bagaimana karakter ditampilkan di halaman web.  

### **Jenis Character Set yang Umum Digunakan**  
1. **UTF-8** (Universal) → Mencakup hampir semua karakter dan simbol di dunia. Disarankan untuk HTML5.  
   - Contoh: `<meta charset="UTF-8">`  
2. **ASCII** → Standar awal dengan 128 karakter (huruf, angka, dan simbol dasar).  
3. **ANSI (Windows-1252)** → Mirip ASCII tetapi memiliki karakter tambahan dari 128-159.  
4. **ISO-8859-1** → Standar HTML4, mirip dengan ANSI tetapi tanpa karakter dari 128-159.  
   - Contoh: `<meta charset="ISO-8859-1">`  

### **Perbandingan Singkat**  
- **ASCII**: Hanya mendukung karakter dasar (0-127).  
- **ANSI**: Tambahan karakter khusus (128-255).  
- **ISO-8859-1**: Sama seperti ANSI tapi tanpa karakter 128-159.  
- **UTF-8**: Fleksibel, mencakup karakter global hingga 10.000 lebih.  

Untuk kompatibilitas terbaik, gunakan **UTF-8** dalam pengkodean HTML modern.

# HTML URL ENCODE
1. URL - Pencari Sumber Daya Seragam
skema : mendefinisikan jenis layanan Internet (yang paling umum adalah http atau https )
awalan : mendefinisikan awalan domain (default untuk http adalah www )
domain : mendefinisikan nama domain Internet (seperti w3schools.com)
port : menentukan nomor port pada host (default untuk http adalah 80 )
path : menentukan jalur di server (Jika dihilangkan: direktori root situs)
nama file : menentukan nama dokumen atau sumber daya

2. Skema URL Umum
http (HyperText Transfer Protocol) : Halaman web umum. Tidak dienkripsi
https (Secure HyperText Transfer Protocol) :halaman web aman. dienkripsi
ftp (File Transfer Protocol) : download atau upload file
file : file di komputer

3. Pengkodean URL
Pengkodean URL mengganti karakter non-ASCII dengan "%" diikuti oleh digit heksadesimal. URL tidak boleh mengandung spasi. Pengkodean URL biasanya mengganti spasi dengan tanda tambah (+), atau %20.

# HTML VS XHTML
XHTML adalah versi HTML yang lebih ketat dan berbasis XML. Adapun Perbedaan Utama XHTML dengan HTML sebagai berikut.
1. Struktur lebih ketat: Semua elemen harus tertutup dengan benar dan bersarang dengan benar.
2. Penulisan lebih rapi: Semua tag dan atribut harus dalam huruf kecil.
3. Wajib menggunakan DOCTYPE: Setiap dokumen XHTML harus memiliki deklarasi DOCTYPE.
4. Atribut harus dikutip: Nilai atribut harus selalu dalam tanda kutip. Tidak boleh ada atribut yang dipersingkat: Contohnya, checked="checked" bukan hanya checked.
5. Elemen kosong harus ditutup: Seperti `<br />, <hr />, dan <img src="image.jpg" alt="desc" />`.

Contoh XHTML yang benar:
`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"`  
  `"http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">`
`<html xmlns="http://www.w3.org/1999/xhtml">`
`<head>`
  `<title>Judul Dokumen</title>`
`</head>`
`<body>`
  `<p>`Ini adalah paragraf.`</p>`
  `<img src="image.jpg" alt="Gambar contoh" />`
`</body>`
`</html>`
