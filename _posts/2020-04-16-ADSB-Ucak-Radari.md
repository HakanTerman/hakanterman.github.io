---
title: ADS-B Uçak Radarı - Nedir, Nasıl Çalışır ?
tags: [adsb, flightradar, flightaware, radar24, uçak radarı, flightfeeder, radarbox, hava radarı]
header:
  teaser: /assets/images/posts/adsb.jpg
  image: /assets/images/posts/adsb.jpg
  caption: "Fotoğraf Sahibi : [Apichart Meesri](https://500px.com/auimeesri)"
category: Teknoloji
layout: single
permalink: /teknoloji/ADSB-Ucak-Radari/
---

Elektronik cihazlara, bilgisayarlara olan ilgime bağlı olarak kablosuz haberleşen cihazlara da ayrı bir merakım var tabii ki.

Bir süre benim de merak konum olan, doğrusu pek Türkçe kaynak bulamadığım bir konu olan ADS-B konusunu birazcık anlatmak istedim. Konu genel olarak havacılık kategorisine girse de, işin teknik yönü yine bilişim ağı ile destekleniyor ve alanımıza giriyor.

### Neymiş bu ADS-B ?

Öncelikle klasik olarak bu kısaltmanın açılımı ile başlayalım.
**A** utomatic, **D** ependent, **S** urveillance, **B** roadcast kelimelerinin kısaltması olarak oluşan bir terim. İyi de ne demek bunlar;

**A** utomatic : Kendi başına çalışabilen, operatör veya teknik müdehale gerektirmeyen bir sistem
**D** ependent : Birbiri ile bağlantılı verileri işleyebilen
**S** urveillance : Anlık gözetim, radar işlevi görebilen
**B** roadcast : Yayın yapabilen

şeklinde kolay anlaşılabilecek bir biçimde özetleyelim.

Genel olarak bu sistem havacılıkta 2500feet üzeri uçan cisimlerin yeryüzünden kontrol edilebilmesi için kullanılmaktadır. Yolcu uçaklarının hangi saatte kalktığını ve hangi saatte iniş yapacağını, hatta daha detaylı olarak flightradar24.com gibi siteler üzerinden ne zaman nerede olduğumunu takip edebiliyoruz ya, işte o takip olayının arkasında bu ADS-B sinyalleri ve alıcıları var.

### Nasıl Çalışıyor ?

GPS sistemlerini hepimiz biliyor olmalıyız, hepimizin hayatına elimizdeki akıllı telefonlarla girdi bu sistem. Konum atıyoruz ya hani. İşte o konumu elimizdeki cihaz gökyüzündeki GPS uydularına bağlanarak buluyor. Dünya çevresinde 24 aktif GPS uydusu var olduğu, ve sistemin en az 3 uydu görüldüğünde sağlıklı çalışıyor olduğu bilgisini de burada ek bilgi olarak verelim. Daha sonra bir başlıkta uzuun uzun GPS'i de inceleyebiliriz.

ADS-B vericisine sahip olan uçaklar GPS uyduları aracılığı ile buldukları konum bilgilerine, hız, rota gibi ek bilgiler ekleyerek bu bilgilerin tamamını 1090Mhz frekansında yer yüzü istasyonları ile paylaşıyorlar.

Eğer bu yazıyı halen okumaya devam ediyorsanız daha önce FlightRadar24 - FlightAware gibi servisler ile uçak takibi yapmışsınızdır diye tahmin ediyorum. O siteler bu uçak verilerini havalimanındaki kulelerden ya da resmi bir kurumdan almıyorlar, bu ADS-B alıcıları ile kendileri toplayıp eşzamanlı hale getirerek yayına açıyorlar. ADS-B sinyalleri öyle gizli saklı, kimsenin ulaşamayacağı veriler de değil, tüm dünya üzerinden tepenizden geçen yolcu uçaklarını açık şekilde izlemenize imkan var.

Olayı görsel olarak anlatmak istersek airkule.com sitesinden alıntı olarak şu görsel özetleyecektir.
(http://www.airkule.com/images/image/ADS-B-takip-izleme05.jpg)
([Teknik Detaylar İçin Kaynak](http://www.airkule.com/yazar/ADS-B-ILE-GELECEGIN-PILOTSUZ-UCAK-TEKNOLOJISI/1229))

### Ne için kullanılıyor ?

Önceliklik olarak hava trafiğini kontrol etmek, hataları minimuma indirmek gibi amaçları var. 2007 yılı sonrası üretilen her türlü hava aracında bu verici bulunurken 2017'den itibaren sadece kendi konumunu paylaştığı verici değil, aynı zamanda diğer araçları takip edebildiği alıcı da bulunmakta. (Bunu zaten üzerindeki radar ile yapabiliyor diye biliyorum ama ADS-B ile daha detaylı bilgilere erişim mevcut, radar havadaki tüm cisimleri görürken, ADS-B uçakları görüp aynı zamanda detay da aktarmakta)

Tabi amaç sadece hava araçlarının konumunu görüp bilgi amaçlı paylaşım yapmak değil. Ticari boyutu da var. İnsansız hava araçları gelişiminde büyük pay oynayan bu sistem ile otomatik olarak rota takibi yapan hava araçları yapılabilmekte. Ülkemizde de bu alanda "Baykar Savunma" adından oldukça söz ettiriyor.

Uçaklarda dahili donanım olarak bulunan çarpışma önleyici sistem (TCAS) gibi hayati önem taşıyan fonkiyonların temeli olarak da yine bu teknoloji yer almakta.

Sanıldığının aksine, elle kapatılabilen bir fonksiyon değildir. Yerden yükselen her türlü hava taşıtında açık kalması gereklilik olduğu kadar mecburidir. Ayrıca pilotun "sivil ve ticari hava taşımacılığında uçağında bulunan ADS-B cihazını kapaması mümkün değildir. Kokpitte hiçbir sigortası veya anahtarı bulunmaz." diye belirtilmekte ancak kapatıldığı yönünde haberler okumak da mümkün.

### Nereden İnceleyebiliriz ?

Flightradar24.com ya da FlightAware.com siteleri üzerinden dünya üzerindeki tüm hava taşıtlarını görebilirsiniz. Haritalara baktığımızda yoğunluğun en çok Amerika kıtasında olduğunu görebilmek açıkca mümkün. Bunun sebebi olarak ise "1 Eylül 2017 itibarıyla, kurallara uygun Otomatik Bağımlı Gözetim-Yayın (ADS-B) Out ekipmanı ABD'de uçan tek motorlu 40 binden fazla uçağa monte edilmiştir. Yani ABD hava sahasında uçuyorsanız, Tek motorlu uçağınız olsa dahi ADS-B takmanız şart." bilgisini gösterebiliriz.

### Bu Siteler Tüm Dünyayı Nasıl İzliyor ?

Elbette tek bir ADS-B anteni ile tüm dünyadaki uçakları izlemeniz mümkün değil. Bir anten yatayda en uzak 250 mil / 400km mesafesindeki uçuşları görüntüleyebiliyor. Bunun için dünyanın bir çok yerine ADS-B alıcıları kurmak gerekiyor ki bu siteler de o şekilde yapıyor. Tamamen gönüllülük esası ile yaptıkları bu sistemler ile tüm dünyada Flightradar'ın sayısını açıklamadığı on binlerce gönüllü veri sağlayıcısı (https://www.flightradar24.com/share-statistics)  ve FlightAware'ın 202 ülkeden 27.139 veri sağlayıcısı (https://flightaware.com/adsb/stats/) olduğunu görebiliyoruz. Siz de kendi yaptığınız alıcınızı bu sistemlerden birine bağlayabilirsiniz.

### ADS-B Alıcısına Sahip Olabilir Miyiz ?

Evet, eğer havacılık merakınız varsa ya da uçuş bilgilerini takip etmekten hoşlanıyorsanız ve biraz yazılım ve elektronik bilginiz varsa bu tarz bir cihazı evde yapabilir ve uçuş bilgilerini takip edebilirsiniz.

Bir Raspberry Pi3 ve ADS-B anteni ile kolay bir şekilde kendi alıcınızı yapmanız mümkün. Ancak takip sistemi için bir altyapıya ihtiyacınız var ve mevcut takip sistemlerinin bir tanesine dahil olmanız daha kolay şekilde anten oluşturmanıza olanak sağlayacak. Eğer FlightRadar24 sistemine dahil olup oraya veri gönderecek şekilde bir alıcı yapmak isterseniz onların sistemini Raspberry'nize kurabilirsiniz. (https://www.flightradar24.com/share-your-data)
Eğer FlightAware ile çalışmak isterseniz de (https://flightaware.com/adsb/piaware/build) yardım alabilirsiniz. Flightaware Türkçe ve gayet detaylı anlatımı ile de öne çıkıyor.
Kendi radarım olsun, kimseyle bir şey paylaşmak istemiyorum derseniz o konuda pek bir döküman yok elimde ancak bu kadar bencilliğiniz varsa, bunu yapmaya yetecek yabancı diliniz ve programlama bilginiz de olmalı bana göre.

Bunların haricinde, eğer gönüllülük hizmetlerine bağlılığınız var ise, bu firmaların cihaz gönderim sistemleri de mevcut. Piyasa değeri yaklaşık 500$ civarı olan bu radar cihazını, söküp parçalamamak, amacı dışında kullanmamak ve sürekli aktif tutmak şartı ile size gönderebiliyorlar. Bu şekilde kendilerine bilgi sağladığınız takdirde sitelerinden size premium hesap tahsisi de yapmayı unutmuyorlar elbette. flightaware sitesinde uçuş takip günlüğünü görüntülerken, FlightFeeder'ınızın katkıda bulunduğu uçak konumlarını görme imkânınız da var. Ayrıca cihaza yerel IP numarası ile SkyView arayüzüne ulaşıp internete ihtiyaç duymadan radarın algıladığı tüm uçuşları görebilmeniz gibi bir şansınız da oluşuyor. Amaç dışı kullanımlarda seri numarası ile uzaktan erişim sağlamaya çalışıyorlar gibi bir söylenti de mevcut tabii ki.

FlightAware'den bir FlightFeeder cihazı talep etmek isterseniz, [şu adresten](https://tr.flightaware.com/adsb/request) başvuru yapabilirsiniz. Aynı cihazı Flightradar24 için talep etmek isterseniz de [şu adresten](https://www.flightradar24.com/apply-for-receiver) başvuru yapabilirsiniz.

Ürün tamamen yurt dışından geldiği için gümrükte takılı kalma gibi durumlar yaşayabiliyorsunuz, yazılı iletişim becerisi ve gerekli evrakların iletilmesi ile bu sorunu da aşmak mümkün. Şahıs adına gelen gönderilerde vergi minimumdan çıkıyor ancak ticari şirket adına istediyseniz gümrük pakete el koyabiliyor.

Ben de bir süredir bu tarz cihazlardan bir tanesine sahibim. Kurulu ve çalışıyor, hem kişisel incelemelerim hem de bağlı bulunduğu siteye bilgi aktarımı yapmaya devam ediyor. Paket içeriğinde bana bir tane de "FlightAware tişörtü" göndermişler, çok sağolsunlar. :)

Kurulumu çok basit, cihazı wireless ya da ethernet aracılığı ile modeminize bağlıyorsunuz, kutu içeriğinden çıkan anteni evinizin çatısına çevresi açık bir alana sabitleyip kablo ile cihaza bağlantı yapıyorsunuz ve veri aktarımı başlıyor.

Şu tarihlerde Koronavirüs salgını sebebi ile ülkemiz hava sahası neredeyse boş olduğu için çok fazla uçuş izleyemiyor olsam da, normal uçuş dönemlerinde radarıma en az 30 civarı uçuş takılıyordu anlık olarak. Coğrafi konumum sebebi ile Marmara Ege ve Akdeniz'deki hemen hemen tüm uçuşlara hakimim.

Şu şekilde de SkyView ekranımdan bir anlık ekran görüntüsü iliştireyim buraya.

![ADSB-Radar](/assets/images/posts/yazi/radar.jpg)

ADS-B konusunu, en azından merak edilen kısımları ile elimden geldiğince anlatmaya çalıştım, sormak istediğiniz her şey için yorumlardan ulaşabilirsiniz. Görüşmek üzere !
