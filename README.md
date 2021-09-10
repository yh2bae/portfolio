Portfolio
<p><b>
Aplikasi website portfolio dengan konten dinamis.
</b></p>

Instalasi
- download zip <a href="https://codeload.github.com/yh2bae/portfolio/zip/refs/heads/master">disini</a> 
- atau clone : git clone https://github.com/yh2bae/portfolio.git

Setup
- buka direktori project di terminal anda.
- ketikan command : cp .env.example .env (copy paste file .env.example)
- buat database 

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear 
- php artisan key:generate (generate app key)
- php artisan migrate (migrasi database)
- php artisan db:seed --class=UserSeeder (mengisi data table users)

Lalu cari file helpers.php di vendor\laravel\framework\src\Illuminate\Foundation\
- kemudia cari sytac asset seperti di gambar dan tambah "public/".

<img src="https://github.com/yh2bae/readme-image/blob/master/portfolio/setting-asset.png?raw=true">

Kemudian run localhost/namefolder


Login
Username : admin <br/>
Password : admin123

Author
- Yudha Harsanto
