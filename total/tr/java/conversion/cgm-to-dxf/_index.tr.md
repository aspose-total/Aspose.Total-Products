---
title: Java aracılığıyla CGM'yi DXF'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan CGM dosyasını Java uygulamalarınızda DXF'ye aktarın
url_ignore: /tr/java/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla CGM'yi DXF'ye dönüştürün" h2="CGM dosyasını Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasından DXF'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Java'da cgm dosyasını DXF görüntüsüne iki basit adımda dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak CGM'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Görüntü İşleme API'sini kullanarak JPEG'i DXF'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi Java aracılığıyla DXF'ye aktarın" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak CGM dosyasını açın
2. sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) kullanarak CGM'yi JPEG'e dönüştürün. aspose.pdf.Page-java.io.OutputStream-) yöntemi
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG dosyasını yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak DXF formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Tek Bir Dosyada CGM'yi DXF'ye Dönüştürün" %}}
API ayrıca CGM dosyasını DXF'ye tek bir dosyaya aktarmanıza olanak tanır. Tüm sayfaları dönüştürmek için önce CGM belgenizi bir TIFF dosyasına dönüştürebilir, ardından TIFF dosyasını DXF'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) kullanarak tek bir TIFF görüntüsü alabilirsiniz. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) sınıfının java.io.OutputStream-) yöntemi. Son olarak, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak TIFF dosyasını yükleyebilir ve [save](https://) kullanarak DXF formatına kaydedebilirsiniz. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) yöntemi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Filigranlı CGM'yi DXF'ye Dönüştürün" %}}
API'yi kullanarak, DXF belgenizde filigran bulunan CGM dosyasını DXF'ye de aktarabilirsiniz. Filigran eklemek için önce CGM'yi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i DXF formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile CGM'yi DXF Dosyasına Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı DXF görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.rotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Kütüphane, tüm çirkin detayları kapsarken karmaşık işlemleri gerçekleştirmek için basit yöntemler sağlar. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için dönüştürülen JPEG görüntüsünü [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak yükleyebilir ve Görüntüyü çağırabilirsiniz. uygun [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) belirtilirken rotaryFlip yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**Bilgisayar Grafik Meta Dosyası (CGM)** dosyalarını **Çizim Değişim Formatı (DXF)**'e dönüştürmek, mühendislik, mimarlık ve imalat sistemleri arasında sorunsuz etkileşim sağlamak için **Bilgisayar Destekli Tasarım (CAD)** iş akışlarında önemlidir. **Java tabanlı uygulamalarda**, bu dönüşüm, CGM'den vektör tabanlı teknik diyagramların geniş desteklenen bir CAD formatına dönüştürülmesine olanak tanır, böylece bunlar düzenlenebilir, paylaşılabilir ve endüstri standardı tasarım araçlarıyla uyumlu hale gelir. Bu, işbirlikçi tasarım, hassas imalat ve teknik çizimlerin arşivlenmesi için kritiktir.


## ✅ Ana Kullanım Senaryoları

- **Mühendislik Tasarımı Etkileşimliği**  
  DXF'yi destekleyen CAD araçlarında CGM tabanlı tasarımları paylaşın ve düzenleyin, platformlar arası işbirliği için.

- **Üretim Planı Değişimi**  
  Üretim ekiplerine CNC işleme ve imalat için CGM diyagramlarından türetilen DXF dosyalarını sağlayın.

- **Vektör Grafik Düzenleme**  
  CGM diyagramlarını DXF'e dönüştürerek vektör sadakatini kaybetmeden CAD yazılımında doğrudan değişiklik yapın.


## ⚙️ Otomasyon Senaryoları

- **Java Tabanlı CAD Araçları**  
  CGM'den DXF'e dönüşümü doğrudan Java destekli CAD düzenleme ve görselleştirme uygulamalarına entegre edin.

- **Mühendislik Çizim Dönüştürücüler**  
  Java API'lerini kullanarak çoklu proje iş akışları için büyük ölçekli CGM'den DXF'e toplu dönüşümleri otomatikleştirin.

- **Otomatik CAD Arşivleme Sistemleri**  
  Gelecekteki yeniden kullanım ve uyumluluk için CGM tasarımlarını DXF dosyaları olarak uzun vadeli mühendislik arşivlerinde saklayın.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}