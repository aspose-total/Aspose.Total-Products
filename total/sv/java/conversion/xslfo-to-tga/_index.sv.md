---
title: Konvertera XSLFO till TGA via Java
description: Exportera XSLFO-fil till TGA i dina Java-applikationer utan att använda någon tredjepartsapplikation
url_ignore: /sv/java/conversion/xslfo-to-tga/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: TGA
otherformats: DXF EMZ WMZ JPEG2000  TGA IMAGE PSD SVGZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera XSLFO till TGA via Java" h2="Exportera XSLFO-fil till TGA inom valfri Java J2SE, J2EE, J2ME-applikation utan att använda Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera xslfo-fil till TGA-bild i Java i två enkla steg. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera XSLFO till JPEG. Efter det, genom att använda [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, kan du rendera JPEG till TGA. Båda API:erna ingår i paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportera XSLFO till TGA via Java" %}}
1. Öppna XSLFO-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initiera klassobjektet och rendera XSLFO till JPEG genom att använda [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metod
3. Ladda JPEG-fil genom att använda klassen [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Spara dokumentet i TGA-format med [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera XSLFO till TGA i en enda fil via Java" %}}
API:et låter dig också exportera XSLFO-fil till TGA till en enda fil. För att konvertera alla sidor kan du först rendera ditt XSLFO-dokument till en TIFF-fil och efter det kan du exportera TIFF-filen till TGA. Du kan öppna indatafilen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) och skapa enhetsobjekt Upplösning, TiffSettings och TIFF. Du kan få en enda TIFF-bild med [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metod av klassen [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Slutligen kan du ladda TIFF-filen med klassen [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) och spara den i TGA-format med [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera XSLFO till TGA med vattenstämpel via Java" %}}
Med hjälp av API:t kan du också exportera XSLFO-fil till TGA med vattenstämpel i ditt TGA-dokument. För att lägga till en vattenstämpel kan du först konvertera XSLFO till JPEG och lägga till en vattenstämpel i den. För att lägga till vattenstämpel, ladda en bildfil med klassen [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), skapa ett objekt av [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) klass och initiera den med bildobjekt, skapa en ny [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) och ställ in översättning och transformation till önskad vinkel och lägg till vattenstämpel med [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) metod. När du har lagt till vattenstämpeln i din bild kan du spara JPEG som TGA-format. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera och rotera XSLFO till TGA-fil via Java" %}}
Med hjälp av API:t kan du också rotera den utgående TGA-bilden enligt dina behov. Metoden Image.rotateFlip kan användas för att rotera bilden 90/180/270 grader och vända bilden horisontellt eller vertikalt. Biblioteket tillhandahåller enkla metoder för att utföra komplexa operationer samtidigt som det kapslar in alla fula detaljer. Du kan ange vilken typ av rotation och vändning som ska tillämpas på bilden. För att rotera och vända bilden kan du ladda den konverterade JPEG-bilden med klassen [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) och anropa bilden. rotateFlip-metoden samtidigt som du anger lämplig [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-emz/" name="XSLFO Till EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-tga/" name="XSLFO Till TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-jpeg2000/" name="XSLFO Till JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-image/" name="XSLFO Till IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-psd/" name="XSLFO Till PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-wmz/" name="XSLFO Till WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-svgz/" name="XSLFO Till SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to/" name="XSLFO Till" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-wmf/" name="XSLFO Till WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-dxf/" name="XSLFO Till DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-dicom/" name="XSLFO Till DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}