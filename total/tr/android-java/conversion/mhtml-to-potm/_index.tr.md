---
title: Android'de MHTML'yi POTM'ye aktarın
description: Microsoft Word kullanmadan MHTML'yi POTM'ye Dönüştürmek için Android API
url: /tr/android-java/conversion/mhtml-to-potm/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: POTM
otherformats: SWF ODP PPTM PPT XAML PPS POTX PPSX PPSM OTP POWERPOINT POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de MHTML'yi POTM'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan Android Uygulamalarınızda MHTML'yi POTM'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak MHTML'den POTM'ye dönüştürme özelliğini Android uygulamalarınıza entegre edebilirsiniz. İlk adımda, [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kullanarak MHTML'yi PPTX'e aktarabilirsiniz. Bundan sonra, [Java üzerinden Android için Aspose.Slides](https://products.aspose.com/slides/android-java/) kullanarak PPTX'i POTM'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML'yi POTM'ye Aktarmak için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MHTML dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) yöntemini kullanarak MHTML'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi POTM biçiminde kaydedin ve ` Potm` SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) ve [Java üzerinden Aspose.Slides for Android](https://docs.aspose.com/slides) yükleyin /androidjava/install-aspose-slides-for-android-via-java/) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de Şifre Korumalı MHTML Dosyasını Açın" %}}
MHTML dosya biçimini yüklerken belgeniz parola korumalı olabilir. [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) şifreli belgeleri de açmanıza olanak tanır. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) yeni örneğini başlatabilirsiniz. .lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Android Uygulamalarında POTM Dosyasının Küçük Resmini Oluşturun" %}}
MHTML'yi POTM'ye dönüştürdükten sonra, çıktı belgenizin küçük resimlerini de oluşturabilirsiniz. [Java üzerinden Aspose.Slides for Android](https://products.aspose.com/slides/android-java/) açısından zengin özelliği kullanarak, [Sunu]() oluşturarak ve örneğini oluşturarak slaytların küçük resimlerini oluşturabilirsiniz. https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfı. Bundan sonra, ID veya indeksini kullanarak istediğiniz herhangi bir slaydın referansını alabilir ve referans verilen slaydın küçük resmini belirli bir ölçekte alabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("output.potm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-swf/" name="MHTML İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-potm/" name="MHTML İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-pptm/" name="MHTML İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-ppt/" name="MHTML İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-xaml/" name="MHTML İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-pps/" name="MHTML İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-potx/" name="MHTML İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-ppsx/" name="MHTML İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-ppsm/" name="MHTML İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-otp/" name="MHTML İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-powerpoint/" name="MHTML İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mhtml-to-pot/" name="MHTML İle POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}