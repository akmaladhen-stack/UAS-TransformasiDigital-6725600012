# Pencegahan Kehilangan Data Akibat Kerusakan Perangkat Menggunakan Backup Google Drive

## Deskripsi Project

Project ini bertujuan untuk mencegah kehilangan data akibat kerusakan perangkat dengan melakukan backup data dari Ubuntu Server ke Google Drive menggunakan Rclone.

## Teknologi yang Digunakan

* Ubuntu Server
* Rclone
* Google Drive
* Linux CLI

## Cara Menjalankan

1. Install Rclone.
2. Konfigurasi Google Drive dengan nama remote akmaldrive.
3. Membuat folder DataPenting.
4. Backup data:
   rclone copy ~/DataPenting akmaldrive:backup-ubuntu
5. Restore data:
   rclone copy akmaldrive:backup-ubuntu ~/DataPenting

## Hasil

Data yang hilang dapat dipulihkan kembali dari Google Drive.
# UAS-TransformasiDigital-6725600012
Backup Google Drive menggunakan Rclone pada Ubuntu Server
