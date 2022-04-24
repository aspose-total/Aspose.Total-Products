---
title: Konvertálja a EPUB-et EMZ-vé a C# API-n keresztül
description: Exportáljon EPUB-et EMZ formátumba .NET-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url: /hu/net/conversion/epub-to-emz/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: EMZ
otherformats: JPEG2000 DXF WMZ IMAGE SVGZ TGA WMF PSD  EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EPUB-fájl konvertálása EMZ-re C#-on keresztül" h2="EPUB exportálása EMZ-be .NET-alkalmazásokon belül Adobe<sup>&reg;</sup> Acrobat Reader vagy bármely más harmadik féltől származó alkalmazás használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával két egyszerű lépésben könnyedén exportálhatja a EPUB-et EMZ-képfájlba bármely .NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a EPUB-et JPEG formátumba. Ezt követően az [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API használatával konvertálhatja a JPEG-et EMZ-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A EPUB-fájl konvertálása EMZ-re .NET-en keresztül" %}}
1. Nyissa meg a EPUB-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Inicializálja a [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) osztályobjektumot, és a [Process](https://apireference.aspose.) segítségével jelenítse meg a EPUB-et JPEG formátumba. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) módszer
3. Töltse be a JPEG fájlt az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
4. Mentse a dokumentumot EMZ formátumba a [Mentés](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="EPUB-fájl konvertálása EMZ-re egyetlen fájlban C#-n keresztül" %}}
Az API használatával a EPUB-fájlt EMZ-re is konvertálhatja egyetlen képfájllá. Az összes oldal konvertálásához először előállíthatja a EPUB-dokumentumot egyetlen TIFF-fájllá, majd exportálhatja a TIFF-fájlt EMZ-be. A bemeneti fájlt megnyithatja a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [TiffDevice] [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) metódusával (https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) osztály. Végül betöltheti a TIFF-fájlt az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
és mentse EMZ formátumba a [Mentés](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="EPUB-fájl konvertálása és elforgatása EMZ-re C#-on keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti EMZ-képet is. Az Image.RotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály által exponált gyári módszerrel, és meghívhatja a képet. .RotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-emz/" name="EPUB Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-tga/" name="EPUB Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-jpeg2000/" name="EPUB Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-image/" name="EPUB Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-psd/" name="EPUB Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-wmz/" name="EPUB Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-svgz/" name="EPUB Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to/" name="EPUB Nak nek" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-wmf/" name="EPUB Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-dxf/" name="EPUB Nak nek DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-dicom/" name="EPUB Nak nek DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}