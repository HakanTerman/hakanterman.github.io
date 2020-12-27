---
permalink: /logbook/
title: "TA4ADP - LogBook"
tags: [TA4ADP Nedir, TA4ADP Kimdir, HakanTerman Logbook, HakanTerman, Amatör Telsizcilikte TA4ADP kime aittir, Hakan TERMAN kimdir, Hakan TERMAN telsiz]
excerpt: "Hakan TERMAN - Amatör Radyo QSO Veritabanı"
layout: collection
collection: portfolio
entries_layout: grid
modified: 2020-12-03T23:55:07.573882-04:00
header:
  image: /assets/images/logbook.jpg
  caption: "Fotoğraf Sahibi : [Miguel MrDJ](https://500px.com/ec1dj)"
  gallery:
    - url: /assets/images/unsplash-gallery-image-1.jpg
      image_path: /assets/images/odul/iss20year.jpg
      alt: "ISS 20.Yıl SSTV Ödülü"
      title: "ISS 20.Yıl SSTV Ödülü"
    - url: /assets/images/odul/2.jpg
      image_path: /assets/images/odul/2.jpg
      alt: "placeholder image 2"
      title: "Image 2 title caption"
    - url: /assets/images/odul/3.jpg
      image_path: /assets/images/odul/3.jpg
      alt: "placeholder image 3"
      title: "Image 3 title caption"
mapping:
  latitude: 51.101
  longitude: 0.1
  locations:
    - title: foo
      latitude: 10
      longitude: 10
    - title: bar
      link: /some/awesome/path
      latitude: -10
      longitude: -10
---
{: #myTable .table table-responsive}
|Sıra|Tarih/Saat&nbsp;(UTC+3)|Ülke  |Çağrı&nbsp;İşareti|Operatör&nbsp;Adı|Op.Konumu          |Mod |Band |Konumum |Tür |Not              |
|:-: |:-:                    |:-:   |:-:               |:-:              |:-:                |:-: |:-:  |:-:     |:-: |:-:              |
|1   |26/11/2020-13:45       |:tr:  |TA4ACQ            |Kaan Çelik       |Merkez&nbsp;Denizli|SSB |UHF  |KM48UM  |HAM |İlk&nbsp;QSO     |
|2   |27/11/2020-20:50       |:tr:  |TA4ABJ            |Sercan Eygi      |Bekilli Denizli    |SSB |UHF  |KM48UM  |HAM |Honaz Röle       |
|3   |28/11/2020-17:38       |:tr:  |TA4MSO            |Muhammet Soydal  |Muratpaşa Antalya  |ECHO|ECHO |KM48UM  |HAM |Antalya&nbsp;Echo|
|4   |03/12/2020-22:55       |:tr:  |TB3CFY            |Fehmi Yakıcılar  |Mobil Uşak         |SSB |VHF  |KM48UM  |HAM |Uşak Röle        |
|5   |03/12/2020-23:00       |:tr:  |TA4IBH            |Halil Kuzu       |Merkez Uşak        |SSB |VHF  |KM48UM  |HAM |Uşak Röle        |
|6   |27/12/2020-23:00       |:tr:  |TA3AEQ            |Ali Berkay Özkan |Çanakkale          |ECHO|ECHO |KM48UM  |HAM |Uşak Röle        |


<script src="/assets/leaflet/L.Maidenhead.js"></script>
<script src="/assets/leaflet/leafembed.js"></script>
<script type="text/javascript">
jQuery(document).ready(function ($) {
    $('#myTable').tooltip()
  });
    var q_lat = 39.30000;
    var q_lng = 36.00000;
    var q_loc = 'https://hakanterman.com/assets/leaflet/noktalar.json';
    var q_zoom = 5;
  $(document).ready(function(){
                    var grid = "No";
                    initmap(grid);
  });
</script>
<div id="map" class="map map-home" style="height: 300px; width: 875px; margin-top: 50px"></div>
<br />
<iframe align="top" frameborder="0" height="200" scrolling="yes" src="https://logbook.qrz.com/lbstat/TA4ADP/" width="875"></iframe>

### QSL Kart, Sertifika ve Ödüller

{% include gallery caption="Amatör Telsizcilik maceramda aldığım ödüller." %}
---

**:warning: QRZ Bağlantıları** [QRZ.Com - TA4ADP](https://www.qrz.com/db/TA4ADP), [AmatörTelsiz - TA4ADP](https://qrz.amatortelsiz.com.tr/profil/TA4ADP)
{: .notice}
