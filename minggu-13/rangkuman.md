# RANGKUMAN KUBERNETES

## Apa itu Kubernetes ?
>Kubernetes merupakan platform open-source yang digunakan untuk melakukan manajemen workloads aplikasi yang dikontainerisasi, serta menyediakan konfigurasi dan otomatisasi secara deklaratif. Kubernetes berada di dalam ekosistem yang besar dan berkembang cepat. Service, support, dan perkakas Kubernetes tersedia secara meluas.

>Google membuka Kubernetes sebagai proyek open source pada tahun 2014. Kubernetes dibangun berdasarkan pengalaman Google selama satu setengah dekade dalam menjalankan workloads bersamaan dengan kontribusi berupa ide-ide terbaik yang diberikan oleh komunitas.

## Mengapa Kubernetes dan hal apa saja yang dapat dilakukan oleh Kubernetes?
>Kubernetes memiliki sejumlah fitur yang dapat dijabarkan sebagai berikut:
1. platform kontainer
2. platform microservices
3. platform cloud yang tidak mudah dipindahkan

>Kubernetes menyediakan manajemen environment yang berpusat pada kontainer. Kubernetes melakukan orkestrasi terhadap computing, networking, dan inftrastruktur penyimpanan. Fitur inilah yang kemudian membuat konsep Platform as a Service (PaaS) menjadi lebih sederhana dilengkapi dengan fleksibilitas yang dimiliki oleh Infrastructure as a Service (IaaS).

## Lalu apa yang menyebabkan Kubernetes disebut sebagai sebuah platform?
>Meskipun Kubernetes menyediakan banyak fungsionalitas, selalu ada keadaan dimana hal tersebut membutuhkan fitur baru. Workflow spesifik yang terkait dengan proses pengembangan aplikasi dapat ditambahkan pada streamline untuk meningkatkan produktivitas developer. Orkestrasi ad-hoc yang dapat diterima biasanya membutuhkan desain otomatisasi yang kokoh agar bersifat scalable. Hal inilah yang membuat Kubernetes juga didesain sebagai platform untuk membangun ekosistem komponen dan dan perkakas untuk memudahkan proses deployment, scale, dan juga manajemen aplikasi.

## Lalu hal apakah yang tidak termasuk di dalam Kubernetes?
>Kubernetes bukanlah sebuah PaaS (Platform as a Service) yang biasanya. Meskipun Kubernetes dijalankan pada tingkatan kontainer dan bukan pada tingkatan perangkat keras, Kubernetes menyediakan beberapa fitur yang biasanya disediakan oleh Paas, seperti deployment, scaling, load balancing, logging, dan monitoring. Akan tetapi, Kubernetes bukanlah sistem monolitik, melainkan suatu sistem yang bersifat sebagai bulding block dan pluggable yang dapat digunakan untuk membangun sebuah platform yang dibutuhkan oleh developer dengan tetap mengutamakan konsep fleksibilitas.

Termasuk Kubernetes:

1. Tidak melakukan limitasi terhadap aplikasi yang di-support. Kubernetes bertujuan untuk mendukung berbagai variasi workloads, termasuk stateless, stateful, dan data-processing. Jika sebuah aplikasi dapat dijalankan di atas kontainer, maka aplikasi tersebut juga dapat dijalankan di atas Kubernetes.

2. Tidak menyediakan mekanisme untuk melakukan deploy kode sumber maupun mekanisme build sebuah aplikasi. Continuous Integration, Delivery, and Deployment (CI/CD) workflows ditentukan oleh preferensi serta kebutuhan teknis organisasi.

3. Tidak menyediakan application-level services, seperti middleware (e.g., message buses), data-processing frameworks (for example, Spark), databases (e.g., mysql), caches, maupun cluster storage systems (e.g., Ceph) sebagai suatu built-in services. Komponen tersebut dapat dijalankan di atas Kubernetes, dan/atau dapat diakses oleh aplikasi yang dijalankan di atas Kubernetes melalui sebuah mekanisme tidak mudah dipindahkan misalnya saja Open Service Broker.

4. Tidak membatasi penyedia layanan logging, monitoring, maupun alerting yang digunakan. Kubernetes menyediakan proof of concept dan mekanisme integrasi yang dapat digunakan untuk mengumpulkan serta mengekspor metriks yang ada.

5. Tidak menyediakan atau mengharuskan penggunaan configuration language/system (e.g., jsonnet). Kubernetes menyediakan suatu API deklaratif yang dapat digunakan oleh berbagai jenis spesifikasi deklaratif.

6. Tidak menyediakan atau mengadaptasi sebuah konfigurasi, maintenance, manajemen, atau self-healing mesin dengan spesifikasi khusus.

Sebagai tambahan, Kubernetes bukanlah sebuah sitem orkestrasi biasa. Bahkan pada kenyataannya, Kubernetes menghilangkan kebutuhan untuk melakukan orkestrasi. Definisi teknis dari orkestrasi merupakan eksekusi dari sebuah workflow yang sudah didefinisikan sebelumnya: pertama kerjakan A, kemudian B, dan terakhir C. Sebaliknya, Kubernetes disusun oleh seperangkat proses kontrol yang dapat idekomposisi yang selalu menjalankan state yang ada saat ini hingga sesuai dengan state yang dinginkan. Kita tidak perlu peduli proses apa saja yang perlu dilakukan untuk melakukan A hingga C. Mekanisme kontrol yang tersentralisasi juga tidak dibutuhkan. Dengan demikian, sistem yang dihasilkan lebih mudah digunakan lebih kokoh, serta lebih extensible.