---
title: .NET API a WORD konvertálásához SXC-vé
description: C# API a WORD konvertálásához SXC-vé Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/word-to-sxc/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: SXC
otherformats: XLS DIF XLSB TSV FODS XLSM EXCEL XLT SXC XLSX XLTM XLAM XLTX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a WORD konvertálásához SXC-vé" h2="WORD exportálása SXC-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával beépíthet WORD-ból SXC-vé konvertáló funkciót bármely .NET, C#, ASP.NET és VB.NET alkalmazásba. két egyszerű lépés. Először is, az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával exportálhatja a WORD-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t SXC-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a WORD konvertálásához SXC-vé" %}}
1. Nyissa meg a WORD-fájlt a [Document](https://apireference.aspose.com/words/net/aspose.words/document) osztály használatával
2. Alakítsa át a WORD-t HTML-vé a [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot SXC-formátumba a [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „SXC”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="WORD dokumentum betöltése a Streamből C#-on keresztül" %}}
Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) lehetővé teszi a WORD-dokumentumok adatfolyamon keresztüli betöltését is. Egy dokumentum adatfolyamból való megnyitásához egyszerűen adja át a dokumentumot tartalmazó adatfolyam objektumot a [Document](https://apireference.aspose.com/words/net/aspose.words/document) konstruktornak. A következő kódpélda bemutatja, hogyan lehet megnyitni egy dokumentumot adatfolyamból:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyéni tulajdonságok hozzáadása a SXC-fájlhoz C#-on keresztül" %}}
Miközben a WORD-t SXC-vé alakítja, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) lehetővé teszi egyéni tulajdonságok hozzáadását a SXC-dokumentumokhoz. Egyéni tulajdonság hozzáadásához használhatja az [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) metódust a [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) osztály. Az Add metódus hozzáadja a tulajdonságot az Excel-fájlhoz, és az új dokumentumtulajdonság hivatkozását adja vissza [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties) néven. /dokumentumtulajdonság) objektum. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-dif/" name="WORD Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsb/" name="WORD Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-tsv/" name="WORD Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-fods/" name="WORD Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlt/" name="WORD Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-excel/" name="WORD Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsx/" name="WORD Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-ods/" name="WORD Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-sxc/" name="WORD Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlam/" name="WORD Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xltm/" name="WORD Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsm/" name="WORD Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xls/" name="WORD Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xltx/" name="WORD Nak nek XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}