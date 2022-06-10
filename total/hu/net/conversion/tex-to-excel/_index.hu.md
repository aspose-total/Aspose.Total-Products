---
title: Konvertálja a TEX-et EXCEL-vé a C# API-n keresztül
description: C# API a TEX-fájlok EXCEL-vé konvertálásához Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/tex-to-excel/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: EXCEL
otherformats: DIF EXCEL XLT MD XLAM XLTM TXT XLSB FODS ODS TSV SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a TEX EXCEL formátumban való megjelenítéséhez" h2="TEX-fájl exportálása EXCEL-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával könnyedén konvertálhat TEX-fájlt EXCEL-formátumba bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a TEX-et XLSX formátumba. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja az XLSX-et EXCEL-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a TEX EXCEL-vé alakításához" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a TEX-et XLSX-re a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot EXCEL-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „Excel”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Védett TEX konvertálása EXCEL-vé C#-on keresztül" %}}
Ha a TEX-dokumentuma jelszóval védett, nem konvertálhatja EXCEL-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, majd konvertálhatja azt. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály új példányát, és argumentumként adja át a fájlnevet és a jelszót.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a TEX fájlt EXCEL-vé vízjellel a C# segítségével" %}}
A TEX-fájl EXCEL-vé konvertálásakor vízjelet is hozzáadhat a kimeneti EXCEL-fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja az átalakított XLSX-dokumentumot, indexén keresztül kiválaszthatja a Munkalapot, létrehozhat egy alakzatot, és használhatja annak AddTextEffect funkcióját. Ezt követően elmentheti az XLSX-dokumentumot EXCEL-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-sxc/" name="TEX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xltx/" name="TEX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-md/" name="TEX Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-tsv/" name="TEX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-txt/" name="TEX Nak nek TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-ods/" name="TEX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xlt/" name="TEX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xlsm/" name="TEX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xlam/" name="TEX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xltm/" name="TEX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-dif/" name="TEX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xlsb/" name="TEX Nak nek XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}