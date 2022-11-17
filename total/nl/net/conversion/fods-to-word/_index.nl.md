---
title: Converteer FODS naar WORD met .NET 
description: Converteer FODS naar WORD op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms

family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOC
otherformats: DOC PPTX POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer FODS naar WORD via C#" h2="Excel exporteren&reg; FODS naar WORD op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS naar WORD-conversie op .NET" %}}
1. Open het FODS-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converteer FODS naar PDF en stel SaveFormat in op Auto
3. Laad het geconverteerde PDF-bestand met de klasse [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)
4. Sla het wordument op in WORD-indeling met de methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) en stel Word in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-code voor conversie van FODS naar WORD" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/csv-to-word/" name="CSV Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/csv-to-powerpoint/" name="CSV Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/csv-to-pptx/" name="CSV Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/csv-to-docx/" name="CSV Tot DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}