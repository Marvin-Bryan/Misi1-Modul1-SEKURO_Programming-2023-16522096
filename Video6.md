# Git Branch

Untuk memasukkan file yang sudah di modify ada beberapa cara:

    $ git add <nama file>
    $ git -a -m "perubahan yang dilakukan"
    $ git -am "perubahan yang dilakukan"

Implementasi Branch di Git:

<a href="https://ibb.co/d6N6Ynn"><img src="https://i.ibb.co/bL4L9pp/image.png" alt="image" border="0"></a>

di Git, ada 2 pointer yaitu untuk branch dan head, keyword head menunjukkan di branch mana kita berada.

Cara membuat branchnya adalah dengan:

    $ git branch <nama branch>

Untuk cek branch yang aktif:

    $ git branch

Untuk menampilkan history dalam bentuk graph:
    
    $ git log --all --decorate --oneline --graph

Membuat alias dapat dilakukan untuk mempersingkat kita menampilkan history dalam graph dengan cara:

    $ alias graph="git log --all --decorate --oneline -- graph"

Alias adalah command yang sementara sampai komputer dimatikan

Cara pindah branch:

    $ git checkout <nama branch yang dituju>

Setelah add dan commit, perubahan hanya terjadi di nama branch yang dimasukkan.

<p>&nbsp;</p>

# Git Merge

Cara menggunakan merge adalah dengan:

    $ git merge <nama branch yang akan dimerge>

Cara menghapus branch:

    $ git branch -d <nama branch yang akan dihapus>

Cara mengetahui branch mana yang sudah dimerge:

    $ git branch --merged

Jika branch belum di merge dengan main branch, dan kita mau paksa menghapusnya, kita dapat menggunakan:

    $ git branch -D <nama branch yang akan dihapus paksa>



Ada beberapa jenis merge:
- Fast Forward: Terjadi ketika branch berada di direct path

- Three-way Merge/Merge commit: Terjadi ketika branch tidak memiliki direct path

### Cara untuk Fast Forward merge dan Three-way Merge sama.

<p>&nbsp;</p>

### Bukti screenshot percobaan di Git-Bash:

<a href="https://ibb.co/qryybLc"><img src="https://i.ibb.co/gRjjsbf/image.png" alt="image" border="0"></a>

