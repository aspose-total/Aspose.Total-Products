---
title: A TSV konvertálása WORD formátumba .NET segítségével 
description: A TSV konvertálása WORD formátumba .NET Framework, .NET Core, Mono vagy Xamarin platformokon
url: /hu/net/conversion/tsv-to-word/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: DOC
otherformats: DOCX PPTX POWERPOINT DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="A TSV konvertálása WORD formátumba C# segítségével" h2="Exportálás Excel&reg; TSV-ből WORD-ba .NET Framework, .NET Core, Mono vagy Xamarin platformokon">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TSV-ből WORD-ba konvertálás .NET-en" %}}
1. Nyissa meg a TSV-fájlt a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével
2. Alakítsa át a TSV-t PDF-be, és állítsa a SaveFormat beállítást Automatikusra
3. Töltse be a konvertált PDF-fájlt a [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument) osztály használatával
4. Mentse a dokumentumot WORD formátumba a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) módszerrel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# kód a TSV-ből WORD-ba való konvertáláshoz" gistPath="" %}}
```cs
// load the TSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.tsv");
// save TSV as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/csv-to-word/" name="CSV Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/csv-to-powerpoint/" name="CSV Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/csv-to-pptx/" name="CSV Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/csv-to-docx/" name="CSV Nak nek DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}