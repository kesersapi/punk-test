# Basit Toplama Hesap Makinesi

# Kullanıcıdan sayıları alıyoruz
# input() fonksiyonu veriyi metin (string) olarak aldığı için float() ile sayıya çeviriyoruz
sayi1 = float(input("Birinci sayıyı girin: "))
sayi2 = float(input("İkinci sayıyı girin: "))

# Toplama işlemini gerçekleştiriyoruz
toplam = sayi1 + sayi2

# Sonucu ekrana yazdırıyoruz..
print(f"Sonuç: {sayi1} + {sayi2} = {toplam}")
