---
title: SSTV Nedir ? ARISS SSTV Sertifikaları Nasıl Alınır ?
tags: [amatortelsiz, amatör telsiz, uzay istasyonundan resim almak, iss, sstv, iss sstv, ariss sstv, sstv sertifikası, sstv nedir, ariss sertifikasi, sstv decode, iss takip, iss detector, rxsstv, iss pd120, amsat]
header:
  teaser: /assets/images/posts/sstv.jpg
  image: /assets/images/posts/sstv.jpg
  caption: "Fotoğraf Sahibi : [YO8TNB](https://www.youtube.com/watch?v=GcxvAyEt7Fo)"
category: Teknoloji
layout: single
toc: true
permalink: /teknoloji/SSTV-Nedir-ARISS-SSTV-Sertifikalari/
---

# SSTV Nedir ?

SSTV, uzun haliyle "Slow Scan Television" yani Türkçe'ye "Yavaş Taramalı Televizyon" olarak çevirebileceğimiz bir veri aktarım metodudur. Verici tarafından RF sinyali olarak gönderilen kodlanmış sesleri bir çözücü (decoder) program kullanarak görsel hale getirmemize imkan sunar. El telsizlerimizle bile alabileceğimiz VHF/UHF sinyalleri üzerinden başka bir bağlantıya ihtiyacımız olmadan resim gönderip, resim alabilme imkanı sunar. İlk duyduğumda bana da oldukça ilginç gelmişti, hadi canım ses ile resim mi gönderilir diyebilirsiniz. Evet gönderiliyor.

![SSTV](/assets/images/sstv/iss-sstv1-290121.jpg)

# Ariss SSTV Etkinlikleri

SSTV sistemine en kolay şekilde erişim ve test yapma şansı Uluslarası Uzay İstasyonu (ISS) ile mümkün. Bazı dernekler yerel olarak da bu tarz etkinlikler düzenliyor olsa da ISS'in bu konudaki en büyük avantajı tüm dünyadan erişilebilir olması. ARISS bu sistemin ve ISS'deki amatör rölenin genel adı, Uluslarası Uzay İstasyonundaki Amatör Radyo Sistemi anlamında kullanılan bir isim.

ARISS SSTV Etkinliklerini takip edebileceğimiz en doğru kaynaklardan birisi de kendilerinin kullandığı [twitter hesabı](https://twitter.com/ARISS_status). Bu adreste SSTV planlamaları yapıldığında başlangıcından günler öncesinde duyruluyor. Bu yazıyı yazmaya başladığım günlerde ISS-MAI SSTV Etkinlikleri vardı, ancak ben yazıyı tamamlayana kadar sona erdi. Aldığım sertifikamı da yazı içinde bulabilirsiniz :)

# Peki Ne İşe Yarıyor ?

Aslında CW gibi, sesli iletişim gibi bir görüşme türü. Ancak biraz zahmetli ve uzun süreçli olduğu için ISS gibi vericilerden gönderilen görseller genel olarak etkinlik olarak sunuluyor ve bu etkinlik sonucunda toplanan görselleri onaylayan kuruluşlara gönderip karşılığında sertifika alabiliyorsunuz. Bir amatör telsizci için QSL kart ve Sertifikalar yaptığı işi kanıtlayan ve takdir belgeler niteliğinde olduğu için oldukça değerli elbette.

# Nasıl Yapıyoruz ?

## ISS için ;

Öncelikle ISS'in bölgemizden geçişini takip etmek için telefonumuza AppStore ya da Google Play üzerinden ISS Detector ya da W1ANT Uygulamalarından birini indiriyoruz. Ben arayüzüne alıştığım için ve kullanım kolaylığı olduğu için ISS Detector uygulamasını kullanıyorum.

ISS Detector'u Android telefonunuza indirdiğinizde ayarlarına girip, amatör uydular seçeneğini aktifleştirmeniz gerekiyor. Bunun karşılığında sizden reklam izlemenizi isteyecek, ve her 4 günde bir sefer reklam izleyip uygulamayı ücretsiz kullanabilirsiniz ya da isterseniz çok cüzi bir ücret karşılığında uygulamayı satın alabiliyorsunuz.

Amatör radyoları açtıktan sonra uydular kısmından ISS'i işaretlemeniz ve %10 üzeri görüşlere ayarlamanız yeterli. Aşağıda gördüğünüz gibi tüm geçişler listelenecektir. Gözle görülebilen geçişlerin karşısında göz işareti mevcut, ayrıca Mag değeri de parlaklığı temsil ediyor.

![ISS-Detector](https://cdn.webtekno.com/custom/images/123145/tr-android-iss-detector-satellite-tracker-5.jpg)
* Görsel : WebTekno

Buradan gördüğümüz uygun bir geçiş saatinde elimizde telsizimiz ile dışarıya çıkıyoruz frekansımızı 145.800 Tonsuz olarak ayarlıyoruz ve yine uygulamanın gösterdiği yöne göre telsizimizi doğrultup ses almayı bekliyoruz. ISS gökyüzünde geçişini tamamladığı süre boyunca telsizden tiz ve sanki yankı yapıyormuşcasına bir ses gelmesi gerekiyor.

Sesi tam olarak anlatmam mümkün değil ama şu video ile örnekleyebilirim :

<iframe width="560" height="315" src="https://www.youtube.com/embed/BKlpueYWvKc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Sesi cep telefonuzdaki ses kaydedici uygulama ile kaydedip evde bilgisayarınızda çözmeniz tavsiyemdir. Telsizinizin ses kayıt özelliği varsa eğer onu da kullanabilirsiniz, ya da açık alandaysanız doğrudan da bilgisayarınıza dinletebilirsiniz. Ancak her türlü kesilme ya da hata durumunda yedek olması açısından bence ses kaydı almanızda fayda var. Dinleme sırasında telefonunuzu sessize alıp, titreşimi de kapatmanız faydanıza olacaktır. Çünkü çok küçük ses bozulmaları bile görsel oluştururken parazite yol açabiliyor.

# SSTV Decode Etme İşlemi

Şimdi sesi kaydettik, eve geri döndük. Buradan sonra ne yapıyoruz ? Kaydettiğimiz SSTV sinyalini decode edip, yani çözümleyip görselimizi oluşturacağız.

Bunun için kullanmanızı tavsiye ettiğim uygulama Windows ortamında rahatlıkla çalışan RX-SSTV uygulaması. Eğer Mac kullanıcısıysanız sadece bu uygulama için sanal olarak windows çalıştırmanızda fayda var. Mac için Multiscan3B uygulaması da aynı işi yapıyor ancak sertifika veren bazı kuruluşlar bu uygulamanın çıktılarını kabul etmeyebiliyor, ayrıca SSTV'den almış olduğunuz görselin sağ altına kimliğinizi ve konumunuzu eklemeniz için RX-SSTV dışında bir alternatifiniz yok. (Görsel üzerinde görüntü düzenleme yazılımları ile düzenleme yapmanız uygun değil, bu yüzden Photoshop ile yazarım gibi düşünceler doğrudan iptal)

RX-SSTV uygulamasının en son sürümünü (RX-SSTV - 2.1.6) [buradan](/assets/Setup_RXSSTV_TA4ADP.zip) benim blog sayfamın sunucusu üzerinden indirebilirsiniz.

Uygulamanın kurulumu klasik zaten, sonrasında uygulamayı açıp üst menüden Setup > RX-SSTV seçeneğine tıklıyoruz ve ayar penceremiz açılıyor. Ayarları aşağıdaki görseldeki gibi düzenliyoruz, işaretli kutuları birebir işaretliyoruz. Kutucukta yazan yazıyı kendi bilgilerinize göre düzenleyebilirsiniz, görselde TA4ADP benim çağrı işaretim KM48UM ise benim grid lokasyon bilgim. Bilmeyenler için bu konuda da çok kısa bir anlatım yakında gelecek.

![RX-SSTV1](/assets/images/posts/yazi/rxsstv1.png)

Ayarları tamamladıktan sonra uygulamamız kullanıma hazır şekilde beklemeye geçecek, sağ tarafta yeşil şekilde "Receiving" yazdığını görebilirsiniz. Bu durum, program bilgisayarınızın mikrofonundan bir SSTV sinyalinin alınmasını bekliyor anlamına geliyor. Bu aşamadan sonra telefonunuza kaydetmiş olduğunuz SSTV sesini bilgisayarınıza dinleterek (2-3 dakika bol kulak çınlaması içeren bir sese sabretmeniz gerekiyor) görseli çözmeye başlayabilirsiniz. Program sesi algıladığı anda çözmeye başlayacak ve görsel oluşturacaktır. Bitiminde otomatik olarak görseli kaydediyor. Eğer birden fazla görsel aldıysanız çözmeyi durdurmanıza gerek yok, otomatik olarak ikinciye geçiş yapıyor. Görsellerinizi History sekmesinde bulabilir, alt kısımdaki ok tuşları ile ileri geri gidebilirsiniz. Yine alt kısımda klasör simgesine tıklayarak ulaşabileceğiniz kayıt klasöründe dosya hallerini bulabilirsiniz. Varsayılan kayıt klasörü : (C:/RX-SSTV/History) İsterseniz görselin üzerine sağ tıklayıp "Save As" seçeneği ile farklı bir konuma da kaydetme imkanınız var.

![RX-SSTV2](/assets/images/posts/yazi/rxsstv2.png)

Eğer elinizde telsizinizin kulaklık çıkışına uyumlu bir aux kablonuz var ise kabloyu doğrudan bilgisayarınızın mikrofon girişine takarak hem çok fazla gürültü yapmadan hem de daha temiz bir şekilde ses aktarımı da yapabilirsiniz. Tabi sesi alırken bilgisayarınızın da yanınızda olması gerekiyor. Bu biraz uğraştırıcı.

# Nereye Yükleyeceğiz ?

Bu konuda sertifika veren veya değerlendirme yapıp isminizi listeye alan birden fazla kuruluş mevcut. Hepsinin farklı değerlendirme şekilleri ve size göndereceği farklı sertifikalar mevcut. Bu konuda çalışma yapan yerli ve yabancı amatörlerin profillerini dolaşarak biraz fikir edinmek istedim. Profilinde birden fazla kaynaktan alınmış sertifikalar olduğunu gördüğüm Sayın [TA5AHO - A.Hamit ÖTE](https://www.qrz.com/db/TA5AHO) bey'e ulaşıp gönderim yapabileceğimiz kaynaklar konusunda bilgi aldım. Sağolsun kırmadı, bu konuda TA (Türkiye)'den temsilciler olması için elinden geleni yapmaya hazır olduğunu belirterek yardımcı oldu. Kendisine de buradan ayrıca teşekkür etmek isterim. Ayrıca bu yazıyı yazdığım saatlerde onaylanmış olan bir sertifikamı bana kendisi ulaştırdı.

## SpaceFlightSoftware

En popüler olanı, aynı zamanda bir galerisi mevcut olan spaceflightsoftware sitesi.

Aldığımız SSTV görselini, ismini değiştirmeden olduğu gibi [spaceflightsoftware](https://www.spaceflightsoftware.com/ARISS_SSTV/submit.php) adresinden gönderiyoruz.
Gönderim sırasında çıkan formu örnek olarak bu şekilde, ancak kendi bilgilerinizle doldurabilirsiniz.
Yukarıdan aşağıya 4 seçenekli olan şıkların açıklamaları da şu şekilde ;

- 1 - Lisans düzeyinde veya daha yüksek düzeyde resmi veya gayri resmi bir eğitimciyim.
- 2 - Lise düzeyinde veya daha düşük düzeyde resmi veya gayri resmi bir eğitimciyim.
- 3 - Lisans düzeyinde veya daha yüksek bir öğrenciyim.
- 4 - Lise düzeyinde veya daha düşük bir öğrenciyim.

Ben bana uygun olan 3.seçeneği işaretledim.

![Form-Polonya](/assets/images/posts/yazi/sstv-form.png)

Formu doldurduktan sonra Upload butonuna tıklayıp gönderim gerçekleştiriyoruz. Gönderdiğimiz sertifikamız önce bir onaya tabi tutuluyor, onaylandıktan sonra [buradaki](https://www.spaceflightsoftware.com/ARISS_SSTV/) galeride yer almaya başlıyor. İsterseniz çağrı işaretinizi girerek sorgulayabilirsiniz.

Bu sayfa ARISS'e SSTV konusunda destek veren [KC6ROL - Will Marchant](https://www.qrz.com/db/KC6ROL) diye bir abimize aitmiş. Kendisi Kaliforniya Üniversitesi - Uzay Bilimleri Laboratuvarında görevliymiş. Buna da değinmeden geçmek istemedim. Emekleri için teşekkürler.

## Polonya Amatör Radyo Birliği

Her etkinlik için ayrı ayrı sertifika veren ve sertifika için bir görsel göndermenin yeterli olduğu bir kuruluştur. Aldığımız görselimizi spaceflightsoftware sitesine yükledikten sonra [Polonya Amatör Radyo Birliği SSTV Ödülü](https://ariss.pzk.org.pl/sstv/) sayfasından SSTV görselini aldığımız etkinlik hangisi ise o etkinliği kontrol ederek, sayfada var ise "Application Form" butonunu tıklayıp karşımıza çıkan "Google Forms" sayfasını dolduruyoruz ve beklemeye başlıyoruz. Sadece bir kez! Unutmayın o formları insanlar tek tek kontrol ediyor ve dünya üzerinde binlerce amatör yanıt gönderiyor.

Bazı etkinlikler için her topluluk sertifika gönderimi yapmayabiliyor. Ancak spaceflightsoftware sitesine görsel yüklemeleri her zaman için açık. Galeriye görsel ekleme hakkınız var. Belgemiz en kısa sürede mail ile tarafımıza ulaştırılıyor. Benim 20.Yıl etkinliği kapsamında aldığım sertifika aşağıdaki gibiydi.

![TA4ADP-Polonya](/assets/images/odul/iss20year.jpg)

## AMSAT Arjantin Uydu Kulübü

Kulübün resmi web sitesine [buradan](http://www.amsat.org.ar/) ulaşabilirsiniz. Bu kulübün verdiği belge diğerlerine bakarak biraz daha uğraştırıcı olduğu için SSTV alanında uzman diyebileceğimiz amatörlerin koleksiyonunu süslüyor diyebiliriz. SSTV peşinde koşan çoğu amatörün almak istediği bir sertifika elbette kolay olmayacaktır.
Buradan belge alabilmek için 15 Tane SSTV görselini almış ve RX-SSTV ile kimlik bilgilerimiz içerecek şekilde çözmüş olmamız aynı zamanda aldığımız görselleri kulübün sitesine [buradan](http://lu7aa.org/index.php?dir=upload%2FISS-SSTV1%2F) en fazla 2 saat içinde yüklemiş olmamız gerekmekte. Dosyaların isimleri RX-SSTV'nin oluşturduğu şekilde kalmalı, değişiklik yapmamaya özen gösterin. Görselleri yüklerken isterseniz yükleme formunun altında yorum satırına çağrı kodunuz + bölgeniz ve ülke ismini (TA4ADP in KM48UM - Turkey) şeklinde yazabilirsiniz.

Yüklemelerin yapıldığı lu7aa.org sitesine (yukarıdaki bağlantı) bazen erişim sorunu olabiliyor, böyle durumlarda VPN kullanarak siteye erişmeyi deneyebilirsiniz. Biraz yavaş olsa da çalışır hale geliyor. Site kapalı diye vazgeçmeyin, benim gibi ilk aldığınız SSTV görselini yüklemediğiniz için pişman olabilirsiniz. :)

Bu siteye farklı etkinlik günlerinde yüklediğiniz toplam görsel sayısı 15 olduğunda, onay verildikten sonra sertifikanız [bu adreste](http://amsat.org.ar/) seri numarası ile birlikte yayınlanacaktır.

Şuan için benim alabildiğim bir sertifika olmadığı için TA5AHO Hamit Bey'in bu siteden aldığı sertifikayı aşağıya ekliyorum.

![TA5AHO-Arjantin](https://s3.amazonaws.com/files.qrz.com/o/ta5aho/ISS_TA5AHO.JPG)

## INSpacE -  Endonezya Uzay Gezgini

Endonezya Amatör Telsizcilerinin bir araya gelerek kurdukları, uydu takibi ve sstv koleksiyonları yapan bir kulüp. Amatör Telsizciliği çocuklara, gençlere ve bu konuda çalışma yapmak isteyen herkese sevdirmek istediklerini söylüyorlar. Tüm Dünyaya da sertifika dağıtıyorlar. Diğer SSTV gönderim siteleri kadar popüler değiller belki, ancak gönderdikleri sertifikaları gerçekten profesyonelce ve çok şık hazırıyorlar. Koleksiyonlarınıza yakışacağına eminim.

[Buradan](https://www.inspace.club/category/sstv/) tüm SSTV etkinliklerine ulaşabilirsiniz, isterseniz güncel etkinlikleri de [buradan](https://www.inspace.club/category/event/) takip edebilirsiniz. Gönderim yapmak istediğimiz etkinliği seçtikten sonra ilgili yazıyı açıp yazı içerisindeki iletişim formu ile bilgilerinizle birlikte SSTV görselinizi iletmeniz mümkün. (Form linki her seferinde değiştği için sabit bir link ekleyemiyorum.) Formu başarılı bir şekilde doldurup gönderdikten sonra 3 gün içerisinde sertifikanız hazırlanıp [burada](https://www.inspace.club/sstv-certificate/) yayınlanacaktır.

![TA4ADP-Endonezya](/assets/images/odul/endonezya-sstv1.jpg)

## Yankee Lima Şili - YLChile

Şili'ye ait bir Amatör Derneğin SSTV etkinliklerinde verdiği sertifikalar mevcut. Neredeyse hiç görmediğim sertifikaları yine TA5AHO - Hamit Bey'in koleksiyonunda görüp öyle ulaştım bu derneğe. Maalesef ki son etkinlikte bir çok dernek gibi burası da sertifika göndermedi, ve buradan da sertifikam yok. Ancak burada da sistem Endonezya'nınki gibi aynı. Derneğin duyuru yayınladığı güncel etkinlikleri [buradan](http://www.ce4ylc.cl/category/concursos/) takip edebilirsiniz. İlgilendiğiniz yarışmanın duyurulduğu yazıya tıklayıp detaylı bilgilere ulaşabilir, duruma göre orada belirtilen formatta olmak şartıyla "ce4ylc@gmail.com" adresine mail atarak başvuru yapabilirsiniz.

![TA5AHO-Şili](https://s3.amazonaws.com/files.qrz.com/o/ta5aho/RED.jpg)
* Görsel : TA5AHO - A.Hamit ÖTE

## R4UAB - Rusya Amatör Radyo Topluluğu

Burası da Rusya'daki bir topluluğa ait Amatör Telsizcilik portalı. Amatör telsiz dünyasındaki olan biten her şeyi paylaşan bir blog sitesi gibi düşünebilirsiniz. Ancak SSTV etkiliklerinde sertifika dağıtmayı da ihmal etmiyorlar elbette. Tüm etkinliklerde dağıtmasalar da kontrol etmekte fayda var.
[Buradan](https://r4uab.ru/diplom-iss-sstv/) Aktif etkinliği kontrol ederek, etkinlik bitiminden en geç 12 saat sonraya kadar göndermeniz gerekiyor. Sertifikaların etkinlik bitişinden itibaren 30 gün içerisinde e-posta ile gönderileceği, ayrıca [bu sayfada](https://r4uab.ru/diplom-iss-sstv/poluchateli-diploma-russia-iss-sstv/)
yayınlanacağı belirtilmiş.

![TA5AHO-Rusya](https://s3.amazonaws.com/files.qrz.com/o/ta5aho/ISS_RU.jpg)
* Görsel : TA5AHO - A.Hamit ÖTE

---

Şu ana kadar bulabildiğim tüm SSTV değerlendirme sistemleri bunlar. Bunların dışında, eğer bu işi gerçekten zevk için yapıyor ve serfilemek istiyorsanız QRZ.com sayfanızda da sergileyebilirsiniz. Oldukça ilgi çekici oluyor. Ayrıca bildiğiniz SSTV gönderimi yapılabilecek dernekler var ise lütfen bana yorum ile ya da iletişim seçeneklerimin herhangi biri ile iletin. Biz de yazıya ekleyelim, TA'yı o sayfalarda da temsil etme şansımız olsun.

Planladığımdan daha uzunca bir yazı oldu. Umarım çok sıkıcı olmamıştır. İlgilenen herkese teşekkürler.

TA4ADP - Hakan TERMAN
