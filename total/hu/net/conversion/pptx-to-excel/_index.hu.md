---
title: Konvertálja a PPTX-ot EXCEL-vé a C# segítségével
description: Konvertálja a PPTX-ot EXCEL-vé C#-ban Microsoft Excel vagy Powerpoint használata nélkül
url: /hu/net/conversion/pptx-to-excel/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: EXCEL
otherformats: MARKDOWN FODS XLTX XLSB XLT XLSM XLS XLTM XLAM XLSX TSV SXC EXCEL MHTML DIF ODS DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PPTX-ot EXCEL-vé a C# segítségével" h2=".NET API a PPTX-ból EXCEL-vé konvertáláshoz Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával PPTX-fájlt konvertálhat EXCEL-vé bármely .NET, C#, ASP.NET és VB.NET alkalmazáson belül két részből. egyszerű lépéseket. Először is, az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával exportálhatja a PPTX-ot HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t EXCEL-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a PPTX-ot EXCEL-vé konvertálni C#-on keresztül" %}}
1. Nyissa meg a PPTX-fájlt a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
2. Exportálja a PPTX-ot HTML-ként a [Mentés](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot EXCEL-fájlba a [Mentés](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett PPTX konvertálása EXCEL-vé C#-on keresztül" %}}
Ha a PPTX-fájlt EXCEL-vé konvertálja, ha a bevitt PPTX-dokumentuma jelszóval védett, nem konvertálhatja EXCEL-vé a dokumentum visszafejtése nélkül. Ha a dokumentum jelszóval védett, az azt jelenti, hogy bizonyos korlátozásokat érvényesít a megjelenítésre vonatkozóan. A korlátozások megszüntetéséhez meg kell adni a jelszót. A jelszóval védett prezentáció zárolt prezentációnak minősül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PPTX-ot EXCEL-vé vízjellel a C# segítségével" %}}
A PPTX fájl EXCEL formátumba konvertálásakor vízjelet is hozzáadhat a kimeneti EXCEL fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja a konvertált HTML-dokumentumot, indexén keresztül kiválaszthatja a Munkalapptx, létrehozhat egy alakzatot, és használhatja az AddTextEffect funkcióját. Ezt követően elmentheti a HTML-dokumentumot EXCEL-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-fods/" name="PPTX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xltm/" name="PPTX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xlt/" name="PPTX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xlam/" name="PPTX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-markdown/" name="PPTX Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-excel/" name="PPTX Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-mhtml/" name="PPTX Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xlsb/" name="PPTX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-ods/" name="PPTX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-sxc/" name="PPTX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xls/" name="PPTX Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xltx/" name="PPTX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xlsx/" name="PPTX Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-tsv/" name="PPTX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-dif/" name="PPTX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-xlsm/" name="PPTX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-doc/" name="PPTX Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-docx/" name="PPTX Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-docm/" name="PPTX Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-dot/" name="PPTX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-dotm/" name="PPTX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-dotx/" name="PPTX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-odt/" name="PPTX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-ott/" name="PPTX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-rtf/" name="PPTX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-word/" name="PPTX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-wordml/" name="PPTX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-text/" name="PPTX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptx-to-flatopx/" name="PPTX Nak nek FLANak nekPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}