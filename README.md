<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"><br>
<img src="[https://img.shields.io/badge/laravel-5.8-orange.svg](https://www.svgrepo.com/show/376332/laravel.svg)"> <img src="https://img.shields.io/badge/yajra-9.x-blueviolet.svg"> <img src="https://img.shields.io/badge/license-MIT-blue.svg"> <img src="https://img.shields.io/badge/build-passing-green.svg"></p>

## Laravel Perpustakaan

<p>Project ini dibuat untuk menghandle sistem informasi perpustakaan<br> <br></p>

# Library yang digunakan :
<ul>
<li>Laravel UI</li>
<li>Bootstrap 4</li>
<li>FontAwesome</li>
<li>realrashid/sweet-alert</li>
<li>Template Ruang Admin</li>
<li>Select2 untuk multiple select</li>
<li>DataTables</li>
<li>DomPDF</li>
</ul>

# Fitur-Fitur  :
<ol>
<li>Ada 2 jenis Anggota yaitu Admin dan Anggota</li>
<li>Setiap User Harus Login Untuk Dapat Mengakses Web, Dapat mendaftar apabila belum mempunyai akun</li>
<li>user harus terdaftar sebagai anggota untuk meminjam buku</li>
<li>Satu user hanya dapat memiliki satu profile</li>
<li>setiap user dapat mengubah profilenya masing"</li>
<li>Setiap Buku dapat memiliki multiple kategori</li>
<li>Judul buku dapat berjumlah lebih dari 1 (dapat dibedakan melalui kode buku)</li>
<li>Bisa melakukan pencaharian buku melalui judul buku</li>
<li>Admin bisa menambah,mengupdate,dan menghapus: data buku,kategori dan user</li>
<li>Setiap Anggota hanya dapat meminjam maksimal 3 buku</li>
<li>Peminjaman maksimal 7 hari. Jika peminjaman lebih dari 7 hari maka akan dikenakan denda</li>
<li>Hanya Admin yang dapat melakukan pengembalian buku, jadi setiap anggota harus menghubungi admin jika ingin mengembalikan buku.</li>
<li>Admin dapat melihat list buku yang dipinjam, sedangkan Anggota hanya dapat melihat list buku yang dipinjam olehnya</li>
<li>Admin dapat melihat dan mencetak riwayat peminjaman buku, sedangkan Anggota hanya dapat melihat list buku yang dipinjam olehnya</li>
</ol>



### Dibutuhkan

------------

- Composer
- PHP >7.8 keatas
- Laravel >10
- Admin Dashboard UI bisa di unduh melalui https://themewagon.com/themes/free-bootstrap-4-html-5-admin-dashboard-website-template-ruang/ (extrack ke folder public/template) 



### Instalasi

Buat database baru/kosong di phpmyadmin

Edit file .env db_database dengan nama database yang sudah dibuat di phpmyadmin

Buka terminal
	
	composer install
 apabila crash silahkan update composer dengan

    composer update
lalu 
  
    php artisan key:generate

migrasi database 

    php artisan migrate --seed

jika sudah berhasil jalankan dengan

    php artisan serve 

copy ip ke web browser


### Screenshot

