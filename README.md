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




