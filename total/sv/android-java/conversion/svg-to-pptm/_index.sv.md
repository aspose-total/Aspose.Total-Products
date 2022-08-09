---
title: Exportera SVG till PPTM i Android
description: Android API för att konvertera SVG till PPTM utan att använda Microsoft Word
url: /sv/android-java/conversion/svg-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: PPTM
otherformats: ODP POT POTM PPSX PPT SWF PPSM POWERPOINT OTP XAML PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera SVG till PPTM på Android via Java" h2="Förvandla SVG till PPTM i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera SVG till PPTM-konverteringsfunktionen i dina Android-applikationer genom att använda två enkla steg. I det första steget kan du exportera SVG till PPTX genom att använda [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/). Efter det, genom att använda [Aspose.Slides för Android via Java](https://products.aspose.com/slides/android-java/), kan du konvertera PPTX till PPTM. Båda API:erna ingår i paketet [Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera SVG till PPTM" %}}
1. Öppna SVG-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera SVG till PPTX genom att använda metoden [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i PPTM-format med metoden [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Pptm` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF för Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Slides för Android via Java](https://docs.aspose.com/slides) /androidjava/install-aspose-slides-for-android-via-java/) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddad SVG-fil i Android via Java" %}}
När du laddar SVG-filformat kan ditt dokument vara lösenordsskyddat. [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa miniatyrbild av PPTM-fil i Android-applikationer" %}}
Efter att ha konverterat SVG till PPTM kan du också skapa miniatyrbilder av ditt utdatadokument. Genom att använda rik på funktioner [Aspose.Slides för Android via Java](https://products.aspose.com/slides/android-java/) kan du skapa miniatyrbilder av bilderna genom att skapa och instans av [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Efter det kan du få referensen till vilken önskad bild som helst genom att använda dess ID eller index och få miniatyrbilden av den refererade bilden i en specificerad skala.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-pptm/" name="SVG Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-pot/" name="SVG Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-potm/" name="SVG Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-ppsx/" name="SVG Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-ppt/" name="SVG Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-swf/" name="SVG Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-ppsm/" name="SVG Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-powerpoint/" name="SVG Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-otp/" name="SVG Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-xaml/" name="SVG Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-pps/" name="SVG Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/svg-to-potx/" name="SVG Till POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}