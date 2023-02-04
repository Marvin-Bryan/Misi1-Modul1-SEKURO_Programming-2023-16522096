# Git

Install [Git](https://git-scm.com/) di https://git-scm.com/

Setelah menginstall git, command dijalankan dengan Command Prompt

Git Client(GUI) adalah User Interface yang dibuat untuk mempermudah melakukan VCS (Mirip dengan menggunakan Github)

Ada e-book [Pro Git](https://git-scm.com/book/en/v2) yang dapat didownload untuk belajar git

## Cara Install Git:
1. Buka https://git-scm.com/

<a href="https://ibb.co/XzxqFfc"><img src="https://i.ibb.co/HrTjGL5/image.png" alt="image" border="0"></a>

2. Klik layar monitor warna biru di kanan layar

3. Ikuti petunjuk instalasi

## Perintah lokal Git
- $ git init: Inisialisasi repo git di komputer
- $ git add <file(s)>: Tambahkan file ke staging area
- $ git status: Mengetahui status repo saat ini (cek file baru, file berubah, file hilang)
- $ git commit: Melakukan commit
- $ git config: Memasukkan konfigurasi
- $ git branch: Membuat branch
- $ git help: Mengetahui cara menggunakan perintah dengan cepat

3 area pada repo Git:
- Working tree
- Staging area
- History

Staging area dan History akan tersimpan ke file/folder .git saat folder sudah diinisialisasi sebagai repo

Implementasi dari Github sebagai berikut
<a href="https://ibb.co/SQxq6d0"><img src="https://i.ibb.co/s5PLg6Q/image.png" alt="image" border="0"></a>

Cara mengubah folder menjadi Git adalah dengan command git init, folder langsung berubah menjadi repo git dengan tulisan master

<a href="https://ibb.co/yNb27c6"><img src="https://i.ibb.co/10wcjtr/image.png" alt="image" border="0"></a>

Untuk melihat status repo, kita dapat menggunakan:

    $ git status

Untuk melakukan tracking (masukkan file ke staging area), kita dapat menggunakan:

    $ git add <file(s)>

Ganti nama file dengan . untuk memasukkan banyak folder sekaligus.

Saat kita menulis git commit untuk pertama kali, kita perlu mengisikan data nama dan email dengan:
    
    $ git config --global user.email "email"
    $ git config --global user.name "Nama"


Cara melakukan commit di git adalah dengan:
    
    $ git commit -m "Pesan yang ingin diberikan"

Untuk mengecek file telah dicommit kita menggunakan:
    
    $ git status

Untuk mengecek history kita dapat menggunakan:
    
    $ git log

Untuk mengecek 3 history commit terakhir:
    
    $ git log -3

Untuk mengecek commit spesifik untuk file tertentu:
    
    $ git log -- <nama file yang dicari>

<p>&nbsp;</p>

# Checkout
Checkout adalah mengembalikan kode dari history yang telah terhapus/termodifikasi ke staging area.

Checkout ke sebuah keadaan
    
    $ git checkout <5 digit pertama commit hashnya>

Mengembalikan perubahan yang terjadi pada file tertentu
    
    $ git checkout <5 digit pertama commit hashnya> -- <nama file yang akan dikembalikan>