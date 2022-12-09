---
title: .NET API a DOT konvertálásához XLTX-vé
description: C# API a DOT konvertálásához XLTX-vé Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/dot-to-xltx/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: XLTX
otherformats: DIF XLS XLT XLSM FODS XLAM XLTM ODS XLTX EXCEL XLSX SXC TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a DOT konvertálásához XLTX-vé" h2="DOT exportálása XLTX-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával beépíthet DOT-ból XLTX-vé konvertáló funkciót bármely .NET, C#, ASP.NET és VB.NET alkalmazásba. két egyszerű lépés. Először is, az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával exportálhatja a DOT-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t XLTX-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a DOT konvertálásához XLTX-vé" %}}
1. Nyissa meg a DOT-fájlt a [Document](https://reference.aspose.com/words/net/aspose.words/Document) osztály használatával
2. Alakítsa át a DOT-t HTML-vé a [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLTX-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „XLTX”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="DOT dokumentum betöltése a Streamből C#-on keresztül" %}}
Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) lehetővé teszi a DOT-dokumentumok adatfolyamon keresztüli betöltését is. Egy dokumentum adatfolyamból való megnyitásához egyszerűen adja át a dokumentumot tartalmazó adatfolyam objektumot a [Document](https://reference.aspose.com/words/net/aspose.words/Document) konstruktornak. A következő kódpélda bemutatja, hogyan lehet megnyitni egy dokumentumot adatfolyamból:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyéni tulajdonságok hozzáadása a XLTX-fájlhoz C#-on keresztül" %}}
Miközben a DOT-t XLTX-vé alakítja, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) lehetővé teszi egyéni tulajdonságok hozzáadását a XLTX-dokumentumokhoz. Egyéni tulajdonság hozzáadásához használhatja az [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) metódust a [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) osztály. Az Add metódus hozzáadja a tulajdonságot az Excel-fájlhoz, és az új dokumentumtulajdonság hivatkozását adja vissza [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties) néven. /dokumentumtulajdonság) objektum. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-dif/" name="DOT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsb/" name="DOT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-tsv/" name="DOT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-fods/" name="DOT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlt/" name="DOT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-excel/" name="DOT Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsx/" name="DOT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ods/" name="DOT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-sxc/" name="DOT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlam/" name="DOT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltm/" name="DOT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsm/" name="DOT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xls/" name="DOT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltx/" name="DOT Nak nek XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}