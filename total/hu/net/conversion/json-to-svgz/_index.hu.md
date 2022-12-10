---
title: Konvertálja a JSON-formátumot SVGZ-vé .NET-en keresztül
description: Elemezze a JSON-t SVGZ-re C#-ban harmadik féltől származó függőségek használata nélkül
url_ignore: /hu/net/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE WMF DXF TGA SVGZ PSD WMZ DICOM JPEG2000 EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot SVGZ-re a C# segítségével" h2="C# API a JSON-nak SVGZ-be történő elemzéséhez harmadik féltől származó függőségek használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül elemezheti a JSON-t SVGZ-be, két egyszerű módon. lépések. Először is, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) használatával JSON-t exportálhat JPEG formátumba. Ezt követően az [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) használatával konvertálhatja a JPEG-et SVGZ-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot SVGZ-re a C# segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) objektumot, és olvassa be a JSON-adatokat a fájlból
2. Konvertálja a JSON fájlt JPEG formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) módszerrel
3. Töltse be a JPEG dokumentumot az [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) osztály használatával
4. Mentse a dokumentumot SVGZ formátumba a [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátu]( SVGZ-re a C#-on keresztül" %}}
A JSON SVGZ-re történő elemzése közben a JSON elrendezési beállításait is megadhatja a [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayotoptions) segítségével. Lehetővé teszi a tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JSON formátum elemzése SVGZ-re vízjellel" %}}
Az API használatával a JSON-t SVGZ-vé alakíthatja vízjellel az SVGZ-dokumentumban. Vízjel hozzáadásához először előállíthatja a JSON-dokumentumot JPEG formátumban, és vízjelet adhat hozzá. A művelet bemutatásához töltse be az átalakított JPEG képet, átalakításokat adjon hozzá egy Matrix osztályú objektum segítségével, és rajzoljon egy karakterláncot vízjelként a kép felületére a [Graphics](https://reference.aspose.com/imaging/) segítségével. net/aspose.imaging/graphics) osztály” [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) módszerrel. Miután hozzáadta a vízjelet, elmentheti a JPEG-et SVGZ formátumban. Az alábbiakban egy kódpélda látható, amely bemutatja, hogyan adhat átlós vízjelet a dokumentumhoz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-wmz/" name="JSON Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-dicom/" name="JSON Nak nek DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-psd/" name="JSON Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-jpeg2000/" name="JSON Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-tga/" name="JSON Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-emz/" name="JSON Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-svgz/" name="JSON Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-wmf/" name="JSON Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-image/" name="JSON Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-dxf/" name="JSON Nak nek DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}