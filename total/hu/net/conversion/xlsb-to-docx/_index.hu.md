---
title: A XLSB konvertálása DOCX formátumba .NET segítségével 
description: A XLSB konvertálása DOCX formátumba .NET Framework, .NET Core, Mono vagy Xamarin platformokon
url: /hu/net/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT WORD DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="A XLSB konvertálása DOCX formátumba C# segítségével" h2="Exportálás Excel&reg; XLSB-ből DOCX-ba .NET Framework, .NET Core, Mono vagy Xamarin platformokon">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB-ből DOCX-ba konvertálás .NET-en" %}}
1. Nyissa meg a XLSB-fájlt a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével
2. Alakítsa át a XLSB-t PDF-be, és állítsa a SaveFormat beállítást Automatikusra
3. Töltse be a konvertált PDF-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
4. Mentse a dokumentumot DOCX formátumba a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# kód a XLSB-ből DOCX-ba való konvertáláshoz" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
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