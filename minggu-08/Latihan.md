# LATIHAN

## Langkah 1
>buat folder dengan nama "compotest"
![img](/latihan1.PNG)

## Langkah 2
>buat file dengan nama "app.py" beserta isi
![img](/latihan2.PNG)

## Langkah 3
>buat file dengan nama "requirement.txt" beserta isi
![img](/latihan3.PNG)

## Langkah 4
>buat file dengan nama "Dockerfile" beserta isi
![img](/latihan4.PNG)

## Langkah 5
>buat file dengan nama "docker-compose.yml" beserta isi
![img](/latihan5.PNG)

## Langkah 6
>ketik "$docker-compose up" dan tunggu hingga selesai
![img](/latihan6.PNG)
![img](/latihan6.1.PNG)

## Langkah 7
>ketik "http://localhost:5000/" dibrowser dan lihat hasil
![img](/latihan7.PNG)
>lakukan refresh
![img](/latihan7.1.PNG)

## Langkah 8
>ketik "docker image ls" untuk melihat image yang dibuat dari docker compose
![img](/latihan8.PNG)

## Langkah 9
>edit file docker-compose.yml seperti dibawah 
![img](/latihan9.PNG)
>setelah itu ketik "$docker-compose down" untuk stop image yang berjalan dan ketikan "$docker-compose up"
![img](/latihan9.1.PNG)

## Langkah 10
>ubah isi app.py dengan output hello world menjadi sesuai keinginan "di modul menjadi from docker"
![img](/latihan10.PNG)

## Langkah 11
>ketikan "$docker-compose up -d" untuk menjalankan service di background dan ketik "$docker-compose ps" untuk melihat service compose yang sedang berjalan
![img](/latihan11.PNG)

## Langkah 12
>ketikan "$docker-compose run web env"
![img](/latihan12.PNG)

## Langkah 12
>ketikan "$docker-compose stop" untuk stop image service yg berjalan
![img](/latihan13.PNG)

## Langkah 13
>ketikan "$docker-compose down --volumes" untuk menghapus data volume yg digunakan dari container
![img](/latihan14.PNG)