---
title: Convert XLT to POWERPOINT with .NET 
description: Convert XLT to POWERPOINT on .NET Framework, .NET Core, Mono or Xamarin Platforms
url_ignore: /net/conversion/xlt-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLT
outformat: PPTX
otherformats: WORD DOCX PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLT to POWERPOINT via C#" h2="Export Excel&reg; XLT to POWERPOINT on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLT to POWERPOINT Conversion on .NET" %}}
1. Open XLT file using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
2. Convert XLT to PDF and set SaveFormat to Auto
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
4. Save the document to PPTX format using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Pptx as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Total API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for XLT to POWERPOINT Conversion" gistPath="" %}}
```cs// load the XLT file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlt");
// save XLT as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
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