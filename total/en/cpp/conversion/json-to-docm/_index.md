---
title: Convert JSON Format to DOCM via C++ 
description: C++ API t0 Parse JSON to DOCM without using Microsoft Word
url_ignore: /cpp/conversion/json-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOCM
otherformats: OTT CHM PCL DOT PS DOTX ODT FLATOPC WORDML EPUB DOC WORD RTF MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to DOCM via C++" h2="Parse JSON to DOCM within C++ applications without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
JSON (JavaScript Object Notation) is a lightweight data-interchange format that is used to store and exchange data. It is a text-based format and is easy for humans to read and write. It is also easy for machines to parse and generate. DOCM is a Microsoft Word Open XML Macro-Enabled Document file. It is a document format that is used to store text, images, macros, and other data. It is a popular format for creating documents that contain macros.

<h2>How Aspose.Total helps for json to docm conversion</h2>
Aspose.Total for C++ is a suite of components that enables developers to create, manipulate, and convert documents within their C++ applications. It includes components for Excel, Words, and other file formats. With Aspose.Total for C++, you can easily parse JSON to DOCM within your C++ applications in two simple steps. Firstly, by using Aspose.Cells for C++, you can export JSON to PDF. After that, by using Aspose.Words for C++, you can convert PDF to DOCM. Aspose.Total for C++ is a powerful suite of components that makes it easy to create, manipulate, and convert documents within your C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to DOCM in C++" %}}
1. Create a new [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and read valid JSON data from file
2. Save JSON as PDF using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method
3. Load PDF document by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOCM format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to DOCM in C++" %}}
While parsing JSON to DOCM, you can also set the size of rows and columns by loading JSON with [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class. If you need to set the same row height for all rows in the worksheet, you can do it by using the [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) method of the [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) collection. Similarly, to set the same column width for all columns in the worksheet, use the ICells collection’s [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to DOCM with Watermark in C++" %}}
Using the API, you can also parse JSON to DOCM with watermark. In order to add a watermark to your DOCM document, you can first convert JSON to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class, set different properties for text watermark,
call SetText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to DOCM.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}