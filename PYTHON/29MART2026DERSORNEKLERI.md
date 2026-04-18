# örnek-001:
           print("Merhaba Dünya")
               Merhaba Dünya
# örnek-002 :
            isim=(input("isim Giriniz: ") )
               print("Hoşgeldin " + isim)
# örnek-003 :
    # Girilen 2 Sayıyı Toplayan Program 
    sayi1=input("1.sayiyi giriniz : ")
    sayi2=input("2.sayiyi giriniz : ")
    Toplam=float(sayi1)+float(sayi2)
     
     #print=("Toplam"+Toplam) << Bu şekilde yaparsak 
     #TypeError: can only concatenate str (not "float") to str
     #hatası alınabilir 

     print("Toplam {0}".format(Toplam) )
     #veya
     print(f"Toplam :{Toplam}")
# örnek-004
    # Girilen 2 Sayıyı Tortalamasını yapan Program 
    sayi1=input("1.sayiyi giriniz : ")
    sayi2=input("2.sayiyi giriniz : ")

    # Toplam=float(sayi1)+float(sayi2)
    # ortalama=Toplam/2

    # veya

    ortalama=(float(sayi1)+float(sayi2))/2

    print(f"Ortalama :{ortalama}")

# örnek-005:
     #Girilen 3 yazılı notunu hesaplayanprogram
     yazili_notu1=float(input("1.Yazili notunu giriniz :") )
    yazili_notu2=float(input("2.Yazili notunu giriniz :") )
    yazili_notu3=float(input("3.Yazili notunu giriniz :") )

    yazili_ortalamasi=(yazili_notu1+yazili_notu2+yazili_notu3)/2

    print(f"Yazili Ortalaması = ",yazili_ortalamasi )
                                 
