Nama: ANDREAN PUTRA ARYA

Kelas: TI.24.A4

NIM: 312410341

Matkul: Bahasa Pemrograman

# Latihan 1

![gambar](https://github.com/andreanbadeh/Praktikum-6-Lab6/blob/b37b5b4b143f6ff0231e70f67ddd7ee45557f096/Image/Screenshot%20from%202024-11-26%2014-22-32.png)

# Latihan 1.py
```
import math

a = lambda x: x**2
b = lambda x, y: math.sqrt(x**2 + y**2)
c = lambda *args: sum(args)/len(args) if args else 0
d = lambda s: "".join(set(s)) 

print("lambda a(5):", a(5))
print("lambda b(3, 4):", b(3, 4))
print("lambda c(1, 2, 3, 4, 5):", c(1, 2, 3, 4, 5))
print("lambda d('hello andre'):", d("andre"))
```
Code Program Tersebut:

![gambar](https://github.com/andreanbadeh/Praktikum-6-Lab6/blob/fb30d09c48ba044f5734748e64a032b2b7695309/Image/latihan1.png)

Hasil Program Tersebut:

![gambar](https://github.com/andreanbadeh/Praktikum-6-Lab6/blob/fb30d09c48ba044f5734748e64a032b2b7695309/Image/Screenshot%20from%202024-11-26%2014-31-30.png)
