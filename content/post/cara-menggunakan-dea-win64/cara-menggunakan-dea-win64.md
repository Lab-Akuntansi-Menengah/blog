---
title: "Cara Menggunakan Software Dac Easy Accounting (DEA) di Windows 64 bit"
date: 2021-01-05T20:34:08+07:00
draft: false
images: ['/images/dea-logo.png']
categories: []
tags: [tutorial]
authors: [kizbudin]
---
DEA adalah singkatan dari DacEasy Accounting, DEA merupakan program akuntansi portable atau tanpa perlu di install di komputer yang digunakan untuk menghitung General Ledger, Accounts Payable, Accounts Receivable, Inventory, Purchasing, Billing, Cash, Recurring, Fixed Assets, Reporting. <!--more-->

Sebelum menggunakan Software dea ini yang akan dipandu oleh kakak-kakak asisten dari [Lab. Akuntansi Menengah UG](https://www.instagram.com/labamen_ug/) kami akan menjelaskan bagaimana DEA di Windows berarsitektur 64 bit

>Sebelum memulai pastikan sudah mendowload DEA [Disini](https://drive.google.com/file/u/4/d/1v7D9VXOdAvg-wFTdew6uilMW2ZbNRzo6/view)

Setelah mendownload lakukan langkah-langkah berikut :

1.Pada file yang sudah di download klik kanan lalu extract to dea
![klik kanan](/images/dea/01.gif)

2.Berikutnya, Copy folder dea4 ke drive c
![copy](/images/dea/02.gif)

3.Setelah itu, buka dosbox lalu masukan perintah sebagai berikut :
```bash
mount c c:\dea4
c:
dea4
```
![dosbox](/images/dea/03.gif)

DEA akan segera terbuka.


### Cara membuat tampilan dosbox menjadi lebih besar
Jika sudah berhasil menjalankan DEA didalam dosbox tapi dirasa tampilanya kecil dan kurang puas ingin menjalankan dosbox di resolusi yang lebih tinggi lagi, maka bisa menggunakan cara sebagai berikut : 

1.klik logo windows atau klik start lalu tulis dosbox pada search bar, klik kanan lalu klik open file location, klik open file location kembali pada shortcut dosbox
![search](/images/dea/04.gif)

2.klik 2 kali pada doxbox option, lalu ubah file yang sudah ada dengan value berikut :
```bash
windowresolution=1200x600
output=ddraw
```
![ganti resolusi](/images/dea/05-baru.gif)

>anda bisa menyesuikan windowresolutin dosbox jika dirasa terlalu besar atau terlalu kecil dengan mengubah value dengan pilihan sebagai berikut 640×480, 800×600, 960×720, 1024×768, 1280×960, 1400×1050, 1440×1080 , 1600×1200, 1856×1392, 1920×1440. 

jika sudah selesai save file yang sudah diubah dengan cara klik file > save atau bisa dengan menggunakan shortcut keyboard ctrs+s lalu exit 

3.Setelah selesai merubah value dari window resolution dan outputnya, jalankan kembali Dosbox dan akan menampilkan jendela baru dengan resolusi yang lebih besar