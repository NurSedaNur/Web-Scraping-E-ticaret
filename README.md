# Web-Scraping-E-ticarett-PYTHON-ANGULAR
 Web-Scraping-E-ticaret-PYTHON-ANGULAR
 
Projeye ait detaylı bilgiye rapor(1).pdf dosyasından ulaşabilirsiniz.

İSTERLER:
Trendyol, Hepsiburada, n11, Amazon, gibi e ticaret sitelerinden istenilen ürüne ait bilgilerin yer aldığı
bir veritabanı oluşturulacak ve bu veritabanından istenilen bilgileri web sayfası üzerinde gösterilecektir.
Amaç:
1. Web scraping ile farklı alışveriş sitelerinden istenilen ürün hakkında bilgi elde etmek.
2. Bir uygulama içerisinde istenilen özellikteki ürünlerin filtrelenmesi ve sıralanması becerisini
geliştirmek,
3. Dinamik özelliklere sahip bir program geliştirmek
4. Web kodlama hakkında bilgi ve beceriye sahip olmak 

• Giriş
Bu projede bizden istenen Trendyol,
Hepsiburada, n11, Amazon, gibi e ticaret
sitelerinden istenilen ürüne ait bilgilerin yer
aldığı bir veritabanı oluşturmamız ve bu
veritabanından istenilen bilgileri web sayfası
üzerinde göstermizdir.
Trendyol, Hepsiburada, n11, Amazon siteleri
üzerinden web scraping kullanılarak
bilgisayar(notebook) kategorisine ait bilgiler
almamız istenmiştir. Ayrıca E-ticaret sitelerine
benzer yapıda kendimiz bir web sitesi oluşturup
(sadece bilgisayar(notebook) kategorisi olacak)
ve web scraping kullanarak sitedeki bilgileri
almamız istenmiştir. Web scraping ile elde
ettiğimiz verileri veritabanına kaydetmemiz
istenmiştir. Scraping ile çekilen bilgilerin
güncellenmesi gerekmektedir. Güncel bilgileri
veritabanında kaydetmemiz istenmiştir. Farklı
sitelerden çekilen ürün bilgilerinin gösterilmesi
için bir web sayfası oluşturmamız istenmiştir.
Bu sayfa ilk açıldığında veritabanında yer alan
tüm kayıtlar listelenmelidir. Web sayfasından
herhangi bir ürünle ilgili dinamik arama işlemi
yapması istenmiştir.Web sayfasında en düşük
fiyattan en yüksek fiyata, en yüksek fiyattan en
düşük fiyata ve en yüksek puandan en düşük
fiyata şeklinde sıralama işlemlerinin de
yapılabilmesi istenmiştir.

• İlerleyiş ve Yöntem
1. Başlamadan Önce
Bu projeye başlamadan önce proje
dokümanında verilen bilgileri derleyip
kullanabileceğimiz metodları araştırdık.
Kütüphaneden ve internet üzerinden
yararlanabileceğimi kaynakları araştırdık. Web
scraping hakkında bilgi edindik.Web scraping
ile elde ettiğimiz verileri kaydetmek için
veritabanı hakkında bilgi edindik.
Kullandığımız MongoDB veritabanı hakkında
araştırma yaptık ve bilgi edindik. Farklı
sitelerden çekilen ürün bilgilerinin gösterilmesi
için bir web sayfası oluşturmamız istenmişti.
Web sayfası oluşturma hakkında bilgi
edindik.Web scraping yaparken python dilini
kullandık.Ayrıca web sitesi için angular
programlama kulandık.
2. Başlangıç
Öncelikle python programlama dili hakkında
eğitim aldık. Sonrasında Trendyol , Hepsiburada
, N11, Vatan sitelerinden bilgisayar
(notebook)kategorisinde web scraping ile
bizden istenen özellikleri(marka,model
adı,model no,işletim sistemi,işlemci
nesli,ram,disk boyutu,ekran
boyutu,puanı,fiyatı,site ismi) elde ettik.
Çektiğimiz verileri bir veritabanına attık.
Mongodb database ini kullandık.MongoDB en
basit tanımlamayla, açık kaynak kodlu bir
NoSQL (Not only SQL) veri tabanı
uygulamasıdır
Sonrasında Angular ile bir
 web sitesi oluşturduk.
 Components lerin içinde ts
 kodları,html kodları,css
 kodları bulunmakta.
 Web sitesini oluşturduktan
 sonra web scraping ile 4
 tane E-Ticaret sitesinden
 aldığımız bilgileri
 MongoDB’ye aktardık.
 MongoDB’de
 Trendyol ,Vatan,N11,
 Hepsiburada sitelerinden
 aldığımız bilgileri tek bir
 sayfada listeledik ve bu
 sayfalar içerisinde sql sorguları yaptık. En son
bir Json dosyası elde ettik ve bu dosyayı
dinamik bir yapı oluşturmak için web
sitemize( db.json adlı dosya) aktardık.
Dosyamızın aktarıldığından emin olmak için
Postman uygulamasında test ettik.postman de
testi aktarmak için komut sisteminde db.json
adlı dosyamızı çalıştırmamız gerekmekte.
Verilerin doğru bir şekilde geldiğini kontrol
ettik. komut sistemi web sitesinde verilerin
görünmesi için her zaman açık kalmalıdır
aksi taktirde web sayfanızda ürün bulunamadı
yazmaktadır.
sistemer herkes kayıt olabilirken
yanlızca admin giriş yapıp ürün ekleme\ silme\
güncelleme yapalilmektedir.

 
