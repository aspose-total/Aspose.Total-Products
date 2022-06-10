---
title: Konvertálja a XPS-et APNG-vé a C# API-n keresztül
description: Exportáljon XPS-et APNG formátumba .NET-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url_ignore: /hu/net/conversion/xps-to-apng/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: APNG
otherformats: DXF  PSD TGA IMAGE SVGZ JPEG2000 WMZ EMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XPS-fájl konvertálása APNG-re C#-on keresztül" h2="XPS exportálása APNG-be .NET-alkalmazásokon belül Adobe<sup>&reg;</sup> Acrobat Reader vagy bármely más harmadik féltől származó alkalmazás használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával két egyszerű lépésben könnyedén exportálhatja a XPS-et APNG-képfájlba bármely .NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a XPS-et JPEG formátumba. Ezt követően az [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API használatával konvertálhatja a JPEG-et APNG-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A XPS-fájl konvertálása APNG-re .NET-en keresztül" %}}
1. Nyissa meg a XPS-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Inicializálja a [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) osztályobjektumot, és a [Process](https://apireference.aspose.) segítségével jelenítse meg a XPS-et JPEG formátumba. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) módszer
3. Töltse be a JPEG fájlt az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
4. Mentse a dokumentumot APNG formátumba a [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XPS-fájl konvertálása APNG-re egyetlen fájlban C#-n keresztül" %}}
Az API használatával a XPS-fájlt APNG-re is konvertálhatja egyetlen képfájllá. Az összes oldal konvertálásához először előállíthatja a XPS-dokumentumot egyetlen TIFF-fájllá, majd exportálhatja a TIFF-fájlt APNG-be. A bemeneti fájlt megnyithatja a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) osztály. Végül betöltheti a TIFF-fájlt az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
és mentse APNG formátumba a [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="XPS-fájl konvertálása és elforgatása APNG-re C#-on keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti APNG-képet is. Az Image.RotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály által exponált gyári módszerrel, és meghívhatja a képet. .RotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-emz/" name="XPS Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-tga/" name="XPS Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-jpeg2000/" name="XPS Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-image/" name="XPS Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-psd/" name="XPS Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-wmz/" name="XPS Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-svgz/" name="XPS Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to/" name="XPS Nak nek" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-wmf/" name="XPS Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-dxf/" name="XPS Nak nek DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-dicom/" name="XPS Nak nek DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}