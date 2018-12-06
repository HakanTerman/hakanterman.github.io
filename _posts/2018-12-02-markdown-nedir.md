---
title: Markdown Nedir ? - Jekyll'e Nasıl Yazı Eklenir ?
tags: [markdown, markdown nedir]
header:
  teaser: /assets/images/posts/markdown.jpg
  image: /assets/images/posts/markdown.jpg
  caption: "Fotoğraf Sahibi : [Hakan Terman](https://hakanterman.com)"
category: Teknoloji
layout: single
permalink: /teknoloji/markdown-nedir/
---

### Jekyll'e Nasıl Yazı Eklenir ?

Jekyll'in online çalışan, veritabanı ihtiyacı olmayan bir sistem olduğundan bir önceki yazımda belirtmiştim.
Sistem üzerinde yazılar '.md' dosyası içinde tutuluyor. Her yazı aslında birer dosyadan oluşmakta. Jekyll bu dosyaları okuyup 'HTML' biçimine çevirerek otomatik olarak yayına alıyor.

'.md' dosyalarının içeriğinde 'Markdown' etiket sistemi ile yazılmış halde yazılar bulunuyor. Bu yazı dosyalarım arasında '2018-12-02-markdown-nedir.md' ismine sahip bir dosya mesela.

### Markdown

İsmini ilk defa duyuyor olabilirsiniz, ama aslında muhtemelen daha önce kullandığınız bir yazı etiket sistemi diyebiliriz. Özellikle forum siteleri ile bir geçmişiniz varsa forum editörlerinin etiketlerine benzer şekilde metin düzenlemesi yapmanızı sağlayan bir sistem.

### Markdown ile nasıl yazı yazılır ?

Online editörlerden hatırlayacağınız üzere metinlerde başlık ve alt başlıklardan oluşan bir hiyerarşik sistem mevcut.

~~~console
* yazi *
~~~

* Yazı içersinde bir kelimeyi öne çıkarmak için kelimenin başına ve sonuna yukarıdaki şekilde yıldız işareti koyabilirsiniz.

~~~console
>
~~~
işareti, HTML'de blockquote'a eşdeğerdir,


yıldız işareti, ve iç içe listeleme yapısı, sırasıyla HTML dilindeki

~~~console
<ul></ul> ve <ol></ol>
~~~

etiketleri anlamına gelir.

* Yeni paragraf eklemek için

~~~console
<p> yazi </p>
~~~

şeklinde eklemeye gerek yoktur. Markdown sistemi aşağıdan başkanan her satırı otomatik olarak paragraf olarak algılayacaktır.

* Paragraf içersinde bir alt satıra geçmek için 2 defa boşlık (SPACE) bırakılması yeterlidir.

* Yazılan satırın altına “=” işareti koyulutsa o satır "<h1>" olarak görüntülenir, “-” yazılırsa o satır <h2> olarak görüntülenir.

* Numaralandırılmamış listeleme için

~~~console
* Madde
* Madde
~~~
* Numaralandırılmış listeleme için

~~~console
1 Madde
2 Madde
~~~

şeklinde gösterim kullanılabilir.

* Satırı 1 TAB içeriden ya da 4 SPACE içeriden başlatırsanız o satır kod blogu olarak görüntülenir.
Aynı zamanda kod blogu için

~~~console

~~~ruby
şeklinde gösterim de kullanabilirsiniz.
~~~

~~~

Ana hatları ile sistemi bu şekilde özetleyebiliriz. Daha detaylı şekilde yazı yazmak için online Markdown editörlerine başvurabilirsiniz.

* [Stackedit](https://stackedit.io/app)

Markdown etiketleri'ni öğrenirken, bu konuda güzel bir rehber hazırlayan [Ömer Yaylaali](http://omeryaylaalti.github.io/blog/markdown/)'nın  blogundaki yazısından biraz kopya çektiğimi de belirtmeden geçmeyeyim.
