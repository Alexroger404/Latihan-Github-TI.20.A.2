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

Selanjut nya adalah membuat folder pada local disk, untuk menyimpan update file dari repository Github yanh telah anda buat.

![ss2](https://user-images.githubusercontent.com/73045261/96359439-151f9280-113d-11eb-971f-50d80dc8c7b1.png)

- Buka folder menggunakan Git Bash












