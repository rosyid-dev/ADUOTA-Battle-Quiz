# ADUOTA Battle Quiz V18

Game kuis berbasis web dengan desain arcade modern, sistem multiplayer, panel admin, dan dukungan database MySQL.

## Fitur
- Game kuis interaktif
- Sistem room multiplayer
- Pengelolaan soal dan materi melalui panel admin
- Leaderboard dan hasil permainan
- API pemain, soal, room, dan battle
- Penyimpanan data menggunakan MySQL
- Template aplikasi Android berbasis Capacitor

## Teknologi
- PHP dan PDO
- MySQL
- HTML, CSS, JavaScript
- Capacitor

## Instalasi Lokal
1. Pasang XAMPP.
2. Salin proyek ke folder `htdocs/aduota`.
3. Jalankan Apache dan MySQL.
4. Buat database melalui phpMyAdmin.
5. Impor file `database.sql`.
6. Sesuaikan konfigurasi database pada `config.php`.
7. Buka `http://localhost/aduota/`.

## Deployment
Untuk hosting, sesuaikan kredensial MySQL dengan informasi dari penyedia hosting. Pastikan koneksi database dan HTTPS berfungsi sebelum digunakan.

## Android
Folder `capacitor-app/` berisi template untuk membungkus versi web menjadi aplikasi Android. APK perlu dibangun menggunakan Node.js, Capacitor, dan Android Studio.

## Keamanan
Jangan mempublikasikan password database, API key, data pengguna, kredensial admin, atau file konfigurasi rahasia.

## Status
Proyek dalam pengembangan.
