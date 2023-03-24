---
title: Converteer PCL naar PSD via C# API
description: Exporteer PCL naar PSD in uw .NET-toepassingen zonder een toepassing van derden te gebruiken
url_ignore: /nl/net/conversion/pcl-to-psd/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: PSD
otherformats: SVGZ WMF PSD WMZ EMZ TGA JPEG2000 DXF  IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer PCL-bestand naar PSD via C#" h2="Exporteer PCL naar PSD binnen .NET-toepassingen zonder Adobe<sup>&reg;</sup> Acrobat Reader of andere toepassingen van derden te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u in twee eenvoudige stappen eenvoudig PCL naar PSD-afbeelding exporteren binnen elke .NET-toepassing. Allereerst, door [Aspose.PDF voor .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u PCL naar JPEG exporteren. Daarna kunt u met behulp van [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API JPEG naar PSD converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer PCL-bestand naar PSD via .NET" %}}
1. Open het PCL-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Initialiseer het klasseobject [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) en render PCL naar JPEG met behulp van [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) methode
3. Laad JPEG-bestand met behulp van [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
4. Sla het document op in PSD-indeling met de methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converteer PCL-bestand naar PSD in een enkel bestand via C#" %}}
Met behulp van de API kunt u ook het PCL-bestand naar PSD converteren naar een enkel afbeeldingsbestand. Om alle pagina's te converteren, kunt u eerst uw PCL-document renderen naar één TIFF-bestand en daarna het TIFF-bestand exporteren naar PSD. U kunt het invoerbestand openen met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) en apparaatobjecten Resolutie, TiffSettings en TIFF maken. U kunt een enkele TIFF-afbeelding verkrijgen met de [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) methode van [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) klasse. Ten slotte kunt u het TIFF-bestand laden met de klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
en sla het op in PSD-indeling met behulp van de methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer en roteer PCL-bestand naar PSD via C#" %}}
Met behulp van de API kunt u ook de uitgevoerde PSD-afbeelding roteren volgens uw behoeften. De Image.RotateFlip-methode kan worden gebruikt om de afbeelding 90/180/270-graden te roteren en de afbeelding horizontaal of verticaal te spiegelen. U kunt het type rotatie en omdraaien opgeven dat op de afbeelding moet worden toegepast. Om de afbeelding te roteren en om te draaien, kunt u de geconverteerde JPEG-afbeelding laden met behulp van de fabrieksmethode die wordt weergegeven door de klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) en de afbeelding aanroepen .RotateFlip-methode terwijl u het juiste [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) specificeert. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}