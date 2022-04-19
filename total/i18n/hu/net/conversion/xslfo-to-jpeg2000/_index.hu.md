---
title: Konvertálja a XSLFO-et JPEG2000-vé a C# API-n keresztül
description: Exportáljon XSLFO-et JPEG2000 formátumba .NET-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url: /hu/net/conversion/xslfo-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: JPEG2000
otherformats: TGA PSD EMZ SVGZ WMF DXF WMZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XSLFO-fájl konvertálása JPEG2000-re C#-on keresztül" h2="XSLFO exportálása JPEG2000-be .NET-alkalmazásokon belül Adobe<sup>&reg;</sup> Acrobat Reader vagy bármely más harmadik féltől származó alkalmazás használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET] (https://products.aspose.com/total/net/) használatával két egyszerű lépésben könnyedén exportálhatja a XSLFO-et JPEG2000-képfájlba bármely .NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) használatával exportálhatja a XSLFO-et JPEG formátumba. Ezt követően az [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API használatával konvertálhatja a JPEG-et JPEG2000-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A XSLFO-fájl konvertálása JPEG2000-re .NET-en keresztül" %}}
1. Nyissa meg a XSLFO-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Inicializálja a [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) osztályobjektumot, és a [Process] (https://apireference.aspose.) segítségével jelenítse meg a XSLFO-et JPEG formátumba. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) módszer
3. Töltse be a JPEG fájlt az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
4. Mentse a dokumentumot JPEG2000 formátumba a [Mentés](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XSLFO-fájl konvertálása JPEG2000-re egyetlen fájlban C#-n keresztül" %}}
Az API használatával a XSLFO-fájlt JPEG2000-re is konvertálhatja egyetlen képfájllá. Az összes oldal konvertálásához először előállíthatja a XSLFO-dokumentumot egyetlen TIFF-fájllá, majd exportálhatja a TIFF-fájlt JPEG2000-be. A bemeneti fájlt megnyithatja a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [TiffDevice] [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) metódusával (https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) osztály. Végül betöltheti a TIFF-fájlt az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
és mentse JPEG2000 formátumba a [Mentés](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XSLFO-fájl konvertálása és elforgatása JPEG2000-re C#-on keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti JPEG2000-képet is. Az Image.RotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) osztály által exponált gyári módszerrel, és meghívhatja a képet. .RotateFlip metódust, miközben megadja a megfelelő [RotateFlipType] (https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-emz/" name="XSLFO Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-tga/" name="XSLFO Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-jpeg2000/" name="XSLFO Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-image/" name="XSLFO Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-psd/" name="XSLFO Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-wmz/" name="XSLFO Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-svgz/" name="XSLFO Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to/" name="XSLFO Nak nek" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-wmf/" name="XSLFO Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-dxf/" name="XSLFO Nak nek DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-dicom/" name="XSLFO Nak nek DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}