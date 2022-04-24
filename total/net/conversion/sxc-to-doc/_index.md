---
title: Convert SXC to DOC with .NET 
description: Convert SXC to DOC on .NET Framework, .NET Core, Mono or Xamarin Platforms
url: /net/conversion/sxc-to-doc/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOC
otherformats: WORD PPTX DOCX POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert SXC to DOC via C#" h2="Export Excel&reg; SXC to DOC on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="SXC to DOC Conversion on .NET" %}}
1. Open SXC file using [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) class
2. Convert SXC to PDF and set SaveFormat to Auto
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
4. Save the document to DOC format using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Total API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for SXC to DOC Conversion" gistPath="" %}}
```cs// load the SXC file using Workbook class
var book = new Aspose.Cells.Workbook("input.sxc");
// save SXC as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}