---
title: Android'de PS'yi XAML'ye aktarın
description: Microsoft Word kullanmadan PS'yi XAML'ye Dönüştürmek için Android API

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: XAML
otherformats: POTX PPTM SWF OTP PPSX PPT POT PPS PPSM ODP POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de PS'yi XAML'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan Android Uygulamalarınızda PS'yi XAML'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak PS'den XAML'ye dönüştürme özelliğini Android uygulamalarınıza entegre edebilirsiniz. İlk adımda, [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kullanarak PS'yi PPTX'e aktarabilirsiniz. Bundan sonra, [Java üzerinden Android için Aspose.Slides](https://products.aspose.com/slides/android-java/) kullanarak PPTX'i XAML'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS'yi XAML'ye Aktarmak için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak PS dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) yöntemini kullanarak PS'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi XAML biçiminde kaydedin ve ` Xaml` SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) ve [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) yükleyin /androidjava/install-aspose-slides-for-android-via-java/) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de Şifre Korumalı PS Dosyasını Açın" %}}
PS dosya biçimini yüklerken belgeniz parola korumalı olabilir. [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) şifreli belgeleri de açmanıza olanak tanır. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) yeni örneğini başlatabilirsiniz. .lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Android Uygulamalarında XAML Dosyasının Küçük Resmini Oluşturun" %}}
PS'yi XAML'ye dönüştürdükten sonra, çıktı belgenizin küçük resimlerini de oluşturabilirsiniz. [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) açısından zengin özelliği kullanarak, [Sunu]() oluşturarak ve örneğini oluşturarak slaytların küçük resimlerini oluşturabilirsiniz. https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfı. Bundan sonra, ID veya indeksini kullanarak istediğiniz herhangi bir slaydın referansını alabilir ve referans verilen slaydın küçük resmini belirli bir ölçekte alabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a XAML file
Presentation presentation = new Presentation("output.xaml");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-potx/" name="PS İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-pptm/" name="PS İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-swf/" name="PS İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-otp/" name="PS İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-ppsx/" name="PS İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-ppt/" name="PS İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-pot/" name="PS İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-pps/" name="PS İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-ppsm/" name="PS İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-xaml/" name="PS İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-potm/" name="PS İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ps-to-powerpoint/" name="PS İle POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}