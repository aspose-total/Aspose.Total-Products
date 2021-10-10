---
title: Convert EXCEL to WORD with Net 
description: Convert EXCEL to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms
url: /net/conversion/excel-to-word/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOCX
otherformats: DOCX POWERPOINT PPTX WORD 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert EXCEL to WORD via C#" h2="Export Excel® CSV to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EXCEL to WORD Conversion on Net" %}}
1. Add reference of Aspose.Total for .NET
2. Open EXCEL file using [Aspose.Cells.Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) class
3. Convert EXCEL to PDF and set Aspose.Cells.SaveFormat to Auto
4. Load the converted PDF file using [Aspose.Cells.Workbook](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
5. Save the document to WORD format using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Word as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for EXCEL to WORD Conversion" gistPath="" %}}
```cs
// load the EXCEL file using Aspose.Cells
var book = new Aspose.Cells.Workbook("input.csv");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Aspose.Pdf
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.DocX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}