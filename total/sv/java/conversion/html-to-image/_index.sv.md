---
title: Konvertera HTML till IMAGE via Java
description: Exportera HTML-fil till IMAGE i dina Java-applikationer utan att använda någon tredjepartsapplikation
url_ignore: /sv/java/conversion/html-to-image/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: JPEG2000
otherformats: EMZ JPEG2000 PSD WMF TGA SVGZ WMZ DXF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera HTML till IMAGE via Java" h2="Exportera HTML-fil till IMAGE inom valfri Java J2SE, J2EE, J2ME-applikation utan att använda Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera html-fil till IMAGE-bild i Java i två enkla steg. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera HTML till JPEG. Efter det, genom att använda [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, kan du rendera JPEG till IMAGE. Båda API:erna ingår i paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportera HTML till IMAGE via Java" %}}
1. Öppna HTML-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initiera klassobjektet och rendera HTML till JPEG genom att använda [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metod
3. Ladda JPEG-fil genom att använda klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Spara dokumentet i IMAGE-format med [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera HTML till IMAGE i en enda fil via Java" %}}
API:et låter dig också exportera HTML-fil till IMAGE till en enda fil. För att konvertera alla sidor kan du först rendera ditt HTML-dokument till en TIFF-fil och efter det kan du exportera TIFF-filen till IMAGE. Du kan öppna indatafilen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) och skapa enhetsobjekt Upplösning, TiffSettings och TIFF. Du kan få en enda TIFF-bild med [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metod av klassen [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Slutligen kan du ladda TIFF-filen med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) och spara den i IMAGE-format med [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera HTML till IMAGE med vattenstämpel via Java" %}}
Med hjälp av API:t kan du också exportera HTML-fil till IMAGE med vattenstämpel i ditt IMAGE-dokument. För att lägga till en vattenstämpel kan du först konvertera HTML till JPEG och lägga till en vattenstämpel i den. För att lägga till vattenstämpel, ladda en bildfil med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), skapa ett objekt av [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) klass och initiera den med bildobjekt, skapa en ny [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) och ställ in översättning och transformation till önskad vinkel och lägg till vattenstämpel med [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) metod. När du har lagt till vattenstämpeln i din bild kan du spara JPEG som IMAGE-format. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera och rotera HTML till IMAGE-fil via Java" %}}
Med hjälp av API:t kan du också rotera den utgående IMAGE-bilden enligt dina behov. Metoden Image.rotateFlip kan användas för att rotera bilden 90/180/270 grader och vända bilden horisontellt eller vertikalt. Biblioteket tillhandahåller enkla metoder för att utföra komplexa operationer samtidigt som det kapslar in alla fula detaljer. Du kan ange vilken typ av rotation och vändning som ska tillämpas på bilden. För att rotera och vända bilden kan du ladda den konverterade JPEG-bilden med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) och anropa bilden. rotateFlip-metoden samtidigt som du anger lämplig [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Att konvertera **HTML** till **BILD** är avgörande för att fånga exakta visuella ögonblicksbilder av webbsidor. Denna process gör det möjligt för designers, marknadsförare och utvecklare att omvandla dynamiskt eller statiskt webbinnehåll till delningsbara, visningsbara bilder som bevarar webbplatsernas utseende och känsla över olika enheter. Genom att skapa bildrepresentationer av webbsidor kan team effektivisera förhandsgranskningar, förbättra digitalt innehåll och effektivt behålla visuella register.

{{% blocks/products/pf/agp/feature-section-col title="Viktiga Användningsfall" %}}

* **Webbplatsförhandsvisningar:** Generera ögonblicksbilder för portföljer, kundrecensioner eller snabba visuella referenser.
* **Infografik:** Konvertera datarika webbsidor till delningsbara visuella format.
* **UI/UX Designarbetsflöden:** Fånga sidodesign för testning, feedback och iteration.
* **Arkivskärmbilder:** Bevara historiska versioner av webbplatser för efterlevnad eller dokumentation.
* **Digitala marknadsföringsresurser:** Skapa banners, sociala mediebilder och marknadsföringsgrafik direkt från webbinnehåll.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario" %}}

* **HTML-till-BILD Pipelines:** Konvertera sömlöst flera webbsidor till bilder med minimal manuell ansträngning.
* **Automatiserad Webbplats-till-Bild Rendering:** Schemalägg rendering av dynamiska sidor för rapportering eller övervakning.
* **Massgenerering av skärmbilder:** Fånga hundratals sidor samtidigt för storskaliga projekt.
* **Digital Publicering i Företagsskala:** Integrera bildgenerering i innehållsarbetsflöden för webbplatser, nyhetsbrev eller produktkataloger.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}