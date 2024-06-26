---
title: Konvertálja a JSON formátumot DOTX-re .NET-en keresztül
description: Elemezze a JSON-t DOTX-be C#-ban Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/json-to-dotx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC PCL EPUB FLATOPC DOCM ODT WORDML DOTX WORD MOBI PS DOT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot DOTX-re a C# segítségével" h2="A C# API a JSON-t DOTX-be elemezheti a Microsoft<sup>&reg;</sup> Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül a JSON-t DOTX-be elemezheti két egyszerű feladattal. lépések. Először is, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) használatával PDF-formátumba exportálhatja a JSON-t. Ezt követően az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával konvertálhatja a PDF-et DOTX formátumba.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot DOTX-re a C# segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Importálja a JSON-fájlt a munkalapra a [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) osztály és a [Save](https://reference.aspose.com/) használatával cell/net/aspose.cells.workbook/save/methods/4) PDF formátumban
3. Töltse be a PDF-dokumentumot a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
4. Mentse a dokumentumot DOTX formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést és konvertálja a JSON formátum](DOTX-re a C# segítségével" %}}
A JSON DOTX-re történő elemzése közben a JSON elrendezési beállításait is megadhatja a [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayotoptions) segítségével. Lehetővé teszi a tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JSON formátum elemzése DOTX-be vízjellel" %}}
Az API használatával a JSON-t vízjellel DOTX-re is konvertálhatja. Ha vízjelet szeretne hozzáadni a DOTX-dokumentumhoz, először elemezheti a JSON-fájlt PDF-be, és vízjelet adhat hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PDF-fájlt a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával, hozzon létre egy TextWatermarkOptions példányt, és állítsa be a tulajdonságait, Hívja a Watermark.SetText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát. A vízjel hozzáadása után a dokumentumot elmentheti a DOTX-be. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}