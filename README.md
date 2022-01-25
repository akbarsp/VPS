# Linux Essentials For Hackers

(File Management & Manipulation)
1. ls -lR Dir/                  : Menampilkan isi Direktori yang dituju.
2. cat /etc/passwd > file.txt   : Menyalin file passwd ke file.txt
3. rm -R                        : Hapus semua isi direktori dan direktori tersebut
4. chmod 444 file.txt           : file hanya bisa di baca 
5. chmod 744 file.txt           : file bisa dibaca dan di edit, tetapi grup hanya baca
6. chmod ugo=rwx file.txt       : sama saja seperti diatas
7. sudo find / -type f/d -iname : Mencari file/direktori, jika -perm 400 dll tidak pakai "sudo" 
8. history -c                   : Hapus histori bash/terminal
9. du -sh *                     : Cek size direktori
10. df -h                       : Cek penggunaan disk
11. tar -cvf dir.tar dir/       : Arsipkan direktori (gzip/,gz tambah -czvf)
12. tar -xcf dir.tar            : Ekstrak direktori
