---
title: Konvertera PDF till EMZ via Java
description: Exportera PDF-fil till EMZ i dina Java-applikationer utan att använda någon tredjepartsapplikation
url_ignore: /sv/java/conversion/pdf-to-emz/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: EMZ
otherformats: SVGZ WMF IMAGE EMZ  DXF TGA JPEG2000 WMZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera PDF till EMZ via Java" h2="Exportera PDF-fil till EMZ inom valfri Java J2SE, J2EE, J2ME-applikation utan att använda Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera pdf-fil till EMZ-bild i Java i två enkla steg. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera PDF till JPEG. Efter det, genom att använda [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, kan du rendera JPEG till EMZ. Båda API:erna ingår i paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportera PDF till EMZ via Java" %}}
1. Öppna PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initiera klassobjektet och rendera PDF till JPEG genom att använda [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metod
3. Ladda JPEG-fil genom att använda klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Spara dokumentet i EMZ-format med [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till EMZ i en enda fil via Java" %}}
API:et låter dig också exportera PDF-fil till EMZ till en enda fil. För att konvertera alla sidor kan du först rendera ditt PDF-dokument till en TIFF-fil och efter det kan du exportera TIFF-filen till EMZ. Du kan öppna indatafilen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) och skapa enhetsobjekt Upplösning, TiffSettings och TIFF. Du kan få en enda TIFF-bild med [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metod av klassen [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Slutligen kan du ladda TIFF-filen med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) och spara den i EMZ-format med [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till EMZ med vattenstämpel via Java" %}}
Med hjälp av API:t kan du också exportera PDF-fil till EMZ med vattenstämpel i ditt EMZ-dokument. För att lägga till en vattenstämpel kan du först konvertera PDF till JPEG och lägga till en vattenstämpel i den. För att lägga till vattenstämpel, ladda en bildfil med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), skapa ett objekt av [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) klass och initiera den med bildobjekt, skapa en ny [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) och ställ in översättning och transformation till önskad vinkel och lägg till vattenstämpel med [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) metod. När du har lagt till vattenstämpeln i din bild kan du spara JPEG som EMZ-format. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera och rotera PDF till EMZ-fil via Java" %}}
Med hjälp av API:t kan du också rotera den utgående EMZ-bilden enligt dina behov. Metoden Image.rotateFlip kan användas för att rotera bilden 90/180/270 grader och vända bilden horisontellt eller vertikalt. Biblioteket tillhandahåller enkla metoder för att utföra komplexa operationer samtidigt som det kapslar in alla fula detaljer. Du kan ange vilken typ av rotation och vändning som ska tillämpas på bilden. För att rotera och vända bilden kan du ladda den konverterade JPEG-bilden med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) och anropa bilden. rotateFlip-metoden samtidigt som du anger lämplig [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**PDF till EMZ** konverteringsprocessen används när **vektorgrafik** från PDF-filer behöver lagras i **Enhanced Metafile (komprimerad)** format. Detta är särskilt användbart för publiceringsflöden, skalbar bildlagring och integrering av PDF-grafik i Windows-applikationer.
{{% blocks/products/pf/agp/feature-section-col title="Huvudsakliga användningsområden" %}}
- Publiceringsflöden som kräver EMZ vektorgrafik
- Arkivering av PDF-illustrationer i komprimerade EMZ-filer
- Konvertering av diagram för teknisk dokumentation
- EMZ-integration med Microsoft Office-applikationer
- Effektiv lagring av skalbara PDF-bilder
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario" %}}
- Batch **PDF till EMZ bildkonvertering**
- Automatiserade flöden för PDF-diagram till EMZ
- Skalbara vektorflöden med användning av EMZ-filer
- Integration av PDF-till-EMZ-export i företagspublicering
- Automatisk grafisk komprimering för dokumenthanteringssystem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}