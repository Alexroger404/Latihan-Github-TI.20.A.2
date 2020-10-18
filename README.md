- Pengertian Git

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

- Instalasi Git

Download Git, buka website resminya Git (git-scm.com)
kemudian unduh Git sesuai dengan arsitektur komputer kita.kalau menggunakan 64 bit, unduh yang 64 bit.begitu juga dengan 32 bit
selamat, Git sudah terinstall di windows.untuk menocbanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah
git --version

- Kemudian menambahkan nama user.name dan user.email

git config --global user.name "nama user"

git config --global user.email "nama email"


![ss1](https://user-images.githubusercontent.com/73045261/96359093-c53ecc80-1138-11eb-8917-b54da87337a3.png)

- Perintah Dasar Git

git init, perintah untuk membuat repository local

git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit

git commit, perintah untuk menyimpan perubahan kedalam databese git.

git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.

git clone [ur1], perintah untuk membuat working directory yang diambil dari repository server.

git remote add origin [ur1], perintah untuk menambahkan remote server/repository server pada local repository (working directory)

git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository


- Buat file pada windows

Selanjut nya adalah membuat folder pada local disk, untuk menyimpan update file dari repository Github yang telah anda buat.

![ss2](https://user-images.githubusercontent.com/73045261/96359439-151f9280-113d-11eb-971f-50d80dc8c7b1.png)

- Buka folder menggunakan Git Bash

![ss3](https://user-images.githubusercontent.com/73045261/96359837-721d4780-1141-11eb-96fd-dccc3fe5160e.png)

Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. lalu kita ketik konfigurasi git init 

![ss4](https://user-images.githubusercontent.com/73045261/96360055-7c404580-1143-11eb-9866-5de6699f2e1a.png)


- Tambahkan File ke Repository

Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:

Buat file di folder yang sudah dibuat (Test Git). Contohnya, di sini kami membuat file index.php
Buka GitBash lalu masukkan perintah berikut:

$ git add index.php


- Buat Commit 
Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "first commit"

Pada tutorial ini kami membuat first commit sebagai Commit pertama kami. Anda bebas membuat membuat nama Commit apa saja.



