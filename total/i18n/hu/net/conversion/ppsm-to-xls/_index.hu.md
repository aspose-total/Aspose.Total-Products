---
title: Konvertálja a PPSM-ot XLS-vé a C# segítségével
description: Konvertálja a PPSM-ot XLS-vé C#-ban Microsoft Excel vagy Powerpoint használata nélkül
url: /hu/net/conversion/ppsm-to-xls/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: XLS
otherformats: FODS SXC EXCEL ODS DIF TSV MHTML XLSM XLTM XLT XLSX XLAM XLSB XLS XLTX MARKDOWN DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PPSM-ot XLS-vé a C# segítségével" h2=".NET API a PPSM-ból XLS-vé konvertáláshoz Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) használatával PPSM-fájlt konvertálhat XLS-vé bármely .NET, C#, ASP.NET és VB.NET alkalmazáson belül két részből. egyszerű lépéseket. Először is, az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával exportálhatja a PPSM-ot HTML-be. Ezt követően az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API használatával konvertálhatja a HTML-t XLS-vé.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a PPSM-ot XLS-vé konvertálni C#-on keresztül" %}}
1. Nyissa meg a PPSM-fájlt a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
2. Exportálja a PPSM-ot HTML-ként a [Mentés](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály használatával
4. Mentse a dokumentumot XLS-fájlba a [Mentés](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett PPSM konvertálása XLS-vé C#-on keresztül" %}}
Ha a PPSM-fájlt XLS-vé konvertálja, ha a bevitt PPSM-dokumentuma jelszóval védett, nem konvertálhatja XLS-vé a dokumentum visszafejtése nélkül. Ha a dokumentum jelszóval védett, az azt jelenti, hogy bizonyos korlátozásokat érvényesít a megjelenítésre vonatkozóan. A korlátozások megszüntetéséhez meg kell adni a jelszót. A jelszóval védett prezentáció zárolt prezentációnak minősül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PPSM-ot XLS-vé vízjellel a C# segítségével" %}}
A PPSM fájl XLS formátumba konvertálásakor vízjelet is hozzáadhat a kimeneti XLS fájlformátumhoz. Vízjel hozzáadásához létrehozhat egy új munkafüzet-objektumot, megnyithatja a konvertált HTML-dokumentumot, indexén keresztül kiválaszthatja a Munkalappsm, létrehozhat egy alakzatot, és használhatja az AddTextEffect funkcióját. Ezt követően elmentheti a HTML-dokumentumot XLS-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-fods/" name="PPSM Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xltm/" name="PPSM Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xlt/" name="PPSM Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xlam/" name="PPSM Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-markdown/" name="PPSM Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-excel/" name="PPSM Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-mhtml/" name="PPSM Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xlsb/" name="PPSM Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-ods/" name="PPSM Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-sxc/" name="PPSM Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xls/" name="PPSM Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xltx/" name="PPSM Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xlsx/" name="PPSM Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-tsv/" name="PPSM Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dif/" name="PPSM Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-xlsm/" name="PPSM Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-doc/" name="PPSM Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-docx/" name="PPSM Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-docm/" name="PPSM Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dot/" name="PPSM Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dotm/" name="PPSM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-dotx/" name="PPSM Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-odt/" name="PPSM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-ott/" name="PPSM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-rtf/" name="PPSM Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-word/" name="PPSM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-wordml/" name="PPSM Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-text/" name="PPSM Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsm-to-flatopx/" name="PPSM Nak nek FLANak nekPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}