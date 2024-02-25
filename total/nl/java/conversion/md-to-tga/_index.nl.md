---
title: Converteer MD naar TGA via Java
description: Exporteer MD-bestand naar TGA in uw Java-applicaties zonder een applicatie van derden te gebruiken
url_ignore: /nl/java/conversion/md-to-tga/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TGA
otherformats: IMAGE WMF TGA WMZ SVGZ EMZ  PSD DXF JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer MD naar TGA via Java" h2="Exporteer MD-bestand naar TGA binnen elke Java J2SE-, J2EE-, J2ME-toepassing zonder Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
U kunt het md-bestand in twee eenvoudige stappen naar een TGA-afbeelding in Java converteren. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u MD naar JPEG exporteren. Daarna kunt u met behulp van [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API JPEG naar TGA renderen. Beide API's vallen onder het pakket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD exporteren naar TGA via Java" %}}
1. Open het MD-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialiseer het klasseobject en render MD naar JPEG met behulp van [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) methode
3. Laad JPEG-bestand met behulp van [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class
4. Sla het document op in TGA-indeling met [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converteer MD naar TGA in een enkel bestand via Java" %}}
Met de API kunt u ook een MD-bestand naar TGA exporteren naar een enkel bestand. Om alle pagina's te converteren, kunt u eerst uw MD-document renderen naar één TIFF-bestand en daarna het TIFF-bestand exporteren naar TGA. U kunt het invoerbestand openen met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) en apparaatobjecten Resolutie, TiffSettings en TIFF maken. U kunt een enkele TIFF-afbeelding verkrijgen met [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) methode van [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) klasse. Ten slotte kunt u het TIFF-bestand laden met de klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) en het opslaan in TGA-indeling met [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer MD naar TGA met watermerk via Java" %}}
Met behulp van de API kunt u ook het MD-bestand exporteren naar TGA met watermerk in uw TGA-document. Om een watermerk toe te voegen kan je eerst MD naar JPEG converteren en er een watermerk in toevoegen. Om een watermerk toe te voegen, laadt u een afbeeldingsbestand met behulp van de klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), maakt u een object van de [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) en initialiseer deze met Image-object, maak een nieuwe [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object en stel de vertaling en transformatie in op de gewenste hoek en voeg een watermerk toe met [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) methode. Nadat u het watermerk aan uw afbeelding hebt toegevoegd, kunt u de JPEG opslaan als TGA-indeling. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer en roteer MD naar TGA-bestand via Java" %}}
Met behulp van de API kunt u ook de uitgevoerde TGA-afbeelding roteren volgens uw behoeften. De Image.rotateFlip-methode kan worden gebruikt om de afbeelding 90/180/270-graden te roteren en de afbeelding horizontaal of verticaal te spiegelen. De bibliotheek biedt eenvoudige methoden om complexe bewerkingen uit te voeren terwijl alle lelijke details worden ingekapseld. U kunt het type rotatie en omdraaien opgeven dat op de afbeelding moet worden toegepast. Om de afbeelding te roteren en om te draaien, kunt u de geconverteerde JPEG-afbeelding laden met behulp van de klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) en de afbeelding aanroepen. roteerFlip-methode terwijl u het juiste [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) specificeert. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}