---
title: Export XML do SWF v systému Android
description: Android API pro převod XML na SWF bez použití aplikace Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: SWF
otherformats: POTM PPSX ODP XAML PPSM POWERPOINT OTP PPS PPT POT PPTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XML na SWF na Androidu přes Java" h2="Transformujte XML na SWF ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu XML na SWF můžete integrovat do aplikací pro Android pomocí dvou jednoduchých kroků. V prvním kroku můžete exportovat XML do PPTX pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Poté můžete pomocí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) převést PPTX na SWF. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XML do SWF" %}}
1. Otevřete soubor XML pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XML na PPTX pomocí metody [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu SWF pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Swf` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Slides pro Android přes Javu](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Otevřete soubor XML chráněný heslem v systému Android přes Java" %}}
Při načítání formátu souboru XML může být váš dokument chráněn heslem. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předat název souboru a heslo jako argumenty.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte obrázek miniatury souboru SWF v aplikacích pro Android" %}}
Po převodu XML na SWF můžete také vytvořit miniatury výstupního dokumentu. Pomocí bohatých funkcí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) můžete vytvářet miniatury snímků vytvořením a instance [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) třídy. Poté můžete získat referenci libovolného požadovaného snímku pomocí jeho ID nebo indexu a získat miniaturu snímku odkazovaného snímku v určeném měřítku.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a SWF file
Presentation presentation = new Presentation("output.swf");
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
{{< blocks/products/pf/agp/other-supported-section title="Další pswforované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-potm/" name="XML Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-ppsx/" name="XML Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-swf/" name="XML Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-xaml/" name="XML Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-ppsm/" name="XML Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-powerpoint/" name="XML Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-otp/" name="XML Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-pps/" name="XML Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-ppt/" name="XML Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-pot/" name="XML Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-pptm/" name="XML Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/xml-to-potx/" name="XML Na POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}