---
title: Konvertera TEX till JPEG2000 via C# API
description: Exportera TEX till JPEG2000 i dina .NET-applikationer utan att använda någon tredjepartsapplikation
url_ignore: /sv/net/conversion/tex-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: JPEG2000
otherformats: DXF SVGZ IMAGE EMZ JPEG2000 WMF PSD  TGA WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera TEX-fil till JPEG2000 via C#" h2="Exportera TEX till JPEG2000 i .NET-applikationer utan att använda Adobe<sup>&reg;</sup> Acrobat Reader eller andra tredjepartsprogram" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt exportera TEX till JPEG2000-bild i alla .NET-applikationer i två enkla steg. Först och främst, genom att använda [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du exportera TEX till JPEG. Efter det, genom att använda [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, kan du konvertera JPEG till JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera TEX-fil till JPEG2000 via .NET" %}}
1. Öppna TEX-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Initiera klassobjektet [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) och rendera TEX till JPEG genom att använda [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metod
3. Ladda JPEG-fil genom att använda klassen [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Spara dokumentet i JPEG2000-format med metoden [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera TEX-fil till JPEG2000 i en enda fil via C#" %}}
Med hjälp av API:t kan du också konvertera TEX-fil till JPEG2000 till en enda bildfil. För att konvertera alla sidor kan du först rendera ditt TEX-dokument till en TIFF-fil och efter det kan du exportera TIFF-fil till JPEG2000. Du kan öppna indatafilen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) och skapa enhetsobjekt Upplösning, TiffSettings och TIFF. Du kan få en enda TIFF-bild med metoden [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) enligt [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Slutligen kan du ladda TIFF-filen med klassen [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
och spara den i JPEG2000-format med metoden [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera & rotera TEX-fil till JPEG2000 via C#" %}}
Med hjälp av API:t kan du också rotera den utgående JPEG2000-bilden enligt dina behov. Metoden Image.RotateFlip kan användas för att rotera bilden 90/180/270 grader och vända bilden horisontellt eller vertikalt. Du kan ange vilken typ av rotation och vändning som ska tillämpas på bilden. För att rotera och vända bilden kan du ladda den konverterade JPEG-bilden med fabriksmetoden exponerad av klassen [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) och anropa bilden .RotateFlip-metoden samtidigt som du anger lämplig [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}