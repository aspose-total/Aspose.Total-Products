---
title: Convert JSON Format to PPSM via C++ 
description: Parse JSON to PPSM in C++ without using Microsoft PowerPoint
url_ignore: /cpp/conversion/json-to-ppsm/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POT PPS PPTM OTP POTX PPT PPSX POWERPOINT POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to PPSM via C++" h2="C++ API to parse JSON to PPSM without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can convert JSON to PPSM within any C++ application in two simple steps. Firstly, by using [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), you can parse JSON to PPTX. After that, by using [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), you can convert PPTX to PPSM. Both APIs come under [Aspose.Total for C++](https://products.aspose.com/total/cpp/) package.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to PPSM via C++" %}}
1. Create a new [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and read valid JSON data from file
2. Save JSON as PPTX using [Save](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method
3. Load PPTX document by using [Presentation](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) class 
4. Save the document to PPSM format using [Save](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout and Convert JSON Format to PPSM via C++" %}}
While parsing JSON to PPSM, you can also set the size of rows and columns by loading JSON with [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class. If you need to set the same row height for all rows in the worksheet, you can do it by using the [SetStandardHeight](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) method of the [ICells](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_cell) collection. Similarly, to set the same column width for all columns in the worksheet, use the ICells collection’s [SetStandardWidth](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to PPSM with Watermark in C++" %}}
Using the API, you can also convert JSON to PPSM with watermark. In order to add a watermark to your PPSM document, you can first parse JSON to PPTX and add a watermark to it. In order to add a watermark, load the newly created PPTX file using the [Presentation](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) class, get the first slide, Add an AutoShape of Rectangle type, add TextFrame to the Rectangle, create the Paragraph object for a text frame, create Portion object for paragraph, add watermark using set_Text() and, can save the document to PPSM.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}