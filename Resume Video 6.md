# GIT BRANCH & MERGE

1. git branch -> menampilkan branch apa saja
2. git branch <fileName> -> menambahkan branch
3. yang terdapat bintang dan berwarna hijau adalah branch master
![Gambar 1](/img/v6-1.png "Gambar 1")
  
4. git checkout <namaBranch> -> pindah branch
5. ketika kita membuat sesuatu pada branch "dosen" maka tidak akan muncul perubahan tersebut pada branch master
![Gambar 2](/img/v6-3.png "Gambar 2")
![Gambar 3](/img/v6-2.png "Gambar 3")
6. git log --all --decorate --oneline --graph -> adalah perintah untuk menampilkan visualisasi dari branch
7. bisa kita singkat dengan perintah, alias graph ="git log --all --decorate --oneline --graph". Dengan seperti ini visualisasi dapat dimunculkan dengan hanya menulis graph

## Merge
  
### Jenis Merge
1. Fast forward merge, ketika branch yang ingin digabungkan berada dalam jalur langsung/direct path
![Gambar 4](/img/v6-4.png "Gambar 4")
![Gambar 5](/img/v6-5.png "Gambar 5")
  
2. Three-way Merge, ketika branch yang ingin digabungkan tidak berada pada jalur yang langsung
![Gambar 6](/img/v6-6.png "Gambar 6")
