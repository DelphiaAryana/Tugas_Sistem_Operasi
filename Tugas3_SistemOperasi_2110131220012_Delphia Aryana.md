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

<p align="center">Ps :</p>
<p align="center"><img src="img/photo2.png" width="450px"></p>

<br>

2. Mematikan Prioritas Proses

<p align="justify">Ketika sebuah proses menggunakan sumber daya terlalu tinggi. Biasanya hal ini membuat kinerja perangkat menjadi lambat atau bahkan dapat menyebabkan <b>‘hang’</b> Biasanya untuk mencegah dan mengatasi ini dilakukan penanganan atau mematikan proses yang tidak terlalu dibutuhkan. Salah satu caranya adalah dengan menggunakan perintah <b>“kill”</b>. Perintah ini digunakan untuk mengirimkan sinyal ke proses untuk menghentikan aktivitasnya.

<p align="center"><img src="img/photo3.png" width="670px"></p>

<br>

## Manajemen Memori

<p align="justify">Pada command line, informasi mengenai memori tersedia melalui <b>free perintah</b>. Pada Debian GNU/Linux, Ubuntu dan Linux Mint program ini merupakan bagian dari paket procps.

<p align="center"><img src="img/photo4.png" width="600px"></p>

<br>

## Manajemen Sistem Berkas

<p align="justify"> Berkas adalah kumpulan informasi yang berhubungan, sesuai dengan tujuan pembuat berkas tersebut. Umumnya berkas merepresentasikan program dan data. Berkas dapatmempunyai struktur yang bersifat hirarkis (direktori, volume, dll.). Sistem operasi bertanggung-jawab dalam aktivitas yang berhubungan dengan manajemen berkas, seperti pembuatan berkas, penghapusan berkas, dll.

<p align="center"><img src="img/photo4.png" width="600px"></p>


<br>

## Manajemen Masukan/Keluaran (I/O)

<p align="justify"> Sistem ini sering disebut dengan device manager. Menyediakan device driver yang umum sehingga operasi Masukan/Keluaran dapat seragam (membuka, membaca, menulis, menutup). Pada command line, Ps merupakan inputan yang sudah ada dari sistem. Jika ingin meminta inputan dari keyboard, gunakan perintah cat. Maka output akan langsung tampil.

<p align="center"><img src="img/photo5.png" width="450px"></p>

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

<br>

Di sini saya akan memberikan 3 contoh komponen sistem operasi :

## Sistem Menipulasi Berkas

<p align="justify"> Sistem manipulasi berkas merupakan layanan sistem operasi yang dimana program harus membaca dan menulis berkas, dan kadang kala juga harus membuat dan menghapus berkas. Berikut contohnya pada command line.

<p align="center"><img src="img/photo6.png" width="600px"></p>

<br>

## Deteksi Error

<p align="justify">Untuk setiap jenis error sistem operasi harus bisa mengambil langkah yang tepat untuk mempertahankan jalannya proses komputasi. Misalnya dengan menghentikan jalannya program, mencoba kembali melakukan operasi yang dijalankan, atau melaporkan kesalahan yang terjadi agar pengguna dapat mengambil langkah selanjutnya. 

<p align="center"><img src="img/photo7.png" width="550px"></p>

<br>

## Proteksi

<p align="justify">Layanan proteksi memastikan bahwa segala akses ke sumber daya terkontrol. Dan tentu saja keamanan terhadap gangguan dari luar sistem tersebut. Keamanan bisa saja dilakukan dengan terlebih dahulu mengidentifikasi pengguna. Ini bisa dilakukan dengan meminta password bila ingin menggunakan sumber daya. 

<p align="center"><img src="img/photo8.png" width="400px"></p>

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