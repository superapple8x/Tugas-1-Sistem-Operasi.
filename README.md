# Tugas-1-Sistem-Operasi.

# Cara Menginstal Linux: Panduan Langkah demi Langkah

## Proses Instalasi

1. **Tampilan Awal Boot**
   - Pengguna bisa mencoba sistem untuk memastikan semuanya telah berjalan dengan benar sebelum yakin untuk menginstal.
![Tampilan awal boot Linux](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/1.png)

2. **Pemilihan Bahasa**
   - Pilih bahasa yang akan digunakan oleh Sistem Operasi dan proses instalasi.

3. **Ringkasan Instalasi**
   - Tinjau opsi konfigurasi yang telah Anda pilih.

4. **Tujuan Instalasi**
   - Pilih di mana sistem operasi akan diinstal. Dalam panduan ini, kita akan memilih opsi kustom.

5. **Pemilihan Sistem File**
   - Kita akan memilih Btrfs karena merupakan sistem file paling modern yang tersedia.

6. **Pemasangan Partisi**
   - Kita akan menginstal Linux dengan partisi yang di-mount ke `/` (juga disebut root), yang merupakan direktori dasar tempat file Linux yang paling penting berada.

7. **Pembuatan Password Root**
   - Buat password root untuk kegiatan superuser.

8. **Mulai Instalasi**
   - Setelah semua konfigurasi selesai, klik 'Mulai Instalasi' dan tunggu sampai proses selesai.

9. **Penyelesaian**
   - Setelah instalasi selesai, Anda bisa mencoba Linux atau reboot untuk masuk ke sistem yang terinstal.

## Penjelasan Opsi Sistem File

| Sistem File | Deskripsi | Ukuran File Maks | Ukuran Volume Maks |
|-------------|-----------|-------------------|---------------------|
| **Ext4**    | Penerus ext3 dengan peningkatan kinerja | 16TB | 1EB |
| **Ext3**    | Sistem file Linux yang lebih lama | 2TB | 32TB |
| **Swap**    | Bukan sistem file, tapi ruang disk yang digunakan sebagai memori virtual untuk membantu RAM saat penuh | T/A | T/A |
| **NTFS**    | Sistem file Windows | 16EB | 16EB |
| **FAT32**   | Sistem file sederhana, kapasitas terbatas | 4GB | 2TB |
| **Btrfs**   | Sistem file Linux modern dengan fitur lanjutan seperti snapshot dan subvolume | 16EB | 16EB |

> **Catatan**: EB singkatan dari Exabyte, yang setara dengan 1 juta terabyte.

---
