# Web1Lab1
## Belajar Tag Dasar HTML

###  Membuat Paragraf

### Membuat Repository:
![Gambar 1](screenshot/Screenshot1.png)
![Gambar 1](https:https://lh3.googleusercontent.com/d/1WFlZwvYPFevWCtxjWeaCThBG38lDDNKK)

1. Apa fungsi deklarasi <-!DOCTYPE html> pada dokumen HTML?
Jawaban:
Deklarasi <-!DOCTYPE html> berfungsi untuk menyatakan kepada browser bahwa dokumen tersebut menggunakan standar HTML5. Deklarasi ini diletakkan pada bagian paling awal dokumen agar browser dapat merender halaman web dengan benar dan sesuai standar.   
2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Jawaban:Tag: Penanda awalan dan akhiran dari sebuah elemen yang ditulis dengan kurung siku (<...> dan </...>), contoh: <p> dan </p>.   Elemen: Komponen lengkap yang menyusun dokumen HTML, terdiri dari kombinasi tag pembuka, konten/isi, dan tag penutup (serta atribut jika ada). Contoh: <p>Ini paragraf</p>.   Atribut: Informasi/properti tambahan yang diberikan kepada suatu elemen, ditulis pada tag pembuka. Contoh: bgcolor="blue" atau href="...".   
3. Apa perbedaan <p> dengan <br>? Jelaskan penggunaannya.
Jawaban:<p> (Paragraf): Digunakan untuk membuat blok paragraf teks. Tag ini membutuhkan tag penutup (</p>) dan secara otomatis memberikan spasi/jarak sebelum dan sesudah paragraf.   <br> (Break): Digunakan untuk membuat pindah baris (line break) baru di dalam teks tanpa membuat blok paragraf baru. Tag ini merupakan self-closing tag (tidak membutuhkan tag penutup).   
4. Apa fungsi atribut href pada tag <a>?
Jawaban: Atribut href (Hypertext Reference) berfungsi untuk menentukan alamat tujuan/URL dari sebuah hyperlink atau penanda lokasi (anchor) yang akan dituju saat elemen link diklik.   
5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?Jawaban:Hyperlink Internal: Mengarah ke dokumen/halaman web lain dalam repositori/server yang sama menggunakan relative path (contoh: <a href="halaman2.html">).   Hyperlink Eksternal: Mengarah ke halaman/website di luar domain/server sendiri dengan menyertakan URL lengkap/absolut beserta protokolnya (contoh: <a href="[https://www.google.com](https://www.google.com)">).   
6. Apa fungsi atribut src dan alt pada tag <img>?
Jawaban:src (source): Menentukan lokasi file atau URL gambar yang akan ditampilkan.   alt (alternate text): Menyediakan deskripsi alternatif berupa teks jika gambar gagal dimuat atau saat dibaca oleh screen reader.   
7. Apa perbedaan penggunaan <ul> dan <ol>?
Jawaban:<ul> (Unordered List): Digunakan untuk membuat daftar item tak berurutan yang umumnya ditampilkan menggunakan penanda bullet.   <ol> (Ordered List): Digunakan untuk membuat daftar item berurutan yang ditampilkan dengan penomoran (angka, huruf, atau angka romawi).   
8. Apa yang terjadi jika path gambar pada atribut src salah?
Jawaban: Jika path gambar salah, browser tidak dapat menemukan file gambar tersebut. Akibatnya, browser akan menampilkan ikon gambar pecah/rusak (broken image) dan akan menampilkan teks alternatif yang ditulis pada atribut alt (jika atribut alt diisi).   
9. Mengapa struktur heading <h1> sampai <h6> perlu digunakan secara terstruktur?
Jawaban: Struktur heading dari <h1> (level utama/terbesar) hingga <h6> (sub-level terkecil) perlu digunakan secara hierarkis untuk:   Memberikan struktur hierarki konten yang jelas dan rapi bagi pembaca.   Membantu mesin pencari (SEO) memahami bobot dan topik utama dari isi halaman web.Membantu alat screen reader dalam menavigasi bagian-bagian halaman bagi pengguna disabilitas.
10. Apa fungsi komentar <!-- ... --> dalam kode HTML?
Jawaban: Komentar berfungsi untuk memberikan catatan atau informasi penjelasan tambahan pada kode program, serta dapat digunakan untuk mematikan/menonaktifkan baris kode tertentu sementara. Isi di dalam komentar akan diabaikan oleh browser dan tidak akan ditampilkan pada layar halaman web. 