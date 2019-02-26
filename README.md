# Labpy3
# Latihan 1

![](https://github.com/danisarif/praktikum3/blob/master/codingan%20latihan1.png)

## Codingan
```print('==== Bilangan Acak yang lebih kecil dari 0.5 ====')
print(' ')
import random
N = int(input("Masukan nilai N : "))
a = 0
for x in range(N):
    a += 1
    b = random.uniform(.0,.5)
    print('Data ke:',a,'==>',b)
print('Selesai')
print(' ')
jawab = 'lanjutkan'
hitung = 0
while jawab == "lanjutkan":
    hitung += 1
    jawab = input('Ingin Mengulang ? (yes/no) : ')
    if jawab == "Lanjutkan":
        break
print('Total perulangan : ' + str (hitung))
```
## Hasil Codingan

![](https://github.com/danisarif/praktikum3/blob/master/hasil%20run%20latihan1.png)

# Latihan 2

![](https://github.com/danisarif/praktikum3/blob/master/codingan%20latihan2.png)

## Codingan
```print("\nMenentukan Bilangan Terbesar")
print("\n")
max=0
while True:
    a=int(input("Masukan Bilangan :"))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar = ", max)
```
## Hasil Codingan

![](https://github.com/danisarif/praktikum3/blob/master/hasil%20run%20latihan%202.png)

# Program 1

![](https://github.com/danisarif/praktikum3/blob/master/codingan%20latihan%203.png)

## Codingan
```a=100000000
for x in range(0,9):
        if(x>0 and x<=2):
                b=a*0
                print("laba bulan ke-",x," :",b)
        if(x>=3 and x<=4):
                c=a*0.1
                print("laba bulan ke-",x," :",c)
        if(x>=5 and x<=7):
                d=a*0.5
                print("laba bulan ke-",x," :",d)
        if(x==8):
                e=a*0.2
                print("laba bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)
input("\n")
```
## Hasil Codingan

![](https://github.com/danisarif/praktikum3/blob/master/hasil%20run%20latihan%203.png)

## Sekian Terima Kasih
