### Tugas 3 Sistem Operasi
Nama : Delphia Aryana
NIM : 2110131220012

<br>

<h2 align="center"> Komponen Sistem Operasi </h2>
<hr>

<p align="justify">Secara umum, para pakar sepakat bahwa terdapat sekurangnya empat komponen manajemen utama sistem operasi, yaitu :

- Manajemen proses
- Manajemen memori
- Manajemen sistem berkas
- Manajemen masukan/keluaran (I/O)

<p align="justify">Selain keempat komponen di atas, Avi Silberschatz, dan kawan-kawan menambahkan beberapa komponen,  seperti : 

- Manajamen penyimpanan sekunder
- Manajemen sistem proteksi
- Manajemen jaringan
- _Command-Interpreter System_

<br>

Di sini saya akan memberikan 3 contoh komponen sistem operasi :

## Manajemen Proses

1. Menampilkan Proses Linux

<p align="justify">Perintah yang paling banyak digunakan untuk melihat proses adalah <b>top</b> dan <b>ps</b>. Perbedaannya dengan top adalah top lebih sering digunakan secara interaktif dan ps lebih sering digunakan dalam script, digabungkan dengan perintah bash lainnya atau yang serupa. Perintah top mungkin adalah salah satu yang paling dasar, sering digunakan untuk menampilkan proses teratas yang biasanya mengkonsumsi resource sistem yang paling besar. Top adalah aplikasi yang berdiri sendiri, setelah perintah dieksekusi, layout baru akan muncul dan daftar beberapa proses akan secara konstan diperbaharui setiap detik. Layout baru ini sebenarnya bisa dikendalikan melalui keyboard Anda.

<p align="center">Top :</p> 
<p align="center"><img src="img/photo1.png" width="670px"></p> 
<p align="center"><img src="img/photo2.png" width="450px"></p>
<br>

<h2 align="center"> Layanan Sistem Operasi </h2>
<hr>

<p align="justify">Layanan sistem operasi dirancang untuk membuat pemrograman menjadi lebih mudah. Sebuah sistem operasi yang baik menurut Tanenbaum harus memiliki layanan sebagai berikut:

1. Pembuatan program
2. Eksekusi program
3. Operasi I/O (pengaksesan I/O device)
4. Sistem manipulasi berkas
5. Komunikasi
6. Deteksi error
7. Deteksi dan pemberian tanggapan pada kesalahan
8. Efesiensi penggunaan sistem
9. _Accounting_

### CONTOH :

<br>

<h2 align="center"> System Call </h2>
<hr>

<p align="justify"> <i>System call</i> dapat diartikan sebagai penyedia antar muka dari pelayanan-pelayanan yang tersedia dengan sistem operasi. Biasanya tersedia sebagai instruksi bahasa <i>assembly</i>. Beberapa sistem mengizinkan <i>system calls</i> dibuat langsung dari program bahasa tingkat tinggi. Beberapa bahasa pemrograman (contoh: C, C++) telah didefenisikan untuk menggantikan bahasa <i>assembly</i> untuk sistem pemrograman. Berikut merupakan jenis-jenis <i>system call</i> :

- Manajemen proses _(proses control)_
- Manajemen berkas _(file management)_
- Manajemen piranti _(device management)_
- Informasi/pemeliharaan _(information maintance)_
- Komunikasi _(communication)_

### CONTOH :