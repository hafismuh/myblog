---
title: "Linux di Windows dengan WSL"
date: 2022-11-11T03:59:13+07:00
draft: false
---
![wsl](wsl.png)

Windows Subsystem for Linux (WSL) merupakan fitur Windows dimana kita dapat menjalankan sistem operasi Linux di Windows dalam waktu yang sama tanpa perlu menggunakan virtual machine atau dual-boot.

WSL dapat dijalankan di Windows 10 versi 2004 ke atas atau di Windows 11 sehingga kita dapat menginstall linux distro seperti Ubuntu, Debian, dan lainnya, termasuk menggunakan aplikasi Linux, utilitas, dan tentu saja bash command-line langsung di Windows.

> *WSL terbaru saat ini sudah versi WSL2, untuk mengetahui perbedaan performance WSL dengan WSL2 silakan baca* [WSL vs WSL2 Performance](https://howto.lintel.in/wsl-vs-wsl-2-performance/) 

Sesuai penjelasan di atas, kali ini kita akan mencoba install salah satu distro Linux, yaitu Ubuntu.

##### Install WSL
Buka Windows PowerShell (Run as Administrator), lalu masukkan perintah

```PowerShell
wsl --install
```
Restart komputer untuk menyelesaikan proses instalasinya.

##### Install Ubuntu
Ketik perintah install di Windows Powershell,
```PowerShell
wsl --install -d Ubuntu
```
Setelah instalasi selesai, tentukan username dan password yang akan digunakan.

Lakukan update untuk memperbarui sistem pada ubuntu dengan perintah **sudo apt update**

Nah, setelah menyelesaikan konfigurasi Ubuntu, kita dapati bahwa Ubuntu yang kita jalankan ini berupa command-line interface (CLI) dengan tampilan yang tidak begitu bagus. Silakan download Windows Terminal di Microsoft Store untuk costumize interface yang lebih modern dan powerful.

