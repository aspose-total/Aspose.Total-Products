---
title: Az PPSM konvertálása JSON formátumba .NET-en keresztül
description: Konvertálja az PPSM-t JSON-ba C#-ban Microsoft Excel vagy Powerpoint használata nélkül
url_ignore: /hu/net/conversion/ppsm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja az PPSM-t JSON formátumba a C# segítségével" h2="Exportáljon PPSM-t JSON-ba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával az PPSM-t JSON formátumba konvertálhatja bármely .NET, C#, ASP.NET és VB.NET alkalmazáson belül két részből egyszerű lépéseket. Először is, az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával exportálhatja az PPSM-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t JSON-ba.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja az PPSM-t JSON formátumba a C# segítségével" %}}
1. Nyissa meg az PPSM-fájlt a [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
2. Alakítsa át az PPSM-t HTML-vé a [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett PPSM konvertálása JSON formátumba a C# segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt PPSM-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba jelszó nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan lehet titkosított dokumentumot jelszóval megnyitni.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja az PPSM-t JSON-ba a tartományban C#-on keresztül" %}}
Miközben az PPSM-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, lekérheti az adatokat tartalmazó munkalap CellsCollection-jét, létrehozhat egy tartományt a CellsCollection-ből sor- és oszlopindexek megadásával, és meghívhatja az ExportRangeToJson metódust Range & ExportRangeToJsonOptions objektumokra való hivatkozásokkal. Végül a JSON-adatokat fájlba mentheti a File.WriteAllText metódussal. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-doc/" name="PPSM Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-docm/" name="PPSM Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-docx/" name="PPSM Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dot/" name="PPSM Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dotm/" name="PPSM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dotx/" name="PPSM Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-odt/" name="PPSM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-ott/" name="PPSM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-rtf/" name="PPSM Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-text/" name="PPSM Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-word/" name="PPSM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-wordml/" name="PPSM Nak nek WORDML" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}