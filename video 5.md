# Rangkuman Video #5 Bekerja Dengan Git
di video ini dijelaskan mengenai Git

## Install Git
installer Git dapat didownload di website resminya di git-scm.com
lalu bisa langsung di install di perangkat

## Command umum di Git Bash
ada beberapa command yang dapat digunakan pad Git Bash:

#### $ cd (change directory)
berfungsi untuk masuk ke dalam folder yang terdapat dalam library 'working directory'
git-test
![image](https://user-images.githubusercontent.com/95738230/153624326-aba784e9-ef66-46df-a1eb-09d16c45f115.png)

#### $ ls 
berfungsi untuk menampilkan library yang terdapat dalam working directory
![image](https://user-images.githubusercontent.com/95738230/153631191-ae9c5bf6-8ea1-4cca-89d3-64f2e3050988.png)

#### $ git status
berfungsi untuk mengetahui perubahan apa yang telah terjadi di repo kita dan perlu dicommit (file baru, dsb.)
contoh yang dibawah adalah ketika menambahkan file baru pada repo
![image](https://user-images.githubusercontent.com/95738230/153628573-50005600-2159-4489-bab7-f49a66c3e4bb.png)

### $ git log
untuk menampilkan file yang telah di commit
![image](https://user-images.githubusercontent.com/95738230/153636612-1785f95a-448e-4ab9-b230-8f324fb2c1c1.png)


<p>&nbsp;</p>

## Menggunakan Git Bash
ada 3 area yang terdapat dalam git bash yaitu:
- working tree : folder tempat kita bekerja
- staging area : area untuk perubahan yang sudah di"stage" ke git
- history : tempat untuk file yang sudah di commite

### Membuat Repository
dengan perintah $ git init 
![image](https://user-images.githubusercontent.com/95738230/153624564-ed914021-cc21-49c5-a6ee-9e5a6c6cf03f.png)

### Melakukan commit file baru
- stage file yang akan di commit : $ git add <nama file>
  ![image](https://user-images.githubusercontent.com/95738230/153630015-9bfc2eed-58a1-45c9-aa7f-31e06719dbbc.png)
- masukkan data user : $ git config --global user.<jenis_data> "nama_data"
  ![image](https://user-images.githubusercontent.com/95738230/153630837-6342a6fc-ec0f-4fc0-8263-9f519262e18b.png)
- commit : $ git commit -m "<comment>"
  ![image](https://user-images.githubusercontent.com/95738230/153632767-e25982a6-a343-497d-a2fa-c6bd45d4fa94.png)
 
### Melakukan commit pada file yang telah diedit
- stage semua file yang ada : $ git add .
  ![image](https://user-images.githubusercontent.com/95738230/153635911-beef1394-11ce-48a2-a852-6325cb115099.png)
- commit : git commit -m "<comment>"
  ![image](https://user-images.githubusercontent.com/95738230/153636199-10de954a-ab9f-457b-9d80-65e3928ddf8f.png)

### Melakukan Checkout atau kembali ke sebuah commit
- checkout ke commit yang diinginkan : $ git checkout <5 digit pertama hash commit> -- "<nama file yang ingin dirubah ke hasil commitnya>"
  ![image](https://user-images.githubusercontent.com/95738230/153637938-3e8606c1-653d-42f2-bdd8-505204bc9de7.png)
- commit : $ git commit -m "<comment>"
  ![image](https://user-images.githubusercontent.com/95738230/153638115-721f6854-fb6b-45e6-a602-a2d447f6a341.png)
