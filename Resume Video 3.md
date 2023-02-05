# GITHUB : BRANCH

## Apa itu Branch?
Branch itu adalah cabang dari jalur commit pada repository yang kita buat

## Branching
Suatu proses pengerjaaan project pada repository dengan menyimpan jalur commit secara bercabang di cabang lain selain cabang utama.
Tujuannya adalah :
1. Membuat snapshot tanpa mengganggu jalur utama (Master Branch)
2. Fitur experimental (Kita bisa melakukan beberapa perubahan yang dirasa belum fix pada repo di cabang lain)
3. Repo dapat dikerjakan oleh lebih dari satu orang

## Cara Branching
Ada dua cara dalam melakukan branching
1. Membuat file baru kemudian menyimpannya dalam branch baru
2. Membuat branch baru kemudian menyimpan perubahan pada branch baru
Ketika branch baru sudah terbentuk, kita bebas melakukan perubahan pada file mana pun dan pada branch manapun.

## Merging (Menggabungkan dua atau lebih branch)
Proses menyatukan commit pada branch lain ke branch master (utama) agar bisa menjadi perubahan yang fix pada repo

## Cara Merging
Ketika perubahan yang dilakukan pada branch lain sudah dirasa fix untuk dimasukkan kedalam branch master, 
kita dapat melakukan merging dengan cara sebagai berikut:
1. Klik Compare & pull request
2. Lalu pilih dari branch mana dan ke branch mana dia akan di-Merging
3. Pastikan tidak ada conflict (able to merge)
4. Isi pesan pull request untuk dibaca oleh pemilik repo
5. Klik Create pull request
6. Jika kita yang melakukan perubahan pada repo sendiri atau kita yang menerima pull request dari orang lain, lakukan merge and pull request
bn

### Jika ada conflict pada saat merging
1. Buka tab pull request
2. Kemudian klik resolve conflicts
3. Pilih perubahan mana yang cocok dari perubahan yang bertabrakan itu 
4. Jika sudah selesai klik commit merge

### Jika kita sudah tidak membutuhkan branch yang ada
1. Masuk ke fitur banches
2. Pilih branch mana yang akan di hapus
3. Klik tanda tempat sampah



