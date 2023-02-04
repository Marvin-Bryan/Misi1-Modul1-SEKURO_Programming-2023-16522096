# .gitignore

File yang dapat disimpan di repo git agar ada file yang tidak ikut dalam proses commit.

File sistem terkadang terbawa setelah dicommit, sehingga kita perlu .gitignore.

Di Github, cara membuat file .gitignore adalah dengan otomatis menggunakan saran dari github.

Push dari repo di Git ke GitHub:

    $ 'git remote...' (ada di GitHub)
    $ git push

Sebelum push, kita perlu menentukan remote dengan copy kode 'git remote...' di Github.

Membuat folder dengan terminal:

    $ mkdir <nama folder>

Cara membuka Visual Studio Code dari Terminal/Git-Bash:

    $ code .

Cara menjalankan .gitignore:
1. Buat file .gitignore di repo
2. Masukkan nama dan extension file (contoh saya.txt) yang tidak ingin dibawa
3. Masukkan folder diikuti dengan / (Misalnya data/) jika ada suatu folder yang tidak ingin dibawa
4. Masukkan * lalu extension (Misalnya *.js) jika semua file berextension tersebut tidak ingin dibawa (Misalnya javascript)

Biasa .gitignore digunakan jika ada konfigurasi di local di dalam repo, misalnya konfigurasi database di local

https://github.com/github/gitignore dapat digunakan untuk kita melihat file apa saja yang disarankan untuk di-ignore di file .gitignore

Mudahnya, hal ini dapat dilakukan di

    https://gitignore.io/ 

Website ini langsung generate isi file/folder .gitignore yang harus tidak dimasukan ke Github.

## Bukti pengerjaan di Git-Bash

<a href="https://ibb.co/mXVQBWJ"><img src="https://i.ibb.co/b2Mp391/image.png" alt="image" border="0"></a>
<a href="https://ibb.co/m03KQX8"><img src="https://i.ibb.co/PMdyB9Q/image.png" alt="image" border="0"></a>
