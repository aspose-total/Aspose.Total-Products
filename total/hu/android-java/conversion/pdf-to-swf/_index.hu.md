---
title: Exportálja a PDF-et SWF-be Androidon
description: Android API a PDF konvertálásához SWF-vé Microsoft Word használata nélkül
url: /hu/android-java/conversion/pdf-to-swf/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: SWF
otherformats: POTX XAML OTP PPT PPSM PPS PPTM ODP PPSX POWERPOINT POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a PDF-et SWF-vé Androidon Java segítségével" h2="Alakítsa át a PDF-et SWF-vé Android-alkalmazásaiban Microsoft<sup>&reg;</sup> PowerPoint vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépéssel integrálhatja a PDF-SWF konverziós funkciót Android-alkalmazásaiba. Az első lépésben exportálhatja a PDF-et PPTX-be az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával. Ezt követően az [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) használatával konvertálhatja a PPTX-t SWF-vé. Mindkét API az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) csomagba tartozik. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a PDF exportálásához SWF-be" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a PDF-et PPTX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot SWF formátumba a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) metódussal, és állítsa be a ` Swf` SaveFormat néven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) /androidjava/install-aspose-slides-for-android-via-java/) az alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a jelszóval védett PDF-fájlt Androidon Java segítségével" %}}
A PDF fájlformátum betöltése közben előfordulhat, hogy a dokumentum jelszóval védett. Az [Aspose.PDF Androidra Java-n keresztül](https://products.aspose.com/pdf/android-java/) lehetővé teszi titkosított dokumentumok megnyitását is. A titkosított fájl megnyitásához inicializálhatja a [Dokumentum](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) új példányát osztály, és adja meg a fájlnevet és a jelszót argumentumként.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hozzon létre miniatűrt az SWF-fájlról az Android alkalmazásokban" %}}
A PDF SWF-vé konvertálása után a kimeneti dokumentum miniatűrjeit is létrehozhatja. Az [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) gazdag funkciójának használatával miniatűrképeket hozhat létre a diákról a [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály. Ezt követően bármely kívánt diára vonatkozó hivatkozást lekérheti annak azonosítójával vagy indexével, és megkaphatja a hivatkozott dia miniatűrjét meghatározott léptékben.
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
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-potx/" name="PDF Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-xaml/" name="PDF Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-otp/" name="PDF Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-ppt/" name="PDF Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-ppsm/" name="PDF Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-pps/" name="PDF Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-pptm/" name="PDF Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-swf/" name="PDF Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-ppsx/" name="PDF Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-powerpoint/" name="PDF Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-potm/" name="PDF Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pdf-to-pot/" name="PDF Nak nek POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}