---
title: Export PCL do PPS v systému Android
description: Android API pro převod PCL na PPS bez použití aplikace Microsoft Word
url: /cs/android-java/conversion/pcl-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: PPS
otherformats: POTM POT PPSX SWF PPT POTX PPSM ODP POWERPOINT OTP PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést PCL na PPS na Androidu přes Java" h2="Transformujte PCL na PPS ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu PCL na PPS můžete integrovat do aplikací pro Android pomocí dvou jednoduchých kroků. V prvním kroku můžete exportovat PCL do PPTX pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Poté můžete pomocí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) převést PPTX na PPS. Obě rozhraní API jsou součástí balíčku [Aspose.Total pro Android přes Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export PCL do PPS" %}}
1. Otevřete soubor PCL pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte PCL na PPTX pomocí metody [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu PPS pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Pps` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF pro Android přes Javu](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Slides pro Android přes Javu](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Otevřete soubor PCL chráněný heslem v systému Android přes Java" %}}
Při načítání formátu souboru PCL může být váš dokument chráněn heslem. [Aspose.PDF pro Android přes Javu](https://products.aspose.com/pdf/android-java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předat název souboru a heslo jako argumenty.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte obrázek miniatury souboru PPS v aplikacích pro Android" %}}
Po převodu PCL na PPS můžete také vytvořit miniatury výstupního dokumentu. Pomocí bohatých funkcí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) můžete vytvářet miniatury snímků vytvořením a instance [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) třídy. Poté můžete získat referenci libovolného požadovaného snímku pomocí jeho ID nebo indexu a získat miniaturu snímku odkazovaného snímku v určeném měřítku.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("output.pps");
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
{{< blocks/products/pf/agp/other-supported-section title="Další pppsorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-potm/" name="PCL Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-pot/" name="PCL Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-ppsx/" name="PCL Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-swf/" name="PCL Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-ppt/" name="PCL Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-potx/" name="PCL Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-ppsm/" name="PCL Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-pps/" name="PCL Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-powerpoint/" name="PCL Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-otp/" name="PCL Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-pptm/" name="PCL Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pcl-to-xaml/" name="PCL Na XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}