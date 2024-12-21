# 1
x = 3 ----> floata çevirelim. Çevirdikten sonra beri tipinide yazdıralım.

y = 4.5 -----> integere çevirelim. Çevirdikten sonra beri tipinide yazdıralım.

z = "8" -----> integera çevirelim. Çevirdikten sonra beri tipinide yazdıralım.

a = "12" -----> floata çevirelim. Çevirdikten sonra beri tipinide yazdıralım.

b = "46.8" ------> integera çevirelim. Çevirdikten sonra beri tipinide yazdıralım.


```python
x = 3
print(float(x))
type(float(x))

```

    3.0
    




    float




```python
y = 4.5 
print(int(y))
type(int(y))
```

    4
    




    int




```python
z = "8"
print(int(z))
type(int(z))
```

    8
    




    int




```python
a = "12"
print(float(a))
type(float(a))
```

    12.0
    




    float




```python
b = "46.8"
float(b)
type(float(b))
```




    float



# 2 
İsimlerden oluşan üç değişkene yaş değerleri atanır. Belirlenen üç değişken birbiriyle karşılaştırma operatörleri ile karşılaştırılır. Bu karşılaştırmalara mantıksal operatörler de eklenir.


```python
Ceyda = 23 
Selin = 11
Sıla = 45 

if Ceyda > Selin :
    print("Selin Ceyda'ya ABLA demelidir.")
if Ceyda < Sıla :
    print("Ceyda Sıla'ya ABLA demelidir.")
if Selin < Sıla :
    print("Selin Sıla'ya ABLA demelidir.")
```

    Selin Ceyda'ya ABLA demelidir.
    Ceyda Sıla'ya ABLA demelidir.
    Selin Sıla'ya ABLA demelidir.
    

# 3
Kullanıcıdan iki değer girmesini istenir. Girilen değerlerin toplama, çıkarma, çarpma, bölme sonuçlarını yazdırılır.


```python
print("Birinci değeri giriniz:")
x = int(input())

print("ikinci değeri giriniz:")
y = int(input())

print("Toplam :", x + y)
print("Çıkarma :", x - y)
print("Çarpma :", x*y)
print("Bölme :", x/y)
```

    Birinci değeri giriniz:
    5
    ikinci değeri giriniz:
    2
    Toplam : 7
    Çıkarma : 3
    Çarpma : 10
    Bölme : 2.5
    

# 4
Kullanıcıdan isim, yaş, şehir ve meslek bilgilerini istenir ve cevaplarını yazdırılır.


```python
print("Adınızı giriniz:")
İsim = str(input())

print("Yaşınızı giriniz:")
Yas = int(input())

print("Yaşadığınız Şehri giriniz:")
Sehir = str(input())
      
print("Mesleğinizi Giriniz:")
Meslek = str(input())



```

    Adınızı giriniz:
    ceyda
    Yaşınızı giriniz:
    23
    Yaşadığınız Şehri giriniz:
    tekirdağ
    Mesleğinizi Giriniz:
    veri bilimci
    

# 5
"Hi-Kod Veri Bilimi Atölyesi" ifadesini bir değişkene tanımlanır.


 1. İfadedeki her bir kelimeyi ("Hi-Kod", "Veri", "Bilimi", "Atölyesi") değişken içinden seçilir. 
 2. İfadeyi hepsini büyük harf olacak hale çevrilir. ("HI-KOD VERİ BİLİMİ ATÖLYESİ") 
 3. İfadeyi hepsini büyük harf olacak hale çevrilir.("hi-kod veri bilimi atölyesi") 

"0123456789" ifadesindeki yalnızca çift sayıları ve yalnızca tek sayıları seçilir. ("02468", "13579")


```python
mesaj = "Hi-Kod Veri Bilimi Atölyesi"

print(mesaj.split())
print(mesaj.upper())
print(mesaj.lower())
```

    ['Hi-Kod', 'Veri', 'Bilimi', 'Atölyesi']
    HI-KOD VERI BILIMI ATÖLYESI
    hi-kod veri bilimi atölyesi
    


```python
sayilar = "0123456789"
cift_sayi = ''.join(sayi for sayi in sayilar if int(sayi) % 2 == 0)
tek_sayi = ''.join(sayi for sayi in sayilar if int(sayi) % 2 != 0)

print(f"Çift Sayilar: {cift_sayi}")
print(f"Tek Sayilar: {tek_sayi}")
```

    Çift Sayilar: 02468
    Tek Sayilar: 13579
    
