# lab2web
Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

Laporan Praktikum
1. Buatlah repository baru dengan nama Lab2Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus

7. jawaban
8. 1.
9. ![belajarhtml](https://github.com/user-attachments/assets/09ca674e-847e-410b-b1a8-4ae082bb0dd0)
10. ![Screenshot (44)](https://github.com/user-attachments/assets/bb10e016-51a1-4640-bd66-156b60acdcbf)
11. 2.
12. h1 {...} adalah deklarasi CSS yang berlaku untuk semua elemen h1 di dalam halaman HTML.
#intro h1 {...} adalah deklarasi CSS yang hanya berlaku untuk elemen h1 yang berada di dalam elemen dengan ID intro. Jadi, ini lebih spesifik dibandingkan dengan deklarasi umum h1.
3.
Jika ada CSS internal, eksternal, dan inline pada elemen yang sama, aturan yang akan digunakan oleh browser adalah aturan inline CSS, karena inline CSS memiliki prioritas tertinggi. Contohnya:
<head>
  <style>
    p { color: blue; } /* CSS internal */
  </style>
  <link rel="stylesheet" href="style.css"> /* CSS eksternal */
</head>
<body>
  <p style="color: red;">This is a paragraph.</p> /* CSS inline */
</body>
Dalam contoh di atas, meskipun ada deklarasi warna biru di CSS internal dan mungkin juga di eksternal, warna yang ditampilkan adalah merah karena inline CSS memiliki prioritas tertinggi.
4.
Jika ada deklarasi CSS dengan selector ID dan class untuk elemen yang sama, maka selector ID akan memiliki prioritas lebih tinggi dibandingkan class
