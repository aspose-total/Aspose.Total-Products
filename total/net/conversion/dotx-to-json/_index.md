---
title: Convert DOTX to JSON format via .NET 
description: Convert DOTX to JSON in C# without using Microsoft Excel or Adobe Reader
url: /net/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTX to JSON Format via C#" h2="Convert DOTX to JSON via C# without using Microsoft<sup>&reg;</sup> Word or Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
By using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can convert DOTX to JSON format within any .NET, C#, ASP.NET and VB.NET application in two simple steps. Firstly, by using [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can export DOTX to HTML. After that, by using [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, you can convert HTML to JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOTX to JSON Format via C#" %}}
1. Open DOTX file using [Document](https://apireference.aspose.com/words/net/aspose.words/document) class
2. Convert DOTX to HTML by using [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) method
3. Load HTML document by using [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTX to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input DOTX document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTX to Export Range to JSON" %}}
While you are converting DOTX to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}