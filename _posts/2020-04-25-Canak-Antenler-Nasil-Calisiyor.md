---
title: Çanak Antenler ve Uydu Sistemleri - Nedir, Nasıl Çalışır ?
tags: [canakanten, canak anten, uydu anteni, uydu alici, satellite, satellite disk]
header:
  teaser: /assets/images/posts/canakanten.jpg
  image: /assets/images/posts/canakanten.jpg
  caption: "Fotoğraf Sahibi : [Hakan Terman](https://hakanterman.com)"
category: Teknoloji
layout: single
permalink: /teknoloji/Canak-Antenler-Nasil-Calisiyor/
---

Çanak antenler, hani hepimizin evinde bahçede balkonda çatıda bir yerlerde olan, garip görünüşlü, bozulunca bir çoğumuzun kendisi ayarlayamayıp tamirci çağırdığı o metal yuvarlaklar. Hiç merak ettiniz mi, bu nasıl çalışıyor, boşluğa bakan bu cihazın içinden o televizyon kanallarının görüntüleri nasıl geçiyor diye.

Doğduğum yıllardan bu güne bizim evde var olan bu sisteme babamın ilgisi olması doğrultusunda ben de oldukça ilgiliyim. Türkiye'de 2000'li yıllardan itibaren oldukça yayınlaştı, hatta öyle ki şuan dijital yayın izlemeyen ev yok diyebiliriz. Daha önceleri karasal antenler ile belediyelerin vericilerinden kanallar izliyordu insanlar. En fazla 14-15 kanal olurdu, hani şu çekmeyinca karıncaları izlediğimiz sistemler..

### Nedir bu Çanak Anten ?

Dünyadan yaklaşık 35.700km kadar yukarıda bulunan yaklaşık 1300+ ün üzerinde yapay haberleşme uydularından dünyaya gelen sinyalleri toplamak için kullandığımız oval ve genellikle metal türevi malzemeden yapılan bir araç diyebiliriz.

Bu araç, yukarıdaki uydudan aldığı sinyali önündeki **LNB (Low Noise Block)** isimli, elektronik bir devre içeren cihaz yardımı ile evdeki uydu cihazına gönderiyor.

## LNB'de Ne ?

Şu uydu çanağının ortasına takılan şeyin ismi işte. Açılımı da şöyle "Low Noise Block downconverter". Mikrodalga kafa, düşük gürültülü konverter. Çanak anten uydudan gelen yayını odak noktasına toplar, bu cihaz da toplanmış olan bu mikrodalga (2-50GHz) sinyali güçlendirip, üzerinde elektronik işlemlerin daha rahat yapılabileceği daha alt bir frekans bandına (1-2GHz) dönüştürür. Esas olarak üç ana kısmı bulunur. Besleme ağzı(feed) , yükseltici(amplifier), ve alt frekansa dönüştürücü(converter).

### Boyutları Ne Fark Ediyor ?

Çanak antenlerin boyutlarının işlevlerine etkisi var :p Şimdi şöyle, dünya üzerinde sadece kendi ülkemize ait uyduları seyretmiyoruz elbette, eğer istersek antenimizi farklı uydulara odaklayıp o uyduda yayın yapan yayınları da izleme şansımız var. Türkiye'den hemen hemen 50 Derece Doğu ile 30 Derece Batı uyduları arasındaki dağılımı ülkemizin üzerinden geçen sinyalleri teknik olarak sorunsuz alabilmemiz mümkün. Ancak bazı uyduların sinyalleri bulunduğumuz coğrafi konuma birazcık uzaktan, ya da çok uzaktan geçebiliyor. Uydu merkez yayınını verdiği konumlara çok güçlü yayın (54 dBW) verirken etrafına doğru bu sinyalin gücü gittikçe azalıyor. Anten olarak kıyaslayacak olursak 54 dBW gücündeki bir yayın 45cm çapındaki bir çanak anten ile bile izlenirken yayın kalitesi 50 dBW olduğunda 60cm çapında bir çanak anten gerekebiliyor. Sinyaller merkez odaktan uaklaştıkça dağılmaya başlıyor ve bu dağılımı toplamak için daha büyük anten gereksinimi doğuyor. Eğer ülkenize yayın vermeyen bir uyduyu izlemek istiyorsanız 2metre çapındaki bir anten bile size yeterli gelmeyebiliyor.

![Turksat3A Sinyal](https://www.turksat.com.tr/sites/all/themes/turksat/images/UyduKapsama/T3ABati.png)

### Uydu Sinyali Derken ?

Dünyanın etrafında sadece haberleşme maksatlı 1300'e yakın uydu varken, askeri-navigasyon-gözlem-uzay-meteoroloji gibi alanların uydularını da sayarsak aktif olan 3000'e yakın uydu var. Tabi bunlara ek olarak ömrünü (15-25 yıl) görevini tamamlamış olan mezarlık yörüngesine çekilerek terk edilmiş binlercesi daha var. [Şu](http://www.celestrak.com/satcat/boxscore.php) kaynağa göre uzayda toplamda 45bin gibi bir uydudan bahsediliyor. Sanırım sadece dünyayı değil, oraları da çöplüğe çeviriyoruz.

Dünya üzerinde belirli üslerden fırlatılan bu uydular uzunca bir yolculuktan sonra yörüngesine oturtuluyor ve test sinyalleri göndermeye başlıyor. Yeryüzünde bu uyduların kontrolü için görevlendirilen kontrol merkezleri tarafından kontrol edilerek uzaktan her türlü müdehale yapılabiliyor.

Bu uyduların gönderdiği sinyaller dünyanın her yerinde bizlere çarpıyor haliyle :)

![Dünya Etrafındaki Uydular](https://i.sozcu.com.tr/wp-content/uploads/2015/12/24/pace-junk.jpg)

### Bu Görüntüler Nasıl Geliyor ?

Bu uydulara çanak antenler aracılığı ile bağlanıp sinyal aldığımız gibi, yetkili kişiler aynı mantığın tam tersi ile çanak antenler ile yayın da gönderebiliyor. Bu şekilde dünyanın herhangi bir yerinde olan bir olayı uyduya gönderip, yine aynı uydu üzerinden bizim izlememiz sağlanıyor. Bu olay doğrudan gerçekleşmiyor tabi, o görüntüler bir kaç yerden dolaşıyor elbette.

Şimdi bir futbol maçını örnek verecek olursak, stadyumda çekim yapan 8 tane kamera bir yayın odasına bağlanıyor. Yayın odasındaki yetkili kişi maçın akışına göre hangi kamerayı ekrana vereceği yönünde ayarlamaları yapıyor ve çıktıyı ham yayın olarak [uplink aracı](http://) ile uyduya gönderiyor.(önce görüntü otuz altı bin kilometre gidip uyduya ulaşıyor) Bu yayına feed deniyor ve sadece kanal yetkilileri görebiliyor.(yayın burada otuz altı bin kilometre geri gelerek kanala ulaşıyor) Feed yayın, ilgili yayıncı kuruluş tarafından logo ve altyazı, seslendirme gibi eklemeler yapılarak kanal üzerinden tekrar yayına veriliyor.(görüntü tekrar otuz altı bin kilometre gidip uyduya ulaşıyor) ve biz bahçemizde, balkonumuzda veya çatımızda bulunan çanak anten ile o yayını uydudan alıp (son otuz altı bin kilometrelik yolculuğu) televizyonumuzun ekranından izliyoruz. Bunca işlem bir kaç saniye milisaniye oluyor ve biz o golü atıldığı anda ekranımızda görüyoruz. Peki onca işlemde hiç mi gecikme yok, teknik olarak saniyenin yarısı, hatta çeyreği kadar belki ancak bu kesinlikle fark edilebilecek düzeyde değil.

### Nasıl bir şey bu uydu ? Nereden Fırlatılıyor ?

Yaklaşık olarak 5000 kilogram civarında bir ağırlığı olan standart şekli ile küp şeklinde olan ve uzay boşluğunda kanatlarını açarak yer alan bir cihazdan bahsediyoruz.

![Haberleşme Uydusu](https://i2.milimaj.com/i/milliyet/75/0x410/5c8e4f7445d2a07c10486a9e.jpg)

Fırlatma rampası olarak dünya üzerine belli başlı yerler mevcut. Genel olarak Avrupa ülkelerine ait uydular Fransız Guyanası'nda bulunan Kourou şehrindeki Avrupa Uzay Ajansına ait "Guiana Space Centre" isimli üsten fırlatılıyor.
Ülkemize ait Turksat 1A(Başarısız)-1B-1C-2A-3A uyduları da bu üsten uzaya gönderildi. Bunun dılında popüler olan bir diğer fırlatma noktası da "Baykonur Uzay Üssü" olarak bilinen, şuan Kazakistan'a ait olan ancak daha önce Sovyetler'in kullandığı hatta dünyanın ilk haberleşme uydusu Sputnik-1 'in fırlatıldığı üstür.
Yine ülkemize ait olan Turksat 4A-4B uyduları da bu üsten fırlatılmış olup şuanda yörüngesindedir.

![Fransız Guyanası](https://www.marcodilauro.com/wp-content/uploads/2015/09/MDL_GUYANNE001-1024x683.jpg)

Uzaya uydu gönderirken uydu maliyetine yakın olarak roket maliyeti de oldukça yüksek miktarlarda olduğu için fırlatmanın kesinlikle çok dikkatli ve profesyonel şekilde yapılması gerekmektedir. Bu yüzden fırlatma başarılarına bakılarak olsa gerek bu üsler kullanılıyor.

Genel olarak kullanılan bu üslere ek olarak dünya üzerinde bir çok uzay üssü de mevcut elbette. Ancak son zamanlarda piyasada oldukça isminden söz ettiren "Elon Musk" ve şirketi "SpaceX" 'e ait Falkon roketleri bu dengeyi oldukça değiştirecek ve fırlatıldıktan sonra geri dönen ve tekrar kullanılabilen fırlatma roketleri sayesinde daha ekonomik çalışabilmekte. Önümüzdeki yılların uydu işlerini tamamen devralacak gibi duruyor. Öyle ki [burada](https://en.wikipedia.org/wiki/T%C3%BCrksat_(satellite)) ülkemize ait planlanan Türksat 5A ve 6A uydularının da Amerika Birleşik Devletleri'nin Florida eyaletinde bulunan "Cape Canaveral Uzay Üssü" nden SpaceX'e ait Falcon9 roketi ile fırlatılacağı bilgisi yer almakta.

<iframe src="https://www.youtube.com/embed/sX1Y2JMK6g8" width="600" height="350" allowfullscreen></iframe>

### Aynı Anda Kaç Uydu İzleyebiliriz ?

Aslında bu sorunun net bir cevabı yok, ama tek uydu izlemek gibi bir kısıtlamanız da yok. Çanak anten sayınıza göre istediğiniz kadar yabancı uyduyu sinyal aldığınız sürece aynı anda izleme imkanınız bulunuyor. Birden fazla uydu izlemek için motorlu anten dediğimiz televizyonunuzun kumandası ile anteni hareket ettirebildiğiniz sistemlerden kullanabilirsiniz ya da sabit birden fazla anten de kullanabilirsiniz. Ben şuanda evimin bahçesinde bulunan 10 tane çanak anten ile 10 farklı uydudan yaklaşık 6000'in üzerinde kanal izlemekteyim.

Bu kadar anteni tek bir uydu cihazına nasıl bağlıyoruz diye sorarsanız ? Disecq ismi verilen küçük aparatlar aracılığı ile aynı anda 4 veya 8 anteni tek uydu cihazına doğrudan bağlama imkanınız var. Eğer bana 8 yetmiyor diyorsanız, Disecq'ler arasında köprüleme yaparak bu sayıyı 32'ye kadar çıkarabilme imkanınız var. E zaten 32'tane sabit anten sahibi olmak mantığınıza yatsa bile, fiziksel olarak o kadar anteni bir araya getirmeniz için çok büyük bir araziye ihtiyacınız olmalı :)

Sanırım bu kadar bilgi yeterli, baya baya uzun anlattığımı düşünüyorum. Aklınıza takılan, ya da bu konuda yapabileceğim her türlü şey için bana çeşili iletişim kanalları ile ulaşabilirsiniz. Görüşürüzz!

![Antenlerim](/assets/images/posts/yazi/canak.jpg)
