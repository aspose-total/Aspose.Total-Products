---
title: Convert JSON Format to DOC via C++ 
description: C++ API t0 Parse JSON to DOC without using Microsoft Word
url_ignore: /cpp/conversion/json-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOC
otherformats: MOBI ODT DOTX CHM PCL RTF PS WORDML DOT EPUB OTT WORD FLATOPC DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to DOC via C++" h2="Parse JSON to DOC within C++ applications without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Converting JSON to DOC is a useful process for many C++ applications. JSON is a popular data format used for exchanging data between a server and a client. It is lightweight and easy to read, making it a great choice for applications that need to store and transfer data. However, many applications require the data to be in a DOC format, which is a more widely used format for documents. Converting JSON to DOC allows the data to be used in more applications and makes it easier to share with others.

<h2>How Aspose.Total Helps for JSON to DOC Conversion</h2>

Aspose.Total for C++ is a suite of APIs that makes it easy to parse JSON to DOC within C++ applications. It includes Aspose.Cells for C++ and Aspose.Words for C++, which are two APIs that can be used to convert JSON to DOC. With Aspose.Cells for C++, you can export JSON to PDF, and then with Aspose.Words for C++, you can convert PDF to DOC. This two-step process makes it easy to convert JSON to DOC within C++ applications. Aspose.Total for C++ also includes other APIs that can be used to manipulate documents, spreadsheets, and other file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to DOC in C++" %}}
1. Create a new [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and read valid JSON data from file
2. Save JSON as PDF using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method
3. Load PDF document by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOC format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to DOC in C++" %}}
While parsing JSON to DOC, you can also set the size of rows and columns by loading JSON with [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class. If you need to set the same row height for all rows in the worksheet, you can do it by using the [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) method of the [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) collection. Similarly, to set the same column width for all columns in the worksheet, use the ICells collection’s [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to DOC with Watermark in C++" %}}
Using the API, you can also parse JSON to DOC with watermark. In order to add a watermark to your DOC document, you can first convert JSON to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class, set different properties for text watermark,
call SetText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to DOC.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}