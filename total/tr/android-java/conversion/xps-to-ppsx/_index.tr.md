---
title: Android'de XPS'yi PPSX'ye aktarın
description: Microsoft Word kullanmadan XPS'yi PPSX'ye Dönüştürmek için Android API

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPSX
otherformats: ODP PPS SWF POWERPOINT PPSM PPTM POTX PPT OTP POTM XAML POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de XPS'yi PPSX'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan Android Uygulamalarınızda XPS'yi PPSX'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak XPS'den PPSX'ye dönüştürme özelliğini Android uygulamalarınıza entegre edebilirsiniz. İlk adımda, [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kullanarak XPS'yi PPTX'e aktarabilirsiniz. Bundan sonra, [Java üzerinden Android için Aspose.Slides](https://products.aspose.com/slides/android-java/) kullanarak PPTX'i PPSX'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS'yi PPSX'ye Aktarmak için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak XPS dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) yöntemini kullanarak XPS'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi PPSX biçiminde kaydedin ve ` Ppsx` SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) ve [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) yükleyin /androidjava/install-aspose-slides-for-android-via-java/) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de Şifre Korumalı XPS Dosyasını Açın" %}}
XPS dosya biçimini yüklerken belgeniz parola korumalı olabilir. [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) şifreli belgeleri de açmanıza olanak tanır. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) yeni örneğini başlatabilirsiniz. .lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Android Uygulamalarında PPSX Dosyasının Küçük Resmini Oluşturun" %}}
XPS'yi PPSX'ye dönüştürdükten sonra, çıktı belgenizin küçük resimlerini de oluşturabilirsiniz. [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) açısından zengin özelliği kullanarak, [Sunu]() oluşturarak ve örneğini oluşturarak slaytların küçük resimlerini oluşturabilirsiniz. https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfı. Bundan sonra, ID veya indeksini kullanarak istediğiniz herhangi bir slaydın referansını alabilir ve referans verilen slaydın küçük resmini belirli bir ölçekte alabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-ppsx/" name="XPS İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-pps/" name="XPS İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-swf/" name="XPS İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-powerpoint/" name="XPS İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-ppsm/" name="XPS İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-pptm/" name="XPS İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-potx/" name="XPS İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-ppt/" name="XPS İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-otp/" name="XPS İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-potm/" name="XPS İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xaml/" name="XPS İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-pot/" name="XPS İle POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}