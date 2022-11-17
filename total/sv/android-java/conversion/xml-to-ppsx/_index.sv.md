---
title: Exportera XML till PPSX i Android
description: Android API för att konvertera XML till PPSX utan att använda Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: PPSX
otherformats: POTM SWF ODP POTX POT PPS XAML PPSM POWERPOINT PPTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera XML till PPSX på Android via Java" h2="Förvandla XML till PPSX i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera XML till PPSX-konverteringsfunktionen i dina Android-applikationer genom att använda två enkla steg. I det första steget kan du exportera XML till PPTX genom att använda [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Efter det, genom att använda [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), kan du konvertera PPTX till PPSX. Båda API:erna ingår i paketet [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera XML till PPSX" %}}
1. Öppna XML-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XML till PPTX genom att använda metoden [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i PPSX-format med metoden [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Ppsx` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) /androidjava/install-aspose-slides-for-android-via-java/) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddad XML-fil i Android via Java" %}}
När du laddar XML-filformat kan ditt dokument vara lösenordsskyddat. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa miniatyrbild av PPSX-fil i Android-applikationer" %}}
Efter att ha konverterat XML till PPSX kan du också skapa miniatyrbilder av ditt utdatadokument. Genom att använda rik på funktioner [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) kan du skapa miniatyrbilder av bilderna genom att skapa och instans av [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Efter det kan du få referensen till vilken önskad bild som helst genom att använda dess ID eller index och få miniatyrbilden av den refererade bilden i en specificerad skala.
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-potm/" name="XML Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-swf/" name="XML Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-ppsx/" name="XML Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-potx/" name="XML Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-pot/" name="XML Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-pps/" name="XML Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-xaml/" name="XML Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-ppsm/" name="XML Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-powerpoint/" name="XML Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-pptm/" name="XML Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-ppt/" name="XML Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xml-to-otp/" name="XML Till OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}