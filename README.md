2# Latihan10

BAHASA PEMROGRAMAN

TEHNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : Arip Hidayattuloh

NIM : 312010244

KELAS : TI.20.B1

DOSEN : Agung Nugroho,S.Kom.,M.Kom

Tugas : Pertemuan 10

![tugas_praktikum](https://user-images.githubusercontent.com/72840534/101016895-f87bd480-359b-11eb-8f23-f964ee0ab43e.png)



Baiklah saya akan menjelaskan fungsi - fungsi dari syntax tersebut:


Keterangan:

○ Kalian bisa menggunakan list atau dictionary sesuai keinginan kalian sendiri tapi tentu saja list dan dictionary berbeda ya tapi kegunaanya sama

1. Tambah data nilai mahasiswa


![tambah](https://user-images.githubusercontent.com/72840534/101018975-d899e000-359e-11eb-8bb5-a4a9c7eee931.jpg)


Keterangan:

○ def tambah, def digunakan untuk membuat fungsi lalu tambah digunakan agar ketika kita memilih menu tambah langsung mengeksekusi syntax tersebut

○ Lalu kita buat inputan nama, nim, nilai tugas, nilai uts, dan nilai uas, lalu kita buat hasil / total dari keseluruhan nilai

2. Hapus data nilai mahasiswa

![hapus](https://user-images.githubusercontent.com/72840534/101017351-8c4da080-359c-11eb-90e3-3e68ca46a5b7.jpg)

Keterangan:

○ Lalu seperti biasa kita gunakan def hapus agar ketika kita memilih pilihan menu hapus akan masuk ke dalam syntax ini untuk menghapus data

○ Kita buat inputan nama karena kita akan menghapus data nilai mahasiswa tersebut dengan menggunakan nama mereka untuk menghapusnya

○ lalu gunakan if untuk mengeksekusi data yang di dictionary menggunakan nama(True)

○ Lalu del untuk menghapus semua data nilai mahasiswa tersebut

○ Lalu kita buat else gunanya untuk ketika kita belum menginputkan data apapun maka tidak ada data yang bisa di hapus(False)

3. Ubah data nilai mahasiswa

![ubah](https://user-images.githubusercontent.com/72840534/101017457-b606c780-359c-11eb-9cce-a479f2e5f762.jpg)


Keterangan:

○ kita gunakan def ubah agar ketika kita memilih pilihan menu ubah akan masuk ke dalam syntax ini untuk mengubah data

○ Lalu kita buat inputan nama karena kita akan mengubah data nilai mahasiswa dengan menginputkan nama mahasiswa tersebut

○ Lalu if nama in data_nilai.keys untuk mengeksekusi jika nama terdapat di dalam dictionary

○ Lalu kita buat inputan untuk memasukkan nilai tugas, uts, dan uas yang terbaru

○ Lalu kita gunakan hasil untuk menghitung total semua nilai tersebut


4. Tampilkan data nilai mahasiswa

![tampil](https://user-images.githubusercontent.com/72840534/101017574-d898e080-359c-11eb-95fe-10f95858bdca.jpg)

Keterangan:

○ kita gunakan if data_nilai.items gunanya untuk melihat hasil / menampilkan semua data di dalam dictionary(True)

○ Lalu kita gunakan print untuk membuat tablenya

○ Lalu for i = 0 digunakan untuk membuat nomor urut otomatis dibagian No. didalam table

○ Lalu kita gunakan for x gunanya untuk format penampilan data nilai mahasiswa

○ lalu gunanya angka yang di dalam {} itu di gunakan untuk membatasi atau bisa di bilang seperti tab agar data yang di tampilkan lebih rapih

○ Lalu else disini di gunakan ketika kita belum menginputkan atau menambahkan data apapun akan muncul tidak ada data(False)

5. Membuat pilihan menu

![tampil menu](https://user-images.githubusercontent.com/72840534/101017837-31687900-359d-11eb-9e21-d83eca35909b.jpg)

Keterangan:

○ Kita gunakan perulangan while True untuk membuat pilihan menunya

○ Karena tidak disuruh untuk menampilkan outputnya seperti apa jadi saya menggunakan nomor saja untuk membuat pilihan menunya alasannya agar terlihat lebih rapih dan mudah

○ Lalu kita buat dibawahnya inputan untuk memasukkan pilihan yang kita inginkan

○ Lalu kita gunakan if dan elif agar ketika kita memiih menu 1, 2, 3, 4, atau 5 kita akan memasuki syntax yang def tadi

○ Lalu dibawahnya kita gunakan tambah, tampil, hapus, dan ubah untuk mengeksekusi syntax yang tadi, itulah kenapa kita menulisnya def tambah, def tampil, def hapus, dan def ubah

○ lalu kita break kita gunakan untuk keluar dari program tersebut

○ Lalu else digunakan agar ketika kita tidak memilih pilihan menu maka akan muncul tulisan "pilih menu yang tersedia diatas"

Maka ini adalah hasil running dari syntax di atas:

1. Pilihan menu tambah, tampil, hapus, ubah, dan keluar dari program

![hasil tampil menu](https://user-images.githubusercontent.com/72840534/101018021-768cab00-359d-11eb-84c0-0add2c279a8b.jpg)


2. Tambah data nilai mahasiswa

![tambah1](https://user-images.githubusercontent.com/72840534/101018708-7640df80-359e-11eb-88b1-56f83321c490.jpg)


3. Tampilkan data nilai mahasiwa

![hasil tampil](https://user-images.githubusercontent.com/72840534/101018176-b5226580-359d-11eb-922c-5617c85fbd6a.jpg)

4. Hapus data nilai mahasiswa

![hasil menghapus](https://user-images.githubusercontent.com/72840534/101018259-ce2b1680-359d-11eb-8dbd-8c15db2fe560.jpg)


5. Keluar dari program

![hasil keluar program](https://user-images.githubusercontent.com/72840534/101018435-15190c00-359e-11eb-9cf4-4a1745614c17.jpg)

