**BAB II**

**LANDASAN TEORI**

**2.1 Model View Controller**

Arsitektur _Model-View-Controller_ adalah sebuah pola yang terbukti membangun proyek secara lebih efektif. Hal itu dilakukan dengan memilih komponen antara _model, view_ dan _controller_ pada bagian-bagian dalam proyek. MVC berhubungan erat dengan arsitektur dari Web Framework.

Pola MVC memiliki layer yang disebut dengan _M__odel_ yang merepresentasikan data yang digunakan oleh aplikasi sebagaimana proses bisnis yang diasosiasikan terhadapnya. Dengan memilihnya sebagai bagian terpisah, seperti penampungan data, _persistence_, serta proses manipulasi terpisah dari bagian lain aplikasi. Terdapat beberapa kelebihan dalam pendekatan ini, yang pertama. Membuat detail dari data dan operasinya dapat ditempatkan pada _area_ yang ditentukan (_Model_) dibanding tersebar dalam keseluruhan lingkup aplikasi. Hal ini memberikan keuntungan dalam proses _maintenace_ aplikasi.

Layer ini mengandung keseluruhan detail dari implementasi keseluruhan _persistence_. Di sini, komponen grafis menyediakan representasi proses _internal_ aplikasi dan menuntun alur interaksi _user_ terhadap aplikasi. Tidak ada layer lain yang berinteraksi dengan _user_ , hanya _View_.

Terakhir, arsitektur MVC memiliki layer _Controller_. Layer ini menyediakan detail alur program dan transisi layer, dan juga bertanggung jawab atas penampungan _event_ yang dibuat oleh _user_ dari _View_ dan melakukan _update_ terhadap komponen _Model_ menggunakan data yang dimasukkan oleh _user_.[3]

**2.2 O**** bj ****ec**** t ****O**** r ****ien**** t ****e**** d ****Pr**** o ****g**** r ****a**** mm ****i**** n ****g**

 ObjectOrientedProgramming(OOP)merupakanparadigmapemrogramanyang berorientasikankepadaobyek.Semuadatadanfungsipadaparadigmainidibungkus dalam kelas-kelas atauobyek-obyek.Bandingkandenganlogikapemrogramanterstruktur, setiapobyek dapatmenerimapesan,memprosesdata, danmengirimpesankeobyeklainnya.OOPdiciptakan untukmengatasiketerbatasanpadabahasapemrogramantradisional.KonsepdariOOPsendiri adalahsemuapemecahanmasalahdibagikedalamobyek.DalamkonsepOOPdatadan fungsi-fungsi yangakanmengoperasikannyadigabungkanmenjadisatukesatuan yangdapatdisebut sebagaiobyek.[4]

**2.3**  **Basis Data**

        Basis Data terdiri atas 2 kata, yaitu Basis dan Data. Basis kurang lebih dapat diartikan sebagai markas atau gudang, tempat bersarang atau berkumpul. Sedangkan data adalah representasi fakta dunia nyata yang mewakili suatu objek seperi manusia (pegawai, siswa, pembeli) , barang, hewan, peristiwa, konsep, keadaan, dan sebagainya, yang direkam dalam bentuk angka, huruf, symbol, teks, gambar, bunyi atau kombinasinya.

Basis Data sendiri dapat didefiinisikan dalam sejumlah sudut pandang seperti:

1. Himpunan kelompok data (arsip) yang saling berhubungan yang diorganisasi sedemikian rupa agar kelak dapat dimanfaatkan kembali dengan cepat dan mudah
2. Kumpulan data yang saling berhubungan yang disimpan secara bersama sedemikian rupa dan tanpa pengulangan (redudansi) yang tidak perlu, untuk memenuhi berbagai kebutuhan.
3. Kumpulan file/tabel/arsip yang saling berhubungan yang disimpan dalam media penyimpanan elektronis.
4. Prinsip utama Basis Data adalah pengaturan data/arsip dan tujuan utamanya adalah kemudahan dan kecepatan. [5]

**2.4**  **Framework**

Framework merupakan suatu kertas kerja dalam membangun aplikasi web. Dengan adanya framework, pembangunan dan pengembangan aplikasi diselesaikan dalam waktu cepat, karena framework telah menyediakan fungsi-fungsi maupun class yang dibutuhkan oleh web.

Dengan adanya framework, segala perbedaan dalam penulisan gaya dilakukan oleh programmer maupun developer dapr diseragamkan. Karena, framework juga memiliki aturan tersendiri, sehingga bagi mereka yang ingin menggunakannya harus terpaksa mengikuti aturan main dari framework tersebut. Sehingga, pengerjaan tidak dapat dilakukan sesuai dengan gaya.

Framework saat ini sudah mulai banyak diminati. Bukan hanya dari kalangan professional, seperti programmer, developer maupun perusahaan jasa website. Tetapi juga diminati oleh kalangan pemula dilingkungan masayarakat.

Secara umum, framework dapat diartikan sebagai suatu frame kerja yang mengatur para pembuat web agar bekerja dengan cara yang terstruktur, dimana didalamnya memiliki modul-modul atau kumpulan potongan program yang disusun sedemikian rupa, sehingga untuk menggunakannya, cukup menambah coding yang diperlukan saja.[6]

**2.5**  **Kelas**

Kelas adalah sebagai suatu masyarakat kecil yang merupakan bagian dari masyarakat sekolah, yang sebagai satu kesatuan diorganisasi menjadi unit kerja yang secara dinamis menyelenggarakan berbagai kegiatan pembelajaran yang kreatif  untuk mencapai suatu tujuan.[7]

**2.6 Sublime**

Sublime Text 2 adalah editor teks yang dirancang untuk mengolah potongan-potongan kode, plugin, dan markup. Tetapi Anda juga bisa memakainya untuk menulis artikel dan mengetik dalam prosanormal. Bagaimanapun Anda mau memakainya, keunggulan Sublime Text 2 ada di kualitas dan kuantitas fitur-fiturnya seperti blok multitempat, kursor banyak, dan pengolahan split. Bermacam-macam fitur ini membuat pengolahan kode menjadi lebih cepat dan mudah. Fitur lain yang menarik adalah dukungannya pada berbagai macam bahasa seperti Clojure, Perl, Javascript, Haskell, Erlango, dan Escala. Anda juga bisa membuat dan menyimpan macro kapan saja, pekerjaan menjadi lebih mudah dengan banyaknys opsi yang bisa dipilih. Adanya kemampuan konfigurasi pintasan kibor menurut kemauan pengguna juga sangat membantu. Dengan ini tindakan yang memakan banyak waktu di program lain bisa Anda lakukan dalam hitungan detik dengan program ini. Sublime Text 2 adalah aplikasi pengolah kata yang sangat lengkap yang akan segera membuat penggunanya jatuh hati padanya.[10]

**2.**** 7 **** UML**

Unified Modeling Language (UML) adalah keluarga notasi grafis yan didukung oleh meta-model tunggal, yang membantu pendeskripsian dan desain sistem perangkat lunak, khususnya sistem yang dibangun menggunakan pemrograman berorientasi objek (OO). Definisi ini merupakan definisi yang sederhana. Pada kenyataanya, pendapat orang-orang tentang UML berbedaan persepsi tentang apa yang membuat sebuah proses rancang-bangun perangkat lunak efektif. [4]

**2.**** 8 **** PHP**

PHP singkatan dari  PHP :Hypertext Preprocessor yaitu bahasa pemograman web sserver-side yang bersifat open source. PHP merupakan script yang terintegrasi dengan HTML dan berada pada server (server side HTML embedded scripting). PHP adalah script yang digunakan unutk membuat halaman website yang dinamis. Dinamis berarti halaman yang akan ditampilkan dibuat saat halaman itu diminta oleh client. Mekanisme ini menyebabkan informasi yang diterima client selalu yang terbaru/up to date. Semua script PHP dieksekusi pada server si mana script tersebut dijalankan2.1.10 WEB

World Wide Web atau lebih sering dikenal sebagai Web adalah suatu layanan sajian informasi yang menggunakan konsep hyperlink (tautan), yang memudahkan surfer (Sebutan para pemakai computer yang melakukan browsing atau penelusuran informasi melalui imternet). Keistimewaan inilah yang telah menjadikan web sebagai service eyang paling cepat pertumbuhannya.

Web mengijinkan pemberian Highlight (penyorotan/penggarisan bawahan) pada kata-kata atau gambar dalam sebuah dokumen untuk menghubungkan atau menunjukan ke media lain seperti dokumen,frase,movi klip, atau file suara. Web dapat menghubungkan dari sembarang tempat darisebuah dokumen atau gambar ke sembarang tempat didokumen lain. Dengan sebuah browser yang memiliki Grapical User Interfaace(GUI0, link-link dapat dihubungkan ketujuannya dengan menunjukan link tersebut dengan mouse dan menekannya.[1]

**2.**** 9 **** Metodelogi Penelitian**

Tahapan-tahapan dalam The Waterfall Model secara ringkas adalah sebagai berikut:

- Tahap  investigasi  dilakukan  untuk  menentukan  apakah  terjadi  suatu masalah atau adakah peluang suatu sistem informasi dikembangkan.  Pada tahapan  ini  studi  kelayakan  perlu  dilakukan  untuk  menentukan  apakah sistem informasi yang akan dikembangkan merupakan solusi yang layak
- Tahap analisis bertujuan untuk mencari kebutuhan pengguna dan organisasi serta menganalisa kondisi yang ada (sebelum diterapkan  sistem informasi yang baru)
- Tahap  disain  bertujuan   menentukan  spesifikasi   detil  dari  komponen- komponen  sistem informasi  (manusia,  hardware, software,  network dan data) dan produk-produk informasi yang sesuai dengan hasil tahap analisis.
-  Tahap   implementasi   merupakan   tahapan   untuk   mendapatkan   atau mengembangkan    hardware    dan    software    (pengkodean    program), melakukan pengujian, pelatihan dan perpindahan ke sistem baru.
- Tahapan perawatan (maintenance) dilakukan ketika sistem informasi sudah dioperasikan. Pada tahapan ini dilakukan monitoring proses, evaluasi dan perubahan (perbaikan) bila diperlukan.

 ![](data:image/*;base64,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)

Gambar 2.1 _The Waterfall Mode__l_