UTS Pemrograman Berorientasi Obyek 2
Mata Kuliah: Pemrograman Berorientasi Obyek 2
Dosen Pengampu: Muhammad Ikhwan Fathulloh
Profil
Nama: Ai Nurul Hidayah 
NIM: 23552011403
Studi Kasus: 
Kasus 3: Kasir Akademik (NIM Belakang 3)
Deskripsi: Kasir untuk pengelolaan pembayaran administrasi kuliah.
Konsep OOP:
  Inheritance: Civitas -> Mahasiswa, Dosen
  Polymorphism: Pembayaran::hitungTagihan()
  Encapsulation: Data nilai dan jadwal
  Abstract Class: Sivitas

Judul Studi Kasus
Kasik Akademik

Penjelasan Studi Kasus
Studi kasus ini mengangkat sistem Kasir Akademik, yaitu sistem yang digunakan untuk mengelola pembayaran administrasi kuliah. Sistem ini bertujuan untuk memudahkan pencatatan dan pengelolaan pembayaran oleh mahasiswa, seperti pembayaran SPP, uang gedung, dan denda keterlambatan. 

Penjelasan 4 Pilar OOP dalam Studi Kasus
1. Inheritance
Digunakan untuk menurunkan atribut dan method dari class umum (Civitas) ke class khusus (Mahasiswa dan Dosen). Class Civitas menyimpan data dasar seperti nama dan alamat, sedangkan class Mahasiswa dan Dosen menambahkan data spesifik sesuai peran masing-masing.
2. Encapsulation
atribut seperti nilai dan jadwal sebagai private agar tidak bisa diakses langsung dari luar class. 
3. Polymorphism
Polymorphism digunakan dengan membuat method hitungTagihan() di class Pembayaran
4. Abstract
Abstract class Sivitas dibuat untuk Bu mendefinisikan struktur umum yang harus dimiliki oleh semua turunan (seperti Mahasiswa dan Dosen)

Demo Proyek
https://github.com/Nurul055/UTS-PEMROGRAMAN-BERORIENTASI-OBJEK-2
Link Gdrive 
https://drive.google.com/folderview?id=1CaRtgc9_IR-eIFma3-H3iCj-PXjoCh5I
