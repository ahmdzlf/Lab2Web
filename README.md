
# Tugas Praktikum Pemrograman Web

#### 1. Membuat file baru dengan nama lab2_css_dasar.html 

# ![App Screenshot](Images2/1.png) 
images2/1.png

#### 2. Mendeklarasikan CSS Internal

# ![App Screenshot](./Images2/2.png) 

#### 3. Menambahkan Inline CSS

# ![App Screenshot](./Images2/3.png) 

#### 4. Membuat CSS Eksternal

# ![App Screenshot](./Images2/4.png) 

#### 5. Menambahkan CSS Selector

# ![App Screenshot](./Images2/5.png) 

### Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`

### Jawab
1. Saya melakukan eksperimen dengan mengubah dan menambah properti serta nilai pada kode CSS Mengubah warna latar belakang `body {background-color: #282c34;}`, Menambahkan efek hover pada link `a:hover {color: #61dafb; text-decoration: underline;}`

2. `h1 {...}` Ini adalah selector yang menargetkan semua elemen `<h1>` di halaman. Artinya, semua elemen h1 akan memiliki gaya yang didefinisikan di dalam kurung.<br>
#intro `h1 {...}` Ini adalah selector yang lebih spesifik. Ini berarti hanya elemen `<h1>` yang berada di dalam elemen dengan ID intro yang akan mendapatkan gaya tersebut. Dengan kata lain, jika ada banyak elemen `<h1>` di halaman, hanya yang ada dalam elemen dengan ID intro yang akan terpengaruh.

3. ika ada deklarasi CSS secara internal, kemudian ditambahkan CSS eksternal dan inline CSS pada elemen yang sama, inline CSS yang akan ditampilkan di browser. Ini disebabkan oleh prinsip specificity (tingkat spesifik) dalam CSS, di mana inline CSS memiliki prioritas tertinggi dibandingkan dengan CSS internal dan eksternal.
![App Screenshot](./Images2/6.png) 
Pada contoh di atas, meskipun ada deklarasi warna biru dalam CSS internal dan warna default di CSS eksternal, elemen `<h1>` akan berwarna merah karena inline CSS memiliki prioritas lebih tinggi.

4. Ketika sebuah elemen HTML memiliki ID dan Class, jika masing-masing selector tersebut memiliki deklarasi CSS, dekorasi ID yang akan ditampilkan di browser. Ini karena selector ID memiliki prioritas lebih tinggi dibandingkan selector Class.
![App Screenshot](./Images2/7.png)
Pada contoh di atas, meskipun class `.text-paragraf` mengatur warna menjadi hijau, paragraf dengan ID `paragraf-1` akan berwarna biru karena deklarasi ID memiliki prioritas lebih tinggi.
