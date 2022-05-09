---
title: Converteer CGM naar APNG via Java
description: Exporteer CGM-bestand naar APNG in uw Java-applicaties zonder een applicatie van derden te gebruiken
url_ignore: /nl/java/conversion/cgm-to-apng/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: APNG
otherformats: EMZ TGA JPEG2000 IMAGE PSD WMZ SVGZ  WMF DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer CGM naar APNG via Java" h2="Exporteer CGM-bestand naar APNG binnen elke Java J2SE-, J2EE-, J2ME-toepassing zonder Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
U kunt het cgm-bestand in twee eenvoudige stappen naar een APNG-afbeelding in Java converteren. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u CGM naar JPEG exporteren. Daarna kunt u met behulp van [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API JPEG naar APNG renderen. Beide API's vallen onder het pakket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM exporteren naar APNG via Java" %}}
1. Open het CGM-bestand met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialiseer het klasseobject en render CGM naar JPEG met behulp van [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) methode
3. Laad JPEG-bestand met behulp van [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) class
4. Sla het document op in APNG-indeling met [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converteer CGM naar APNG in een enkel bestand via Java" %}}
Met de API kunt u ook een CGM-bestand naar APNG exporteren naar een enkel bestand. Om alle pagina's te converteren, kunt u eerst uw CGM-document renderen naar één TIFF-bestand en daarna het TIFF-bestand exporteren naar APNG. U kunt het invoerbestand openen met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) en apparaatobjecten Resolutie, TiffSettings en TIFF maken. U kunt een enkele TIFF-afbeelding verkrijgen met [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) methode van [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) klasse. Ten slotte kunt u het TIFF-bestand laden met de klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) en het opslaan in APNG-indeling met [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer CGM naar APNG met watermerk via Java" %}}
Met behulp van de API kunt u ook het CGM-bestand exporteren naar APNG met watermerk in uw APNG-document. Om een watermerk toe te voegen kan je eerst CGM naar JPEG converteren en er een watermerk in toevoegen. Om een watermerk toe te voegen, laadt u een afbeeldingsbestand met behulp van de klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), maakt u een object van de [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) en initialiseer deze met Image-object, maak een nieuwe [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object en stel de vertaling en transformatie in op de gewenste hoek en voeg een watermerk toe met [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) methode. Nadat u het watermerk aan uw afbeelding hebt toegevoegd, kunt u de JPEG opslaan als APNG-indeling. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer en roteer CGM naar APNG-bestand via Java" %}}
Met behulp van de API kunt u ook de uitgevoerde APNG-afbeelding roteren volgens uw behoeften. De Image.rotateFlip-methode kan worden gebruikt om de afbeelding 90/180/270-graden te roteren en de afbeelding horizontaal of verticaal te spiegelen. De bibliotheek biedt eenvoudige methoden om complexe bewerkingen uit te voeren terwijl alle lelijke details worden ingekapseld. U kunt het type rotatie en omdraaien opgeven dat op de afbeelding moet worden toegepast. Om de afbeelding te roteren en om te draaien, kunt u de geconverteerde JPEG-afbeelding laden met behulp van de klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) en de afbeelding aanroepen. roteerFlip-methode terwijl u het juiste [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) specificeert. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-emz/" name="CGM Tot EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-tga/" name="CGM Tot TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-jpeg2000/" name="CGM Tot JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-image/" name="CGM Tot IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-psd/" name="CGM Tot PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-wmz/" name="CGM Tot WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-svgz/" name="CGM Tot SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to/" name="CGM Tot" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-wmf/" name="CGM Tot WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-dxf/" name="CGM Tot DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/cgm-to-dicom/" name="CGM Tot DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}