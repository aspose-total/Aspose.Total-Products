---
title: Java aracılığıyla XSLFO'yi WMZ'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan XSLFO dosyasını Java uygulamalarınızda WMZ'ye aktarın
url_ignore: /tr/java/conversion/xslfo-to-wmz/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: WMZ
otherformats: PSD  WMZ JPEG2000 SVGZ WMF EMZ IMAGE DXF TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla XSLFO'yi WMZ'ye dönüştürün" h2="XSLFO dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından WMZ'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da xslfo dosyasını WMZ görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak XSLFO'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i WMZ'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO'yi Java aracılığıyla WMZ'ye aktarın" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak XSLFO dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak XSLFO'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak WMZ formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada XSLFO'yi WMZ'ye Dönüştürün" %}}
API ayrıca XSLFO dosyasını WMZ'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce XSLFO belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını WMZ'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak WMZ formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı XSLFO'yi WMZ'ye Dönüştürün" %}}
API'yi kullanarak, WMZ belgenizde filigran bulunan XSLFO dosyasını WMZ'ye de aktarabilirsiniz. Filigran eklemek için önce XSLFO'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i WMZ formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile XSLFO'yi WMZ Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı WMZ görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



XSLFO'nun **WMZ (Sıkıştırılmış Windows Metafile)** biçimine dönüştürülmesi, ölçeklenebilirliği korurken sıkıştırılmış vektör görüntüler sağlar, e-posta, sunumlar ve web entegrasyonu için idealdir.



{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Senaryoları" %}}



* Sıkıştırılmış ekler olarak XSLFO ile oluşturulan görsellerin gönderilmesi.

* PowerPoint ve Word'e ölçeklenebilir grafiklerin gömülmesi.

* Sıkıştırılmış vektör rapor görsellerinin arşivlenmesi.

* Operasyonel panoların e-posta veya iç portal aracılığıyla paylaşılması.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}



* XSLFO dosyalarının WMZ'ye toplu dönüşümü, yerden tasarruf sağlayan depolama için.

* Görsel raporların zamanlanmış otomatik sıkıştırılması.

* Tekrarlanan sunum iş akışları için tetiklenen WMZ oluşturma.

* Otomatik slayt ve belge akışlarına entegrasyon.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}