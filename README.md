#Latihan 1




TUTORIAL
MENGGUNAKAN GITHUB


1.     Silahkan buka website resminya Git (git-scm.com). 
Kemudian unduh Git sesuai dengan arsitektur komputer kita. 
Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.



2.     Setelah unduhan selesai, instal aplikasi tersebut dengan mengklik  next > hingga instal. 




3.     Tunggu beberapa saat hingga instalisasi berhasil, lalu klik finish .



4.     Git sudah terinstal. Untuk mencobanya, silakan buka CMD kemudian ketik perintah git –version


![1](https://user-images.githubusercontent.com/56390857/67141269-d043f000-f28b-11e9-9a07-31da8490457f.png)



5.     Buatlah akun github di website https://github.com/ . 


 ![2](https://user-images.githubusercontent.com/56390857/67141270-d043f000-f28b-11e9-925c-0dfacd4fda73.png)


6.     Untuk membuat Reposiory Local, buka aplikasi Git bash 




7.     Sebelum mulai menggunakan Git, Silahkan lakukan konfigurasi dengan perintah berikut ini.


$ git config --global user.name "nama_user"


$ git config --global user.email "nama_user"


![3](https://user-images.githubusercontent.com/56390857/67141271-d043f000-f28b-11e9-9132-91693037cc29.png)



8.     Untuk membuat direktory aktif, ketiklah $ mkdir latihan1


$ cd
latihan1


 
![4](https://user-images.githubusercontent.com/56390857/67141272-d0dc8680-f28b-11e9-8fad-1ef2aad7a2d0.png)



9.     Lalu akan muncul folder Latihan1


![5](https://user-images.githubusercontent.com/56390857/67141273-d1751d00-f28b-11e9-83d0-6bb63b15521a.png)




10.   Untuk membuat Reposiory Local, ketik lah 


$ git init


![6](https://user-images.githubusercontent.com/56390857/67141274-d20db380-f28b-11e9-8077-7a10cf94371b.png)
 



11.   Kemudian pada folder latihan1, aktifkan hidden items.
Akan muncul file .git


![7](https://user-images.githubusercontent.com/56390857/67141275-d20db380-f28b-11e9-9067-b4321a2ee0e2.png)

 



12.   Coba buat satu file bernama README.md (text file), ketiklah


$ echo “#Latihan 1” >> README.md


![8](https://user-images.githubusercontent.com/56390857/67141276-d2a64a00-f28b-11e9-8a67-75816a67e533.png)



13.   File berhasil dibuat.


![9](https://user-images.githubusercontent.com/56390857/67141277-d2a64a00-f28b-11e9-914e-566b25a0d327.png)



14.    Untuk menambahkan file yang baru saja dibuat tersebut
gunakan perintah git add.


$ git add README.md


![10a](https://user-images.githubusercontent.com/56390857/67142846-7a714700-f28f-11e9-9bdb-120bf11c0505.JPG)



Dan untuk menyimpan perubahan yang ada
kedalam database repository local, ketiklah 


$ git commit –m
latihan1


![10b](https://user-images.githubusercontent.com/56390857/67142847-7a714700-f28f-11e9-84d8-1401ec4923b0.JPG)


 
 
15.     Untuk membuat Reposiory Server. Masuk ke website https://github.com/ .



Lalu klik ikon pojok kanan atas (+) dan klik new reposiory .






16.    Kemudian kembali ke git bash, dan ketiklah 


$ git remote add origin [url]


![11a](https://user-images.githubusercontent.com/56390857/67142876-cfad5880-f28f-11e9-8d5b-0bb37a0c644e.JPG)
 



17.    Kemudian, untuk mengirim perubahan pada local repository ke server
ketiklah 





$ git push -u origin master


![10c](https://user-images.githubusercontent.com/56390857/67142848-7b09dd80-f28f-11e9-8db1-24f69c131420.JPG)





18.     Untuk melihat perubahannya, masuk ke github lalu ke reposiory. Akan muncul seperti berikut.


![13](https://user-images.githubusercontent.com/56390857/67141281-d4700d80-f28b-11e9-9d61-5cc6d2a7f485.png)



 



