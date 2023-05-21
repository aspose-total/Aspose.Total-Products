---
title: Export XML do POWERPOINT v systému Android
description: Android API pro převod XML na POWERPOINT bez použití aplikace Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: POWERPOINT
otherformats: PPSM ODP OTP PPSX PPS PPT POT PPTM POTM XAML SWF POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XML na POWERPOINT na Androidu přes Java" h2="Transformujte XML na POWERPOINT ve svých aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu XML na POWERPOINT můžete integrovat do aplikací pro Android pomocí dvou jednoduchých kroků. V prvním kroku můžete exportovat XML do PPTX pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Poté můžete pomocí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) převést PPTX na POWERPOINT. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro export XML do POWERPOINT" %}}
1. Otevřete soubor XML pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XML na PPTX pomocí metody [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu POWERPOINT pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Powerpoint` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Slides pro Android přes Javu](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve vašich aplikacích.

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
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
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

{{% blocks/products/pf/feature-page-section  h2="Vytvořte obrázek miniatury souboru POWERPOINT v aplikacích pro Android" %}}
Po převodu XML na POWERPOINT můžete také vytvořit miniatury výstupního dokumentu. Pomocí bohatých funkcí [Aspose.Slides pro Android přes Java](https://products.aspose.com/slides/android-java/) můžete vytvářet miniatury snímků vytvořením a instance [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) třídy. Poté můžete získat referenci libovolného požadovaného snímku pomocí jeho ID nebo indexu a získat miniaturu snímku odkazovaného snímku v určeném měřítku.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}