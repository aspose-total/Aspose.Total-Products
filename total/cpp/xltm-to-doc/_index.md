---
title: Convert XLTM to DOC with C++ 
description: Convert XLTM to DOC within C++ applications
url: /cpp/conversion/xltm-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOC
otherformats: WORD POWERPOINT PPTX DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLTM to DOC via C++" h2="Export Excel&reg; XLTM to DOC within full-functional C++ applications">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTM to DOC Conversion on C++" %}}
1. Open XLTM file using [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) member function of [Factory](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) class reference
2. Convert XLTM to PDF and set SaveFormat to Pdf
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
4. Save the document to DOC format using [Save](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with CPP Total API" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C++ Code for XLTM to DOC Conversion" gistPath="" %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.{inputformat}}_LOWER");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}