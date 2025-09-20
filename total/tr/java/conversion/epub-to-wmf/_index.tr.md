---
title: Java aracılığıyla EPUB'yi WMF'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan EPUB dosyasını Java uygulamalarınızda WMF'ye aktarın
url_ignore: /tr/java/conversion/epub-to-wmf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: WMF
otherformats: JPEG2000  PSD WMZ SVGZ DXF TGA WMF IMAGE EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla EPUB'yi WMF'ye dönüştürün" h2="EPUB dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından WMF'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da epub dosyasını WMF görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak EPUB'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i WMF'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB'yi Java aracılığıyla WMF'ye aktarın" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak EPUB dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak EPUB'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak WMF formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada EPUB'yi WMF'ye Dönüştürün" %}}
API ayrıca EPUB dosyasını WMF'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce EPUB belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını WMF'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak WMF formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı EPUB'yi WMF'ye Dönüştürün" %}}
API'yi kullanarak, WMF belgenizde filigran bulunan EPUB dosyasını WMF'ye de aktarabilirsiniz. Filigran eklemek için önce EPUB'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i WMF formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile EPUB'yi WMF Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı WMF görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**EPUB**'ı **WMF (Windows Metafile)**'a dönüştürmek, e-kitaplardan **vektör tabanlı Windows uyumlu grafikler** oluşturmak için önemlidir. WMF dosyaları, sunumlar, diyagramlar ve ofis yayıncılığı için uygun, ölçeklenebilir, yüksek kaliteli görseller sağlar. EPUB'u WMF'ye dönüştürerek yayıncılar, eğitimciler ve işletmeler profesyonel grafikler üretebilir, çözünürlük bağımsızlığını koruyabilir ve Windows odaklı iş akışlarını optimize edebilir.

{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}
- **Ofis tabanlı yayıncılık** – E-kitap görsellerini Microsoft Office belgelerine sorunsuzca entegre edin.
- **Diyagram oluşturma** – Metin ve görsel içeriği düzenlenebilir vektör diyagramlara dönüştürün.
- **Sunum grafikleri** – Slaytları ölçeklenebilir ve yüksek kaliteli görsellerle geliştirin.
- **Arşiv iş akışları** – E-kitap grafiklerini standartlaştırılmış bir vektör formatında koruyun.
- **Kurumsal raporlama** – Yayın grafiklerini profesyonel raporlar ve panolar içine dahil edin.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}
- **EPUB'ten-WMF'ye boru hatları** – E-kitapları Windows Metafile grafiklerine otomatik olarak dönüştürün.
- **Otomatik diyagram dönüşümü** – Metin veya görsel içerikten ölçeklenebilir diyagramlar oluşturun.
- **Toplu metafile oluşturma** – Yayınlardan verimli bir şekilde birden fazla WMF grafiği üretin.
- **Kurumsal düzey belge iş akışları** – WMF grafiklerini büyük ölçekli raporlama ve yayıncılık sistemlerine entegre edin.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}