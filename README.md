# CODE PROGRAM DAFTAR NILAI

## Step 1 : Class DaftarNilaiMahasiswa dan Method Init

Kelas yang diberikan adalah struktur utama untuk mengelola data mahasiswa. Semua operasi seperti menambah, menampilkan, menghapus, dan mengubah data dilakukan melalui metode-metode yang ada dalam kelas ini.

Selain itu, Method init adalah konstruktor yang dijalankan saat objek kelas dibuat. Di sini, atribut data_mahasiswa diinisialisasi sebagai list kosong untuk menyimpan data mahasiswa.

![gambar](https://github.com/M-Rakha/labpy08/blob/9f7489b18edbc9b44140fce14fafb9f531703fd3/Cuplikan%20layar%202024-12-09%20185341.png)

## Step 2 : Method tambah

Metode ini digunakan untuk menambahkan data mahasiswa baru ke dalam list data_mahasiswa. Data disimpan sebagai dictionary dengan kunci seperti nama, nim, L/P?, dan nilai :

![gambar](https://github.com/M-Rakha/labpy08/blob/053c6aea8191e0ac95c3353c0043ccda3c468677/Cuplikan%20layar%202024-12-09%20185634.png)

## Step 3 : Method tampilkan

Method atau Fungsi ini mencetak daftar mahasiswa yang sudah tersimpan. Jika daftar kosong, akan menampilkan pesan "Tidak ada data mahasiswa". Jika tidak kosong, data ditampilkan dalam bentuk tabel dengan nomor urut, nama, NIM, gender, dan nilai :

![gambar](https://github.com/M-Rakha/labpy08/blob/1b8553ab492ce8cc8e51e7f9ef8b60008ce117e1/Cuplikan%20layar%202024-12-09%20190045.png)

## Step 4 : Method hapus

Selanjutnya ada method menghapus data mahasiswa dengan cara kerja program mencari sebuah nama yang telah diinputkan, jika nama ditemukan maka program akan langsung menghapus nama tersebut dari daftar, namun jika tidak ditemukan program akan memberi tahu kalau tidak ada daftar yang ditemukan :

![gambar](https://github.com/M-Rakha/labpy08/blob/6e96b588344512a69ff23f890446b2f0815018f7/Cuplikan%20layar%202024-12-09%20190349.png)

## Step 5 : Method ubah

Method ini sama seperti sebelumnya jika di lihat dari cara kerjanya namun di fungsi kali ini program akan mengubah suatu nama dari daftar, Jika nama ditemukan, data seperti NIM, gender, dan nilai akan diperbarui. Jika tidak, akan menampilkan pesan bahwa data tidak ditemukan :

![gambar](https://github.com/M-Rakha/labpy08/blob/6086af0bac87a45f36a5f1a935e6b1afd7c7b142/Cuplikan%20layar%202024-12-09%20190540.png)

## Step 6 : Fungsi main dan Menu interaktif

Bagian ini adalah titik awal program. Program berjalan dalam loop yang menawarkan menu interaktif kepada pengguna untuk memilih salah satu opsi, Setiap pilihan menjalankan metode yang sesuai dari kelas DaftarNilaiMahasiswa. Jika pilihan tidak valid, program akan meminta pengguna mencoba lagi :

1. Tambah data (opsi 1)
2. Tampilkan data (opsi 2)
3. Hapus data (opsi 3)
4. Ubah data (opsi 4)
5. Keluar dari program (opsi 5)

![gambar](https://github.com/M-Rakha/labpy08/blob/3f6651744b4f2237cb0f67e4fc77213f5ed4fc19/Cuplikan%20layar%202024-12-09%20190828.png)

![gambar](https://github.com/M-Rakha/labpy08/blob/76e694277aecd1cc7786e6b9eef26e82300b89c9/Cuplikan%20layar%202024-12-09%20190912.png)

## Step 7 : Run Program

Tahap akhir adalah uji coba code program yang sudah dibuat dengan mencoba berbagai kemungkinan yang ada.

## Case 1 :

Kondisi pertama kita akan coba melihat tabel dengan inputkan 2 tampa menambahkan data/masih kosong, maka akan ditampilkan isi tabel masih belum ada datanya, akan ditampilkan 'Tidak ada Data Mahasiswa' :

![gambar](https://github.com/M-Rakha/labpy08/blob/1a845d8821544c6ea1a0d46aa43bac0852b12492/Cuplikan%20layar%202024-12-09%20191258.png)

## Case 2 :

Kondisi kedua selanjutnya mencoba menambahkan data mahasiswa pada tabel, dengan menginputkan 1 untuk menambahkan data mahasiswa. Untuk awalan, coba memasukan satu data mahasiswa :

- Nama : Muhammad Rakha Ghani
- Nim : 312410421
- Gender : L
- Nilai : 90

![gambar](https://github.com/M-Rakha/labpy08/blob/553aca6e2bc3d225d6c91a8b45504faceaefdc62/Cuplikan%20layar%202024-12-09%20191634.png)

## Case 3 :

Selanjutnya, kondisi ketiga masukan/tambah lagi daftar mahasiswa sebanyak 3 data untuk memperbanyak data yang ditampilkan, setelah itu pilih 2 kembali untuk melihat data yang sudah ditambahkan, berikut data yang harus di tambahkan :

1. Data pertama :
- Nama : Raihan Ardiansyah
- Nim : 312410396
- Gender : L
- Nilai : 92

![gambar](https://github.com/M-Rakha/labpy08/blob/81ccc4a52d7a36363c7cd01ee732ec6f1db92901/Cuplikan%20layar%202024-12-09%20192057.png)

2. Data kedua :
- Nama : M. Nikmal Wahid
- Nim : 312410372
- Gender : L
- Nilai : 95

![gambar](https://github.com/M-Rakha/labpy08/blob/9c9ff10f7f132397ed9637c7ec6c4c3bc6f1e904/Cuplikan%20layar%202024-12-09%20192625.png)

3. Data ketiga :
- Nama : Yarni Gea
- Nim : 312410413
- Gender : P
- Nilai : 98

![gambar](https://github.com/M-Rakha/labpy08/blob/cc5522a9aeb3d8b7b0e319718649b4a577b5e478/Cuplikan%20layar%202024-12-09%20193119.png)

Jika sudah maka tampilan pada tabel akan seperti berikut :

![gambar](https://github.com/M-Rakha/labpy08/blob/8fbc2af7961af0ec0ae1bf6de62af233672d5dd2/Cuplikan%20layar%202024-12-09%20193315.png)

## Case 4 :

Masuk kondisi keempat kita akan coba mengubah data, ada data yang salah diinputkan pada Nilai Mahasiswa 92 diubah menjadi 93, sebelum itu inputkan 4 untuk mengubah lalu user diminta untuk memasukan nama mahasiswa, nim, gender, dan Nilai beru, kita coba memasukan data berikut :

Data yang diubah :
- Nama : Raihan Ardiansyah
- Nim : 312410396
- Gender : L
- Nilai : 93

![gambar](https://github.com/M-Rakha/labpy08/blob/232bb648f2077646dc8a215c440bade77a6da084/Cuplikan%20layar%202024-12-09%20193720.png)

Maka Tampilan nya akan seperti berikut ini :

![gambar](https://github.com/M-Rakha/labpy08/blob/431ff3968f36d05ac7438dd99135084642f44fe4/Cuplikan%20layar%202024-12-09%20193933.png)

## Case 5 :

Kondisi keenam, kita mencoba menghapus sebuah data mahasiswa dengan menginputkan 3 untuk menghapuskan data mahasiswa lalu user diminta memasukan nama mahasiswa yang akan dihapus :







