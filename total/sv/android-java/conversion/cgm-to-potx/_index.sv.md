---
title: Exportera CGM till POTX i Android
description: Android API för att konvertera CGM till POTX utan att använda Microsoft Word
url: /sv/android-java/conversion/cgm-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POTX
otherformats: PPTM SWF XAML OTP PPS PPSM ODP PPT PPSX POWERPOINT POT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera CGM till POTX på Android via Java" h2="Förvandla CGM till POTX i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera CGM till POTX-konverteringsfunktionen i dina Android-applikationer genom att använda två enkla steg. I det första steget kan du exportera CGM till PPTX genom att använda [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/). Efter det, genom att använda [Aspose.Slides för Android via Java](https://products.aspose.com/slides/android-java/), kan du konvertera PPTX till POTX. Båda API:erna ingår i paketet [Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera CGM till POTX" %}}
1. Öppna CGM-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera CGM till PPTX genom att använda metoden [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i POTX-format med metoden [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Potx` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF för Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Slides för Android via Java](https://docs.aspose.com/slides) /androidjava/install-aspose-slides-for-android-via-java/) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddad CGM-fil i Android via Java" %}}
När du laddar CGM-filformat kan ditt dokument vara lösenordsskyddat. [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa miniatyrbild av POTX-fil i Android-applikationer" %}}
Efter att ha konverterat CGM till POTX kan du också skapa miniatyrbilder av ditt utdatadokument. Genom att använda rik på funktioner [Aspose.Slides för Android via Java](https://products.aspose.com/slides/android-java/) kan du skapa miniatyrbilder av bilderna genom att skapa och instans av [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Efter det kan du få referensen till vilken önskad bild som helst genom att använda dess ID eller index och få miniatyrbilden av den refererade bilden i en specificerad skala.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-pptm/" name="CGM Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-swf/" name="CGM Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-xaml/" name="CGM Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-otp/" name="CGM Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-pps/" name="CGM Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-ppsm/" name="CGM Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-potx/" name="CGM Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-ppt/" name="CGM Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-ppsx/" name="CGM Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-powerpoint/" name="CGM Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-pot/" name="CGM Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/cgm-to-potm/" name="CGM Till POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}