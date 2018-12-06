---
title: Bu Site Nasıl Yapıldı ?
tags: [nasil yapildi, blog sitesi yapımı, jekyll, jekyll nedir,github pages]
header:
  teaser: /assets/images/posts/jekyll.jpg
  image: /assets/images/posts/jekyll.jpg
  caption: "Fotoğraf Sahibi : [Ilya Pavlov](https://www.everypixel.com/search?q=&authorname=Ilya%20Pavlov)"
category: Teknoloji
layout: single
---

Blog'umu beğendin değil mi ? Hatta konu hakkında biraz bilgi sahibiysen muhtemelen site kaynak kodlarını da inceledin. Biliyorum, çünkü benim de yaptığım şeylerden biri, bu siteyi nasıl yaptılar acaba diye kurcalamak.

Bu site hosting ihtiyacı olmadan, sadece GitHub üzerinden çalışıyor. Github'un projeler için github-pages isminde oluşturduğu otomatik sayfalar var. (Bir nevi projelerinizi tanıtmak için web sayfası oluşturabileceğiniz bir hosting hizmeti diyebiliriz.) Bu sistemi kullanarak, herhangi bir veritabanına ihtiyaç duymadan jekyll sistemi üzerinde çalışıyor.

### jekyll Nedir ?

* Ruby ile yazılmış, açık kaynak kodlu (MIT Lisans'ı ile) sabit içerikli site oluşturma yazılımı diye özetleyebiliriz.

### Nasıl Çalışır ?

* MarkDown (.md) formatında yazdığınız yazılarınızı otomatik olarak web sitesi sayfalarına dönüştürerek yayına alır.

### Nasıl Kurulur ?

* Localde Kurulum

Öncelikli olarak bilgisayarınızda 'Ruby' kurulumu yapılmış ve 'Ruby gem' in çalışıyor olması gerekiyor.

- Ruby Kurulu değilse

- Windows İçin

[Bu](https://www.ruby-lang.org/tr/downloads/) ve [Bu](https://rubygems.org/pages/download) paketleri indirip kurmanız gerekiyor.

- Linux için

~~~console
sudo apt-get install ruby1.9.1-full
~~~

- Kurulumu Kontrol Etmek İçin

~~~console
ruby -v
gem -v
~~~

Kodlarının çıktılarında versiyon numarası alıyorsak Ruby sistemimizde çalışıyor demektir.

Terminal üzerinden (Windows için CMD Ekranı)

~~~ruby
gem install jekyll
~~~

yazarak jekyll'i bilgisayarınıza kurabilirsiniz. Kurulum internet bağlantınıza bağlı olarak yaklaşık 30sn-1 dk arası sürüyor.

Bu işlem bittikten sonra

~~~ruby
jekyll new siteadi
~~~

komutu ile jekyll ile yeni sitenizi oluşturabilirsiniz. Site oluşturma işlemi bittikten sonra

~~~ruby
cd siteadi
jekyll serve
~~~

komutu ile sitenizin jekyll ile localhost üzerinde 4000 portunda çalıştırmaya başlayabilirsiniz.
Eğer tüm işlemler sorunsuz ise `http://localhost:4000` adresine girdiğinizde jekyll sitenize ulaşabilirsiniz.

* GitHub Üzerinde Kurulum

GitHub kullanmayı bir miktar bildiğinizi, bazı terimler hakkında bilgi sahibi olduğunuzu düşünerek devam ediyorum. Bilginiz yok ise 'arasındaki' kelimeleri araştırarak anlamlarını bulduktan sonra bu kısmı daha iyi anlayabilirsiniz.

[Bu adresteki](http://jekyllthemes.org/) temalardan bir tanesini GitHub hesabınıza 'fork'layıp oluşan reponun ismini 'siteadiniz.github.io' olarak düzenleyerek kendi 'github-pages' sayfanızı yani blogunuzu oluşturabilirsiniz.

Düzenlemek için bu oluşturduğunuz 'repo'nuzu bilgisayarınıza klonladıktan sonra klasör içindeki 'config.yml' dosyasını  herhangi bir text editör ile açıp düzenleyerek kişiselleştirmeye başlayabilirsiniz. Düzenlemeleri kaydedip 'commit' edip 'push' ederek (nasıl bi cümle oldu ya) siteniz üzerinde çalıştığını görebilirsiniz.

Oluşturma kısmı bu kadar, kullandıkça ve yazı yazdıkça ben de öğrenmeye devam edeceğim. Bir sonraki yazıda MarkDown formatı ile yazı eklemekten bahsetmeyi düşünüyorum. Hoşcakalın.
