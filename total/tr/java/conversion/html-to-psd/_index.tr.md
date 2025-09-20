---
title: Java aracılığıyla HTML'yi PSD'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan HTML dosyasını Java uygulamalarınızda PSD'ye aktarın
url_ignore: /tr/java/conversion/html-to-psd/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: PSD
otherformats: EMZ SVGZ IMAGE PSD WMF WMZ  TGA DXF JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla HTML'yi PSD'ye dönüştürün" h2="HTML dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından PSD'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da html dosyasını PSD görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak HTML'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i PSD'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="HTML'yi Java aracılığıyla PSD'ye aktarın" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak HTML dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak HTML'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak PSD formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada HTML'yi PSD'ye Dönüştürün" %}}
API ayrıca HTML dosyasını PSD'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce HTML belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını PSD'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak PSD formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı HTML'yi PSD'ye Dönüştürün" %}}
API'yi kullanarak, PSD belgenizde filigran bulunan HTML dosyasını PSD'ye de aktarabilirsiniz. Filigran eklemek için önce HTML'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i PSD formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile HTML'yi PSD Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı PSD görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTML'yi PSD'ye (Photoshop Belgesi) dönüştürmek**, web sayfalarından **katmanlı grafik dosyaları** oluşturmak için önemlidir. PSD dosyaları katmanları, metni ve tasarım unsurlarını korur, tasarımcılara web içeriğini düzenlemek, uyarlamak ve tekrar kullanmak için verimli bir şekilde olanak tanır. HTML'i PSD'ye dönüştürerek, kuruluşlar UI/UX iş akışlarını optimize edebilir, yüksek kaliteli pazarlama varlıkları oluşturabilir ve web yeniden tasarımı ile dijital tasarım projeleri için esnekliği koruyabilirler.

{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Senaryoları" %}}

- **UI/UX tasarımı** – Web sayfa düzenlerini düzenlenebilir PSD katmanlarına çıkararak hızlı prototipleme ve tasarım iterasyonu için.
- **Web sitesi yeniden tasarım iş akışları** – Mevcut sayfaları katmanlı dosyalara dönüştürerek güncellemeleri veya yeniden tasarımları kolaylaştırmak için.
- **Pazarlama yaratıcıları** – Web içeriğinden afişler, sosyal medya görselleri ve kampanya grafikleri oluşturmak için.
- **Dijital maketler** – Sunumlar ve müşteri onayları için gerçekçi ürün veya web sayfası maketleri oluşturmak için.
- **E-ticaret tasarım varlıkları** – Ürün sayfaları, promosyon görselleri ve kataloglar için web sayfa bölümlerini tekrar kullanmak için.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}

- **HTML'den PSD'ye boru hatları** – Web sayfalarını katmanlı Photoshop dosyalarına otomatik olarak dönüştürmek.
- **Otomatik katmanlı grafik oluşturma** – Projeler arasında düzenlenebilir katmanlara sahip PSD dosyaları üretmek.
- **Toplu yaratıcı iş akışları** – Büyük ölçekli pazarlama veya tasarım kampanyaları için aynı anda birden fazla web sayfasını dönüştürmek.
- **Kurumsal düzey tasarım otomasyonu** – PSD oluşturmayı kurumsal tasarım ve içerik üretim iş akışlarına entegre etmek.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}