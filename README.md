# Praktikum3
## Ricky Alfian Saputra
## 31221027
## TI.22.A4

## Python
## Program Penghitungan Luas & Keliling Lingkaran

Rumus Luas & Keliling Lingkaran
Luas     = phi*(r*r)
Keliling = 2 x phi*r
Nilai Phi yang akan kita gunakan adalah 3.14
r merupakan jari-jari lingkaran
Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.


import math
r = float(input("Masukan Jari-jari : "))

luas = math.pi*(r*r)
keliling = 2*math.pi*r
print ("Luas Lingkaran \t\t= ",luas)
print ("Keliling Lingkaran\t= ",keliling)


## Ini adalah Flowchart dari program yang akan di jalankan

![](Gambar/flw%20chrt.png)


### Ini gambar programnya

![](Gambar/Screenshot%20(10).png)

Dan ini adalah hasil dari program diatas

![](Gambar/Screenshot%20(11).png)

Masukkan Jari-jari pada program tersebut
maka akan muncul hasil dari luas dan keliling lingkaran yang dicari

![](Gambar/Screenshot%20(12).png)

Penjelasan:
Program diatas saya mengimport modul math yang sudah di sediakan oleh python. Fungsinya supaya saya dapat menyertakan nilai phi yang sudah tersedia dalam modul tersebut dengan perintah math.pi jika kita coba mencetak fungsi tersebut maka akan menghasilkan nilai 3.14

import math
print (math.pi)
Output:
3.141592653589793
Selanjutnya kita memerlukan nilai jari-jari (r) yang nantinya akan di masukan oleh pengguna pada layar console. Kita menggunakan fungsi input() yang nilainya di konversi ke tipe data float (bilangan riil). Ingat bahwa fungsi input() akan menganggap semua nilai inputan bertipe string, sehingga kita perlu melakukan konversi ke tipe yang diinginkan.

Ketika kita sudah mendapat nilai phi dan jari-jari selanjutnya kita bisa menghitung luas dan keliling sesuai dengan rumus-nya masing-masing (lihat pada baris ke 3 & 4).

Selanjutnya kita tampilkan hasilnya dengan fungsi print(). sintak \t merupakan karakter espace yang berfungsi untuk membuat tab. dalam kasus ini agar sejajar karakter sama dengan (=) nya.

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil 2 angka pecahan saja kita pakai fungsi format() seperti berikut:

print ("Luas Lingkaran \t= ",format(luas,'.2f'))
print ("Keliling Lingkaran \t= ",format(keliling,'.2f'))
Luas Lingkaran          =  40.72
Keliling Lingkaran      =  22.62
Dengan penggunaan fungsi format(luas,'.2f') akan menghasilkan 2 angka pecahan saja.