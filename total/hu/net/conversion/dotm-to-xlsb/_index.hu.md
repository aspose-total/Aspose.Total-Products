---
title: .NET API a DOTM konvertálásához XLSB-vé
description: C# API a DOTM konvertálásához XLSB-vé Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/dotm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: XLSB
otherformats: TSV XLAM SXC XLSB EXCEL ODS FODS XLSM XLTX XLS XLSX DIF XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a DOTM konvertálásához XLSB-vé" h2="DOTM exportálása XLSB-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával beépíthet DOTM-ból XLSB-vé konvertáló funkciót bármely .NET, C#, ASP.NET és VB.NET alkalmazásba. két egyszerű lépés. Először is, az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával exportálhatja a DOTM-t HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t XLSB-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a DOTM konvertálásához XLSB-vé" %}}
1. Nyissa meg a DOTM-fájlt a [Dotmument](https://reference.aspose.com/words/net/aspose.words/dotmument) osztály használatával
2. Alakítsa át a DOTM-t HTML-vé a [Save](https://reference.aspose.com/words/net/aspose.words.dotmument/save/methods/4) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLSB-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „XLSB”-t SaveFormat-ként.
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

<h3>Ingyenes online konverter DOTM-hez XLSB-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlsb&from=dotm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="DOTM dokumentum betöltése a Streamből C#-on keresztül" %}}
Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) lehetővé teszi a DOTM-dokumentumok adatfolyamon keresztüli betöltését is. Egy dokumentum adatfolyamból való megnyitásához egyszerűen adja át a dokumentumot tartalmazó adatfolyam objektumot a [Document](https://reference.aspose.com/words/net/aspose.words/dotmument) konstruktornak. A következő kódpélda bemutatja, hogyan lehet megnyitni egy dokumentumot adatfolyamból:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyéni tulajdonságok hozzáadása a XLSB-fájlhoz C#-on keresztül" %}}
Miközben a DOTM-t XLSB-vé alakítja, az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) lehetővé teszi egyéni tulajdonságok hozzáadását a XLSB-dokumentumokhoz. Egyéni tulajdonság hozzáadásához használhatja az [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdotmumentpropertycollection/methods/add/index) metódust a [CustomDotmumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdotmumentpropertycollection) osztály. Az Add metódus hozzáadja a tulajdonságot az Excel-fájlhoz, és az új dokumentumtulajdonság hivatkozását adja vissza [Aspose.Cells.Properties.DotmumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties) néven. /dokumentumtulajdonság) objektum. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-dif/" name="DOTM Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xlsb/" name="DOTM Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-tsv/" name="DOTM Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-fods/" name="DOTM Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xlt/" name="DOTM Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-excel/" name="DOTM Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xlsx/" name="DOTM Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-ods/" name="DOTM Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-sxc/" name="DOTM Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xlam/" name="DOTM Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xltm/" name="DOTM Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xlsm/" name="DOTM Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xls/" name="DOTM Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotm-to-xltx/" name="DOTM Nak nek XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}