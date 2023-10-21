<p align="center">
    <a href="https://github.com/Kantrawibawa10" target="_blank"><img src="https://developers.giphy.com/branch/master/static/api-512d36c09662682717108a38bbb5c57d.gif" width="500"></a>
</p>

## Tentang Aplikasi

Aplikasi <b>REST API Laravel 8</b> sederhana yang digunakan untuk melakukan input, update, delete, dan view data testing endpoint pada local database. enjoy to learn👋🏻👋🏻.

## Instalasi
#### Via Git
```bash
git clone https://github.com/Kantrawibawa10/Rest-API-Laravel8.git
```

### Download ZIP
[Link](https://github.com/Kantrawibawa10/Rest-API-Laravel8/archive/refs/heads/master.zip)

### Setup Aplikasi
Jalankan perintah 
```bash
composer update
```
atau:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_akun
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Akun
APP_ENV=local
APP_KEY=base64:UvAYgUUD1t9NhyoYbFS0SUAqV/gO3LzY91a1j9Tyk74=
APP_DEBUG=true
APP_URL=http://localhost
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Menjalankan aplikasi
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
