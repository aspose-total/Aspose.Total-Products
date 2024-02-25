---
title: Convert JSON Format to POWERPOINT via C++ 
description: Parse JSON to POWERPOINT in C++ without using Microsoft PowerPoint
url_ignore: /cpp/conversion/json-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POWERPOINT
otherformats: OTP PPSM PPT POTM PPTM PPS POT ODP PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to POWERPOINT via C++" h2="C++ API to parse JSON to POWERPOINT without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Converting JSON to POWERPOINT within any C++ application is now possible with the help of two powerful APIs from Aspose.Total for C++. Aspose.Cells for C++ and Aspose.Slides for C++ are the two APIs that can be used to parse JSON to PPTX and then convert PPTX to POWERPOINT respectively. 

Aspose.Cells for C++ is a powerful API that can be used to parse JSON to PPTX. It provides a wide range of features that can be used to manipulate the data in the JSON file and convert it into a PPTX file. It also provides a comprehensive set of features to work with the PPTX file, such as formatting, adding images, and more. 

Aspose.Slides for C++ is an API that can be used to convert PPTX to POWERPOINT. It provides a wide range of features that can be used to manipulate the data in the PPTX file and convert it into a POWERPOINT file. It also provides a comprehensive set of features to work with the POWERPOINT file, such as formatting, adding images, and more. 

Both APIs come under the Aspose.Total for C++ package, which provides a comprehensive set of features to work with various file formats. With the help of these two APIs, you can easily convert JSON to POWERPOINT within any C++ application in two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to POWERPOINT via C++" %}}
1. Create a new [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and read valid JSON data from file
2. Save JSON as PPTX using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class 
4. Save the document to POWERPOINT format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout and Convert JSON Format to POWERPOINT via C++" %}}
While parsing JSON to POWERPOINT, you can also set the size of rows and columns by loading JSON with [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class. If you need to set the same row height for all rows in the worksheet, you can do it by using the [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) method of the [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) collection. Similarly, to set the same column width for all columns in the worksheet, use the ICells collection’s [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to POWERPOINT with Watermark in C++" %}}
Using the API, you can also convert JSON to POWERPOINT with watermark. In order to add a watermark to your POWERPOINT document, you can first parse JSON to PPTX and add a watermark to it. In order to add a watermark, load the newly created PPTX file using the [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class, get the first slide, Add an AutoShape of Rectangle type, add TextFrame to the Rectangle, create the Paragraph object for a text frame, create Portion object for paragraph, add watermark using set_Text() and, can save the document to POWERPOINT.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}