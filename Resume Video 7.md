# GIT MERGE CONFLICT
Hal ini terjadi akibat dari dua branch mengerjakan baris yang sama pada repo yang sama. Pada kasus ini harus diresolve dengan cara manual dengan memilih kode mana yang akan dipilih.

Ketika kita telah melakukan perubahan pada dua branch di baris yang sama dan repo yang sama. lalu kita ingin menggabungkan dua branch tersebut akan terlihat seperti gambar di bawah
![Gambar 1](/img/v6-7.png "Gambar 1")
hal ini perlu diselesaikan dengan cara memilih perubahan mana yang akan dipilih
setelah itu simpan perubahan lalu commit kembali
![Gambar 2](/img/v6-8.png "Gambar 2")

### kasus khusus ketika ingin melakukan checkout ke commit yang sebelumnya dan ingin melanjutkannya

Misal kita ingin kembali ke commit pada saat menambahkan file dosen
1. copy 7 digit pertama dari hash kemudian lakukan perintah seperti berikut
![Gambar 3](/img/v6-9.png "Gambar 3")
![Gambar 4](/img/v6-10.png "Gambar 4")
![Gambar 5](/img/v6-11.png "Gambar 5")
2. setelah itu jika kita membuat commit pada branch tersebut akan terbuat jalur baru
