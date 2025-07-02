# KeuanganAPP
# Aplikasi Catatan Keuangan Harian

# I.	Latar Belakang
Banyak orang sering lupa mencatat pengeluaran atau pemasukan sehari-hari, padahal kebiasaan mencatat keuangan penting untuk mengatur finansial pribadi. Sayangnya, tidak semua orang ingin menggunakan aplikasi yang rumit. Oleh karena itu, dibutuhkan aplikasi sederhana yang bisa digunakan secara offline di komputer/laptop untuk mencatat keuangan harian. Proyek ini dikembangkan menggunakan prinsip Pemrograman Berorientasi Objek (OOP) dan dijalankan di lingkungan console.

# II.	Alur Sistem
1.	Pengguna membuka aplikasi dan login ke akun masing-masing.
2.	Setelah login, pengguna bisa mencatat pemasukan atau pengeluaran.
3.	Sistem akan menyimpan setiap transaksi ke file lokal.
4.	Pengguna bisa melihat riwayat transaksi dan total saldo harian/bulanan.
5.	Pengguna bisa menghapus catatan jika ada kesalahan input.

# III.	Aktor pada Sistem
a. User
- Registrasi dan login
- Input pemasukan/pengeluaran
- Melihat catatan transaksi
- Melihat total saldo
- Menghapus catatan transaksi

# IV.	Rencana Fitur
- Login dan Registrasi: Untuk memisahkan data antar pengguna.
- Input Transaksi: Bisa memilih jenis transaksi (pemasukan/pengeluaran), jumlah, dan deskripsi.
- Lihat Riwayat: Menampilkan semua transaksi yang pernah dicatat.
- Lihat Total Saldo: Menampilkan sisa saldo berdasarkan semua transaksi.
- Hapus Transaksi: Menghapus transaksi berdasarkan ID atau tanggal.
- Penyimpanan Lokal: Data disimpan di file .txt atau .json.
  
# V.	Rencana Implementasi
1.	Perencanaan & Analisis
- Menentukan ide dan tujuan proyek
- Mengidentifikasi aktor, fitur, dan kebutuhan fungsional
- Mendesain class diagram untuk objek-objek utama seperti User, Transaksi, dan KeuanganApp

2. Persiapan Proyek
- Membuat repository GitHub untuk dokumentasi dan versioning
- Menyusun struktur folder dan file proyek
- Menyiapkan template awal program (main class, struktur package)

3.	Pembuatan Fitur Dasar
- Membuat sistem login dan registrasi
- Menyimpan data user secara sederhana (file atau list)

4.	Pembuatan Fitur Inti
- Membuat fitur input transaksi (pemasukan/pengeluaran)
- Menyimpan transaksi ke dalam file
- Menambahkan fitur melihat semua catatan transaksi
- Menambahkan fitur perhitungan saldo total secara otomatis

5.	Pengelolaan Data & Validasi
- Menambah fitur hapus transaksi jika ada kesalahan input
- Validasi input dari user (jumlah tidak boleh minus, dsb)
- Pengelompokan data berdasarkan kategori atau tanggal

6.	Penyempurnaan dan Dokumentasi
- Melakukan testing setiap fitur untuk memastikan berjalan dengan baik
- Membersihkan kode (refactor) dan menambahkan komentar
- Menyusun dokumentasi proyek di file README.md di GitHub
- Menyiapkan laporan akhir dan file presentasi

📄 [Lihat Laporan Proyek (PDF)](https://github.com/haruyaaa-ai/KeuanganAPP/blob/main/Kelompok%209_PBO2.pdf
)
