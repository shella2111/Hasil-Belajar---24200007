HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk membantu dalam pemnbuatan website, HTML menggambarkan struktur halaman web dan punya serangkaian elemen HTML yang bertujuan memberitahu browser cara untuk menampilkan konten.

Elemen HTML adalah tag awal, beberapa konten dan tag akhir. Tidak semua elemen memiliki konten, ada yang disebut elemen kosong atau elemen yang tidak memiliki tag penutup seperti elemen (<br>). 

Chrome, Edge, Firefox dan Safari adalah web browser untuk membaca dokumen HTML dan menampilkannya dengan benar. Browser bukan untuk menampilkan tag HTML, tetapi digunakan untuk menentukan cara menampilkan dokumen.

Berikut ini langkah-langkah membuat halaman website menggunakan Notepad atau TextEdit:
1. Buka NotePad atau TextEdit
3. Salin kode HTML yang dibuat
4. Simpan Halaman HTML dengan nama file 'index.htm'
   ![image](https://github.com/user-attachments/assets/eeb3a744-d2c1-4f8e-8bfc-c4b008fd3412)
5. Lihat halaman HTML di browser dengan cara membuka file HTML yang sudah disimpan tadi
   ![image](https://github.com/user-attachments/assets/c0ca5cd6-c9b6-4f4a-802a-a8a0a61b507f)


Dokumen HTML WAJIB ADA <!DOCTYPE html> untuk bagian awalnya (sebelum apapun dan hanya muncul satu kali diawal). Untuk HTML5 gunakan <!DOCTYPE html>.
Selanjutnya memulai dengan <html&gt dan diakhiri dengan </html>, sedangkan untuk bagian yang terlihat berada diantara <body> dan </body>.
Judul HTML menggunakan tag <h1> to <h6>.
Paragraf HTML menggunakan tag <p>.
Tautan HTML menggunakan tag <a>.
Gambar HTML didefinisikan dengan <img> , file sumber (src) , teks alternatif (alt) , lebar (width) , tinggi(height).
Tag <br> mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup.
HTML tidak peka huruf besar/kecil, <P> artinya sama dengan <p>. Tetapi lebih baik gunakan huruf kecil.


#ATRIBUT DALAM HTML
Atribut (href) mendefinisikan hyperlink dengan tag <a>  untuk menentukan URL halaman yang dituju tautan tersebut.
Atribut (src) dengan tag <img> untuk menyematkan gambar dan menentukan jalur ke gambar yang akan ditampilkan.
Atribut (width and height) memberikan tag <img> untuk informasi ukuran sebuah gambar.
Atribut (alt) tag <img> memerlukan alt untuk menentukan teks alternatif suatu gambar.
Atribut (style) digunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.
Atribut (lang) sertakan dalam <html> untuk mendeklarasikan bahasa halaman Web. Misal menentukan bahasa inggris <html lang="en"> dan untuk bahasa inggris sebagai bahasa dan negara <html lang="en-US"mg>.
Atribut (title) mendefinisikan beberapa informasi tambahan tentang suatu elemen.


Judul HTML penting untuk mesin pencari mengindeks struktur dan konten halaman website.
<h1> Judul harus digunakan untuk judul utama dengan ukuran besar, lalu <h2> hingga <h6> adalah subjudul karena akurannya akan mengecil. Untuk menentukan ukuran setiap judul bisa menggunakan atribut style dan properti CSS font-size:, contoh: <h1 style="font-size:60px;">Heading 1</h1>


Tag <p> mendefinisikan sebuah paragraf.
Tag <hr> untuk memisahkan konten di halaman HTML. Menggunakan tag <hr> untuk memberikan pemisah antara paragraf satu dengan paragraf lainnya dengan garis horizontal.
Tag <br> untuk memberikan spasi, sebagai pemutus baris HTML.
Tag <p> bisa diganti dengan <pre> untuk mempertahankan spasi yang kita beri sebelumnya.


ATRIBUT STYLE DALAM HTML (HTML STYLE)
background-color: Mengatur warna latar belakang elemen.
color: Mengatur warna teks.
font-family: Mengatur jenis font.
font-size: Mengatur ukuran teks.
text-align: Mengatur perataan teks (misalnya: kiri, tengah, kanan).


PEFORMATAN DALAM TEKS HTML
<b>: Membuat teks tebal tanpa makna khusus.
<strong>: Membuat teks tebal dengan arti penting.
<i>: Membuat teks miring, sering digunakan untuk istilah teknis atau bahasa asing.
<em>: Menekankan teks (dibaca dengan penekanan oleh screen reader).
<mark>: Menyoroti teks.
<small>: Menampilkan teks lebih kecil.
<del>: Menunjukkan teks yang dihapus (coretan).
<ins>: Menunjukkan teks yang ditambahkan (garis bawah).
<sub>: Menampilkan teks subscript (misalnya rumus kimia: H₂O).
<sup>: Menampilkan teks superscript (misalnya pangkat: x²).


KUTIPAN DAN REFERENSI DALAM HTML
<blockquote>: untuk definisikan bagian yang dikutip dari sumber lain.
<q>: untuk definisikan kutipan pendek (ada tanda kutip).
<abbr>: untuk definisikan singkatan.
<address>: untuk definisikan informasi penulis (ditampilkan italic).
<cite>: untuk definisikan judul suatu karya (ditampilkan italic).
<bdo>: untuk mengganti arah teks saat ini.

KOMENTAR HTML
Tag Komentar HTML Untuk menambahkan komentar ke sumber HTML perlu menggunakan sintaks berikut:
<!-- Write your comments here -->
ini tidak ditampilkan di browser

Dengan komentar kita dapat:
menempatkan pemberitahuan dan pengingat dalam kode HTML
menyembunyikan konten sementara
menyembunyikan konten sebaris


PENGGUNAAN NAMA WARNA DALAM HTML
Tomato: merah
Orange: orange
DodgerBlue: biru
MediumSeaGreen: hijau
Gray: abu-abu
SlateBlue: Ungu
Violet: pink
LightGray: abu-abu muda

Warna Teks Contoh penggunaan:
<h1 style="color:Tomato;">Hello World</h1>

Warna Batas Contoh penggunaan:
<h1 style="border:2px solid Tomato;">Hello World</h1>

Nilai Warna (stabilo) Contoh penggunaan:
<h1 style="background-color:rgb(255, 99, 71);">... </h1>


