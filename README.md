*Inisialisasi Repository Git: git init

Perintah ini menginisialisasi repository Git baru di dalam folder Latihan VCS. Setelah perintah ini dijalankan, Git akan mulai melacak perubahan file di dalam folder tersebut. Membuat File README.md: Perintah touch README.md digunakan untuk membuat file kosong bernama README.md di dalam folder yang sedang dikerjakan.

Menambahkan File ke Staging Area: git add README.md

Perintah ini menambahkan file README.md ke staging area. Artinya, file ini akan siap untuk di-commit pada langkah berikutnya.

Memeriksa Status Repository:

git status Perintah ini menunjukkan status dari repository Git. Di sini, ditampilkan bahwa ada satu file (README.md) yang berada di staging area dan siap untuk di-commit.

Melakukan Commit:

git commit -m "Menambahkan File Readme"

Perintah ini membuat commit baru dengan pesan "Menambahkan File Readme". Commit menyimpan snapshot dari file yang berada di staging area, sehingga perubahan dapat dilacak oleh Git.

Menambahkan Remote Origin: git remote add origin

Perintah ini menghubungkan repository lokal dengan repository di GitHub 

Nama "origin" biasanya digunakan sebagai nama default untuk remote repository utama.

Mengirimkan (Push) Perubahan ke Repository Remote:

git push -u origin master

Perintah ini mengirimkan commit dari branch master di repository lokal ke repository remote di GitHub. Opsi -u digunakan agar Git mengingat branch yang dipilih, sehingga pada push berikutnya cukup mengetik git push.
