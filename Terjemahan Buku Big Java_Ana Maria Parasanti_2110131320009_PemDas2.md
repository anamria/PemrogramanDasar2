**Ana Maria Parasanti - 2110131320009**

---
# BAB 1

## PENGENALAN

### TUJUAN BAB 

  Untuk belajar tentang komputer dan pemrograman

  Untuk mengkompilasi dan menjalankan program Java pertama Anda

  Untuk mengenali kesalahan waktu kompilasi dan run-time

  Untuk menggambarkan suatu algoritma dengan pseudocode

### ISI BAB

1.1 PROGRAM KOMPUTER 2

1.2 ANATOMI KOMPUTER 3

1.3 PEMROGRAMAN BAHASA JAVA 6

1.4 MENJADI MAKSIMAL DENGAN LINGKUNGAN PEMROGRAMAN ANDA 7

1.5 MENGANALISIS PROGRAM PERTAMA ANDA 11

1.6 ERRORS 14

1.7 PENYELESAIAN MASALAH: DESAIN ALGORITMA 15

---

Sama seperti Anda mengumpulkan alat, mempelajari proyek, dan membuat rencana untuk mengatasinya, dalam bab ini Anda akan mengumpulkan dasar-dasar Anda perlu mulai belajar memprogram. Setelah perkenalan singkat perangkat keras komputer, perangkat lunak, dan pemrograman dalam
umum, Anda akan belajar cara menulis dan menjalankan yang pertama program Java. Anda juga akan belajar cara mendiagnosis dan memperbaiki kesalahan pemrograman, dan cara menggunakan kodesemu untuk menggambarkan suatu algoritme—deskripsi langkah demi langkah tentang bagaimana
untuk memecahkan masalah—saat Anda merencanakan program komputer Anda.

### 1.1 PROGRAM KOMPUTER

Anda mungkin pernah menggunakan komputer untuk bekerja atau bersenang-senang. Banyak orang menggunakan komputer untuk tugas sehari-hari seperti perbankan elektronik atau menulis makalah. Komputer adalah baik untuk tugas-tugas seperti itu. Mereka dapat menangani tugas berulang, seperti menjumlahkan angka atau menempatkan kata-kata di halaman, tanpa merasa bosan atau lelah.

Fleksibilitas komputer adalah fenomena yang cukup menakjubkan. Mesin yang sama dapat menyeimbangkan buku cek Anda, meletakkan kertas istilah Anda, dan bermain game. Sebaliknya, mesin lain melakukan berbagai tugas yang jauh lebih sempit; mobil yang dikendarai dan pemanggang roti bersulang. Komputer dapat melakukan berbagai tugas karena mereka menjalankan tugas yang berbeda program, yang masing-masing mengarahkan komputer untuk bekerja pada tugas tertentu.

Komputer itu sendiri adalah mesin yang menyimpan data (angka, kata-kata, gambar), berinteraksi dengan perangkat (monitor, sistem suara, printer), dan menjalankan program. Sebuah program komputer memberi tahu komputer, secara rinci, urutan langkah-langkah yang diperlukan untuk memenuhi tugas. Komputer fisik dan perangkat periferal secara kolektif disebut perangkat keras. Program yang dijalankan komputer disebut barang lunak.

Program komputer saat ini sangat canggih sehingga sulit dipercaya bahwa mereka terdiri dari instruksi yang sangat primitif. Instruksi tipikal mungkin satu dari berikut ini:

+	Letakkan titik merah pada posisi layar tertentu.

+	Tambahkan dua angka.

+	Jika nilai ini negatif, lanjutkan program pada instruksi tertentu.

Pengguna komputer memiliki ilusi interaksi yang lancar karena sebuah program berisi sejumlah besar instruksi semacam itu, dan karena komputer dapat mengeksekusinya di kecepatan luar biasa.

Tindakan merancang dan mengimplementasikan program komputer disebut pemrograman. Dalam buku ini, Anda akan belajar cara memprogram komputer yaitu cara mengarahkan komputer untuk menjalankan tugas.

Untuk menulis game komputer dengan efek gerakan dan suara atau pengolah kata yang mendukung font dan gambar mewah adalah tugas kompleks yang membutuhkan tim yang terdiri dari banyak orang programmer yang sangat terampil. Upaya pemrograman pertama Anda akan lebih biasa.Konsep dan keterampilan yang Anda pelajari dalam buku ini membentuk fondasi penting, dan Anda tidak boleh kecewa jika program pertama Anda tidak menyaingi sophis ticated perangkat lunak yang akrab bagi Anda. Sebenarnya, Anda akan menemukan bahwa ada sensasi yang luar biasa bahkan dalam tugas pemrograman sederhana. Ini adalah pengalaman yang luar biasa untuk melihat komputerdengan tepat dan cepat melaksanakan tugas yang akan memakan waktu berjam-jam kerja keras, untuk membuat perubahan kecil dalam program yang mengarah pada perbaikan segera, dan untuk melihat komputer menjadi perpanjangan dari kekuatan mental Anda.

    1. Apa yang diperlukan untuk memutar musik di komputer?

    2. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?

    3. Apa yang perlu diketahui pengguna komputer tentang pemrograman agar dapat bermain video game?

---

### 1.2	Anatomi Komputer

Untuk memahami proses pemrograman, Anda harus memiliki pemahaman dasar dari blok bangunan yang membentuk komputer. Kami akan melihat secara pribadi komputer. Komputer yang lebih besar memiliki komponen yang lebih cepat, lebih besar, atau lebih kuat, tetapimereka pada dasarnya memiliki desain yang sama.

Di jantung komputer terletak pusatnya unit pemrosesan (CPU) (lihat Gambar 1). Bagian dalam pengkabelan CPU sangat rumit.Misalnya, prosesor Intel Core (yang populerCPU untuk per komputer pribadi pada saat initulisan) terdiri dari beberapa ratus juta elemen struktural, yang disebut transistor.CPU melakukan kontrol program dan data pengolahan. Artinya, CPU menempatkan dan mengeksekusi instruksi program; itu melaksanakan operasi aritmatika seperti penjumlahan, pengurangan,perkalian, dan pembagian; itu mengambil datadari memori eksternal atau perangkat dan tempatdata yang diproses ke dalam penyimpanan.

<p align="center">
<img width="145" src="https://user-images.githubusercontent.com/112605121/190378117-75e8603c-669b-4cdd-855d-e5463b94ee14.PNG">
</p>

<p align="center">
  <b>Gambar 1</b> Central Processing Unit</p>

Ada dua macam penyimpanan. Penyimpanan utama,atau memori, dibuat dari sirkuit elektronik yang dapat menyimpan data, asalkan:disuplai dengan tenaga listrik. Penyimpanan sekunder, biasanya hard disk (lihat Gambar 2)atau solid-state drive, menyediakan penyimpanan yang lebih lambat dan lebih murah yang bertahan tanpa listrik. Sebuah hard disk terdiri dari piringan berputar, yang dilapisi dengan magnetnbahan. Solid-state drive menggunakan komponen elektronik yang dapat menyimpan informasitanpa daya, dan tanpa bagian yang bergerak.Untuk berinteraksi dengan pengguna manusia, komputer membutuhkan perangkat periferal. Komputer mentransmisikan informasi (disebut output) kepada pengguna melalui layar tampilan, speaker, dan printer. Pengguna dapat memasukkan informasi (disebut input) untuk komputerdengan menggunakan keyboard atau alat penunjuk seperti mouse.

<p align="center">
<img width="221" alt="BJ2" src="https://user-images.githubusercontent.com/112605121/190378250-01eded44-d189-4dac-81f5-f59a879f92b7.PNG"></p>

<p align="center">
  <b>Gambar 2</b> A Hard Disk</p>

Beberapa komputer adalah unit mandiri, sedangkan yang lain saling berhubungan melalui jaringan. Melalui kabel jaringan, komputer dapat membaca data dan program dari lokasi penyimpanan pusat atau mengirim data ke komputer lain. Untuk penggunadari komputer jaringan, bahkan mungkin tidak jelas data mana yang berada di komputeritu sendiri dan yang ditransmisikan melalui jaringan.

Gambar 3 memberikan gambaran skematis arsitektur komputer pribadi. Instruksi dan data program (seperti teks, angka, audio, atau video) berada di sekunder penyimpanan atau di tempat lain di jaringan. Ketika sebuah program dimulai, instruksinyadibawa ke memori, di mana CPU dapat membacanya. CPU membaca dan mengeksekusi satu instruksi pada suatu waktu. Seperti yang diarahkan oleh instruksi ini, CPU membacadata, memodifikasinya, dan menulisnya kembali ke memori atau penyimpanan sekunder. Beberapa programinstruksi akan menyebabkan CPU menempatkan titik-titik pada layar tampilan atau printer atau kegetaran speakernya. Karena tindakan ini terjadi berkali-kali dan dengan kecepatan tinggi,pengguna manusia akan melihat gambar dan suara. Beberapa instruksi program membaca penggunamasukan dari keyboard, mouse, sensor sentuh, atau mikrofon. Analisis program sifat input ini dan kemudian mengeksekusi instruksi yang sesuai berikutnya.

<p align="center">
<img width="359" alt="BJ3" src="https://user-images.githubusercontent.com/112605121/190378661-a9edf983-4901-4870-a762-c5351b524d1c.PNG"></p>

<p align="center">
  <b>Gambar 3</b> Skema Desain Personal Computer</p>

    4. Di mana program disimpan saat sedang tidak berjalan?

    5. Bagian komputer mana yang melakukan operasi aritmatika, seperti penjumlahan, dan perkalian?

    6. Smartphone modern adalah komputer, sebanding dengan komputer desktop. Komponen smartphone mana yang sesuai dengan yang ditunjukkan pada Gambar 3?

#### Komputasi & Masyarakat

Ketika komputer pertama kali ditemukan pada tahun 1940-an, komputer memenuhi seluruh ruangan.  Foto di bawah menunjukkan ENIAC (integrator numerik elektronik dan komputer), selesai pada tahun 1946 di University of Pennsylvania.  ENIAC digunakan oleh militer untuk menghitung lintasan proyektil.  Saat ini, fasilitas komputasi mesin pencari, toko internet, dan jejaring sosial memenuhi gedung-gedung besar yang disebut pusat data.  Di ujung lain spektrum, komputer ada di sekitar kita.  Ponsel Anda memiliki komputer di dalamnya, seperti halnya banyak kartu kredit dan kartu tarif untuk angkutan umum.  Sebuah mobil modern memiliki beberapa komputer––untuk mengontrol mesin, rem, lampu, dan radio.  

Munculnya komputasi di mana-mana berubah banyak aspek dari kami hidup.  Pabrik digunakan mempekerjakan orang untuk lakukan perakitan berulang tugas-tugas yang hari ini dilakukan oleh komputer- robot yang dikendalikan, operasi dimakan oleh segelintir orang siapa yang tahu caranya bekerja dengan komputer.  Buku, musik, dan film saat ini sering dikonsumsi di komputer, dan komputer hampir selalu terlibat dalam produksi mereka.  Buku yang sedang Anda baca sekarang tidak mungkin ditulis tanpa komputer.

<p align="center">
<img width="184" src="https://user-images.githubusercontent.com/112605121/190378764-ce9a1e96-7f6d-49e0-8127-d181ecfb2ee7.PNG"></p>

<p align="center">
Kartu transit ini berisi komputer.</p>

Mengetahui tentang komputer dan cara memprogramnya telah menjadi keterampilan penting dalam banyak karier.  Insinyur merancang mobil yang dikendalikan komputer dan peralatan medis yang menyelamatkan nyawa.  Ilmuwan komputer mengembangkan program yang membantu orang berkumpul untuk mendukung tujuan sosial.  Misalnya, para aktivis menggunakan jejaring sosial untuk berbagi video yang menunjukkan pelecehan oleh rezim yang represif, dan informasi ini berperan penting dalam mengubah opini publik. 

<p align="center">
<img width="273" src="https://user-images.githubusercontent.com/112605121/190378839-2657f6ab-859b-4bcc-b17a-4396935a490c.PNG"></p>

<p align="center">
ENIAC</p>

Ketika komputer, besar dan kecil, menjadi semakin tertanam dalam kehidupan kita sehari-hari, semakin penting bagi setiap orang untuk memahami cara kerjanya, dan cara bekerja dengannya.  Saat Anda menggunakan buku ini untuk mempelajari cara memprogram komputer, Anda akan mengembangkan pemahaman yang baik tentang dasar-dasar komputasi yang akan membuat Anda menjadi warga negara yang lebih berpengetahuan dan, mungkin, seorang profesional komputasi.

---

### 1.3 Bahasa Pemrograman Java

Untuk menulis program komputer, Anda perlu memberikan urutan instruksi yang dapat dieksekusi oleh CPU. Sebuah program komputer terdiri dari sejumlah besar program instruksi CPU sederhana, dan membosankan juga rawan untuk kesalahan untuk menentukannya satu persatu. Karena alasan itu, bahasa pemrograman tingkat tinggi telah dibuat. Dalam bahasa tingkat tinggi, Anda menentukan tindakan yang harus dilakukan programnya. Penyusun menerjemahkan instruksi tingkat tinggi ke dalam instruksi yang lebih rinci (disebut kode mesin) yang dibutuhkan oleh CPU. Banyak bahasa pemrograman yang berbeda telah dirancang untuk tujuan yang berbeda.

Pada tahun 1991, sebuah kelompok yang dipimpin oleh James Gosling dan Patrick Naughton di Sun Microsystems merancang sebuah bahasa pemrograman, berkode nama “Green”, untuk kegunaan di perangkat konsumen, seperti “set-top” televisi cerdas. Bahasanya dirancang untuk sederhana, aman, dan dapat digunakan oleh berbagai tipe prosesor yang berbeda. Tidak ada pelanggan yang pernah ditemukan untuk teknologi ini.

Gosling menceritakan pada tahun 1994 tim menyadari “Kita bisa menulis browser yang sangat keren. Itu adalah salah satu dari sedikit hal dalam arus utama klien/server yang membutuhkan beberapa hal aneh yang telah kami lakukan: arsitektur netral, waktu nyata, andal, aman.” Java diperkenalkan kepada orang banyak yang antusias di pameran SunWorld pada tahun 1995, bersama dengan browser yang menjalankan applet—kode Java yang dapat ditemukan di mana saja di Internet. Gambar di sebelah kanan menunjukkan contoh khas applet.

<p align="center">
<img width="130" src="https://user-images.githubusercontent.com/112605121/190378957-bf9f6283-cd8c-4400-b2f1-8784bd65b11d.PNG"></p>

<p align="center">
Sebuah Applet untuk Memvisualisasikan Molekul</p>

Sejak saat itu, Java telah berkembang dengan kecepatan yang fenomenal. Programmer telah menggunakan bahasa ini karena lebih mudah digunakan daripada saingan terdekatnya, C++. Selain itu, Java memiliki perpustakaan yang kaya yang memungkinkan untuk menulis program portabel yang dapat melewati sistem operasi berpemilik—fitur yang sangat dicari oleh mereka yang ingin menjadi independen dari sistem berpemilik tersebut dan diperjuangkan dengan sengit oleh vendor mereka.

Karena Java dirancang untuk internet, ia mempunyai dua atrbut yang membuatnya sangat cocok untuk pemula: keamanan dan portabilitas.

<p align="center">
<img width="395" src="https://user-images.githubusercontent.com/112605121/190379108-f8782d84-a772-4594-87c1-dbccd83f3620.PNG"></p>

Java dirancang sehingga siapapun dapat menjalankan program di browser mereka tanpa takut. Fitur keamanan bahasa Java memastikan program dihentikan apabila mencoba untuk melakukan sesuatu membahayakan. Memiliki lingkungan yang aman juga membantu bagi siapapun yang mempelajari Java. Disaat Anda melakukan error yang mengakibatkan perilaku membahayakan, program Anda dihentikan dan Anda menerima laporan eror yang akurat.

Manfaat lain dari Java adalah portabilitas. Program Java yang sama akan jalan, tanpa perubahan, pada Windows, UNIX, Linux, atau Macintosh. Untuk mencapai portabilitas, penyusun Java tidak menerjemahkan program-program Java langsung ke dalam instruksi CPU. Melainkan, program Java yang tersusun memuat instruksi untuk mesin virtual Java, sebuah program yang menyimulasikan CPU nyata. Portabilitas adalah manfaat lain untuk murid pemula. Anda tidak harus belajar bagaimana cara menulis program untuk platform yang berbeda.

Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.

Karena Java tidak dirancang khusus untuk siswa, tidak ada pemikiran yang diberikan untuk membuatnya sangat sederhana untuk menulis program dasar. Sejumlah mesin teknis diperlukan untuk menulis bahkan program yang paling sederhana. Hal ini bukan masalah bagi programmer profesional, tetapi bisa menjadi gangguan bagi pelajar pemula. Saat Anda mempelajari caranya untuk memprogram di Java, akan ada saatnya Anda akan diminta untuk puas dengan penjelasan awal dan menunggu detail yang lebih lengkap di bab selanjutnya.

Java telah diperpanjang berkali-kali selama masa pakainya—lihat Table 1. Dalam buku ini, kami menganggap bahwa Anda memiliki Java versi 8 atau yang lebih baru.

Pada akhirnya, Anda tidak dapat berharap untuk mempelajari keseluruhan dari Java dalam satu pembelajaran. Bahasa Java itu sendiri relatif sederhana, tapi Java berisi sekumpulan library packages yang diperlukan untuk menulis program yang berguna. Ada paket untuk grafik, desain antarmuka pengguna, kriptografi, jaringan, suara, penyimpanan basis data, dan banyak kegunaan lainnya. Bahkan programmer Java yang ahli sekalipun tidak dapat berharap untuk mengetahui isi semua paket—mereka hanya menggunakan yang mereka perlukan untuk proyek tertentu.

Dengan  menggunakan buku ini, Anda diharapkan untuk belajar banyak tentang bahasa Java dan tentang paket yang paling penting. Camkan selalu bahwa tujuan utama dari buku ini bukan untuk Anda mengingat detail kecil Java, tapi untuk mengajari Anda cara berpikir tentang pemrograman.

    7. Apa dua manfaat terpenting dari bahasa Java?

    8. Berapa lama waktu yang dibutuhkan untuk mempelajari seluruh perpustakaan Java?

---

### 1.4 Menjadi Familiar dengan Lingkungan Pemrograman Anda

Banyak siswa menemukan bahwa alat yang mereka butuhkan sebagai pemrogram sangat berbeda dari perangkat lunak yang mereka kenal. Anda harus meluangkan waktu untuk membiasakan diri dengan lingkungan pemrograman Anda. Karena sistem komputer sangat bervariasi, buku ini hanya dapat memberikan garis besar langkah-langkah yang perlu Anda ikuti. Merupakan ide bagus untuk Anda berpartisipasi dalam lab praktik, atau meminta teman yang berpengetahuan luas untuk memberi Anda penjelasan.

<p align="center">
<img width="314" src="https://user-images.githubusercontent.com/112605121/190379176-a45c8306-67ce-4a38-a7b1-14a851ba42be.PNG"></p>

<p align="center">
  <b>Gambar 4</b> Menjalankan Program HelloPrinter dalam Lingkungan Pengembangan Terintegrasi</p>

**Langkah 1** Mulai lingkungan pengembangan Java.

Sistem komputer sangat berbeda dalam hal ini. Pada banyak komputer terdapat lingkungan pengembangan terintegrasi di mana Anda dapat menulis dan menguji program Anda. Di komputer Anda pertama kali meluncurkan editor, sebuah program yang berfungsi seperti pengolah kata, di mana Anda dapat memasukkan instruksi Java Anda; Anda kemudian membuka jendela konsol dan ketik perintah untuk menjalankan program Anda. Anda perlu mencari tahu bagaimana memulai dengan lingkungan Anda.

**Langkah 2** Tulis sebuah program yang sederhana.

Pilihan tradisional untuk program pertama dalam bahasa pemrograman baru adalah program yang menampilkan sapaan sederhana: “Halo, Dunia!”. Mari kita ikuti tradisi itu. Inilah "Halo, Dunia!" program di java:
    publicclassHelloPrinter
    {
        publicstaticvoidmain(String[]args)
        {
            System.out.println("Hello,World!");
        }
    }
Kami akan memeriksa program ini di bagian selanjutnya.

Apa pun lingkungan pemrograman yang Anda gunakan, Anda memulai aktivitas Anda dengan mengetikkan pernyataan program ke dalam jendela editor.

Buat file baru dan beri namaHelloPrinter.java, menggunakan langkah-langkah yang sesuai untuk lingkungan Anda. (Jika lingkungan Anda mengharuskan Anda memberikan nama proyek selain nama file, gunakan namahello untuk proyek tersebut.) Masukkan instruksi program persis seperti yang diberikan di atas. Atau, temukan salinan elektronik dalam kode pendamping buku ini dan tempelkan ke editor Anda.

<p align="center">
<img width="230" src="https://user-images.githubusercontent.com/112605121/190379287-62b9e291-088d-4610-893d-371de0970098.PNG"></p>

<p align="center">
  <b>Gambar 5</b> Menjalankan HelloPrinter Program di Jendela Konsol</p>

Saat Anda menulis program ini, perhatikan baik-baik berbagai simbol, dan ingatlah bahwa Java sensitif terhadap huruf besar-kecil. Anda harus memasukkan huruf besar dan kecil persis seperti yang muncul dalam daftar program. Anda tidak dapat mengetikMAIN atauPrintLn. Jika Anda tidak hati-hati, Anda akan mengalami masalah—lihat Kesalahan Umum 1.2.

**Langkah 3** Jalankan programnya.
 
Proses untuk menjalankan program sangat bergantung pada lingkungan pemrograman Anda. Anda mungkin harus mengklik tombol atau memasukkan beberapa perintah. Saat Anda menjalankan program pengujian, pesannya.

    Hello,World!

akan muncul di suatu tempat di layar (lihat Gambar 4 dan Gambar 5).

Untuk menjalankan program Anda, kompiler Java menerjemahkan file sumber Anda (yaitu, pernyataan yang Anda tulis) ke dalam file kelas. (Sebuah file kelas berisi instruksi untuk mesin virtual Java.) Setelah kompilator menerjemahkan kode sumber Anda ke dalam instruksi mesin virtual, mesin virtual akan mengeksekusinya. Selama eksekusi, mesin virtual mengakses pustaka kode yang telah ditulis sebelumnya, termasuk implementasi kelasSystem danPrintStream yang diperlukan untuk menampilkan keluaran program. Gambar 6 merangkum proses membuat dan menjalankan program Java. Di beberapa lingkungan pemrograman, kompilator dan mesin virtual pada dasarnya tidak terlihat oleh pemrogram—mereka dijalankan secara otomatis setiap kali Anda meminta untuk menjalankan program Java. Di lingkungan lain, Anda perlu meluncurkan kompiler dan mesin virtual secara eksplisit.

**Langkah 4** Rapikan pekerjaanmu.

Sebagai seorang programmer, Anda menulis program, mencobanya, dan memperbaikinya. Anda menyimpan program Anda dalam file. File disimpan dalam folder atau direktori. Sebuah folder dapat berisi

<p align="center">
<img width="401" src="https://user-images.githubusercontent.com/112605121/190379353-0ff8ed8d-91f8-4f4f-97e9-244acd42f1d7.PNG"></p>

<p align="center">
  <b>Gambar 6</b> Dari Kode Sumber untuk Menjalankan Program</p>

file serta folder lain, yang dengan sendirinya dapat berisi lebih banyak file dan folder 
(lihat Gambar 7). Hirarki ini bisa sangat besar, dan Anda tidak perlu khawatir dengan semua cabangnya. Namun, Anda harus membuat folder untuk mengatur pekerjaan Anda. Sebaiknya buat folder terpisah untuk pro-tugas mata kuliah tata bahasa. Di dalam folder itu, buat folder terpisah untuk setiap program.Beberapa lingkungan pemrograman menempatkan program Anda ke lokasi default jika Anda tidak menentukan folder sendiri. Dalam hal ini, Anda perlu mencari tahu di mana file-file itu berada.Pastikan Anda memahami di mana file Anda berada dalam hierarki folder. Informasi ini penting ketika Anda mengirimkan file untuk penilaian, danuntukmembuat salinan cadangan (lihat Tip Pemrograman 1.1). 

<p align="center">
<img width="81" src="https://user-images.githubusercontent.com/112605121/190379403-15eba723-7d84-42a6-b31b-88acdd4431ed.PNG"></p>

<p align="center">
  <b>Gambar 7</b>  Hirarki Folder</p>

    9. Di mana file HelloPrinter.java disimpan di komputer Anda?

    10. Apa yang Anda lakukan untuk melindungi diri Anda dari kehilangan data saat Anda mengerjakan proyek pemrograman?

**TipPemrograman 1.1**

Salinan Cadangan

Anda akan menghabiskan banyak waktu untuk membuat dan meningkatkan program Java. Sangat mudah untuk menghapus file secara tidak sengaja, dan terkadang file hilang karena kerusakan komputer. Mengetik ulang konten file yang hilang membuat frustrasi dan memakan waktu. Oleh karena itu, sangat penting bagi Anda untuk mempelajari cara melindungi file dan membiasakannya jikamelakukannya sebelum bencana terjadi. Mencadangkan file di memoristick adalah metode penyimpanan yang mudah dan nyaman bagi banyak orang. Bentuk pencadangan lain yang semakin populer adalah penyimpanan file Internet.

Berikut adalah beberapa petunjuk yang perlu diingat:
    + Sering-seringlah membuat cadangan. Mencadangkan file hanya membutuhkan beberapa detik, dan Anda akan membenci diri sendiri jika harus menghabiskan banyak waktu untuk membuat ulang pekerjaan yang sebenarnya bisa Anda simpan dengan mudah. Saya sarankan Anda mencadangkan pekerjaan Anda setiap tiga puluh menit sekali.
    + Putar cadangan. Gunakan lebih dari satu direktori untuk cadangan, dan putar mereka. Artinya, back up dulu ke direktori pertama. Kemudian kembali ke direktori kedua. Kemudian gunakan yang ketiga, lalu kembali ke yang pertama. Dengan begitu Anda selalu memiliki tiga cadangan terbaru. Jika perubahan terbaru Anda memperburuk keadaan, Anda dapat kembali ke versi yang lebih lama.
    + Perhatikan arah pencadangan. Pencadangan melibatkan penyalinan file dari satu tempat ke tempat lain. Anda harus melakukannya dengan benar—yaitu, menyalin dari lokasi kerja Anda ke lokasi pencadangan. Jika Anda melakukannya dengan cara yang salah, Anda akan menimpa file yang lebih baru dengan versi yang lebih lama.
    + Periksa cadangan Anda sesekali. Periksa kembali apakah cadangan Anda berada di tempat yang Anda pikirkan. Tidak ada yang lebih membuat frustrasi daripada mengetahui bahwa cadangan tidak ada saat Anda membutuhkannya.
    + Santai, lalu pulihkan. Saat Anda kehilangan file dan perlu memulihkannya dari cadangan, kemungkinan besar Anda berada dalam keadaan gelisah dan tidak bahagia. Ambil napas dalam-dalam dan pikirkan proses pemulihan sebelum Anda mulai. Bukan hal yang aneh bagi pengguna komputer yang gelisah untuk menghapus cadangan terakhir ketika mencoba memulihkan file yang rusak

---

### 1.5 Menganalisis Program Pertama Anda

Pada bagian ini, kita akan menganalisis program Java pertama secara rinci. Di sini adalah kode sumber.

<p align="center">
<img width="319" src="https://user-images.githubusercontent.com/112605121/190379461-72ee400f-fa76-4aed-8b3e-eaec4cecc2b4.PNG"></p>

Garis

	public class HelloPrinter

menunjukkan deklarasi kelas yang disebut HelloPrinter. 

Setiap program Java terdiri dari satu atau lebih kelas. Kita akan membahas kelas secara lebih rinci di Bab 2 dan 3.
Kata publik menunjukkan bahwa kelas dapat digunakan oleh "publik". Anda kemudian akan menemukan fitur pribadi.
Di Java, setiap file sumber dapat berisi paling banyak satu kelas publik, dan nama kelas publik harus sesuai dengan nama file yang berisi kelas tersebut. Misalnya, kelas HelloPrinter harus dimuat dalam file bernama HelloPrinter.java.

Konstruksi

    public static void main(String[] args) 
    { 
        . . . 
    }

mendeklarasikan metode yang disebut main. Metode berisi kumpulan instruksi pemrograman yang menjelaskan bagaimana melakukan tugas tertentu. Setiap aplikasi Java harus memiliki metode utama. Sebagian besar program Java berisi metode lain selain utama, dan Anda akan melihat di Bab 3 cara menulis metode lain.

Istilah statis dijelaskan secara lebih rinci dalam Bab 8, dan arti dari String[ ] args dibahas dalam Bab 11. Pada saat ini, cukup pertimbangkan

    public class ClassName
    { 
        public static void main(String[] args) 
        { 
        . . . 
        } 
    } 

sebagai bagian dari "pipa" yang diperlukan untuk membuat program Java. Program pertama kita memiliki semua instruksi di dalam metode main kelas.

Metode main berisi satu atau lebih instruksi yang disebut pernyataan. Setiap pernyataan diakhiri dengan titik koma (;). Ketika sebuah program dijalankan, pernyataan dalam metode utama dieksekusi satu per satu.

<p align="center">
<img width="402" alt="BJ14" src="https://user-images.githubusercontent.com/112605121/190379569-06dd49e8-0fd8-47d2-ab88-a0e5d40a7b90.PNG"></p>

Dalam contoh program kita, metode utama memiliki satu pernyataan:

    System.out.println("Hello, World!");

Pernyataan ini mencetak sebaris teks, yaitu “Hello, World!”. Dalam pernyataan ini, kita memanggil metode yang, untuk alasan yang tidak akan kita jelaskan di sini, ditentukan dengan nama System.out.println yang agak panjang.

Kita tidak harus mengimplementasikan metode ini—programmer yang menulis library Java sudah melakukannya untuk kita. Kita hanya ingin metode melakukan tugas yang dimaksudkan, yaitu mencetak nilai.

Setiap kali Anda memanggil metode di Java, Anda perlu menentukan

    1. Metode yang ingin Anda gunakan (dalam hal ini, System.out.println).
    2. Nilai apa pun yang dibutuhkan metode untuk menjalankan tugasnya (dalam hal ini, "Hello, World!"). Istilah teknis untuk nilai seperti itu adalah argumen Argumendiapitdalamtandakurung. Beberapaargumendipisahkandengankoma.

Urutan karakter yang diapit tanda kutip

    "Hello, World!" 

disebut string. Anda harus menyertakan isi string di dalam tanda kutip sehingga kompilator mengetahui maksud Anda secara harfiah "Hello, World!". Ada alasan untuk persyaratan ini. Misalkan Anda perlu mencetak kata main. Dengan melampirkannya dalam tanda kutip, "main", kompiler tahu maksud Anda urutan karakter m a i n,
bukan metode bernama main. Aturannya sederhana, Anda harus menyertakan semua string teks dalam tanda kutip, sehingga kompilator menganggapnya sebagai teks biasa dan tidak mencoba menafsirkannya sebagai instruksi program.

Anda juga dapat mencetak nilai numerik. Misalnya pernyataan

    System.out.println(3 + 4);

mengevaluasi ekspresi 3 + 4 dan menampilkan angka 7.

Metode System.out.println mencetak string atau angka dan kemudian memulai baris baru. Misalnya, urutan pernyataan

    System.out.println("Hello"); 

    System.out.println("World!");

mencetak dua baris teks:

    Hello 
    
    World!

Ada metode kedua, System.out.print, yang dapat Anda gunakan untuk mencetak item tanpa memulai baris baru. Misalnya, output dari dua pernyataan

    System.out.print("00"); 
    
    System.out.println(3 + 4);

adalah garis tunggal

    007
    

    11. Bagaimana Anda memodifikasi program HelloPrinter untuk menyambut Anda?

    12. Bagaimana Anda memodifikasi program HelloPrinter untuk mencetak kata “Halo” Tegak lurus?

    13. Apakah program akan terus bekerja jika Anda mengganti baris 7 dengan pernyataan ini?
        
        System.out.println(Halo);

    14. Apa yang dicetak oleh kumpulan pernyataan berikut?
        
        System.out.print("Angka keberuntungan saya adalah");
        
        System.out.println(3 + 4 + 5);

    15. Apa yang dicetak oleh pernyataan berikut?
        
        System.out.println("Halo");
        
        System.out.println("");
        
        System.out.println("Dunia")

**Kesalahan Umum 1.1**

Menghilangkan Titik Koma

Di Java setiap pernyataan harus diakhiri dengan titik koma. Lupa mengetik titik koma adalah kesalahan umum. Ini membingungkan kompiler, karena kompiler menggunakan titik koma untuk menemukan di mana satu pernyataan berakhir dan yang berikutnya dimulai. Kompilator tidak menggunakan jeda baris atau kurung kurawal untuk mengenali akhir pernyataan. Misalnya, kompiler menganggap

    System.out.println("Hello") 
    
    System.out.println("World!");

satu pernyataan, seolah-olah Anda telah menulis

    System.out.println("Hello") System.out.println("World!");

Kemudian tidak mengerti pernyataan itu, karena tidak mengharapkan kata Sistem mengikuti kurung penutup setelah "Hello". 
Obatnya sederhana. Pindai setiap pernyataan untuk mencari titik koma, sama seperti Anda akan memeriksa bahwa setiap kalimat bahasa Inggris diakhiri dengan tanda titik. Namun, jangan menambahkan titik koma di akhir public class Hello atau public static void main. Garis-garis ini bukan pernyataan.

---

### 1.6 Errors


Bereksperimenlah sedikit dengan program HelloPrinter. Apa yang terjadi jika Anda membuat kesalahan pengetikan seperti

    System.ou.println("Hello, World!"); 
    
    System.out.println("Hello, Word!");

Dalam kasus pertama, kompiler akan mengeluh. Kompiler akan mengatakan bahwa ia tidak tahu apa yang Anda maksud dengan ou. Kata-kata yang tepat dari pesan kesalahan tergantung pada lingkungan pengembangan Anda, tetapi mungkin seperti "Tidak dapat menemukan simbol ou". Ini adalah kesalahan waktu-kompilasi. Ada yang salah menurut aturan bahasa dan kompiler menemukannya. Untuk alasan ini, kesalahan waktu kompilasi sering disebut kesalahan sintaksis. Ketika kompilator menemukan satu atau lebih kesalahan, ia menolak untuk menerjemahkan program kedalam instruksi mesin virtual Java, dan sebagai konsekuensinya Anda tidak memiliki program yang dapat dijalankan. Anda harus memperbaiki kesalahan dan mengkompilasi lagi. Faktanya, kompilator cukup pilih-pilih, dan adalah umum untuk melewati beberapa putaran memperbaiki kesalahan waktu kompilasi sebelum kompilasi berhasil untuk pertama kalinya.

Jika kompiler menemukan kesalahan, itu tidak akan berhenti dan menyerah begitu saja. Kompiler akan mencoba melaporkan kesalahan sebanyak yang dapat ditemukan, sehingga Anda dapat memperbaiki semuanya sekaligus.

Terkadang, kesalahan membuat kompiler keluar jalur. Misalkan, misalnya, Anda lupa tanda kutip di sekitar string: System.out.println(Hello, World!).Kompiler tidak akan mengeluh tentang tanda kutip yang hilang. Sebagai gantinya, kompiler akan melaporkan "Tidak dapat menemukan simbol Hello". Sayangnya, kompilernya tidak terlalu pintar dan tidak menyadari bahwa Anda bermaksud menggunakan string. Terserah Anda untuk menyadari bahwa Anda perlu menyertakan string dalam tanda kutip.

Kesalahan pada baris kedua di atas adalah jenis yang berbeda. Program akan dikompilasi dan dijalankan, tetapi outputnya akan salah. Ini akan mencetak

    Hello, Word!

Ini adalah kesalahan run-time. Program ini secara sintaksis benar dan melakukan sesuatu, tetapi tidak melakukan apa yang seharusnya dilakukan. Karena kesalahan run-time disebabkan oleh kelemahan logis dalam program, mereka sering disebut kesalahan logika.

Kesalahan run-time khusus ini tidak menyertakan pesan kesalahan. Itu hanya menghasilkan output yang salah. Beberapa jenis kesalahan run-time sangat parah sehingga menghasilkan pengecualian: pesan kesalahan dari mesin virtual Java. Misalnya, jika program Anda menyertakan pernyataan

    System.out.println(1 / 0);

Anda akan mendapatkan pesan kesalahan run-time "Pembagian dengan nol".

Selama pengembangan program, kesalahan tidak dapat dihindari. Begitu sebuah program lebih panjang dari beberapa baris, itu akan membutuhkan konsentrasi manusia super untuk memasukkannya dengan benar tanpa tergelincir satu kali pun. Anda akan menemukan diri Anda menghilangkan titik koma atau tanda kutip lebih sering daripada yang Anda inginkan, tetapi kompilator akan melacak masalah ini untuk Anda.

Kesalahan run-time lebih merepotkan. Kompilator tidak akan menemukannya—sebenarnya, kompilator akan dengan senang hati menerjemahkan program apa pun selama sintaksnya benar—tetapi program yang dihasilkan akan melakukan kesalahan. Ini adalah tanggung jawab pembuat program untuk menguji program dan menemukan kesalahan run-time.

    16. Misalkan Anda menghilangkan karakter "" di sekitar Hello, World! dari HelloPrinter. program jawa. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?

    17. Misalkan Anda mengubah println menjadi printline pada program HelloPrinter.java. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?

    18. Misalkan Anda mengubah main menjadi hello pada program HelloPrinter.java. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?

    19. Saat Anda menggunakan komputer, Anda mungkin pernah mengalami program yang "crash" (berhenti secara spontan) atau "digantung" (gagal menanggapi masukan Anda). Adalah perilaku itu kesalahan waktu kompilasi atau kesalahan waktu proses?

    20. Mengapa Anda tidak dapat menguji program untuk kesalahan run-time ketika memiliki kesalahan kompiler?

**CONTOH KODE** Lihat sec06 dari eText atau kode pendamping untuk tiga program yang menggambarkan kesalahan.

**Kesalahan Umum 1.2**

Kata-kata yang salah eja

Jika Anda secara tidak sengaja salah mengeja kata, maka hal-hal aneh mungkin terjadi, dan itu mungkin tidak selalu
benar-benar jelas dari pesan kesalahan apa yang salah. Berikut adalah contoh yang bagus tentang caranya
kesalahan ejaan sederhana dapat menyebabkan masalah:

    public class HelloPrinter
    { 
        public static void Main(String[] args) 
        { 
            System.out.println("Hello, World!"); 
        } 
    }

Kelas ini mendeklarasikan sebuah metode yang disebut Main. Kompiler tidak akan menganggap ini sama dengan metode main, karena Main dimulai dengan huruf besar dan bahasa Java peka huruf besar/kecil. Huruf besar dan kecil dianggap benar-benar berbeda satu sama lain, dan bagi kompiler Main tidak lebih cocok untuk main dari pada rain. Kompiler akan dengan senang hati mengkompilasi metode Main Anda, tetapi ketika mesin virtual Java membaca file yang dikompilasi, ia akan mengeluh tentang metode utama yang hilang dan menolak untuk menjalankan program. Tentu saja, pesan "metode utama yang hilang" akan memberi Anda petunjuk di mana mencari kesalahan.

Jika Anda mendapatkan pesan kesalahan yang tampaknya menunjukkan bahwa kompiler atau mesin virtual berada di jalur yang salah, periksa ejaan dan kapitalisasi. Jika Anda salah mengeja nama simbol (misalnya, out alih-alih out), kompilator akan menghasilkan pesan seperti "tidak dapat menemukan symbol ou". Pesan kesalahan itu biasanya merupakan petunjuk bagus bahwa Anda membuat kesalahan ejaan.

---

### 1.7 Pemecahan Masalah: Desain Algoritma

Anda akan segera belajar bagaimana memprogram perhitungan dan pengambilan keputusan di Java. Tetapi sebelum kita melihat mekanisme penerapan perhitungan di bab berikutnya, mari kita pertimbangkan bagaimana Anda dapat menjelaskan langkah-langkah yang diperlukan untuk menemukan solusi dari suatu masalah.

#### 1.7.1 Konsep Algoritma

Anda mungkin telah menemukan iklan yang mendorong Anda untuk membayar layanan terkomputerisasi mencocokkan Anda dengan pasangan cinta. Memikirkan bagaimana ini bisa berhasil. Anda mengisi formulir dan kirimkan. Yang lain melakukan hal yang sama. Data diproses oleh program komputer. Apakah masuk akal untuk asumsikan bahwa komputer dapat melakukan tugasmenemukan pasangan terbaik untuk Anda? Misalkan Anda adik laki-laki, bukan komputer, memiliki semua formulir di mejanya. Instruksi apa yang bisa Anda berikan? memberinya? Anda tidak bisa mengatakan, “Temukan yang paling tampan orang yang suka inline skating dan browsing internet”. Tidak ada standar objektif untuk ketampanan, dan pendapat saudaramu (atau itu program komputer yang menganalisis foto calon mitra) kemungkinan akan berbeda dari milik Anda. Jika Anda tidak dapat memberikan instruksi tertulis kepada seseorang untuk menyelesaikannya masalah, tidak mungkin komputer secara ajaib dapat menemukan solusi yang tepat. Itu komputer hanya dapat melakukan apa yang Anda perintahkan. Itu hanya melakukannya lebih cepat, tanpa mendapatkan bosan atau lelah.

Oleh karena itu, layanan pembuatan jodoh yang terkomputerisasi tidak dapat menjamin untuk menemukanpasangan yang optimal untuk Anda. Sebagai gantinya, Anda mungkin disajikan dengan serangkaian calon mitra yang memiliki minat yang sama dengan Anda. Itu adalah tugas yang program computer dapat memecahkan.

Agar program komputer memberikan jawaban atas masalah yang menghitung jawaban, itu harus mengikuti urutan langkah-langkah yang

    + Jelas
    + Dapat dijalankan
    + Mengakhiri

Urutan langkah tidak ambigu ketika ada instruksi yang tepat tentang apa yang harus dilakukan pada setiap langkah dan kemana harus pergi selanjutnya. Tidak ada ruang untuk menebak atau pendapat pribadi. Sebuah langkah dapat dieksekusi ketika itu dapat dilaksanakan dalam praktek. Misalnya, komputer dapat mencantumkan semua orang yang memiliki hobi yang sama dengan Anda, tapi itu tidak bisa memprediksi siapa yang akan menjadi pasangan seumur hidup Anda. Akhirnya, urutan langkah berakhir jika pada akhirnya akan berakhir. Sebuah program yang terus bekerja tanpa memberikan jawaban adalah jelas tidak berguna.

Urutan langkah yang tidak ambigu, dapat dieksekusi, dan diakhiri disebut algoritma. Meskipun tidak ada algoritme untuk menemukan pasangan, banyak masalah memiliki algoritme untuk diselesaikan mereka. Bagian berikutnya memberikan contoh. 

#### 1.7.2 Algoritma untuk Memecahkan Masalah Investasi

Pertimbangkan masalah investasi berikut:

Anda memasukkan $10.000 ke dalam rekening bank yang menghasilkan bunga 5 persen per tahun. Berapa banyak tahun yang diperlukan agar saldo akun menjadi dua kali lipat dari aslinya?

Bisakah Anda memecahkan masalah ini dengan tangan? Tentu, Anda bisa. Anda mengetahui keseimbangannya sebagai berikut:
 
 <p align="center">
<img width="268" src="https://user-images.githubusercontent.com/112605121/190379679-f0e3a9fc-1839-4490-a010-eb7e7eab542c.PNG"></p>

Anda terus berjalan sampai saldo setidaknya $20.000. Kemudian angka terakhir di tahun inikolom adalah jawabannya.

Tentu saja, melakukan perhitungan ini sangat membosankan bagi Anda atau adik laki-laki Anda. Tetapi komputer sangat pandai melakukan perhitungan berulang dengan cepat dan tanpa cacat. Yang penting bagi komputer adalah deskripsi langkah-langkah untuk menemukan solusi. Setiap langkah harus jelas dan tidak ambigu, tidak memerlukan tebak-tebakan. Berikut adalah deskripsi seperti itu:

Setel tahun ke 0, saldo ke 10.000.

<p align="center">
<img width="115" alt="BJ16" src="https://user-images.githubusercontent.com/112605121/190379749-2ea6b09f-8bb5-41b5-87db-effe84043622.PNG"></p>

Ketika saldo kurang dari $20,000

Tambahkan 1 ke tabel tahun.

Tetapkan bunga ke saldo x 0,05 (yaitu, bunga 5 persen).

Tambahkan bunga ke saldo

<p align="center">
<img width="123" alt="BJ17" src="https://user-images.githubusercontent.com/112605121/190379770-b383a666-1385-4268-aba2-2992b76caac0.PNG"></p>

Laporan tahun sebagai jawabannya.

Langkah-langkah ini termasuk dalam bahasa yang belum dapat dipahami oleh komputer, tapi kamu akan segera belajar bagaimana merumuskannya dalam Java. Deskripsi ini disebut dengan pseudocode. Kami membahas aturan untuk menulis pseudocode di bagian selanjutnya.

#### 1.7.3 Pseudocode

Tidak ada persyaratan ketat untuk pseudocode karena dibaca oleh manusia,bukan program komputer. Berikut adalah jenis-jenis pernyataan pseudocode dan bagaimana kita akan menggunakan penerapannya dalam buku ini:

+ Gunakan pernyataan seperti berikut ini untuk menjelaskan bagaimana suatu nilai ditetapkan atau diubah:

biaya total = harga beli + biaya operasi

Kalikan nilai saldo dengan 1,05.

Hapus karakter pertama dan terakhir dari kata.

+ Jelaskan keputusan dan pengulangan sebagai berikut:

Jika total biaya 1 < total biaya 2

Ketika saldo kurang dari $20,000

Untuk setiap gambar dalam urutan

Gunakan lekukan untuk menunjukkan pernyataan mana yang harus dipilih atau diulang:

Untuk setiap mobil

biaya operasi = 10 x biaya bahan bakar tahunan

biaya total = harga beli + biaya operasi

Di sini, lekukan menunjukkan bahwa kedua pernyataan harus dieksekusi untuk setiap mobil.

+ Tunjukkan hasil dengan pernyataan seperti:

Pilih mobil.

Laporkan tahun sebagai jawabannya.

#### 1.7.4 Dari Algoritma ke Program

Di Bagian 1.7.2, kami mengembangkan pseudocode untuk menemukan berapa lama waktu yang dibutuhkan untuk menggandakan investasi. Mari kita periksa kembali bahwa pseudocode mewakili suatu algoritma itu . adalah bahwa pseudocode itu jelas, dapat dieksekusi, dan diakhiri.

Pseudocode kami jelas. Ini hanya memberi tahu cara memperbarui nilai di setiap langkah. Pseudocode dapat dieksekusi karena kami menggunakan tingkat bunga tetap. Apakah kami mengatakan untuk menggunakan tingkat bunga aktual yang akan dibebankan di tahun-tahun mendatang, dan bukan tingkat bunga tetap 5 persen per tahun, instruksi tidak akan dapat dieksekusi. Tidak ada jalan bagi siapa pun untuk mengetahui berapa tingkat bunga di masa depan. Ini membutuhkan sedikit berpikir untuk melihat bahwa langkah-langkahnya berakhir: Dengan setiap langkah, keseimbangan naik setidaknya $ 500, jadi akhirnya harus mencapai $ 20.000.

Oleh karena itu, kami telah menemukan algoritme untuk menyelesaikan masalah investasi kami, dan kami tahu kami dapat menemukan solusinya dengan memprogram komputer. Keberadaan algoritma adalah prasyarat penting untuk memprogram tugas. Anda harus terlebih dahulu algoritma untuk tugas anda sebelum Anda memulai pemrograman (lihat Angka 8). Dalam bab-bab berikutnya, Anda akan mempelajari cara mengekspresikan algoritme dalam bahasa Java.

    21. Misalkan tingkat bunga adalah 20 persen. Berapa lama waktu yang dibutuhkan agar investasi menjadi dua kali lipat?

    22. Misalkan operator ponsel Anda menagih Anda $29,95 hingga 300 menit panggilan, dan $0,45 untuk setiap menit tambahan, ditambah pajak dan biaya 12,5 persen. Memberi algoritma untuk menghitung biaya bulanan dari sejumlah menit tertentu.

    23. Perhatikan pseudocode berikut untuk menemukan foto paling menarik dari urutan foto:

    Pilih foto pertama dan beri nama "yang terbaik sejauh ini".

    Untuk setiap foto dalam urutan

    Jika itu lebih menarik daripada "terbaik sejauh ini"
    
    Buang "yang terbaik sejauh ini".
    
    Sebut foto ini "yang terbaik sejauh ini".
    
    Foto yang disebut "yang terbaik sejauh ini" adalah foto paling menarik dalam urutan itu.

    Apakah ini algoritma yang akan menemukan foto paling menarik?

    24. Misalkan setiap foto di Self Check 23 memiliki label harga. Berikan algoritma untuk menemukan foto yang paling mahal.

    25. Misalkan Anda memiliki urutan acak kelereng hitam dan putih dan ingin atur ulang sehingga kelereng hitam dan putih dikelompokkan bersama. Mempertimbangkan
    algoritma ini:

    Ulangi sampai terurut
    
    Temukan kelereng hitam pertama yang didahului oleh kelereng putih, dan alihkan.
    
    Apa yang dilakukan algoritma dengan urutan mlmll? Sebutkan langkah-langkahnya sampai algoritma berhenti.

    26. Misalkan Anda memiliki urutan acak kelereng berwarna. Pertimbangkan kode semu ini:

    Ulangi sampai terurut
    
    Temukan kelereng pertama yang didahului oleh kelereng dengan warna berbeda, dan ganti.
    
    Mengapa ini bukan algoritma?
   
---
