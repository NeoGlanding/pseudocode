## No 1

Buatlah Algoritma untuk menyelesaikan problem ini
David memiliki program yang membutuhkan untuk convert data dari jumlah jam ke detik
Contohnya jika program memiliki input 2 jam maka output yang diharapkan adalah 7200 detik

1. buat variable jam dan detik
2. isi variable jam dengan value number
3. convert nilai yang ada pada variable jam dengan dikali 3600
4. simpan nilai convert didalam variable detik
5. tampilkan detik

## No 2

Buatlah Algoritma untuk menyelesaikan problem ini
Ridho ingin memiliki program untuk mengetahui hasil perbandingan dari 2 buah nilai yang tersedia.
Program harus bisa menampilkan output nilai terbesar atau nilai yang sama jika kedua buah nilai memiliki nilai yang sama.
Contohnya jika Ridho input nilai pertama 10 dan nilai kedua 20. Maka output program adalah: 20 nilai terbesar
Jika Ridho input nilai pertama adalah 5 dan nilai kedua adalah 5. Maka output program adalah nilai pertama sama dengan nilai kedua

1. buat variable nilai1, nilai2
2. jika nilai1 lebih besar dari nilai2 maka tampilkan nilai1 nilai terbesar
3. jika nilai2 lebih besar dari nilai1 maka tampilkan nilai2 nilai terbesar
4. jika nilai1 dan nilai2 memiliki nilai yang sama makan tampilkan nilai pertama sama dengan nilai kedua

## No 3

Buatlah Algoritma untuk menyelesaikan problem ini
Amanda ingin memiliki aplikasi yang dapat menghitung harga tiket pesawat yang harus dibayar oleh Traveler.
Data yang akan diinput adalah
Jumlah Traveler
Harga Tiket Pesawat
Cek apakah membeli tiket one way or two way
Misalnya jumlah traveler 2 orang. Per tiketnya seharga Rp 600.000.
Maka program akan memberikan nilai berupa harga yang harus dibayar sebesar Rp 1.200.000

1. buatlah variable jumlahTraveller, hargaTiketPesawat
2. jika membeli tiket one way maka jumlahTraveller dikali hargaTiketPesawat
3. jika membeli tiket two way maka jumlahTraveller dikali (hargaTiketPesawat \* 2)
4. tampilkan harga yang harus dibayar

## No 4

Buatlah Algoritma untuk menyelesaikan problem ini
William ingin menampilkan deretan nilai dari 0 sampai N.
N adalah nilai akhir yang diinputkan.
Jika William menginput N dengan nilai 100, maka program akan menampilkan deretan nilai 1, 2, 3, 4, 5, ??? , 100

SET N with input value 10
Number with 0
WHILE Number <= N
DISPLAY Number
Number ++

## No 5

Buatlah Algoritma untuk menyelesaikan problem ini
Sarah ingin membuat aplikasi yang bisa mendeteksi dari operasi yang dilakukan seperti dibawah ini:
User menginputkan max nilai (n)
Min nilai adalah 1
Lakukan perulangan untuk cek kondisi berikut:
Jika nilai dapat dibagi dengan 3, program akan menghasilkan output text ???Fizz???
Jika nilai dapat dibagi dengan 5, program akan menghasilkan output text ???Buzz???
Jika tidak munculkan angkanya

DECLARE max with input
DECLARE min with 1
WHILE min <= max
if min % 3 === 0
DISPLAY "Fizz"
if min % 5 === 0
DISPLAY "Buzz"
if min % 15 === 0
DISPLAY "FizzBuzz"
else
DISPLAY min
min++
