# 【 Ｍｏｄｕｌ－Ｗｅｂ－Ｎａｔｉｖｅ 】
𝘈𝘴𝘴𝘢𝘭𝘢𝘮𝘶𝘢𝘭𝘢𝘪𝘬𝘶𝘮 𝘞𝘳. 𝘞𝘣,
𝘚𝘢𝘭𝘢𝘮 𝘴𝘦𝘫𝘢𝘩𝘵𝘦𝘳𝘢 𝘣𝘢𝘨𝘪 𝘬𝘪𝘵𝘢 𝘴𝘦𝘮𝘶𝘢,
𝘖𝘮 𝘚𝘸𝘢𝘴𝘵𝘺𝘢𝘴𝘵𝘶,
𝘕𝘢𝘮𝘰 𝘉𝘶𝘥𝘥𝘩𝘢𝘺𝘢,
𝘚𝘢𝘭𝘢𝘮 𝘒𝘦𝘣𝘢𝘫𝘪𝘬𝘢𝘯

Jadi, kali ini saya akan menjelaskan modul 0-4 saja, untuk penjelasan yang modul selanjutnya akan menyusul di lain hari.
Di modul tersebut berisikan sebuah pembuatan WEB ADMIN PERPUSTAKAAN. Nah, kalian bisa simak penjelasan berikut ini.

# 【 ＭＯＤＵＬ　０ 】
Nah, pada modul 0 tersebut merupakan pembuatan database, di mana ya kira-kira ??
- Penjelasan Modul 0 :
1. Buka XAMPP dan run apache serta mySQL yaitu dengan menekan button start
2. Buka localhost/phpmyadmin/ di browser kalian, OKEYYY
3. Buatlah database, dengan cara klik new kemudian ketikkan nama database yang akan dibuat jika sudah klik create
4. Untuk membuat tabel, klik nama databasenya pastikan berada di structure kemudian terdapat kolom pembuatan tabel, ketik nama dan masukkan jumlah baris dari tabel tersebut.
5. Isikan masing-masing kolom nama, type, length, dll sesuai dengan yang terdapat pada modul 0
6. Setelah selesai membuat semua tabel buatlah relasi antar tabel dengan cara klik navbar more dibagian atas kemudian pilih designer untuk menghubungkan pilihlah tool create relationship setelah itu letakkan di primary key dan hubungkan ke foreign key
7. Untuk mengisi table, silahkan klik nama tabel dan pilih insert pada navbar atas isikan sesuai values nya
8. Database telah selesai dibuat

# 【 ＭＯＤＵＬ　１ 】
Di dalam Modul 1 ini  kita akan diarahkan untuk melakukan proses pembuatan dashboard, seperti gambar berikut

![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/1.PNG)

Untuk proses pembuatan programnya silakan buka modul 1 yang sudah saya masukkan di file modul, nah di dalam tampilan dashboard ini terdapat navbar di bagian atas yang nantinya akan berfungsi apabila kita mengklik saah satu dari navbar tersebut. Sebelum masuk dalam dashboard sebenarnya masih ada form login, karena form login berada di modul 6 dan belum saya desain maka belum saya tampilkan. Dalam tampilan dashboard ini menggunakan bootstrap, jquery, dan juga font awesome untuk masing-masing icon. untuk pengoperasian navbar terdapat pada modul berikutnya.

# 【 ＭＯＤＵＬ　２ 】
Modul 2 kali ini akan membuat isi dari navbar buku dan anggota, di mana nantinya apabila memilih navbar buku dan anggota akan di tampilkan datanya, seperti yang berada di gambar berikut tampilan tetap menampilkan header dan footer yang sama. Untuk langkah pembuatannya bisa mengikuti modul 2 yang sudah ada. Berikut merupakan hasil dari Modul 2

![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/2.PNG)
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/4.PNG)

# 【 ＭＯＤＵＬ　３ 】
Bagaimanana data dapat ditambahkan ? Nah jawabannya terdapat di modul ini. Dalam penambahan data pastikan file koneksi telah terisi supaya dapat terkoneksi dengan database di phpmyadmin. Apa sih gunanya ? yap,, jadi gunanya supaya kita lebih mudah dalam penambahan datanya, tidak perlu membuka database di phpmyadminnya tapi cukup menambahkan di button tambahnya saja. OKEY SIMPLE KAN ?? Berikut merupakan form dari button tambahnya yang apabila di klik simpan akan langsung menambah di tampilan data.

![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/3.PNG)
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/5.PNG)

# 【 ＭＯＤＵＬ　４ 】
Jadi, apa sih isi dari modul 4 ini ?
Kalian perlu tau bahwa di modul 4 ini kita akan fokus di bagian peminjaman, seperti pada gambar di bawah ini
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/6.PNG)

Wah, kok bisa muncul ke halaman ini ? Nah kita dapat masuk ke button detail. Di halaman detail ini menampilkan isi ddari dari data peminjaman atas nama anggota tersebut. 
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/7.PNG)

Lalu kita bisa masuk juga di form pengembalian. Tau gak sih fungsinya form ini apa ? Nah, fungsi dari form ini adalah form di mana kita akan mengoperasikannya apabila anggota mengembalikan bukunya. Lantas apa bedanya dengan tanggal jatuh tempo, tanggal jatuh tempo yaitu tanggal di mana si anggota harus mengembalikan buku yang dipinjam pada tanggal tersebut. Dan apabila si anggota mengembalikan lebih dari tanggal jatuh tempo maka akan dikenakan denda, sesuai tampilan detai peminjaman.
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/9.PNG)

Di bagian edit peminjaman ini kita hanya dapat mengubah pada tanggal peminjamannya saja, nama peminjam dan judulnya masih sesuai button yang kita pilih dari aksinya. Setelah disimpan maka akan berubah pada tampilan halaman peminjaman.
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/8.PNG)

Okey, yang ini adalah form untuk tambah peminjaman. Mengapa dalam form ini hanya terdapat 3 kolom data tetapi di halaman peminjaman lebih dari 3 data. Nah, di sini data tanggal jatuh tempo akan terkonsep otomatis karena telah tetuliskan PHPnya bahwa akan menambah 7 hari ke depan. Selain itu juga nama petugas akan otomatis masuk di datanya. Untuk status, sewaktu buku belum dikembalikan masih tertulis dipinjam secara otomatis pula. Ini jawabannya mengapa kita hanya menulis nama anggota, judul buku, dan tanggal pinjam.
![ALT TEXT](https://github.com/memorezasabana/Modul-Web-Native/blob/master/SS%20SIPERPUS/10.PNG)

𝑀𝑜𝒽𝑜𝓃 𝓂𝒶𝒶𝒻,
Dalam pengerjaan modul 4 ini sebenarnya masih ada kesalahan, hanya saja keerorran tersebut tidak tampil pada tampilannya sehingga dalam penjelasan di atas saya menjelaskan hasil ekspetasi saya mengenai modul 4 tersebut dan menurut hasil codingan saya juga belum terarah sesuai konsep, mohon dimaklumi Terima Kasih :)

# 【 ＰＥＮＪＥＬＡＳＡＮ　ＭＯＤＵＬ ５－６ 】
『T』『E』『R』『B』『I』『T』   『S』『E』『G』『E』『R』『A』

# 𝙆𝙖𝙡𝙖𝙪 𝙗𝙞𝙣𝙜𝙪𝙣𝙜 𝙝𝙖𝙧𝙪𝙨 𝙩𝙖𝙣𝙮𝙖 𝙠𝙚𝙢𝙖𝙣𝙖 ??
𝘾𝙪𝙠𝙪𝙥 𝙝𝙪𝙗𝙪𝙣𝙜𝙞 𝙠𝙤𝙣𝙩𝙖𝙠 𝙗𝙚𝙧𝙞𝙠𝙪𝙩 :
- 𝙒𝘼 : +62 857 3604 1408
- 𝙄𝙂 : @𝙤𝙯𝙯𝙖𝙨_
