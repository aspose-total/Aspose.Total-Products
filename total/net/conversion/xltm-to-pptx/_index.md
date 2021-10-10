---
title: Convert XLTM to PPTX with Net 
description: Convert XLTM to PPTX on .NET Framework, .NET Core, Mono or Xamarin Platforms
url: /net/conversion/xltm-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOC PPTX WORD DOCX 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLTM to PPTX via C#" h2="Export Excel® XLTM to PPTX on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTM to PPTX Conversion on Net" %}}
1. Add reference of Aspose.Total for .NET
2. Open XLTM file using [Aspose.Cells.Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) class
3. Convert XLTM to PDF and set Aspose.Cells.SaveFormat to Auto
4. Load the converted PDF file using [Aspose.Cells.Workbook](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
5. Save the document to PPTX format using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Pptx as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Font API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for XLTM to PPTX Conversion" gistPath="" %}}
```cs
// load the XLTM file using Aspose.Cells
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Aspose.Pdf
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in PPTX format
document.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}