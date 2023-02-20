# Whitespace | Etkisiz Boşluk Karakterleri

### C++ Karakter Seti
Her programlama dilinin kendine özgü bir takım karakterleri vardır. Bu karakterler ve ne
anlama geldikleri önceden tanımlanmıştır. Örneğin; * (yıldız) karakteri BASIC dillerinde
sadece çarpma anlamına gelirken, C++'da çarpma işleminin yanı sıra çok daha farklı işlevler
yüklenmiştir. Bu durum diğer karakterler için de geçerli olabilir. Örneğin ^ (şapka) işareti
BASIC dillerinde üs alma anlamına gelirken, C++ için bu karakterin böyle bir anlamı yoktur.
C++'da kullanılabilecek karakterler sınıflandırılmıştır.

| RAKAMLAR |
| :------------- |
| 0 1 2 3 4 5 6 7 8 9 |
| **KÜÇÜK ALFABETİK KARAKTERLER** |
| a b c d e f g h i j k l m n o p q r s t u v w x y x |
| **BÜYÜK ALFABETİK KARAKTERLER** |
| A B C D E F G H I J K L M N O P Q R S T U V W X Y Z |
| **ÖZEL KARAKTERLER** |
| . , ; : ' " + - * / _ = ! ? # $ % & @ < > ( ) { } [ ] \ | ~ ^ |
| **ETKİSİZ BOŞLUK KARAKTERLERİ** |
| \n \t \v \r |
| **DİĞER KARAKTERLER** |
| \a \b \0 \\ \* |

Etkisiz boşluk karakterlerinin ingilizce karşılığı 'whitespace' olup, bu ifade 'beyaz boşluk'
şeklinde Türkçeye çevrilebilir. Etkisiz boşluk karakterlerinin program içinde kullanılıp
kullanılmaması derleyici için farketmez. Ancak bu durum C++'la program yazan bizler için
önemlidir. Yazdığımız programların okunabilirliğinin kolaylaştırılması amacıyla sıkça
kullanacağımız karakterlerin başında etkisiz boşluk karakterleri gelmektedir.

| KARAKTER | ANLAMI | GÖREVİ | 
| ------------- | ------------- |:-------------:|
|\n | Yeni Satır | Bir sonraki satıra geçmek |
|\t | Tab (Sekme) |Bir tab ölçüsünde boşluk bırakmak |
|\v | Dikey Tab | Bir tab ölçüsünde dikey boşluk bırakmak |
|\r | Satır Başı | İmleçi satır başına konumlandırmak |
|\a | Alarm | Uyarı amaçlı bir ses çıkarmak |
|\b | Backspace (Geri Al) | Kendinden önceki karakteri silmek |
|\0 | Null |Karakter dizilerini string haline getirmek |
|\\ | \ karakterini kullanabilmek için \ \ şeklinde yazılır  | (Arada boşluk bırakılmaz) |
|\" | " karakterini kullanabilmek için \ " şeklinde kullanılır | (Arada boşluk bırakılmaz) |
