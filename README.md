# Tugas-1-Sistem-Operasi

## Proses Instalasi

1. **Tampilan Awal Boot**
   - Pengguna bisa mencoba sistem untuk memastikan semuanya telah berjalan dengan benar sebelum yakin untuk menginstal.

   ![Tampilan awal boot Linux](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/1.png)

2. **Pemilihan Bahasa**
   - Pilih bahasa yang akan digunakan oleh Sistem Operasi dan proses instalasi.

   ![Pemilihan Bahasa](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/2.png)

3. **Ringkasan Instalasi**
   - Tinjau opsi konfigurasi yang telah Anda pilih.

   ![Ringkasan Instalasi](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/3.png)

4. **Tujuan Instalasi**
   - Pilih di mana sistem operasi akan diinstal. Dalam panduan ini, kita akan memilih opsi kustom.

   ![Tujuan Instalasi](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/4.png)

5. **Pemilihan Sistem File**
   - Kita akan memilih Btrfs karena merupakan sistem file paling modern yang tersedia.

   ![Pemilihan Sistem File](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/5.png)

6. **Pemasangan Partisi**
   - Kita akan menginstal Linux dengan partisi yang di-mount ke `/` (juga disebut root), yang merupakan direktori dasar tempat file Linux yang paling penting berada. Kita juga `mount` sebagian dari sistem operasi ke `/home` terpisah dari root untuk lebih mudah manajemen file, namun dalam kasus ini kita akan mount sistem operasi seperti pada awal

   ![Pemasangan Partisi](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/6.png)

7. **Pembuatan Password Root**
   - Buat password root untuk kegiatan superuser.

   ![Pembuatan Password Root](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/7.png)

8. **Mulai Instalasi**
   - Setelah semua konfigurasi selesai, klik 'Mulai Instalasi' dan tunggu sampai proses selesai.

   ![Mulai Instalasi](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/8.png)

9. **Penyelesaian**
   - Setelah instalasi selesai, Anda bisa mencoba Linux atau reboot untuk masuk ke sistem yang terinstal.

   ![Penyelesaian](https://github.com/superapple8x/Tugas-1-Sistem-Operasi./blob/main/9.png)

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
