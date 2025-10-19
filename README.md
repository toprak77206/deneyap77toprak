def ekrana_yaz():
    for i in range(10):
        print("Dene")
    for i in range(2):
        print("Merhaba!")





def ucgen_alani(tabani, yukseklik):
    alan = (tabani * yukseklik) / 2
    return alan

# Örnek:
print(ucgen_alani(10, 5))  # 25.0




def bolunme_kontrolu(sayi):
    if sayi % 5 == 0:
        print("Tam bölünür")
    else:
        print("Kalan:", sayi % 5)

bolunme_kontrolu(13)




def kucuk_sayi(a, b):
    if a < b:
        return a
    else:
        return b

# Daha kısa hali:
# def kucuk_sayi(a, b):
#     return min(a, b)

print(kucuk_sayi(8, 3))  # 3

