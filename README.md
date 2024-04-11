

#### Fitur aplikasi.
- Login Register mengunakan Laravel Fortify
- Dashboard Admin (hak hapus postingan, hak edit postingan user, menambahkan tags dan kategori).
- Dashboard User  (Menganti photo profile).

#### Aplikasi ini mengunakan beberapa library sebagai berikut
- Blade Ui Kit.
- Fortify.
- CK editor

## Instalasi

Pertama

```bash
php artisan config:clear
```
Instalasi Blade ui Kit

```bash
composer require blade-ui-kit/blade-ui-kit
```

Instalasi blade hero icon

```bash
composer require blade-ui-kit/blade-heroicons
```

Instalasi zond icons

```bash
composer require blade-ui-kit/blade-zondicons
```
lalu

```bash
php artisan vendor:publish --tag=blade-heroicons-config
```


Instalasi laravel

```bash
composer install
```
lalu config file SVG path untuk semua depency UI

```
create file:
resource/svg
```

Setelah itu generate link publik

```
php artisan storage:link
```

migrate database 

```
php artisan migrate:fresh --seed
```

Lalu jalankan aplikasi
```
php artisan serve
```

## akun

    ADMIN:
      EMAIL:  admin@sainsforum.com
      PASS:   password

      EMAIL:  rahma@sainsforum.com
      PASS:   password
    
    MODERATOR
      EMAIL:  markus@sainsforum.com
      PASS:   password

      EMAIL:  ade@sainsforum.com
      PASS:   password

    USER

      EMAIL:  rico@sainsforum.com
      PASS:   password
