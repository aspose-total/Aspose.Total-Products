---
title: Convert TSV to DOCX with C++ 
description: Convert TSV to DOCX within C++ applications
url_ignore: /cpp/conversion/tsv-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD POWERPOINT DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TSV to DOCX via C++" h2="Export Excel&reg; TSV to DOCX within full-functional C++ applications">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TSV to DOCX Conversion on C++" %}}
1. Open TSV file using [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) member function of [Factory](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) class reference
2. Convert TSV to PDF and set SaveFormat to Pdf
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
4. Save the document to DOCX format using [Save](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function and set DocX as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C++ Code for TSV to DOCX Conversion" gistPath="" %}}
```cs
// load the TSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");
// save TSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
doc->Save(u"convertedFile.docx", SaveFormat::DocX);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}