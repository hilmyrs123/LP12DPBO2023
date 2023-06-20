# Penjelasan program Latihan 7 DPBO 2023 (JAVA)

###### Saya Muhammad Hilmy Rasyad Sofyan NIM 2100187 mengerjakan Latihan 7 dalam mata kuliah Desain Pemograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.


## Update
Memodifikasi kelas controller dan juga game

## Deskripsi Update

### Dalam Controller.java

Menambahkan method objlastdir yang berfungsi untuk menandai dimana lokasi player berada, dan menambahkan variabel baru yakni curr_direction dan lastdirection.
Setelah method objlastdir dijalankan maka akan didapatkan lokasi player saat ini apakah sedang berjalan lurus terus atau tidak.
Lalu masuk method KeyPressed dimana akan diberikan curr_direction ketika tombol keyboard ditekan, dan nanti akan dibandingkan antara curr_direction dengan lastdirection.
Apabila curr_direction dan lastdirection memiliki value yang sama maka skor tidak akan bertambah, bila berbeda maka skor akan bertambah

### Dalam Game.java

Menambahkan method AddScore dan variabel deltascore agar poin bisa bertambah
