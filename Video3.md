# Branch - Command Git
Jika kita punya repo di github, dan sudah melakukan beberapa commit, di tab network muncul bentuk master branch, garis yang sebagai cabang utama dengan titik biru berupa commit.

Dari master branch kita dapat membuat cabang yang independen, berfungsi saat kita mau membuat fitur baru tanpa mengubah master branchnya, dalam 1 repo kita dapat membuat beberapa branch.

Branching:
- Saat membuat Git Branch
- Membuat snapshot tanpa mengganggu master branch
- Fitur yang experimental
- Ada orang lain yang mengerjakan repo yang sama (digabung kembali menggunakan merge)

Cara buat branch:
- Cara 1:

<a href="https://ibb.co/ZXyptkR"><img src="https://i.ibb.co/02PR8dp/image.png" alt="image" border="0"></a>
1. Edit/Buat file
2. Saat commit, pilih create a new branch for this commit and start a pull request
- Cara 2:

<a href="https://ibb.co/crcDv5j"><img src="https://i.ibb.co/XCZS4Bq/image.png" alt="image" border="0"></a>
1. Klik branch, lalu di bawah tulisan switch branches, kita bisa search atau create branch baru
2. tampilannya sama/snapshot di duplikat, lalu kita dapat menambahkan file/folder sama seperti di master branch
3. saat commit, tombol commit directly berubah ke branch yang baru dibuat, bukan master branch

Perubahan yang dilakukan di branch tidak akan mengganggu master branch.

Untuk mengembalikan fitur branch ke master branch, kita melakukan merging dengan klik compare & pull request.

Github mengecek apakah 2 commit ini bisa merge atau tidak, jika bisa git akan merging secara otomatis.

Branch harus minta izin ke pemilik repo untuk menarik perubahan yang dilakukan, sehingga namanya pull request.

Pesan pull request muncul di master branch, di tab pull request, jika perubahan sudah disetujui, langsung klik tombol merge, lalu ada tempat untuk membalas pesan orang yang melakukan merge tadi.

Setelah selesai, pull request hilang dan master berubah.

Untuk menghapus branches, langkahnya:

<a href="https://ibb.co/4SbNgMs"><img src="https://i.ibb.co/WzrKpFD/image.png" alt="image" border="0"></a>
1. Klik branches
2. Klik delete this branch

Jika ada konflik dengan master, kita dapat melakukan pull request, namun isinya tidak dapat dimerge otomatis, di pull request, conflict diselesaikan secara manual di code editor.

Setelah conflict selesai, baru bisa di merge.
Jika kita sudah tidak butuh branches, branch dapat didelete

Recap:
- Branch: Jalur 'development' bebas dari sebuah commit
- Checkout: Berpindah ke branch / commit yang lain
- Pull Request: Meminta pemilik repo 'mengambil' perubahan yang telah dilakukan
- Merge: Menggabungkan 2 branch
- Merge conflict: Baris yang sama diubah oleh 2 branch yang berbeda