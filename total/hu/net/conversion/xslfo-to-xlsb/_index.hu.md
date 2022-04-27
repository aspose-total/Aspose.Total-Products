---
title: Konvertálja a XSLFO-et XLSB-vé a C# API-n keresztül
description: C# API a XSLFO-fájlok XLSB-vé konvertálásához Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/net/conversion/xslfo-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLSB
otherformats: XLAM MD SXC XLTX TXT FODS EXCEL XLTM XLSM DIF TSV ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a XSLFO XLSB formátumban való megjelenítéséhez" h2="XSLFO-fájl exportálása XLSB-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával könnyedén konvertálhat XSLFO-fájlt XLSB-formátumba bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a XSLFO-et XLSX formátumba. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja az XLSX-et XLSB-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a XSLFO XLSB-vé alakításához" %}}
1. Nyissa meg a XSLFO-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a XSLFO-et XLSX-re a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLSB-formátumba a [Mentés](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „Xlsb”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Védett XSLFO konvertálása XLSB-vé C#-on keresztül" %}}
Ha a XSLFO-dokumentuma jelszóval védett, nem konvertálhatja XLSB-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, majd konvertálhatja azt. A titkosított fájl megnyitásához inicializálhatja a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály új példányát, és argumentumként adja át a fájlnevet és a jelszót.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a XSLFO fájlt XLSB-vé vízjellel a C# segítségével" %}}
A XSLFO-fájl XLSB-vé konvertálásakor vízjelet is hozzáadhat a kimeneti XLSB-fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja az átalakított XLSX-dokumentumot, indexén keresztül kiválaszthatja a Munkalapot, létrehozhat egy alakzatot, és használhatja annak AddTextEffect funkcióját. Ezt követően elmentheti az XLSX-dokumentumot XLSB-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-sxc/" name="XSLFO Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xltx/" name="XSLFO Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-md/" name="XSLFO Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-tsv/" name="XSLFO Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-txt/" name="XSLFO Nak nek TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-ods/" name="XSLFO Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xlt/" name="XSLFO Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xlsm/" name="XSLFO Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xlam/" name="XSLFO Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xltm/" name="XSLFO Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-dif/" name="XSLFO Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xlsb/" name="XSLFO Nak nek XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}