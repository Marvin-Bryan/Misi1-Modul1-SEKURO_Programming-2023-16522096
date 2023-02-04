# Git Merge Conflict

Merge conflict terjadi karena 2 branch mengerjakan baris yang sama dalam 1 repo, sehingga git tidak dapat resolve secara otomatis.

Cara menyelesaikan masalah ini adalah dengan melakukan merging manual di code editor.

File yang sudah dimodifikasi harus disimpan di staging area, lalu di commit dan file yang tadinya conflict akan terselesaikan.

Untuk kembali ke branch setelah di-delete kita dapat menggunakan:

    $ git checkout <7 digit hash>

Ini merupakan kondisi "detached head", head yang tidak menempel di branch, namun di sebuah commit.

Untuk kembali dan melanjutkan dari commit sebelumnya, kita dapat membuat branch baru.

    $ git branch test
    $ git checkout test

Branch baru berisi file dari commit yang ingin kita kembalikan berhasil dibuat.

## Bukti screenshot percobaan di Git-Bash

<a href="https://ibb.co/tckCnRQ"><img src="https://i.ibb.co/GkBPGmn/image.png" alt="image" border="0"></a>
