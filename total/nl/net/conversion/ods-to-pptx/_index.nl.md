---
title: Converteer ODS naar PPTX met .NET 
description: Converteer ODS naar PPTX op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms

family: total
platformtag: net
feature: conversion
informat: ODS
outformat: PPTX
otherformats: POWERPOINT DOCX WORD DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer ODS naar PPTX via C#" h2="Excel exporteren&reg; ODS naar PPTX op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ODS naar PPTX-conversie op .NET" %}}
1. Open het ODS-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converteer ODS naar PDF en stel SaveFormat in op Auto
3. Laad het geconverteerde PDF-bestand met de klasse [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Sla het pptxument op in PPTX-indeling met de methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) en stel Pptx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-code voor conversie van ODS naar PPTX" gistPath="" %}}
```cs
// load the ODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.ods");
// save ODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
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