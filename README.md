#Latihan 1 : >> README.md
Belajar git 
yang utama adalah download terlebih dahulu git dan buat akun pada git tersebut.
1. konfigurasi untuk git terlebih dahulu, dengan $ config --global.user.name "[username]" 
dan dengan $ CONFIG --global user.email "[email]". 
2. buat file baru direktori pada folder kalian dengan nama bebas
3. klik kanan pada file tersebut, klik menu Git Bash Here, untuk memasuki program git bash. 
4. kita mulai dengan membuat file baru, yang dibuat di git bash. menggunakan perintah $ mkdir latihan1
5. lalu $ cd latihan1
6. maka file dengan nama latihan1 sudah dibuat. selanjutnya membuat file didalam latihan1 dengan format .git
7. masukkan perintah "$ git init " untuk membuat repository local pada didalam folder latihan1
8. lalu kita membuat file baru dengan nama README.md pada repository tersebut, yaitu " $ echo "#Latihan 1 : >> README.md
9. jika sudah, maka tambahkan file README.md tersebut dengan menggunakan perintah " $ git add (nama file), disini kita menggunakan nama file README.md, maka perintahnya " $ git add README.md "
10. untuk menyimpan perubahan ke dalam adtabase repository, maka gunakan perintah " $ git commit -m "nama file (bebas)"
11. maka file sudah tersimpan di dalam databse. kemudian kita masuk ke website github.com dan membuat repository server. 
12. lalu login dengan username dan password masing masing pada github.com
13. untuk menambahkan repository server, yang digunakan untuk menyimoan perubaha pada local repository, maka gunakan perintah " $ git remote add origin [url github kalian] dengan ditambahkan .git dibelakangnya
14. untuk mengirim perubahan pada local repository ke server repository gunakan perintah " $ git push -u origin master"
15. perintah tersebut akan meminta password dan username github kalian
16. untuk melihat hasilnya, buka github.com dan login dengan akun masin - masing, lalu klik compare & pull request
