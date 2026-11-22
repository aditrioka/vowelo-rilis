# Vowelo untuk komputer (Windows)

Tempat mengunduh installer Vowelo versi komputer. Repo ini hanya berisi berkas rilis; kode sumbernya tidak ada di sini.

## Memasang pertama kali

1. Unduh installer terbaru: **[Vowelo.msi](https://github.com/aditrioka/vowelo-rilis/releases/latest/download/Vowelo.msi)**
2. Klik dua kali berkas yang terunduh. Kalau Windows menampilkan "Windows protected your PC", klik "More info", lalu "Run anyway".
3. Ikuti langkahnya sampai selesai, lalu buka Vowelo dari pintasan di desktop atau dari menu Start.

## Memperbarui

Tidak perlu mengunduh lagi dari sini. Saat ada versi baru, Vowelo menawarkannya sendiri waktu dibuka: tekan "Perbarui sekarang", tunggu unduhannya, lalu ikuti jendela pemasangan yang terbuka.

## Untuk aplikasi

Tiap rilis memuat dua berkas: `Vowelo.msi` dan `versi.json`, yang menyebut versi terbaru, alamat installernya, dan sidik SHA-256-nya. Vowelo membaca `versi.json` rilis terbaru dan mencocokkan sidik itu sebelum menjalankan installer.
