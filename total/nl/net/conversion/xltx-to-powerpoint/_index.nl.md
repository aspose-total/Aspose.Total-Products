---
title: Converteer XLTX naar POWERPOINT met .NET 
description: Converteer XLTX naar POWERPOINT op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms
url: /nl/net/conversion/xltx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer XLTX naar POWERPOINT via C#" h2="Excel exporteren&reg; XLTX naar POWERPOINT op .NET Framework-, .NET Core-, Mono- of Xamarin-platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTX naar POWERPOINT-conversie op .NET" %}}
1. Open het XLTX-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converteer XLTX naar PDF en stel SaveFormat in op Auto
3. Laad het geconverteerde PDF-bestand met de klasse [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Sla het powerpointument op in POWERPOINT-indeling met de methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) en stel Powerpoint in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-code voor conversie van XLTX naar POWERPOINT" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
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