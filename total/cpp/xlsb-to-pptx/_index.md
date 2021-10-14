---
title: Convert XLSB to PPTX with C++ 
description: Convert XLSB to PPTX within C++ applications
url: /cpp/conversion/xlsb-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: DOCX WORD POWERPOINT DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSB to PPTX via C++" h2="Export Excel&reg; XLSB to PPTX within full-functional C++ applications">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB to PPTX Conversion on C++" %}}
1. Open XLSB file using [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) member function of [Factory](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) class reference
2. Convert XLSB to PDF and set SaveFormat to Pdf
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
4. Save the document to PPTX format using [Save](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function and set Pptx as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with CPP Total API" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C++ Code for XLSB to PPTX Conversion" gistPath="" %}}
```cs
// load the XLSB file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.{inputformat}}_LOWER");
// save XLSB as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in PPTX format
doc->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}