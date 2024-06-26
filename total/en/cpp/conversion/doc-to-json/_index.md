---
title: Convert DOC to JSON format in C++ 
description: Export DOC to JSON in C++ without using Microsoft Excel or Word
url_ignore: /cpp/conversion/doc-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOC to JSON Format via C++" h2="Export DOC to JSON via C++ without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Converting documents from one format to another is a common requirement for many applications. For example, converting a DOC file to JSON format can be useful for web applications that need to store and display data in a structured format. JSON is a popular data format that is used for storing and exchanging data between different applications.

<h2>How Aspose.Total Helps for DOC to JSON Conversion</h2>

Aspose.Total for C++ is a suite of APIs that can be used to convert documents from one format to another. It includes Aspose.Words for C++, which can be used to export DOC files to HTML. Aspose.Cells for C++ can then be used to convert the HTML to JSON format. This makes it easy to convert DOC files to JSON format within C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOC to JSON Format via C++" %}}
1. Open DOC file using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference
2. Convert DOC to HTML by using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) member function
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOC to JSON Format via C++" %}}
Using the API, you can also open the password-protected document. If your input DOC document is password protected, you cannot convert it to JSON format without using the password. To do this, use a special constructor overload, which accepts a LoadOptions object. This object contains the Password property, which specifies the password string.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}