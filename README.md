# OtomaX Client

Aplikasi ini berfungsi sebagai penghubung antara pengembang dan software OtomaX. Aplikasi ini menggunakan HTTP request dan webhook untuk berkomunikasi.

## Cara Mengunduh dan Menginstal

1. Unduh dari [sini](https://github.com/ndiing/otomax-client/releases).
2. Install aplikasi yang telah diunduh.

## Cara Menggunakan

1. **Melihat Versi**: Arahkan mouse ke ikon di tray untuk melihat versi aplikasi.
2. **Menghentikan Aplikasi**: Klik kanan pada ikon tray dan pilih "Berhenti".
3. **Meluncurkan Kembali**: Klik kanan pada ikon tray dan pilih "Relaunch".

## Pengaturan Default

Pengaturan default dapat ditemukan di file `.env`, yang berada di `%appdata%/OtomaX Client`. Berikut adalah contoh isinya:

<pre>
HTTP_PORT=2002
HTTPS_PORT=0
OTOMAX_DATABASE=otomax

OTOMAX_WEBHOOK=http://127.0.0.1:2003/webhook
</pre>

## Penting untuk Diketahui

1. Aplikasi ini dirancang untuk digunakan secara lokal dengan tingkat keamanan yang rendah.
2. Jika Anda ingin menggunakan aplikasi ini secara publik, silakan hubungi developer untuk melakukan filter data yang tidak diperlukan dan meningkatkan keamanan.
