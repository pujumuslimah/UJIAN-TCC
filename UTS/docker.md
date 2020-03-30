1.	Daftar dockerhub

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar1.jpg

- tampilan setelah melakukan pendaftaran
https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar2.jpg


2.	Install docker toolbox di windows
-	 Link untuk menginstal docker toolbox https://github.com/docker/toolbox/releases. Setelah selesai terdownload langsung saja jalankan aplikasi docker toolbox.
 
 https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar3.jpg

-	Tampilan pertama instalasi docker toolbox seperti gambar di bawah ini. klik next untuk melanjutkan instalasi.

 https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar4.jpg

-	 Step selanjutnya yaitu pengaturan direktori instalasi. Klik browse, untuk menentukan direktori instalasi. Jika tidak biarkan default direktori awal kemudian klik next.

-	https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar5.jpg
 
-	Selanjutnya memilih service apa saja yang di instal. Pada instalasi ini pilih full  insttallation. kemudian klik next.
 
https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar6.jpg

-	Selanjutnya yaitu memilih additional task yang dibutuhkan. Biarkan default.kemudian klik next.

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar7.jpg
 
-	Lalu klik install untuk memulai instalasi docker toolbox

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar8.jpg
 
-	Tunggu proses instalasi docker toolbox hingga selesai seperti gambar dibawah ini.

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar9.jpg
 
-	Klik finish. 

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar10.jpg
 
-	Tampilan docker setelah terinstall
https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar11.jpg

- terjadi kesalahan saat membuka docker 

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar12.JPG
 



maaf sebelumnya pak laptop saya spesifikasinya tidak memadai untuk install docker.




menjalankan docker


https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar13.JPG

1. Docker pull. Docker pull digunakan untuk mendownload image yang telah tersedia di repository docker hub. Contoh penggunaan seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar14.jpg
 
2. Docker images. Docker images digunakan untuk melihat images yang ada. Contoh penggunaan seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar15.jpg
 
3. “docker run -it image /bin/bash” digunakan untuk masuk kedalam sistem image. Contoh penggunaan seperti ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar16.jpg
 
- Untuk test apakah kita masuk di sistem image bisa ketikkan perintah “cat /etc/osrelease” seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar17.jpg

- Ketikkan exit untuk keluar dari sistem image seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar18.jpg
 
4. “docker run -d -p 8080:80 - -name nama-container image” perintah tersebut digunakan untuk membuat image menjadi container. Arti -p port yang digunakan untuk mengakses dan - -name digunakan untuk memberika nama container yang akan dijalankan. Sebagai contoh seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar19.jpg
 
5. “docker ps” perintah ini digunakan untuk melihat container yang sedang aktif atau berjalan. Sebagai contoh seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar20.jpg
 
6. “docker ps -a” perintah ini digunakan untuk melihat semua container yang sedang aktif atau berjalan. Sebagai contoh seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar21.jpg
 
7. “docker exec -it nama-container /bin/bash” Setelah menjalankan perintah ini, anda akan berada dalam sistem operasi container. Dengan menggunakan command tersebut, dapat melakukan pengecekan file konfigurasi, data, dsb. Sebagai contoh seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar22.jpg

- Untuk melihat test apakah kita masuk pada sistem container jita berikan perintah “cat /etc/os-release” seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar23.jpg

- Ketikkan exit untuk keluar dari sistem image seperti gambar dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar24.jpg

8. “docker inspect nama-container/container-id” Digunakan untuk melihat detail dari container yang berjalan seperti: IP Address dan lainnya Sebagai contoh seperti gambar di bawah ini
 
https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar25.JPG

9.  “docker stop id-container” perintah ini digunakan untuk menghentikan container yang berjalan. Id container yang dituliskan cukup 4 digit paling depan. Sebagai contoh ikuti langkah dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar26.jpg

10.  “docker start id-container” perintah ini digunakan untuk menjalankan container. Id container yang dituliskan cukup 4 digit paling depan. Sebagai contoh ikuti langkah dibawah ini.

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar27.jpg

11. “docker rm id-container/nama-container” perintah ini digunakan untuk menghapus container yang berjalan. Sebagai contoh ikuti langkah dibawah ini

https://github.com/pujumuslimah/UJIAN-TCC/blob/master/UTS/gambar28.JPG