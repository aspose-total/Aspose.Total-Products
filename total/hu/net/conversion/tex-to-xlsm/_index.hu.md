---
title: Konvertálja a TEX-et XLSM-vé a C# API-n keresztül
description: C# API a TEX-fájlok XLSM-vé konvertálásához Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/tex-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: XLSM
otherformats: TSV XLTM XLSM XLSB TXT ODS DIF MD SXC FODS XLT XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a TEX XLSM formátumban való megjelenítéséhez" h2="TEX-fájl exportálása XLSM-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával könnyedén konvertálhat TEX-fájlt XLSM-formátumba bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a TEX-et XLSX formátumba. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja az XLSX-et XLSM-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a TEX XLSM-vé alakításához" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a TEX-et XLSX-re a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLSM-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „Xlsm”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Védett TEX konvertálása XLSM-vé C#-on keresztül" %}}
Ha a TEX-dokumentuma jelszóval védett, nem konvertálhatja XLSM-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, majd konvertálhatja azt. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály új példányát, és argumentumként adja át a fájlnevet és a jelszót.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a TEX fájlt XLSM-vé vízjellel a C# segítségével" %}}
A TEX-fájl XLSM-vé konvertálásakor vízjelet is hozzáadhat a kimeneti XLSM-fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja az átalakított XLSX-dokumentumot, indexén keresztül kiválaszthatja a Munkalapot, létrehozhat egy alakzatot, és használhatja annak AddTextEffect funkcióját. Ezt követően elmentheti az XLSX-dokumentumot XLSM-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}