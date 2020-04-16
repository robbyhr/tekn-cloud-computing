# LATIHAN & TUGAS

## RUN SIMPLE DOCKER CONTAINER
### Langkah 1
>Clone Image dari github
![img](1.PNG)

### Langkah 2
>Menjalankan docker container<br>
![img](2.PNG)

### Langkah 3
>Tampilan run container
![img](3.PNG)

### Langkah 4
>menjalankan container berdasarkan versi Linux yang berbeda dari yang dijalankan pada host Docker
![img](4.PNG)
>Melihat versi host VM (Linux Ubuntu 18.0)

### Langkah 5
>Jalankan container MySQL baru
![img](5.PNG)

### Langkah 6
>Daftar running containers
![img](6.PNG)

### Langkah 7
>memeriksa apa yang terjadi di Container dengan menggunakan beberapa perintah Docker bawaan
![img](7.PNG)

### Langkah 8
>melihat daemon MySQL (mysqld) berjalan di container
![img](8.PNG)

### Langkah 9
>Daftar versi MySQL menggunakan docker kontainer exec. kita dapat melihat versi linux pada gambar
![img](9.PNG)

### Langkah 10
>Dapat juga menggunakan perintah ini (yg diatas lebih simple)
![img](10.PNG)
<br>
<br>

##  PACKAGE DAN MENJALANKAN CUSTOM APP DARI DOCKER
### Langkah 11
>
![img](11.PNG)

### Langkah 12
>
![img](12.PNG)

### Langkah 13
>
![img](13.PNG)

### Langkah 14
>
![img](14.PNG)

### Langkah 15
>Hasil dari container yang telah di jalankan 
![img](15.PNG)

### Langkah 16
>Mematikan dan menghapus container yg berjalan
![img](16.PNG)
<br>
<br>

## MODIFIKASI WEBSITE YANG BERJALAN
### Langkah 17
>Menjalankan container dengan menambah perintah -mount
![img](17.PNG)

### Langkah 18
>Meng-copy index.html baru dengan yang lama
![img](18.PNG)

### Langkah 19
>Matikan container, jalankan, dan matikan kembali container
![img](19.PNG)

### Langkah 20
>Membuild image baru dengan versi 2.0 dari linux_tweet_app
![img](20.PNG)

### Langkah 21
>Melihat image yang ada dalam sistem telah tertambah
![img](21.PNG)

### Langkah 22
>jalankan image container linux tweet 2.0
![img](22.PNG)

### Langkah 23
>Hasil run dari container linux tweet 2.0 (beda warna dengan versi 1)
![img](23.PNG)

### Langkah 24
>Jalankan container linux tweet 1.0 bersamaan dengan 2.0 tapi dengan mengganti nama old_linux_tweet dan mengganti port dengan 8080, karena port 80 sudah di gunakan oleh versi 2.0 dan tidak dapat menggunakan 2 container dalam 1 port <br>
![img](24.PNG)

### Langkah 25
>Saat keduanya dijalankan<br>
![gif](25.gif)
<br>
<br>

## PUSH IMAGE KE DOCKER HUB/DOCKER REPOSITORY
### Langkah 26
>ist dari docker host kita berdasarkan nama dockerid
![img](26.PNG)

### Langkah 27
>login docker
![img](27.PNG)

### Langkah 28
>push image linux_tweet versi 1.0
![img](28.PNG)

### Langkah 29
>push image linux_tweet versi 2.0
![img](29.PNG)

### Langkah 30
>Buka Repositori dockerhub, dan cek app linux_tweet_app akan ada 2 versi tags yang telah di push
![img](30.PNG)

# SELESAI
