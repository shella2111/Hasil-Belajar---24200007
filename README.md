HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk membantu dalam pemnbuatan website, HTML menggambarkan struktur halaman web dan punya serangkaian elemen HTML yang bertujuan memberitahu browser cara untuk menampilkan konten.

Elemen HTML adalah tag awal, beberapa konten dan tag akhir. Tidak semua elemen memiliki konten, ada yang disebut elemen kosong atau elemen yang tidak memiliki tag penutup seperti elemen (<br>). 

Chrome, Edge, Firefox dan Safari adalah web browser untuk membaca dokumen HTML dan menampilkannya dengan benar. Browser bukan untuk menampilkan tag HTML, tetapi digunakan untuk menentukan cara menampilkan dokumen.

Berikut ini langkah-langkah membuat halaman website menggunakan Notepad atau TextEdit:
1. Buka NotePad atau TextEdit
2. Salin kode HTML yang dibuat
   Contoh kodenya:
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>


4. Simpan Halaman HTML dengan nama file 'index.htm'
5. Lihat halaman HTML di browser dengan cara membuka file HTML yang sudah disimpan tadi
6. Selesai

WAJIB dimulai dengan <!DOCTYPEhtml> (untuk mewakili jenis dokumen, HARUS diawal).
<!DOCTYPE html> deklarasi untuk HTML5.
Memulai dengan <html> diakhiri dengan </html>.
Judul HTML menggunakan tag <h1> to <h6>.
Paragraf HTML menggunakan tag <p>.
Tautan HTML menggunakan tag <a>.
Gambar HTML didefinisikan dengan <img> , file sumber (src) , teks alternatif (alt) , (width) , (height)
Elemen HTML tanpa konten disebut ELEMEN KOSONG.
Tag <br> mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup.
HTML tidak peka huruf besar/kecil, <P> artinya sama dengan <p>. Tetapi lebih baik gunakan huruf kecil.

Semua elemen HTML dapat memiliki atribut.
Atribut (href) menentukan <a> URL halaman yang dituju tautan tersebut.
Atribut (src) menentukan <img> jalur ke gambar yang akan ditampilkan.
Atribut (width and height) memberikan <img> informasi ukuran untuk gambar.
Atribut (alt) menyediakan <img> teks alternatif untuk gambar.
Atribut (style) digunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.
Atribut langtag <html> mendeklarasikan bahasa halaman Web.
Atribut (title) mendefinisikan beberapa informasi tambahan tentang suatu elemen.

an: Peramban secara otomatis menambahkan spasi (margin) sebelum dan sesudah judul.

Judul HTML penting untuk mesin pencari mengindeks struktur dan konten halaman website.
<h1> Judul harus digunakan untuk judul utama, diikuti oleh <h2> sub-judul, lalu yang kurang penting <h3> dan seterusnya.
Setiap judul HTML memiliki ukuran default. Untuk menentukan ukuran setiap judul dengan styleatribut, gunakan properti CSS font-size seperti ini:
<h1 style="font-size:60px;">Heading 1</h1>

Elemen HTML <p>mendefinisikan sebuah paragraf.
Sebuah paragraf selalu dimulai pada baris baru dan web browser secara otomatis menambahkan spasi (margin) sebelum dan sesudah paragraf. Contohnya seperti berikut ini:
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
Tag ini <hr>mendefinisikan pemisah tematik pada halaman HTML, dan paling sering ditampilkan sebagai aturan horizontal. Elemen ini <hr>digunakan untuk memisahkan konten (atau menentukan perubahan) di halaman HTML, Contohnya:
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
Tag tersebut <hr>adalah tag kosong, artinya tidak memiliki tag akhir.

Elemen HTML <br> mendefinisikan jeda baris, tag kosong, artinya tidak memiliki tag akhir. Gunakan <br> jika menginginkan jeda baris (baris baru) tanpa memulai paragraf baru, Contohnya:
<p>This is<br>a paragraph<br>with line breaks.</p>

Elemen HTML <pre>mendefinisikan teks yang telah diformat sebelumnya. Teks di dalam <pre> elemen ditampilkan dalam font dengan lebar tetap (biasanya Courier), dan mempertahankan spasi dan jeda baris.
