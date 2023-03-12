---
title:Convert XLSX to WORD with .NET or with free Online Converter
description: Convert XLSX to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms or online. Test free CSV to DOC online converter quickly before integrating the code. 
url_ignore: /net/conversion/xlsx-to-word/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: DOC
otherformats: DOC DOCX POWERPOINT PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSX to WORD via C# or Online App" h2="Export Excel&reg; XLSX to WORD on .NET Framework, .NET Core, Mono or Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX to WORD Conversion on .NET" %}}
1. Open XLSX file using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
2. Convert XLSX to PDF and set SaveFormat to Auto
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
4. Save the document to DOC format using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET Total API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for XLSX to WORD Conversion" gistPath="" %}}
```cs// load the XLSX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsx");
// save XLSX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Free Online Converter for XLSX to WORD</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}