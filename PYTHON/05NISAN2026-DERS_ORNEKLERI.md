# örnek-001:
    #if - else
    #ortalamnın 50 yukarı ise geçti yoksa kaldı yazacak
    not1=float(input("1. Notu Giriniz:"))
    not2=float(input("2. Notu Giriniz:"))           
     ortalama=(float(not1)+float(not2))/2
    if ortalama >=50 :
        print("Geçti..")
    else :
        print("Kaldınız")       

# örnek-002:
    #if elif  else
    # kullanıcı rakam girşi yapıyor çıktı pozitif sayı ,negatif  ve nötr şeklinde  çıktı vercek
    rakam=float(input("lütfen rakam giriniz:"))
    if rakam>0 :
       print("Sayı Pozitiftir.")
    elif rakam<0:
      print("Sayı negatiftir")
    else:
      print("Saı nötrdür.")      

# ÖRNEK-003
    # for döngüsü kullanımı
    # 1 ile 100 arası sayıları ekranda sıralama uygulaması
    for sayi in range(1,11):
      print(sayi)


# örnek-004
     # for döngüsü kullanımı
     # 1 ile 100 arası sayıları ekranda sıralama uygulaması
     for sayi in range(1,11):
         print("METIN") 

# örnek-005
       # for döngüsü kullanımı
       # 1 ile 10 arası çift sayıları ekranda sıralama uygulaması
       for i in range (0,11) :
           if i%2==0 :
               print(i) 

# örnek-006
    # for döngüsü kullanımı
    # 1 ile 10 arası teksayıları ekranda sıralama uygulaması
    for i in range (1,11,2) :
        if i%2==1:
          print(i)
 # örnek-007
       # for döngüsü kullanımı
       # 1 ile 10 arası tek sayıları ekranda sıralama uygulaması
       for i in range (0,11) :
           if i%2!=0 :
               print(i) 

# örnek-008 :
     # for döngüsü kullanımı
     # 1 ile 100 arası 3'e ve 5'e tam bölünen  sayıları ekranda sıralama uygulaması
      for i in range(1,100):
          if i%3==0 or  i%5==0 :
                     print(i) 

# örnek-009
      #1 den kullanıcıların girdiği sayıya kadar sıralayan program

     kullanici_bitis_sayisi=int(input("Bitiş Sayısını Giriniz :") )
     for i in range(1,kullanici_bitis_sayisi+1):
     print(i)


# örnek -010
     ## while döngüsü
     # 1.sınıf,2.sınıf .... 12.sınıf yazacak döngü 

     i=1
    while i<=12 :
      print("{}.sınıf".format(i))
      i+=1

 # örnek 011
           # while döngüsü
          # 1.sınıf,2.sınıf .... 12.sınıf yazacak döngü 

              i=1
           while i<=12 :
               print(f"{i}.sınıf")
               i+=1


# örnek 012:
    sayı tahmin oyunu
    from random import randint

    random_sayi = randint(1, 100)
    sayac = 0

    while True:
    sayac += 1
    # input() sonucunu int() ile sayıya çevirmeliyiz
    tahmin_sayisi = int(input("Lütfen Sayıyı giriniz (1-100) - çıkış için (0): "))

    if tahmin_sayisi == 0:
        print("Oyundan Çıktınız.")
        break
    elif tahmin_sayisi < random_sayi:
        print("Daha büyük bir sayı giriniz.")
    elif tahmin_sayisi > random_sayi:
        print("Daha küçük bir sayı giriniz.")
    else:
        print(f"TEBRİKLER!! {sayac}. denemede doğru bildiniz.")


 # örnek 013:
        #ortalama için sum ve len kullanımı
       liste1=[10,20,30,40,50,60]
       Toplam=sum(liste1)
       adet=len(liste1)
       print(Toplam)
       print(Toplam/adet)

        break

# örnek 0014
             #mutlak değer hesabı
             sayi11=int(input("Sayı Giriniz :") )
            Mutlak_Deger=abs(sayi11)
            print(Mutlak_Deger)
 # örnek 0015
        #fonksiyon kullanımı

         def dikdortgen(genislik,yukseklik):
         alan=float(genislik)*float(yukseklik)
         print("alan =",alan)
         return alan
         gen=input("Genişlik Giriniz: ")
         yuk=input("Yükseklik Giriniz :")
         

        dikdortgen(yuk,gen)



# örnek 016

     #format kullanımı
     meyveler=["Muz","elma","armut"]
     print("en sevdiğim meyveler {}".format(meyveler))
