# OtomaX Client
[![GitHub Release](https://img.shields.io/github/v/release/ndiing/otomax-client)](https://github.com/ndiing/otomax-client/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/ndiing/otomax-client/total)](https://github.com/ndiing/otomax-client/releases)

**OtomaX Client** adalah aplikasi yang membantu menghubungkan pengembang dengan software OtomaX. Aplikasi ini menggunakan *HTTP request* dan *webhook* untuk berkomunikasi.

## Cara Mengunduh dan Menginstal

1. **Unduh Aplikasi**: Klik [di sini](https://github.com/ndiing/otomax-client/releases) untuk mengunduh aplikasi.
2. **Instal Aplikasi**: Setelah diunduh, buka file dan ikuti petunjuk untuk menginstal aplikasi di komputer Anda.

## Cara Menggunakan

1. **Melihat Versi Aplikasi**: Arahkan mouse ke ikon aplikasi di tray (pojok kanan bawah layar) untuk melihat versi yang terpasang.
2. **Menghentikan Aplikasi**: Klik kanan pada ikon di tray dan pilih opsi "Berhenti" jika Anda ingin menutup aplikasi.
3. **Meluncurkan Kembali**: Jika ingin membuka aplikasi lagi, klik kanan pada ikon di tray dan pilih "Relaunch".

## Pengaturan Default

Beberapa pengaturan aplikasi bisa ditemukan di file bernama `.env`. File ini terletak di folder `%appdata%/OtomaX Client`. Berikut adalah contoh isi file tersebut:

<pre>
HTTP_PORT=2002
HTTPS_PORT=0
OTOMAX_DATABASE=otomax

OTOMAX_WEBHOOK=http://127.0.0.1:2003/webhook
</pre>

## Contoh REST API

Anda bisa melihat contoh penggunaan API di sini:

1. [Semua](./http/otomax.http) - Untuk mengakses semua data.
2. [Inbox](./http/otomax-inbox.http) - Untuk mengakses pesan masuk.

## Penting untuk Diketahui

1. Aplikasi ini dirancang untuk digunakan di komputer lokal, jadi keamanannya masih rendah.
2. Jika Anda ingin menggunakan aplikasi ini di internet, silakan hubungi pengembang agar bisa mengatur keamanan dan filter data yang tidak perlu.

Jika Anda butuh bantuan lebih lanjut, jangan ragu untuk bertanya!
