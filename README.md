"# TugasbesarProklan" 
Dokumen/Program Specification:

Tujuan Program:

Program ini bertujuan untuk menyediakan aplikasi kasir sederhana menggunakan JavaFX.
Mampu mencatat transaksi penjualan, mengelola daftar produk, menghitung total belanja, dan mencetak nota pembayaran.
Fungsi Utama:

Menambahkan produk baru ke daftar.
Melihat daftar produk yang tersedia.
Menambahkan produk ke dalam transaksi.
Menghitung total belanja.
Melakukan pembayaran dan menghitung kembalian.
Mencetak nota pembayaran.
Penggunaan:

Pengguna dapat menambahkan produk baru dengan menekan tombol "Tambah Produk."
Daftar produk ditampilkan dengan tombol untuk menambahkannya ke transaksi.
Transaksi dan total belanja ditampilkan pada panel transaksi.
Pembayaran dilakukan dengan memasukkan jumlah bayar, dan kembalian dihitung.
Pengguna dapat mencetak nota pembayaran.
Deffensive Programming (based on point 1):

Validasi Input:

Mengecek apakah harga dan jumlah stok saat menambah produk adalah numerik.
Memastikan pembayaran dan jumlah produk yang dibeli juga numerik.
Handling Exception:

Menangani IOException, NumberFormatException, dan eksepsi lainnya yang mungkin terjadi selama operasi file dan pengolahan data.
Program Verification/Testing (based on point 1):

Unit Testing:

Melakukan pengujian unit pada setiap metode untuk memastikan fungsionalitas yang benar.
Pengujian untuk menambah produk baru, menambahkan produk ke transaksi, menghitung total, menghitung kembalian, dan mencetak nota.
Integration Testing:

Menguji integrasi antara berbagai bagian aplikasi, memastikan kerja sama yang benar di antara panel produk, transaksi, dan pembayaran.
Project Documentation (JavaDoc/Java Comment; Read-Me file):

JavaDoc:

Memberikan dokumentasi JavaDoc untuk setiap metode dan kelas, menjelaskan parameter, return value, dan tujuan dari setiap fungsi.
Read-Me File:

Menyertakan file Read-Me yang menjelaskan cara menggunakan aplikasi, persyaratan sistem, dan instruksi instalasi.
Penggunaan Version Control (Git/GitHub):

Version Control:

Menggunakan Git untuk melacak perubahan kode.
Melakukan commit dengan pesan yang jelas untuk setiap perubahan.
Mungkin mencakup branch untuk pengembangan fitur atau perbaikan bug.
GitHub:

Menyimpan repository di GitHub untuk kolaborasi dan distribusi kode.
Mungkin menggunakan isu (issue) untuk melacak pekerjaan yang harus dilakukan.
API Implementation:

JavaFX API:
Menggunakan API JavaFX untuk membangun antarmuka pengguna grafis.
Menggunakan kontrol seperti Button, Label, TextField, ListView, dll.
I/O File Handling (Read & Write file):

Read File:

Membaca data produk dari file "produk.txt" pada saat aplikasi dimulai.
Write File:

Menyimpan data produk ke file setiap kali terjadi perubahan pada daftar produk.
GUI Based Application:

Antarmuka Pengguna:

Menyediakan antarmuka pengguna yang intuitif dengan bantuan JavaFX.
Menyajikan daftar produk, transaksi, dan pembayaran secara terpisah di dalam panel.
Responsif:

Menanggapi input pengguna secara dinamis dan memberikan umpan balik visual yang sesuai.
