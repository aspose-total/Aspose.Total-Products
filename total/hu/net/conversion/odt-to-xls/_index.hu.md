---
title: .NET API a ODT konvertálásához XLS-vé vagy ingyenes online konverterrel
description: C# API a ODT konvertálásához XLS-vé vagy Online App Microsoft Excel vagy Adobe Reader használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes CSV-DOC online konvertert. 
url_ignore: /hu/net/conversion/odt-to-xls/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: XLS
otherformats: EXCEL XLSB XLAM XLS XLSM XLTX XLTM ODS XLSX DIF XLT TSV FODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a ODT konvertálásához XLS-vé vagy Online App" h2="ODT exportálása XLS-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával beépíthet ODT-ból XLS-vé konvertáló funkciót bármely .NET, C#, ASP.NET és VB.NET alkalmazásba. két egyszerű lépés. Először is, az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával exportálhatja a ODT-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t XLS-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a ODT konvertálásához XLS-vé" %}}
1. Nyissa meg a ODT-fájlt a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
2. Alakítsa át a ODT-t HTML-vé a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLS-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „XLS”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter ODT-hez XLS-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xls&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="ODT dokumentum betöltése a Streamből C#-on keresztül" %}}
Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) lehetővé teszi a ODT-dokumentumok adatfolyamon keresztüli betöltését is. Egy dokumentum adatfolyamból való megnyitásához egyszerűen adja át a dokumentumot tartalmazó adatfolyam objektumot a [Document](https://reference.aspose.com/words/net/aspose.words/document) konstruktornak. A következő kódpélda bemutatja, hogyan lehet megnyitni egy dokumentumot adatfolyamból:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyéni tulajdonságok hozzáadása a XLS-fájlhoz C#-on keresztül" %}}
Miközben a ODT-t XLS-vé alakítja, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) lehetővé teszi egyéni tulajdonságok hozzáadását a XLS-dokumentumokhoz. Egyéni tulajdonság hozzáadásához használhatja az [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) metódust a [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) osztály. Az Add metódus hozzáadja a tulajdonságot az Excel-fájlhoz, és az új dokumentumtulajdonság hivatkozását adja vissza [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties) néven. /dokumentumtulajdonság) objektum. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-dif/" name="ODT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xlsb/" name="ODT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-tsv/" name="ODT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-fods/" name="ODT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xlt/" name="ODT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-excel/" name="ODT Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xlsx/" name="ODT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-ods/" name="ODT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-sxc/" name="ODT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xlam/" name="ODT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xltm/" name="ODT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xlsm/" name="ODT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xls/" name="ODT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/odt-to-xltx/" name="ODT Nak nek XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}