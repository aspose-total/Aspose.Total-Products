---
title: Konvertálja a PDF-et CSV-vé a C# API-n keresztül
description: C# API a PDF-fájlok CSV-vé konvertálásához Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/net/conversion/pdf-to-csv/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: CSV
otherformats: ODS XLAM DIF XLT XLSB TSV XLSM EXCEL FODS XLTX SXC TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API a PDF CSV formátumban való megjelenítéséhez" h2="PDF-fájl exportálása CSV-fájlba C#-on keresztül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával könnyedén konvertálhat PDF-fájlt CSV-formátumba bármely .NET-, C#-, ASP.NET- és VB.NET-alkalmazáson belül. Először is, az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával exportálhatja a PDF-et XLSX formátumba. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja az XLSX-et CSV-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a PDF CSV-vé alakításához" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a PDF-et XLSX-re a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot CSV-formátumba a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) metódussal, és állítsa be a „Csv”-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Védett PDF konvertálása CSV-vé C#-on keresztül" %}}
Ha a PDF-dokumentuma jelszóval védett, nem konvertálhatja CSV-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, majd konvertálhatja azt. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály új példányát, és argumentumként adja át a fájlnevet és a jelszót.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PDF fájlt CSV-vé vízjellel a C# segítségével" %}}
A PDF-fájl CSV-vé konvertálásakor vízjelet is hozzáadhat a kimeneti CSV-fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja az átalakított XLSX-dokumentumot, indexén keresztül kiválaszthatja a Munkalapot, létrehozhat egy alakzatot, és használhatja annak AddTextEffect funkcióját. Ezt követően elmentheti az XLSX-dokumentumot CSV-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}