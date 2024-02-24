---
title: Convert Word to JSON format via .NET 
description: Convert Word to JSON in C# without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: XLSX XLSM XLS XLT CSV TSV EXCEL XLSB SXC FODS DIF ODS XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert Word Files to JSON Format via C#" h2="Parse & Convert Word to JSON via C# without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of APIs that enables developers to easily convert Word documents to JSON format in their .NET, C#, ASP.NET, or VB.NET applications. This conversion process can be completed in two simple steps. Firstly, the Aspose.Words for .NET API is used to export the Word file to HTML. This API is a feature-rich library that enables the manipulation of Word documents in various formats, including DOC, DOCX, RTF, and ODT. It ensures that the document retains its formatting and structure. Secondly, the Aspose.Cells for .NET Spreadsheet Programming API is used to convert the HTML file to JSON. This API supports the conversion of HTML to various formats, including JSON. It also provides high-speed generation, manipulation, and rendering of spreadsheets in various formats, such as XLSX, XLS, XLSM, CSV, and TXT. By using Aspose.Total for .NET, developers can easily convert Word documents to JSON format with just two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert Word to JSON via C#" %}}
1. Load any Word document using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
2. Convert Word to HTML by using [Document.Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method
3. Load HTML in an instance of [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the result in JSON format using [Workbook.Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected Word to JSON Format via C#" %}}
In addition to converting Word documents to JSON format, the Aspose.Total for .NET API also provides the ability to open password-protected documents. If your input Word document is password-protected, you'll need to provide the correct password to convert it to JSON format. With the API, you can open the encrypted document by passing the password in a ```LoadOptions``` object. The code snippet below illustrates how you can attempt to open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Word to JSON in Range via C#" %}}
You can also specify a range for your output JSON. To do so, you can first convert the Word document to HTML using the API, and then open the resulting HTML file using the ```Workbook``` class. From there, you can retrieve the ```CellsCollection``` of the worksheet that contains the data, and create a range by specifying the row and column indices. Finally, you can call the ```ExportRangeToJson``` method with references to the ```Range``` and ```ExportRangeToJsonOptions``` objects to generate the JSON data, which can be saved to a file using the ```File.WriteAllText``` method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}