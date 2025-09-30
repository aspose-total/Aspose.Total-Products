---
title: Java aracılığıyla PDF'yi IMAGE'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan PDF dosyasını Java uygulamalarınızda IMAGE'ye aktarın
url_ignore: /tr/java/conversion/pdf-to-image/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: IMAGE
otherformats: JPEG2000 EMZ  WMZ TGA PSD DXF WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla PDF'yi IMAGE'ye dönüştürün" h2="PDF dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından IMAGE'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da pdf dosyasını IMAGE görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak PDF'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i IMAGE'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF'yi Java aracılığıyla IMAGE'ye aktarın" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak PDF dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak PDF'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak IMAGE formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada PDF'yi IMAGE'ye Dönüştürün" %}}
API ayrıca PDF dosyasını IMAGE'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce PDF belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını IMAGE'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak IMAGE formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı PDF'yi IMAGE'ye Dönüştürün" %}}
API'yi kullanarak, IMAGE belgenizde filigran bulunan PDF dosyasını IMAGE'ye de aktarabilirsiniz. Filigran eklemek için önce PDF'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i IMAGE formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile PDF'yi IMAGE Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı IMAGE görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**PDF'yi RESME** dönüştürmek, belgelerin PNG, JPG veya TIFF gibi çeşitli görüntü formatlarına dönüştürülmesine izin veren en yaygın iş akışlarından biridir. Bu, PDF'lerin **web yayıncılığı, arşivleme ve dijital sunum** ortamlarında daha kolay kullanılmasını sağlar.
{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Senaryoları" %}}
- PDF belgelerini resim dosyaları olarak arşivleme
- PNG veya JPG olarak web sitelerine PDF sayfaları gömme
- PDF'lerden küçük resimler ve önizlemeler oluşturma
- PDF'leri dijital slayt ve sunumlarla entegre etme
- Uyumluluk ve denetimler için görüntü tabanlı depolama
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}
- Otomatik **PDF'den RESME toplu iş akışları**
- Web platformları için PDF'den PNG veya JPG iş akışları
- Belge yönetim sistemleri için önizleme görüntüsü oluşturma
- Kurumsal arşivleme için çoklu sayfalı TIFF'e PDF dönüşümü
- Otomatik API tabanlı PDF'den RESME dönüşüm
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}