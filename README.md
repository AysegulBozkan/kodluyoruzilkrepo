# kodluyoruzilkrepo
Kodluyoruz Eğitimi kapsamında açtığım ilk repo

print("Girilen sayının asal olup olmadığını bul")
sayi = int(input('sayı: '))
asalmi = True

if sayi == 1:
    asalmi = False

for i in range(2, sayi):
    if (sayi % i == 0):
        asalmi = False
        break
