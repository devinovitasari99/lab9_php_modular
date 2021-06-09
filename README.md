# lab9_php_modular
Modularisasi sendiri merupakan proses penyederhanaan program yang kompleks menjadi lebih efisien. Program disusun berdasarkan modul-modul yang berupa function atau prosedur. Sebagai contoh, dalam pembuatan website terdapat halaman index/utama yang terdiri dari header, konten, dan footer. Apabila halaman index tersebut diselesaikan tanpa menggunakan modul, maka akan hanya ada satu file php saja, namun dengan banyak baris kode program didalamnya. Kendalanya adalah ketika terjadi kesalahan, maka akan terlihat rumit untuk menemukan dan memperbaiki kesalahan tersebut.

Modularisasi didalam PHP terdiri dari:

1. Require, merupakan bentuk modular yang digunakan untuk menggabungkan file PHP atau file lain dengan file PHP yang memanggilnya. File yang digabungkan tidak harus script PHP.

2. Include, hampir sama dengan require namun bedanya adalah include digunakan untuk menggabungkan file PHP dengan file pemanggilnya. Include dapat digunakan didalam pengulangan untuk memanggil file-file yang berbeda.

3. Require_once, pada dasarnya sama dengan require, perbedaannya adalah jika menggunakan require_once apabila terjadi duplikasi fungsi atau duplikasi pemanggilan maka akan terhindar karena require_once akan memaksa PHP untuk menggunakan nama fungsi dan pemanggilan yang telah ada.

4. Include_once, hampir sama dengan require_once, perbedaannya adalah include_once apabila dijalankan akan selalu ada evaluasi ulang.

# Langkah-langkah praktikum

Membuka Xampp

![logo]()

Membuat Folder baru dengan nama lab9_php_modular pada htdocs

![logo]()

Membuat file header.php

![logo]()

output

![logo]()

Membuat file baru footer.php

![logo]()

output

![logo]()

# Jawaban Tugas

Membuat file footer.php untuk kemudian di masukan ke index dengan menggunakan require

![logo]()

Buat file baru dengan nama header.php

![logo]()

Menambahkan Style CSS untuk mepercantik tample

![logo]()

Output

![logo]()

![logo]()
