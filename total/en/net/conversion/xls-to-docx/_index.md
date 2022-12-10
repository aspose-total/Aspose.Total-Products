---
title: Convert XLS to DOCX with .NET 
description: Convert XLS to DOCX on .NET Framework, .NET Core, Mono or Xamarin Platforms
url_ignore: /net/conversion/xls-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLS to DOCX via C#" h2="Export Excel&reg; XLS to DOCX on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLS to DOCX Conversion on .NET" %}}
1. Open XLS file using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
2. Convert XLS to PDF and set SaveFormat to Auto
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
4. Save the document to DOCX format using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set DocX as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Total API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for XLS to DOCX Conversion" gistPath="" %}}
```cs// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
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