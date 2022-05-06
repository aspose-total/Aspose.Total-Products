---
title: Java aracılığıyla EPUB'yi APNG'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan EPUB dosyasını Java uygulamalarınızda APNG'ye aktarın
url_ignore: /tr/java/conversion/epub-to-apng/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: APNG
otherformats: DXF  PSD SVGZ EMZ JPEG2000 TGA WMZ WMF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla EPUB'yi APNG'ye dönüştürün" h2="EPUB dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından APNG'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da epub dosyasını APNG görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak EPUB'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i APNG'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB'yi Java aracılığıyla APNG'ye aktarın" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak EPUB dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak EPUB'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak APNG formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada EPUB'yi APNG'ye Dönüştürün" %}}
API ayrıca EPUB dosyasını APNG'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce EPUB belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını APNG'ye aktarabilirsiniz. Giriş dosyasını [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak APNG formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı EPUB'yi APNG'ye Dönüştürün" %}}
API'yi kullanarak, APNG belgenizde filigran bulunan EPUB dosyasını APNG'ye de aktarabilirsiniz. Filigran eklemek için önce EPUB'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://apireference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i APNG formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile EPUB'yi APNG Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı APNG görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-emz/" name="EPUB İle EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-tga/" name="EPUB İle TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-jpeg2000/" name="EPUB İle JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-image/" name="EPUB İle IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-psd/" name="EPUB İle PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-wmz/" name="EPUB İle WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-svgz/" name="EPUB İle SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to/" name="EPUB İle" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-wmf/" name="EPUB İle WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-dxf/" name="EPUB İle DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/epub-to-dicom/" name="EPUB İle DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}