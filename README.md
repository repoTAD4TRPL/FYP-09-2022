<!-- <p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT). -->

## FYP-09-2022
## Topik Proyek			: Identifikasi Kepribadian Seseorang berdasarkan Tes Kepribadian DISC dengan Menggunakan Metode Forward Chaining
## Nama Sistem atau Aplikasi	: Sistem Identifikasi Kepribadian
## Jenis Sistem atau Aplikasi	: Website

## Spesifikasi minimal dari device : 
-     Windows 10
-     Installed Memory (RAM) 8 Gb
-     Processor Intel?? Core(TM) i5
## Kebutuhan tools terkait		:
-     XAMPP
-     Visual Studio Code atau aplikasi sejenis untuk editor code
-     Composer
-     Laravel V8.8
-     Chrome atau aplikasi sejenis untuk browser
-     MySQL
## Konfigurasi untuk menjalanakan aplikasi web atau mobile tersebut.
-     Melakukan penyesuaian versi komposer
-     Melakukan penyesuaian versi laravel
## Daftar User Type
-    Admin di tabel user dengan value role 0 yang berfungsi untuk melakukan otorisasi terkait semua fungsi yang ada di aplikasi,beserta mengelola seluruh fitur yang ada di aplikasi.Untuk dapat masuk kedalam aplikasi,akun admin sudah di buat terlebih dahulu secara default melalai sistem menggunakan seeder
-         dengan email adalah "admin@gmail.com" dan password adalah "password"
-    Pengunjung atau user yang melakukan identifikasi di tabel user dengan value role 1 yang berfungsi untuk melakukan indentifikasi kepribadian dan dapat melihat history.untuk dapat melakukan identifikasi pengunjung diharuskan untuk register akun dan melakukan login ke aplikasi
-         dimana akun dari pengunjung dapat dibuat dengan melakukan registrasi akun pada sistem 
## Link dari aplikasi dapat dilihat di
-    https://personalitydisc.online/

## Langkah-langkah menjalankan aplikasi web atau mobile
-	1. Lakukan download projek atau clone project atau dapat menggunakan command
-         git clone https://github.com/repoTAD4TRPL/FYP-09-2022.git  di cmd
![git clone](https://user-images.githubusercontent.com/65029328/183838611-1cd764c9-2375-4103-bd8d-33d427783092.png)
-   2. Kemudian buka folder project yang di clone menggunakan cmd atau terminal di visual studio code
-	3. Kemudian update composer atau dapat menggunakan command
-         composer update
[![composer update](https://user-images.githubusercontent.com/65029328/183836732-b88865e3-489e-4fe8-906d-45621139f14f.png)](https://github.com/repoTAD4TRPL/FYP-09-2022/issues/1#issue-1334177164)
-	4. Kemudian membuat file .env baru
-         dapat menggunakan command "php artisan key:generate"
-         atau menggunakan file env.example kemudian command "php artisan key:generate"
![env](https://user-images.githubusercontent.com/65029328/183838299-4c1410a9-689d-4e3b-9682-ca2fe44ab179.png)
-   5. Kemudian nyalakan apache dan mysql di xampp
![xampp](https://user-images.githubusercontent.com/65029328/183839836-2dbec494-49ee-4c22-9f21-b10afd31f9f2.png)
-	6. Kemudian buat database baru
-	7. Lakukan konfigurasi pada file .env
-         seperti mengganti nama database,username dan password di file .env
![konfigurasi env](https://user-images.githubusercontent.com/65029328/183838859-34da2c20-af66-48e0-964b-695f4aa35ee0.png)
-	8. Kemudian lakukan migrasi database atau dapat menggunakan command
-         php artisan migrate
![migrate](https://user-images.githubusercontent.com/65029328/183839235-a042d897-8b44-4806-8c41-5ece4b2453ca.png)
-	9. Kemudian jalankan seeder atau dapat menggunakan command
-         php artisan db:seed
![seed](https://user-images.githubusercontent.com/65029328/183839408-ddd8cca1-a5ac-4208-823d-1b4deb6333cb.png)
-	10. Kemudian run project atau dapat menggunakan command
-         php artisan serve
![php artisan serve](https://user-images.githubusercontent.com/65029328/183839310-5d1a30f3-669b-45ed-82a9-1fbe397d0ebd.png)
		
