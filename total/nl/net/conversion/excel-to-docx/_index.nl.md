---
title: Converteer EXCEL naar DOCX met .NET 
description: Converteer EXCEL naar DOCX op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms
url: /nl/net/conversion/excel-to-docx/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOCX
otherformats: WORD DOC PPTX POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer EXCEL naar DOCX via C#" h2="Excel exporteren&reg; EXCEL naar DOCX op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EXCEL naar DOCX-conversie op .NET" %}}
1. Open het EXCEL-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converteer EXCEL naar PDF en stel SaveFormat in op Auto
3. Laad het geconverteerde PDF-bestand met de klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Sla het document op in DOCX-indeling met de methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) en stel Docx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-code voor conversie van EXCEL naar DOCX" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
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