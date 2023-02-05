# Git dan Github

## Version Control System
Version Control System, disebut juga revision control system atau source code management 
adalah sistem yang mengelola perubahan dari sebuah dokumen, program komputer, website dan kumpulan informasi lain

### Alasan menggunakan Version Control System

1. Memudahkan kolaborasi pekerjaan yang dilakukan secara berkelompok
2. Meringkas sampah file akibat revisi yang dilakukan berkali kali
3. Bisa mengerjakan project walaupun sedang tidak menggunakan komputer lokal

### Keuntungan Menggunakan Version Control System
1. Memungkinkan bekerja berkolaborasi dengan lebih baik
2. Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi 
3. Memungkinkan kita untuk kembali ke keadaan sebelum perubahan
 
## Git
Git adalah sebuah VCS (Version Control System) terdistribusi untuk mengelola perubahan file di dalam folder. Folder tersebut biasa disebut repository/repo. Riwayat perubahan file disimpan menggunakan serangkaian commit

## Github
Github adalah layanan cloud untuk menyimpan dan mengelola project/repo git. Salah satu VCS juga sama seperti git tapi bedanya jika git hanya bisa mengelola dalam komputer lokal, kalau github bisa mengelola repo secara online, jadi bisa kolaborasi dengan orang lain secara online.

## Dampak apabila Git dan Github dipasang bersamaan
Pada kasus ini kita bisa mengirim source code dari git menuju github (Push), kita juga bisa mengambil source code dari github ke dalam git komputer kita (Pull). Sesuatu yang di-Push atau di-Pull adalah commit nya. Syarat dalam melakukan hal ini adalah kita perlu membuat github menjadi remote (Sumber dari repo). Kemudian repo tersebut di-Clone ke dalam git dalam komputer kita.

## Beberapa istilah dalam Git
1. Repo : Folder dari project kita
2. Commit : Rekaman/snapshot dari repo kita
3. Hash : Penanda unik pada commit
4. Checkout : Berpindah ke sebuah commit
5. Branch : Cabang bebas dari sebuah commit
6. Merge : Menggabungkan branch
7. Remote : Sumber yang memiliki repo
8. Clone : Mengambil repo dari remote
9. Push : Mengirimkan commit ke repo
10. Pull : Mengambil commit dari repo
