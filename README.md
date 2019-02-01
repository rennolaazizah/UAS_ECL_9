# UAS_ECL_9
Artikel Project Laravel

Laravel merupakan suatu framework dalam membangun suatu aplikasi berbasis website. 
laravel menggunakan PHP sebagai bahasa pemrograman nya dan saat ini laravel merupakan 
salah satu framework populer yang banyak digunakan oleh programer maupun orang - orang 
yang masih belajar pemrograman. kelebihan dari laravel ini adalah pengembang dapat 
menghemat biaya sebaik mungkin, selain itu perawatan dari aplikasi berbasis laravel 
ini bisa dikatakan mudah dalam perawaran nya serta menyediakan pengalaman kerja dengan
syntax yang ekspresif dan jelas sehingga dapat menghemat waktu developer dalam 
mengembangkan apikasinya.
MVC adalah sebuah pendekatan perangkat lunak yang memisahkan aplikasi logika dari presentasi. 
MVC memisahkan aplikasi berdasarkan komponen- komponen aplikasi, seperti : manipulasi data, controller, dan user interface.
Bundles, yaitu sebuah fitur dengan sistem pengemasan modular dan tersedia beragam di aplikasi.
Eloquent ORM, merupakan penerapan PHP lanjutan menyediakan metode internal dari pola “active record” yang menagatasi masalah pada hubungan objek database.
Application Logic, merupakan bagian dari aplikasi, menggunakan controller atau bagian Route.
Reverse Routing, mendefinisikan relasi atau hubungan antara Link dan Route.
Restful controllers, memisahkan logika dalam melayani HTTP GET and POST.
Class Auto Loading, menyediakan loading otomatis untuk class PHP.
View Composer, adalah kode unit logikal yang dapat dieksekusi ketika view sedang loading.
IoC Container, memungkin obyek baru dihasilkan dengan pembalikan controller.
Migration, menyediakan sistem kontrol untuk skema database.
Unit Testing, banyak tes untuk mendeteksi dan mencegah regresi.
Automatic Pagination, menyederhanakan tugas dari penerapan halaman

Model, Model mewakili struktur data. Biasanya model berisi fungsi-fungsi yang membantu seseorang dalam pengelolaan basis data seperti memasukkan data ke basis data, pembaruan data dan lain-lain.
View, View adalah bagian yang mengatur tampilan ke pengguna. Bisa dikatakan berupa halaman web.
Controller, Controller merupakan bagian yang menjembatani model dan view.

kelebihan dari framework laravel dalam membangun suatu website adalah :
1. dalam segi struktur laravel sudah memiliki strukturnya sendiri, jadi pengguna hanya perlu mengedit yang sekiranya dibutuhkan oleh programmer
2. dalam pengelompokan class laravel memiliki fitur command prompt artisan yang mempunyai fungsi membbuat file class sesuai fungsinya, termasuk class untuk model, untuk migrasi, controller maupun untuk command sendiri.
3. Untuk views atau tampilan user interface, laravel menggunakan system templating  blade. Penggunaannya cukup mudah, hanya deiperlukan penguasaan HTML dan  penulisan PHP ke dalam HTML.
4. Mengakese database menggunakan laravel akan jauh lebih mudah dibandingkan cara  biasa tanpa menggunakan framework. Sebelum mengambil data kedalam database, kita harus konfigurasi aplikasi kita agar bisa tersambung kedalam database yang sudah disiapkan.

Langkah - langkah mengerjakan project tahap 1 :

1. langkah pertama yang harus dilakukan adalah melakukan set up awal seperti memasukan PHP kedalam System Environment, menginstal laravel melalui composer
2. langkah kedua adalah mengintegrasikan laravel dengan template yang sudah di download sebelumnya di website github
3. langkah ketiga adalah melakukan copy paste beberapa folder yang diperlukan lalu melakukan edit sesuai dengan panduan yang ada
4. langkah selanjutnya adalah dengan membuat tabel dengan migration dengan mengikuti instruksi yang ada lalu membuat data dummy dengan menggunakan database seed yang sudah dijelaskan pada panduan
5. tidak lupa pada project ini dimasukan fungsi CRUD yang berfungsi untuh membuat, membaca, update, dan menghapus data.

Langkah mengerjakan project tahap 2 :

pada tahap kedua, dilakukan Eloquent Relationship atau penggabungan relasi dua tabel yang mempunyai kelebihan tidak perlu membuat syntax query Join Join.

Langkah Mengerjakan project tahap 3 :
tahap ketiga ini merupakan tahap dimana bagaimana cara mengautentikasi user atau login.
langkah membuat fungsi login ini adalah dengan membuat tampilan login, melakukan migration 
Table Login, membuat model User, membuat user admin melalui seeder, memodifikasi login controller,
dan membuat fungsi logout.

Langkah Mengerjakan project tahap 4 :
tahap ini merupakan tahap terakhir dalam membuat project ini dimana dalam tahap ini dilakukan 
pengkonfigurasian Storage, menambahkan form upload, dan membuat field foto pada database.
semua langkah-langkah dalam mengerjakan project ini sudah dijelaskan pada modul yang tersedia.
