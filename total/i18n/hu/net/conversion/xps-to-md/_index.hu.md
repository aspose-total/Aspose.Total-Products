---
title: Konvertálja a XPS-et MD-vé a C# API-n keresztül
description: C# API a XPS-fájlok MD-vé konvertálásához Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/net/conversion/xps-to-md/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: MD
otherformats: EXCEL MD XLTM TXT XLSM XLSB SXC XLT FODS XLAM XLTX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a XPS MD formátumban való megjelenítéséhez" h2="XPS-fájl exportálása MD-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET] (https://products.aspose.com/total/net/) használatával könnyedén konvertálhat XPS-fájlt MD-formátumba bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) használatával exportálhatja a XPS-et XLSX formátumba. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja az XLSX-et MD-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a XPS MD-vé alakításához" %}}
1. Nyissa meg a XPS-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a XPS-et XLSX-re a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot MD-formátumba a [Mentés](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „Md”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Védett XPS konvertálása MD-vé C#-on keresztül" %}}
Ha a XPS-dokumentuma jelszóval védett, nem konvertálhatja MD-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, majd konvertálhatja azt. A titkosított fájl megnyitásához inicializálhatja a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály új példányát, és argumentumként adja át a fájlnevet és a jelszót.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a XPS fájlt MD-vé vízjellel a C# segítségével" %}}
A XPS-fájl MD-vé konvertálásakor vízjelet is hozzáadhat a kimeneti MD-fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja az átalakított XLSX-dokumentumot, indexén keresztül kiválaszthatja a Munkalapot, létrehozhat egy alakzatot, és használhatja annak AddTextEffect funkcióját. Ezt követően elmentheti az XLSX-dokumentumot MD-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-sxc/" name="XPS Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xltx/" name="XPS Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-md/" name="XPS Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-tsv/" name="XPS Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-txt/" name="XPS Nak nek TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-ods/" name="XPS Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xlt/" name="XPS Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xlsm/" name="XPS Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xlam/" name="XPS Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xltm/" name="XPS Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-dif/" name="XPS Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xlsb/" name="XPS Nak nek XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}