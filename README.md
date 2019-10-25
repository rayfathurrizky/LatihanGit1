CARA MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB SERTA CARA MEMBUAT FILE README.md

Yang kalian butuhkan :
1. Akun GitHub
2. Software atau Program Git

DAFTAR AKUN GitHub

  1. Buat akun GitHub dengan cara membuka laman https://github.com
  2. Masukan Username, Email dan Password yang akan kalian gunakan pada akun GitHub kalian.
  ![Screenshot (6)](https://user-images.githubusercontent.com/56881488/67597550-ae6bd100-f795-11e9-989b-526321137133.png)
  3. Lalu buka email yang anda masukan tadi dan lakukan verifikasi.
  ![Screenshot (7)](https://user-images.githubusercontent.com/56881488/67597551-ae6bd100-f795-11e9-8902-aa2240f6deb8.png)
  4. Setelah melakukan verifikasi, kalian akan di alihkan ke laman GitHub untuk selanjutnya membuat Repository baru, lalu masukan
     nama Repository kalian dan klik "create repository".
  ![Screenshot (24)](https://user-images.githubusercontent.com/56881488/67597707-060a3c80-f796-11e9-8b8a-10857920484e.png)
  5. Seperti inilah tampilan Repository baru.
  ![Screenshot (12)](https://user-images.githubusercontent.com/56881488/67597552-af046780-f795-11e9-9924-3564394396ee.png)
  
DOWNLOAD SOFTWARE Git

  1. Untuk mendownload software Git kita harus masuk ke laman https://git-scm.com
  ![download git](https://user-images.githubusercontent.com/56971806/67517048-ee668180-f6cb-11e9-8f7e-999a25a197c2.png)
  2. Pilih download dan sesuaikan dengan operating system dan spesifikasi laptop atau komputer kalian.
  ![git download](https://user-images.githubusercontent.com/56971806/67517709-61242c80-f6cd-11e9-8023-c3e408500952.png)
  3. Lakukan instalasi Git pada laptop atau komputer kalian.
  ![install git](https://user-images.githubusercontent.com/56971806/67518320-c593bb80-f6ce-11e9-8bec-2d7f431b16ec.png)
  4. Pastikan software atau program Git sudah terinstall 100%.
  ![git install complete](https://user-images.githubusercontent.com/56971806/67518391-ebb95b80-f6ce-11e9-97ed-37038b021405.png)
  5. Pastikan program Git sudah dapat di gunakan di perangkat kalian dengan cara membuka Command Prompt lalu ketik "git
  --version"
     jika sudah muncul berarti Git sudah dapat di gunakan.
  ![git verio](https://user-images.githubusercontent.com/56971806/67518796-acd7d580-f6cf-11e9-9170-92d6fd646554.png)
  
 MEMBUAT REPOSITORY LOKAL DAN MEMBUAT FILE README.md
  
  1. Buatlah "folder" baru di directory kalian lalu "klik kanan" pada folder tersebut dan pilih "Git Bash Here"
  ![git bash](https://user-images.githubusercontent.com/56971806/67519128-620a8d80-f6d0-11e9-80e8-53ea3f21054c.png)
  2. Lalu konfigurasi dengan menggunakan perintah "git config --global user.name "nama_user" dan "git config --global user.email
  "email_user"
  ![Screenshot (15)](https://user-images.githubusercontent.com/56881488/67597555-af046780-f795-11e9-97ff-354369f940f4.png)
  3. Buatlah direktori baru dengan menggunakan perintah "mkdir latihan1" dan pindah ke direktori tersebut dengan menggunakan
  perintah "cd latihan1"
  ![2](https://user-images.githubusercontent.com/56881488/67597745-17ebdf80-f796-11e9-8669-daa16d247aaa.png)
  4. Buat file kosong berformat .git dengan cara menjalankan perintah "git init".
  ![3](https://user-images.githubusercontent.com/56881488/67597800-3356ea80-f796-11e9-9120-276372338351.png)
  5. Buat file README.md dengan menggunakan perintah echo "#latihanphyton1" >> README.md"
  ![4](https://user-images.githubusercontent.com/56881488/67597802-3356ea80-f796-11e9-9c95-f93a9cf0a3ba.png)
  6.Untuk melihat File, gunakan perintah ls -l
  ![5](https://user-images.githubusercontent.com/56881488/67597803-33ef8100-f796-11e9-8b90-b0be586fe87f.png)
  7.Memasukan File README.md ke repository lokal dengan menggunakan perintah "git add README.md"
  ![6](https://user-images.githubusercontent.com/56881488/67597804-33ef8100-f796-11e9-86b1-df8719b6b6d8.png)
  8.Simpan perubahan kedalam database repository dengan menggunakan perintah "git commit -m"
  ![7](https://user-images.githubusercontent.com/56881488/67597806-33ef8100-f796-11e9-9d27-b43d7d467f4e.png)
  9.Masuk ke laman GitHub dan buka URL yang sudah di buat di repository GitHub, gunakan perintah "git remote add origin [url]", contoh: git remote add origin https://github.com/rayfathurrizky/LatihanGit1.git
 ![8](https://user-images.githubusercontent.com/56881488/67597807-34881780-f796-11e9-94a1-c9d05c5e92de.png)
  10.Kirim perubahan local repository ke GitHub dengan menggunakan perintah "git push -u origin master"
  ![9](https://user-images.githubusercontent.com/56881488/67597809-34881780-f796-11e9-809d-8ed0b3fa23bb.png)
  11.Cek kembali repository di laman GitHub
