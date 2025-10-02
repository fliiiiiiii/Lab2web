# MODUL PRAKTIKUM PEMROGRAMAN WEB

NAMA : RAFLI ANUGRAH RAMADHAN

Nim : 312410351

Kelas : TI.24.A4

# INSTRUKSI PRAKTIKUM 

1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lat2web1.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

# 1. MEMBUAT DOKUMEN HTML

CODE HTML SEPERTI BERIKUT :

~~~html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>

    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>

    <!-- CSS ID Selector -->
    <div id="intro">
        <h1>Helloo Everyone</h1>
        <p>
            Saya <b>Rafli Anugrah Ramadhan</b> sedang belajar HTML dan CSS dasar, 
            pada mata kuliah <b>Pemrograman Web</b> di 
            <i>Universitas Pelita Bangsa</i>. 
            Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
            dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>

        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>

</body>
</html>
~~~~

# CODE HTML DI VSCODE:

<img width="399" height="377" alt="image" src="https://github.com/user-attachments/assets/8d67a7b4-58f9-4f5a-8ff5-2ecbe98dbf41" />

# HASIL:

<img width="959" height="244" alt="image" src="https://github.com/user-attachments/assets/f010457a-bcc7-4e8b-8722-056d6f1b8ac5" />

# 2. MEMBUAT STYLE UNTUK HTML MENGGUNAKAN INTERNAL CSS:

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <style>
    body {
      font-family: 'Open Sans', sans-serif;
    }
    header {
      min-height: 80px;
      border-bottom: 1px solid #ff00fb;
    }
    h1 {
      font-size: 24px;
      color: #ff00fb;
      text-align: center;
      padding: 20px 10px;
    }
    h1 i {
      color: #1aff00;
    }
  </style>

    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>

    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>

    <!-- CSS ID Selector -->
    <div id="intro">
        <h1>Helloo Everyone</h1>
        <p>
            Saya <b>Rafli Anugrah Ramadhan</b> sedang belajar HTML dan CSS dasar, 
            pada mata kuliah <b>Pemrograman Web</b> di 
            <i>Universitas Pelita Bangsa</i>. 
            Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
            dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>

        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>

</body>
</html>
~~~

# CODE HTML INTERNAL CSS DI VSCODE:

<img width="325" height="458" alt="image" src="https://github.com/user-attachments/assets/f71fa458-1b2e-44bc-979c-d0cd4c0da433" />

# HASIL:

<img width="958" height="266" alt="image" src="https://github.com/user-attachments/assets/c31a8b0b-a785-4f3b-9c3a-2aded32fe441" />

# 3. MENAMBAHKAN INLINE CSS:

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <style>
    body {
      font-family: 'Open Sans', sans-serif;
    }
    header {
      min-height: 80px;
      border-bottom: 1px solid #ff00fb;
    }
    h1 {
      font-size: 24px;
      color: #ff00fb;
      text-align: center;
      padding: 20px 10px;
    }
    h1 i {
      color: #1aff00;
    }
     #intro p {
      text-align: center;
      color: #ccd8e4;
      line-height: 1.6;
    }
    nav a {
      margin-right: 15px;
      text-decoration: none;
      color: #0F189F;
    }
    nav a:hover {
      color: #77CCEF;
    }
  </style>

    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>

    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>

    <!-- CSS ID Selector -->
    <div id="intro">
        <h1>Helloo Everyone</h1>
        <p>
            Saya <b>Rafli Anugrah Ramadhan</b> sedang belajar HTML dan CSS dasar, 
            pada mata kuliah <b>Pemrograman Web</b> di 
            <i>Universitas Pelita Bangsa</i>. 
            Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
            dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>

        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>

</body>
</html>
~~~

# INLINE HTML CSS DI VSCODE:

<img width="394" height="397" alt="image" src="https://github.com/user-attachments/assets/da435e42-8195-4b09-b7cb-88a390e4974a" />

<img width="364" height="280" alt="image" src="https://github.com/user-attachments/assets/764bfd09-c8f8-4ad2-899d-06170fb36500" />

# HASIL:

<img width="959" height="279" alt="image" src="https://github.com/user-attachments/assets/2c8b8a30-d160-4a03-bb95-331792464d01" />

# 4. MEMBUAT CSS EKSTERNAL UNTUK HTML:

~~~html
nav {
    background: #ff00dd;
    color: #1aff00;
    padding: 10px;
}

nav a {
    color: #ff00fb;
    text-decoration: none;
    padding: 10px 20px;
}

nav .active,
nav a:hover {
    background: #1aff00;
}
~~~

# HASIL:

<img width="958" height="285" alt="image" src="https://github.com/user-attachments/assets/d054891f-3273-4f0d-9303-02fc85da58c3" />

# 5. MENAMBAHKAN CSS SELECTOR:

~~~html
header {
  text-align: center;
  margin-bottom: 10px;
}

nav {
  background: #1aff00;
  padding: 10px;
}

nav a {
  color: #ff00d0;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: bold;
}

nav a:hover {
  background: #1aff00;
}

#intro {
  background: #ff00d0;
  border: 1px solid #1aff00;
  min-height: 200px;
  padding: 20px;
}

#intro h1 {
  text-align: left;
  border: 0;
  color: #fff !important;
}

#intro p {
  color: #000000 !important;
}

.button {
  padding: 15px 20px;
  background: #bebcbd;
  color: #fff;
  display: inline-block;
  margin: 10px 0;
  text-decoration: none;
}

.btn-primary {
  background: #000000;
}
~~~

# HASIL:

<img width="959" height="339" alt="image" src="https://github.com/user-attachments/assets/9f1a21a9-dba6-4b61-b767-bf78523fbc78" />

# TUGAS:

<img width="449" height="161" alt="image" src="https://github.com/user-attachments/assets/2720d5b5-fd4b-461d-9d24-6f64e66f1a0e" />

# 1. EKSPERIMEN PROPERTI CSS:

~~~html
h1 i {
  color: #6d6a6b;
}

body {
  background-color: lightblue;
  font-family: Arial, sans-serif;
}

p {
  color: #a0522d; 
  font-size: 18px;
}
~~~

# HASIL:

<img width="956" height="515" alt="image" src="https://github.com/user-attachments/assets/220b26b2-fac8-4562-bf30-4fe54728366e" />

# 2. PERBEDAAN h1 {…} dengan #intro h1 {…}:

h1 {} = global, semua <h1> di halaman.
intro h1 {} = spesifik, hanya <h1> yang ada di dalam elemen dengan id="intro".

~~~
<div>
  <h1>Judul 1 (umum)</h1>
</div>

<div id="intro">
  <h1>Judul 2 (khusus di dalam #intro)</h1>
</div>
~~~
~~~
h1 {
  color: red;
}

intro h1 {
  color: green;
}
~~~
# 3. PRIORITAS CSS (Internal, Eksternal, Inline)

Inline CSS (langsung di atribut elemen HTML) → prioritas tertinggi
Internal CSS (<style> di dalam file HTML) → prioritas menengah
Eksternal CSS (file .css yang dilink) → prioritas lebih rendah

```
<head>
  <!-- Eksternal CSS -->
  <link rel="stylesheet" href="style.css">
  <style>
    /* Internal CSS */
    p { color: blue; }
  </style>
</head>
<body>
  <p style="color: red;">Teks percobaan</p>
</body>
```

# 4. JIKA ELEMEN PUNYA ID & CLASS

Aturan prioritas selector:
Inline CSS > ID > Class > Elemen

```
<p id="paragraf-1" class="text-paragraph">Teks uji coba</p>
```

```
p {
  color: black;       /* paling lemah */
}

.text-paragraph {
  color: blue;        /* class */
}

#paragraf-1 {
  color: green;       /* id lebih kuat */
}
```




