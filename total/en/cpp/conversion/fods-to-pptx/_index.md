---
title: Convert FODS to PPTX with C++ 
description: Convert FODS to PPTX within C++ applications
url_ignore: /cpp/conversion/fods-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOC WORD POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert FODS to PPTX via C++" h2="Export Excel&reg; FODS to PPTX within full-functional C++ applications">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS to PPTX Conversion on C++" %}}
1. Open FODS file using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) member function of [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) class reference
2. Convert FODS to PDF and set SaveFormat to Pdf
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
4. Save the document to PPTX format using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function and set Pptx as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C++ Code for FODS to PPTX Conversion" gistPath="" %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in PPTX format
doc->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online Converter for FODS to PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=fods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/fods-to-pptx/">Try our free app for FODS to PPTX conversion</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}