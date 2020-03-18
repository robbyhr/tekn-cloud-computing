1. APA PERBEDAAN ANTARA IAAS, SAAS DAN PAAS ?

Software as a Service (SaaS)
	layanan Cloud pada jenis ini disediakan dalam bentuk perangkat lunak. Contoh dari SaaS adalah 
	Google Apps (Docs, Spreadsheet, dll), Office 365, dan Adobe Creative Cloud.
	Pada Layanan SaaS pengguna layanan hanya perlu menggunakan aplikasi tersebut tanpa harus mengerti dan mengurus bagaimana data 
	disimpan atau bagaimana aplikasi tersebut di maintenance, karena hal tersebut merupakan service yang disediakan penyedia layanan.

	Keuntungan:
	Pengguna dapat langsung memanfaatkan layanan secara gratis atau dengan bayar biaya sewa tanpa harus mengeluarkan investasi untuk 
	membuat sendiri (in-house development) atau membeli lisensi yang relatif mahal.
	Ketersediaan dan reliabilitas aplikasi terjamin oleh penyedia layanan. Pengguna hanya perlu fokus pada data miliknya. Perangkat
	yang dibutuhkan oleh pengguna juga hanya komputer dan internet.


Platform as a Service (PaaS)
	layanan Cloud pada jenis ini disediakan dalam bentuk platform yang dapat dimanfaatkan pengguna untuk membuat aplikasi diatasnya. 
	Contoh PaaS adalah Amazon Web Service, Microsoft Azure, Facebook, dll. Hal-hal yang dapat dilakukan pengguna layanan PaaS adalah 
	membangun aplikasi, upload aplikasi, testing, dan mengatur konfigurasi.

	Keuntungan:
	Pengguna dapat membuat aplikasi sendiri dengan banyak fitur yang sudah tersedia seperti keamanan platform, OS, sistem database, 
	web server, dan framework aplikasi. Pengguna dapat lebih fokus pada pengembangan aplikasi.
	Fitur utama dari PaaS biasanya adalah skalabilitas yang tinggi. Ketika aplikasi yang kita upload mulai digunakan oleh banyak user 
	maka secara otomatis layanan PaaS akan menskalakan aplikasi kita menjadi lebih baik dalam melayani pengguna aplikasi kita. 
	Sedangkan ketika aplikasi kembali sepi, maka akan diskalakan ulang sehingga biaya yang dibayarkan benar-benar sesuai dengan yang 
	kita gunakan saat itu.


Infrastructure as a Service (IaaS)
	layanan Cloud jenis IaaS pada dasarnya adalah fisik kotak server dan komputer virtual. 
	IaaS menyediakan perusahaan dengan sumber daya komputasi meliputi server, jaringan, storage dan ruang data center.

	Keuntungan:
	Pengguna tidak perlu membeli komputer dan peralatannya secara fisik, melakukan pemeliharaan rutin, dan 
	melakukan konfigurasi perangkat.

2. ARSITEKTUR SOFTWARE AS A SERVICE

	Model SaaS meliputi konsep-konsep dalam arsitektur aplikasi terdistribusi tetapi lebih lanjut memperluas 
	arsitektur untuk menyertakan komponen untuk memfasilitasi dan meningkatkan  model bisnis. Sebuah vendor perangkat  
	lunak tradisional terutama berkaitan dengan kemampuan aplikasi dan pelanggan mereka  yang  bertanggung jawab  
	untuk mengoperasikan dan mengelola lingkungan  yang  bersangkutan  di  mana mereka menjalankan perangkat lunak. 
	Sebuah  vendor SaaS, di sisi lain, adalah sama-sama memperhatikan pengoperasian dan pengelolaan lingkungan yang mendukung 
	seluruh pelanggan mereka.

3. SAAS (Software as a Service) PLATFORM ITECTURE

	SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia 
	cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang 
	disampaikan melalui internet seperti:

	1. Infrastruktur sebagai Layanan
	2. Platform sebagai Layanan
	3. Pembelajaran Mesin sebagai Layanan dan banyak lagi!

4. HOW TO BUILD A CLOUD-BASED SAAS APPLICATION
	a. pilih bahasa pemrograman (disarankan python), database dan software tools
	b. build cloud dengan bahasa pemrograman
	c. buat dokumen orientasi database (disarankan mongoDB)
	d. Membangun aplikasi web yang skalabel, Anda mungkin akan berakhir menggunakan Amazon Web Services, cepat atau lambat
	e. Semakin banyak pengguna yang bergabung dengan produk Anda akan membuat Anda dengan mudah bertanya-tanya tentang penyimpanan 
	web Anda. Dengan layanan penyimpanan Amazon, kami memiliki penyimpanan objek yang hebat, dan sangat skalabel terpasang.
	f. Jaringan pengiriman konten (CDN) pada dasarnya adalah sistem server terdistribusi yang memungkinkan Anda untuk menyajikan konten 		kepada pengguna aplikasi Anda dengan kinerja tinggi dan ketersediaan tinggi.
	g. Dengan Python, MongoDB - sebagai basis data yang berorientasi pada dokumen, perangkat lunak RabbitMQ sebaiknya dilakukan dengan 	pengaturan dasar. Namun, ada banyak cara untuk dipikirkan. Dalam posting tindak lanjut kami, kami akan membahas kebutuhan perangkat 	lunak pemantauan dan analitik yang tepat serta bagaimana prosedur pembayaran dapat berjalan dengan lancar di cloud.
	h. Mulailah dengan pengujian perangkat lunak sekarang !

	