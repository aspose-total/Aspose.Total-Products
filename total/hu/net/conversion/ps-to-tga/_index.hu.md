---
title: Konvertálja a PS-et TGA-vé a C# API-n keresztül
description: Exportáljon PS-et TGA formátumba .NET-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url_ignore: /hu/net/conversion/ps-to-tga/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: TGA
otherformats: TGA DXF IMAGE PSD EMZ  JPEG2000 SVGZ WMF WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PS-fájl konvertálása TGA-re C#-on keresztül" h2="PS exportálása TGA-be .NET-alkalmazásokon belül Adobe<sup>&reg;</sup> Acrobat Reader vagy bármely más harmadik féltől származó alkalmazás használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával két egyszerű lépésben könnyedén exportálhatja a PS-et TGA-képfájlba bármely .NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a PS-et JPEG formátumba. Ezt követően az [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API használatával konvertálhatja a JPEG-et TGA-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A PS-fájl konvertálása TGA-re .NET-en keresztül" %}}
1. Nyissa meg a PS-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Inicializálja a [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) osztályobjektumot, és a [Process](https://apireference.aspose.) segítségével jelenítse meg a PS-et JPEG formátumba. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) módszer
3. Töltse be a JPEG fájlt az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
4. Mentse a dokumentumot TGA formátumba a [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="PS-fájl konvertálása TGA-re egyetlen fájlban C#-n keresztül" %}}
Az API használatával a PS-fájlt TGA-re is konvertálhatja egyetlen képfájllá. Az összes oldal konvertálásához először előállíthatja a PS-dokumentumot egyetlen TIFF-fájllá, majd exportálhatja a TIFF-fájlt TGA-be. A bemeneti fájlt megnyithatja a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) osztály. Végül betöltheti a TIFF-fájlt az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
és mentse TGA formátumba a [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="PS-fájl konvertálása és elforgatása TGA-re C#-on keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti TGA-képet is. Az Image.RotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály által exponált gyári módszerrel, és meghívhatja a képet. .RotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}