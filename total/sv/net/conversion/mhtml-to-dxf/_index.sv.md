---
title: Konvertera MHTML till DXF via C# API
description: Exportera MHTML till DXF i dina .NET-applikationer utan att använda någon tredjepartsapplikation
url_ignore: /sv/net/conversion/mhtml-to-dxf/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DXF
otherformats: SVGZ EMZ  DXF WMF WMZ PSD IMAGE TGA JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera MHTML-fil till DXF via C#" h2="Exportera MHTML till DXF i .NET-applikationer utan att använda Adobe<sup>&reg;</sup> Acrobat Reader eller andra tredjepartsprogram" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt exportera MHTML till DXF-bild i alla .NET-applikationer i två enkla steg. Först och främst, genom att använda [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du exportera MHTML till JPEG. Efter det, genom att använda [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, kan du konvertera JPEG till DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MHTML-fil till DXF via .NET" %}}
1. Öppna MHTML-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Initiera klassobjektet [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) och rendera MHTML till JPEG genom att använda [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metod
3. Ladda JPEG-fil genom att använda klassen [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Spara dokumentet i DXF-format med metoden [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera MHTML-fil till DXF i en enda fil via C#" %}}
Med hjälp av API:t kan du också konvertera MHTML-fil till DXF till en enda bildfil. För att konvertera alla sidor kan du först rendera ditt MHTML-dokument till en TIFF-fil och efter det kan du exportera TIFF-fil till DXF. Du kan öppna indatafilen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) och skapa enhetsobjekt Upplösning, TiffSettings och TIFF. Du kan få en enda TIFF-bild med metoden [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) enligt [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Slutligen kan du ladda TIFF-filen med klassen [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
och spara den i DXF-format med metoden [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera & rotera MHTML-fil till DXF via C#" %}}
Med hjälp av API:t kan du också rotera den utgående DXF-bilden enligt dina behov. Metoden Image.RotateFlip kan användas för att rotera bilden 90/180/270 grader och vända bilden horisontellt eller vertikalt. Du kan ange vilken typ av rotation och vändning som ska tillämpas på bilden. För att rotera och vända bilden kan du ladda den konverterade JPEG-bilden med fabriksmetoden exponerad av klassen [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) och anropa bilden .RotateFlip-metoden samtidigt som du anger lämplig [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-emz/" name="MHTML Till EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-tga/" name="MHTML Till TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-jpeg2000/" name="MHTML Till JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-image/" name="MHTML Till IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-psd/" name="MHTML Till PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-wmz/" name="MHTML Till WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-svgz/" name="MHTML Till SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to/" name="MHTML Till" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-wmf/" name="MHTML Till WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-dxf/" name="MHTML Till DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-dicom/" name="MHTML Till DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}