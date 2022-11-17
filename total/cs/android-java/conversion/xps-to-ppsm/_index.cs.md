---
title: Export XPS do PPSM v systému Android
description: Android API pro převod XPS na PPSM bez použití aplikace Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPSM
otherformats: POT SWF POTX OTP POTM PPTM POWERPOINT PPS ODP XAML PPT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XPS na PPSM na Androidu přes Java" h2="Transformujte XPS na PPSM ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu XPS na PPSM můžete integrovat do aplikací pro Android pomocí dvou jednoduchých kroků. V prvním kroku můžete exportovat XPS do PPTX pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Poté můžete pomocí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) převést PPTX na PPSM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XPS do PPSM" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XPS na PPTX pomocí metody [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu PPSM pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Ppsm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Slides pro Android přes Javu](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Otevřete soubor XPS chráněný heslem v systému Android přes Java" %}}
Při načítání formátu souboru XPS může být váš dokument chráněn heslem. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předat název souboru a heslo jako argumenty.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte obrázek miniatury souboru PPSM v aplikacích pro Android" %}}
Po převodu XPS na PPSM můžete také vytvořit miniatury výstupního dokumentu. Pomocí bohatých funkcí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) můžete vytvářet miniatury snímků vytvořením a instance [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) třídy. Poté můžete získat referenci libovolného požadovaného snímku pomocí jeho ID nebo indexu a získat miniaturu snímku odkazovaného snímku v určeném měřítku.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("output.ppsm");
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
{{< blocks/products/pf/agp/other-supported-section title="Další pppsmorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-pot/" name="XPS Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-swf/" name="XPS Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-potx/" name="XPS Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-otp/" name="XPS Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-potm/" name="XPS Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-pptm/" name="XPS Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-powerpoint/" name="XPS Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-pps/" name="XPS Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-ppsm/" name="XPS Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-xaml/" name="XPS Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-ppt/" name="XPS Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xps-to-ppsx/" name="XPS Na PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}