---
title: Convert TSV to WORD with .NET 
description: Convert TSV to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms
url_ignore: /net/conversion/tsv-to-word/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: DOC
otherformats: DOCX PPTX POWERPOINT DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TSV to WORD via C#" h2="Export Excel&reg; TSV to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TSV to WORD Conversion on .NET" %}}
1. Open TSV file using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
2. Convert TSV to PDF and set SaveFormat to Auto
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
4. Save the document to DOC format using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Total API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for TSV to WORD Conversion" gistPath="" %}}
```cs// load the TSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.tsv");
// save TSV as PDF
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