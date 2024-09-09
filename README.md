import random
parolauzunlugu = int(input("Parolanın uzunluğunu giriniz: "))
parola = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

for i in range(parolauzunlugu):
    a = random.choice(parola)

print(a * parolauzunlugu)
