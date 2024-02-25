---
title: Convert JSON Format to CHM via C++ 
description: C++ API t0 Parse JSON to CHM without using Microsoft Word
url_ignore: /cpp/conversion/json-to-chm/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: CHM
otherformats: DOC WORD OTT DOTX DOT PCL PS FLATOPC EPUB RTF WORDML DOCM MOBI ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to CHM via C++" h2="Parse JSON to CHM within C++ applications without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert JSON to CHM</h2>

The JSON (JavaScript Object Notation) format is a popular data interchange format used for exchanging data between different applications. It is a lightweight, text-based, language-independent data exchange format that is easy for humans and machines to read and write. On the other hand, CHM (Compiled HTML Help) is a Microsoft proprietary online help format, used for providing help and documentation for Windows applications. It is a single file that contains HTML pages, images, and navigation. Therefore, it is necessary to convert JSON to CHM in order to make the data available in a format that can be used by Windows applications.

<h2>How Aspose.Total Helps for JSON to CHM Conversion</h2>

Aspose.Total for C++ is a suite of APIs that enables developers to create, manipulate, and convert various file formats within their C++ applications. It includes APIs for manipulating documents, images, emails, and other file formats. With Aspose.Total for C++, developers can easily parse JSON to CHM within their C++ applications in two simple steps. 

Firstly, by using Aspose.Cells for C++, developers can export JSON to PDF. Aspose.Cells for C++ is a powerful spreadsheet processing API that enables developers to create, manipulate, and convert spreadsheets within their C++ applications. It supports a wide range of features, including creating, reading, and writing spreadsheets, manipulating data, and converting spreadsheets to other popular file formats. 

After that, by using Aspose.Words for C++, developers can convert PDF to CHM. Aspose.Words for C++ is a powerful word processing API that enables developers to create, manipulate, and convert documents within their C++ applications. It supports a wide range of features, including creating, reading, and writing documents, manipulating data, and converting documents to other popular file formats. 

Therefore, with Aspose.Total for C++, developers can easily parse JSON to CHM within their C++ applications in two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to CHM in C++" %}}
1. Create a new [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and read valid JSON data from file
2. Save JSON as PDF using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method
3. Load PDF document by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to CHM format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to CHM in C++" %}}
While parsing JSON to CHM, you can also set the size of rows and columns by loading JSON with [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class. If you need to set the same row height for all rows in the worksheet, you can do it by using the [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) method of the [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) collection. Similarly, to set the same column width for all columns in the worksheet, use the ICells collection’s [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to CHM with Watermark in C++" %}}
Using the API, you can also parse JSON to CHM with watermark. In order to add a watermark to your CHM document, you can first convert JSON to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class, set different properties for text watermark,
call SetText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to CHM.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}