---
title: "Git x Github"
date: 2022-07-23T14:44:05+07:00
draft: false
---

Git merupakan Version Control System yang digunakan sebagai tools sedangkan Github merupakan tempat menyimpan kode sehingga kombinasi keduanya banyak digunakan dalam pengembangan suatu aplikasi atau perangkat lunak.

#### Instalasi Git

Buka terminal, lalu ketik 
```bash
sudo apt-get install git
```
Cek versi git apakah sudah terinstal : **git --version**

#### Konfigurasi Git

Konfigurasi username dan email bertujuan untuk menyesesuikan data user pada Github. Begitu pun pada saat membuat repositori antara keduanya haruslah sama.
```bash
git config --global user.name “username”
git config --global user.email “username@mail.com”
```
Cek konfigurasi apakah sudah benar : **git config --list**

#### Perintah di Git
- git init untuk inisialisasi atau memperkenalkan direktori git.
- git add untuk menambahkan suatu file atau semua file ke dalam kerangka kerja
- git status untuk melihat setiap perubahan yang dilakukan, bertanda merah apabila belum di add dan hijau apabila sudah siap untuk di commit.
- git commit -m “first commit” untuk memberi keterangan dari file yang sudah ditambahkan (git add) atau tanda dari file tersebut. (-m) yang berarti message.
- git remote add origin “link repo .git di github untuk memberi akses remot ke repository di github
- git push -u origin master untuk mendistribusikan file kerja ke repo github.

![wsl](git-way.gif)
