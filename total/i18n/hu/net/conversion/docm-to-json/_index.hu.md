---
title: A DOCM konvertálása JSON formátumba .NET-en keresztül
description: Konvertálja a DOCM-t JSON-ba C#-ban Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/net/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: ODS XLTM XLAM FODS DIF XLS XLSM TSV XLTX EXCEL XLSB SXC CSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOCM konvertálása JSON formátumba a C# segítségével" h2="Elemezze a DOCM-t JSON-ba C#-on keresztül Microsoft<sup>&reg;</sup> Word vagy Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával bármely .NET, C#, ASP.NET és VB.NET alkalmazáson belül a DOCM-t JSON formátumba konvertálhatja két részből egyszerű lépéseket. Először is, az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával exportálhatja a DOCM-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t JSON-ba.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A DOCM konvertálása JSON formátumba a C# segítségével" %}}
1. Nyissa meg a DOCM-fájlt a [Docmument](https://apireference.aspose.com/words/net/aspose.words/docmument) osztály használatával
2. Alakítsa át a DOCM-t HTML-vé a [Mentés](https://apireference.aspose.com/words/net/aspose.words.docmument/save/methods/4) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [Mentés](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett DOCM konvertálása JSON formátumba a C# segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt DOCM-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba a jelszó használata nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan próbáljon meg jelszóval megnyitni egy titkosított dokumentumot:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a DOCM-t JSON-ba a tartományban C#-on keresztül" %}}
Miközben a DOCM-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, lekérheti az adatokat tartalmazó munkalap CellsCollection-jét, létrehozhat egy tartományt a CellsCollection-ből sor- és oszlopindexek megadásával, és meghívhatja az ExportRangeToJson metódust Range & ExportRangeToJsonOptions objektumokra való hivatkozásokkal. Végül a JSON-adatokat fájlba mentheti a File.WriteAllText metódussal. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-csv/" name="DOCM Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xlam/" name="DOCM Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-sxc/" name="DOCM Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-tsv/" name="DOCM Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xlt/" name="DOCM Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-excel/" name="DOCM Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-dif/" name="DOCM Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xlsm/" name="DOCM Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xltm/" name="DOCM Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xlsx/" name="DOCM Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xlsb/" name="DOCM Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-fods/" name="DOCM Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-ods/" name="DOCM Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/docm-to-xltx/" name="DOCM Nak nek XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}