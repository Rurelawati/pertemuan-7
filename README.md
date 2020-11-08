# Pertemuan 7
#Program Python perulangan beringkat (nested)
 for
Perulangan dalam bahasa pemrograman berfungsi melakukan secara berulang-ulang, terdapat dua jnis perulangan dalam python. yaitu: *for* dan *while*.

for disebut counted loop (perulangan yang terhitung)
for biasanya digunakan untuk mengulangi code yang sudah diketahui dengan banyaknya perulangan.

while disebut uncounted loop (perulangan yang tak terhitung)
while biasanya digunakan untuk perulangan yang memilik syarat dan tidak tentu berapa banyak perulangan yang diketahui nya.


#Latihan 1

Tugas membuat program dengan perulangan bertingkat (nested) for.

code
baris = 10
kolom = baris
for i in range (baris):
for j in range (kolom):
hitung = i+j
print("{0:>5}.format(hitung), end ='')

print()

gambar1

tentukan banyak nya perulangan contoh : 10
variable i berfungsi menampung indeks dan fungsi range() untuk membuat list range dari 1-10
klik run (shift+F6) dan tampilah hasil output di sebelah kanan gambar.
![latihan1.py.png](/gambar1/latihan1.py.png)


#Latihan 2

Struktur algorithma latihan 2

- Tampilkan n bilangan acak yang lebih kecil dari 0.5.
- Nilai n diisi pada saat runtime.
- Anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya.

Fungsi random()
Fungsi ini akan mengembalikan bilangan float random x, dimana 0 < x < 1. Fungsi random() tidak memiliki parameter masukan.

lihatlah gambar2 dibawah ini
cara bekerja serta hasil output nya.
![latihan2.py.png](gambar2/latihan2.py.png)
