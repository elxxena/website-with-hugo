---
title: Cara Membuat WhatsApp Bot
description: Cara Mudah Membuat Bot WA
slug: Cara-Membuat-WhatsApp-Bot
date: 2022-11-11 00:00:00+0000
image: "https://i.ibb.co/C68VJDZ/Hero-Banner.jpg"
categories:
    - IoT
tags:
    - WhatsApp Bot
---

# Cara Membuat Bot WhatsApp (Step by Step)

Diera jaman sekarang kita sudah tidak asing lagi dengan yang namanya _Artificial intelligence_ (AI) atau Kecerdasan Buatan. Ada banyak sekali kelebihan yang dapat dilakukan oleh AI, diantaranya adalah membuat pekerjaan kita semakin efisien, hemat waktu, dan lain sebagainya. WhatsApp Bot merupakan salah satu contoh kecerdasan buatan, yang dimana kita dapat merespon pesan secara cepat _(Real-Time)_ tanpa kita harus mengetik.

Kali ini saya akan share bagaimana cara membuat bot whatsapp menggunakan website berbasis _cloud_ yaitu **Heroku**.

### Apa itu Heroku ?

![Heroku Images!](https://i.postimg.cc/pd2GdL7K/heroku.png "Heroku")

Dikutip dari [Wikipedia](https://en.wikipedia.org/wiki/Heroku), **Heroku** adalah platform cloud sebagai layanan yang mendukung beberapa bahasa pemrograman. Salah satu platform cloud pertama, Heroku telah dikembangkan sejak Juni 2007, ketika hanya mendukung bahasa pemrograman Ruby, tetapi sekarang mendukung `Java, Node.js, Scala, Clojure, Python, PHP, dan Go.`

Oleh karena itu kita akan menggunakan Heroku sebagai tempat hosting bot kita nanti. Oke mari kita mulai....

## Download _Source Code_

Langkah awal yang harus kita lakukan adalah mendownload terlebih dulu asset atau _Source Code_ bot WhatsApp, kalian bisa cari di Github atau juga bisa download melalui link yang sudah saya sediakan <a href="https://github.com/4ndrexyz/KatoBot-v1" target="_blank">Download WhatsApp Bot</a> 

## Github

Setelah file tadi terdownload, langkah selanjutnya adalah login ke akun [Github](https://github.com) kalian lalu upload file tadi ke _Repository_ kalian.

![Github Repository Preview!](https://i.postimg.cc/PqgzHbPx/repository.png "Github Repository Preview")

Jika file tadi sudah terupload ke _Repsitory_ Github kalian, langkah selanjutnya adalah mengganti nama _Repository_ sesuai dengan keinginan kalian, untuk mengganti nama _Repository_ kalian tinggal pergi ke `Settings > General > Repository Name` lalu klik "Rename"

![Rename Git!](https://i.postimg.cc/MG1cFscC/rename.jpg "Rename Repository")

## Heroku & Heroku CLI

Pertama-tama kunjungi website resmi Heroku terlebih dahulu yaitu [https://www.heroku.com/](https://www.heroku.com/) lalu masuk menggunakan email aktif kalian.

![Heroku!](https://i.postimg.cc/yNxRnDb1/login-heroku.png "Heroku Web Preview")

Setelah kita berhasil masuk, kita akan diarahkan ke laman Dashboard Heroku, dan klik tombol **Create New App**, untuk membuat Aplikasi baru.

![Create New App!](https://i.postimg.cc/bNVFZrFC/create-app.jpg "Create New App")

Setelah itu kita akan disuruh untuk memasukkan **_Name_, _Region_, dan _Pipeline_**, disini kita hanya mengisikan Nama Aplikasinya saja, sebagai contoh saya menggunakan nama **"andrexyz-bot"**

![Nama Aplikasi!](https://i.postimg.cc/Gh4xSQqK/name-app.jpg "Nama Aplikasi Heroku")

> Note:
> Pastikan nama Aplikasi sesuai dengan nama Repository kalian. 
> Untuk nama aplikasi hanya boleh berisikan _lower-case_ saja (huruf kecil)

Setelah itu klik "Create App", maka akan tampil konfigurasi aplikasi kalian.