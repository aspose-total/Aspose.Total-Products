---
title: Convert DOCX to JSON format in C++ 
description: Export DOCX to JSON in C++ without using Microsoft Excel or Word
url_ignore: /cpp/conversion/docx-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to JSON Format via C++" h2="Export DOCX to JSON via C++ without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Converting documents from one format to another is a common requirement in many applications. For example, converting a DOCX file to JSON format can be useful for applications that need to store and manipulate data in a structured format. JSON is a popular data interchange format that is used to store and exchange data between different applications.

<h2>How Aspose.Total Helps for DOCX to JSON Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of components that enables developers to create, manipulate and convert various document formats within their C++ applications. It includes Aspose.Words for C++, which can be used to export DOCX files to HTML. Aspose.Cells for C++ can then be used to convert the HTML to JSON format. This makes it easy to convert DOCX to JSON within C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOCX to JSON Format via C++" %}}
1. Open DOCX file using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference
2. Convert DOCX to HTML by using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) member function
3. Load HTML document by using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCX to JSON Format via C++" %}}
Using the API, you can also open the password-protected document. If your input DOCX document is password protected, you cannot convert it to JSON format without using the password. To do this, use a special constructor overload, which accepts a LoadOptions object. This object contains the Password property, which specifies the password string.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}