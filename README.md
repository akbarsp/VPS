# Linux Essentials For Hackers

(File Management & Manipulation)
1. ls -lR Dir/                  : Menampilkan isi Direktori yang dituju.
2. cat /etc/passwd > file.txt   : Menyalin file passwd ke file.txt
3. rm -R                        : Hapus semua isi direktori dan direktori tersebut
4. chmod 444 file.txt           : file hanya bisa di baca 
5. chmod 744 file.txt           : file bisa dibaca dan di edit, tetapi grup hanya baca
6. chmod ugo=rwx file.txt       : sama saja seperti diatas
7. sudo find / -type f/d -iname : Mencari file/direktori, jika -perm 400 dll tidak pakai "sudo", -size 1033c(byte)
8. find . -type f | xargs file  : Mencari file yang dapat dibaca human
9. history -c                   : Hapus histori bash/terminal
10. du -sh *                     : Cek size direktori
11. df -h                       : Cek penggunaan disk
12. tar -cvf dir.tar dir/       : Arsipkan direktori (gzip/,gz tambah -czvf)
13. tar -xcf dir.tar            : Ekstrak direktori

(Networking)
1. ip route show        : Menampilkan ip router/gateway
2. ip addr              : Menampilkan IP address
3. sudo netdiscover -i eth0 : Menampilkan scan jaringan anda
4. systemd-resolve --status : Menampilkan informasi DNS
5. sudo systemctl restart network-manager.service : restart network setelah melakukan perubahan
6. htop             : informasi penggunaan prosesor 
7. free             : informasi penggunaan memori yang terpakai dan yang kosong
