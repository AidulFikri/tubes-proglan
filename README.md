# Aplikasi Penyewaan Mobil GUI

Aplikasi ini adalah sebuah program sederhana untuk penyewaan mobil dengan antarmuka pengguna grafis (GUI) menggunakan Java Swing. Aplikasi ini memungkinkan pengguna untuk menampilkan daftar mobil, menyewa mobil, dan melihat serta mengelola struk penyewaan.

## Fitur

1. **Tampilkan Daftar Mobil:**
   - Pengguna dapat melihat daftar mobil beserta informasi seperti nama, tahun produksi, harga sewa per hari, ketersediaan, dan kategori.

2. **Sewa Mobil:**
   - Pengguna dapat menyewa mobil dengan memilih mobil dari daftar dan memasukkan durasi sewa dalam jumlah hari.

3. **Tampilkan Struk:**
   - Pengguna dapat melihat struk penyewaan yang telah dibuat. Struk mencakup informasi seperti nomor transaksi, nama mobil, tahun produksi, lama sewa, dan total biaya.

4. **Update dan Hapus Struk:**
   - Pengguna dapat mengupdate lama sewa pada struk penyewaan dan melihat perubahan tersebut dalam tampilan tabel.
   - Pengguna dapat menghapus struk penyewaan.

5. **Penyimpanan Data:**
   - Catatan penyewaan disimpan dalam file "rental_records.dat".
   - Struk penyewaan disimpan dalam file teks "rental_records.txt".

## Cara Menjalankan Aplikasi

1. Pastikan Java Development Kit (JDK) telah terinstal di komputer Anda.
2. Kompilasi dan jalankan program menggunakan perintah berikut di terminal atau command prompt:

   ```bash
   javac AplikasiPenyewaanMobilGUI.java
   java AplikasiPenyewaanMobilGUI
