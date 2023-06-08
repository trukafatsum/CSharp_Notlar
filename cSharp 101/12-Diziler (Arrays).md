# C# Notları (Diziler)

[TOC]



## Dizi nedir?

> Dizi (Array) : Tek bir değişken altında birden fazla "aynı türde" değeri toplamamızı sağlayan veri kümelerine dizi denmektedir.
>
> ```csharp
> int ogrenci1 = 20;
> int ogrenci2 = 23;
> int ogrenci3 = 25;
> ```
>
> * Diziler içerisinde birden fazla aynı türde değer tutabilen yapılardır.
>
> * Prosedürel programlamanın temel veri kümeleridir. Yani yazılımsal boyutta, yazılım adına RAM'de birden fazla değeri, tek bir değişken altında bir veri kümesi halinde tutabilirler.
>
> * Diziler veri kümeleri oldukları için, içlerindeki birden fazla veri üzerinde kümesel işlemler yapmamızı sağlayabilirler.
>
> * Diziler, prosedürel programlamanın temel yapıları oldukları için daha gelişmiş yapılar olan koleksiyonlarında temelini teşkil etmektedirler ve gelişmelerine katkıda bulunmaktadırlar.
>
> * *Diziler referans türlü değerlerdir. Yani nesnel yapılardır, özlerinde classtırlar.*
>
> * Yapısal olarak RAM'de Heap'te tutulurlar.
>
>   > Kritik
>   >
>   > Dizi içerisine her türlü değer koyulabilir. (Değer türlü-Referans türlü)
>   >
>   > Bir dizi sadece tek bir türde değer alabilir.
>   >
>   > Dizi içerisine koyulan değerler işlevsel olarak aynı mahiyette olmalıdır. 
>   >
>   > Örneğin; yas dizisine, maas bilgisi aynı türde olduğu halde verilmemelidir.
>
>   * Diziler içerisine eleman/değer eklendikçe bunları düzenli bir şekilde, sıralı depolayacaktır.
>
>   * Dizilerde eklenen elemanlar index ismini verdiğimiz numaralarla, ardışık bir şekilde numaralandırlırlar.
>
>   Index no : Her bir elemana verilen ardışık sayı, 0'dan başlar n-1'e kadar gider.
>
> > Prototip
> >
> > ```csharp
> > // type a; -->Değişken
> > // type []a -->Dizi
> > 
> > /*
> > [] operatörü : Bir değişken tanımlanırken türünün yanına bu operatörü koyarsak o değişken o türde bir dizi değişkeni olacaktır. Bu operatöre INDEXER ismi verilmektedir.
> > */
> > 
> > type[] name = new type[...]; //... Bu dizinin alacağı eleman sayısını buraya bildiriyoruz.
> > ```
> >
> > * Buradaki new keywordu, bir dizi nesnesi oluşturmamızı sağlar,
> >
> >   OOP'de detayları ile inceleyeceğiz.
> >
> > 
>
> 



## Dizi Tanımlama

### Tanımlanmış Diziye Değer Atama

### Tanımlanmış Diziden Değer Okuma

### Tanımlanmış Dizi İçerisinde Döngüyle Dönme

#### Kritik 1

### Dizilerin Sınırlılıkları ve Koleksiyon Yapılarının Doğuşu

### Dizi Tanımlama Varyasyonları

#### Varyasyon 1

#### Varyasyon 2

#### Varyasyon 3

#### Varyasyon 4

#### Varyasyon 5

## Array Sınıfı

### Bir Dizinin Kendi Türünde Tanımlanmasıyla Array Türünde Tanımlanması Arasındaki Fark Nedir?

### Array Türünden Dizilere Değer Atama/Okuma

### Metotlar

#### Clear

#### Copy

#### IndexOf

#### Reverse

#### Sort

#### Özellikler

#### IsReadOnly

#### IsFixedSize

#### Length

#### Rank

#### CreateInstance Metodu ile Dizi Tanımlama

#### Çok Boyutlu Dizi Tanımlama

#### Ranges and Indices

#### System.Index

##### İnceleme

#### System.Range

##### İnceleme 1

##### İnceleme 2

#### .. Operatörü

##### İnceleme

#### ^ Operatörü

##### İnceleme

## Çok Boyutlu Diziler

### Tanımlanmış Çok Boyutlu Diziye Değer Atama

### Çok Boyutlu Dizilerde Değer Atama Farklı Varyasyonu

### Çok Boyutlu Dizilerden Değer  Okuma

### Dizinin Derecesini Öğrenme (Rank Özelliği)

### Çok Boyutlu Dizilerin Eleman Sayısını Hesaplama

### Çok Boyutlu Dizilerin Belirli Bir Derecesinin Eleman Sayısını Hesaplama

### Çok Boyutlu Dizilerdeki Verileri İç İçe Döngülerle Ekrana Yazdırma

## Düzensiz Diziler

### Düzensiz Dizi Tanımlama

### Değer Atama/Değer Okuma

### Eleman Sayısını Öğrenme

### Düzensiz Dizilerde İç İçe Döngülerle Çalışma

