Cara Instalasi Website 1. Clone Repositori:
Buka terminal atau command prompt dan eksekusi perintah berikut untuk meng-clone repositori dari GitHub:
git clone <URL_REPOSITORI>
Gantilah <URL_REPOSITORI> dengan URL repositori Laravel yang ingin Anda clone. 2. Pindah ke Direktori Proyek:
Masuk ke direktori proyek yang baru saja Anda clone:
cd nama-proyek 3. Instal Dependensi:
Setelah masuk ke direktori proyek, jalankan perintah Composer untuk menginstal dependensi:
composer install 4. Konfigurasi Lingkungan:
Duplikat file .env.example dan ganti namanya menjadi .env.
Buka file .env dan atur konfigurasi database, seperti nama database, pengguna, dan kata sandi. 5. Migrasi dan Penyemaian Basis Data:
Jalankan perintah migrasi untuk membuat tabel-tabel basis data:
php artisan migrate 6. Kunci Aplikasi dan Persiapan:
Eksekusi perintah untuk menghasilkan kunci aplikasi:
php artisan key:generate 7. Jalankan Server Pembangunan:
Gunakan perintah berikut untuk menjalankan server pengembangan:
php artisan serve 8. Buka Aplikasi dalam Browser:
Buka browser dan akses http://localhost:8000 (sesuaikan port jika perlu) untuk melihat aplikasi Laravel yang baru saja diunduh. 9. Selesai:
Selamat! Laravel sekarang diinstal dan berjalan di lingkungan lokal Anda.

Framework : Laravel
Programming Languages : PHP
UI Framework : Bootstrap
JavaScript libraries : Swiper, Isotope, AOS, Lightbox
Font scripts : Google Font API, Bootstrap Icons

Informasi Sumber Template:
_ Template Name: Arsha
_ Updated: Sep 18 2023 with Bootstrap v5.3.2
_ Template URL: https://bootstrapmade.com/arsha-free-bootstrap-html-template-corporate/
_ Author: BootstrapMade.com \* License: https://bootstrapmade.com/license/
