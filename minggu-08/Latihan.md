# LATIHAN

## Langkah 1
>buat folder dengan nama "compotest"
![img](/minggu-08/latihan1.PNG)

## Langkah 2
>buat file dengan nama "app.py" beserta isi
![img](/minggu-08/latihan2.PNG)

## Langkah 3
>buat file dengan nama "requirement.txt" beserta isi
![img](/minggu-08/latihan3.PNG)

## Langkah 4
>buat file dengan nama "Dockerfile" beserta isi
![img](/minggu-08/latihan4.PNG)

## Langkah 5
>buat file dengan nama "docker-compose.yml" beserta isi
![img](/minggu-08/latihan5.PNG)

## Langkah 6
>ketik "$docker-compose up" dan tunggu hingga selesai
![img](/minggu-08/latihan6.PNG)
![img](/minggu-08/latihan6.1.PNG)

## Langkah 7
>ketik "http://localhost:5000/" dibrowser dan lihat hasil
![img](/minggu-08/latihan7.PNG)
>lakukan refresh
![img](/minggu-08/latihan7.1.PNG)

## Langkah 8
>ketik "docker image ls" untuk melihat image yang dibuat dari docker compose
![img](/minggu-08/latihan8.PNG)

## Langkah 9
>edit file docker-compose.yml seperti dibawah 
![img](/minggu-08/latihan9.PNG)
>setelah itu ketik "$docker-compose down" untuk stop image yang berjalan dan ketikan "$docker-compose up"
![img](/minggu-08/latihan9.1.PNG)

## Langkah 10
>ubah isi app.py dengan output hello world menjadi sesuai keinginan "di modul menjadi from docker"
![img](/minggu-08/latihan10.PNG)

## Langkah 11
>ketikan "$docker-compose up -d" untuk menjalankan service di background dan ketik "$docker-compose ps" untuk melihat service compose yang sedang berjalan
![img](/minggu-08/latihan11.PNG)

## Langkah 12
>ketikan "$docker-compose run web env"
![img](/minggu-08/latihan12.PNG)

## Langkah 12
>ketikan "$docker-compose stop" untuk stop image service yg berjalan
![img](/minggu-08/latihan13.PNG)

## Langkah 13
>ketikan "$docker-compose down --volumes" untuk menghapus data volume yg digunakan dari container
![img](/minggu-08/latihan14.PNG)
