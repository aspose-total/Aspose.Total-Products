---
title: Convert DOCX to JSON format via .NET 
description: Convert DOCX to JSON in C# without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to JSON Format, Convert Word to JSON, DOCX to JSON Converter via C#" h2="Parse DOCX to JSON via C# without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily convert DOCX to JSON format within any .NET, C#, ASP.NET, and VB.NET application. This powerful suite of components provides a simple two-step process for converting DOCX to JSON. 

The first step is to use Aspose.Words for .NET to export the DOCX file to HTML. Aspose.Words for .NET is a powerful .NET library that enables developers to create, edit, convert, and manipulate Microsoft Word documents without using Microsoft Office. It provides a wide range of features, including the ability to export DOCX to HTML. 

The second step is to use Aspose.Cells for .NET to convert the HTML to JSON. Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, manipulate, and convert Microsoft Excel spreadsheets without using Microsoft Office. It provides a wide range of features, including the ability to convert HTML to JSON. 

By using Aspose.Total for .NET, developers can quickly and easily convert DOCX to JSON format within any .NET, C#, ASP.NET, and VB.NET application. The two-step process of using Aspose.Words for .NET to export the DOCX file to HTML and then using Aspose.Cells for .NET to convert the HTML to JSON is simple and straightforward. With Aspose.Total for .NET, developers can easily and quickly convert DOCX to JSON format in no time.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOCX to JSON Format via C#" %}}
1. Open DOCX file using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
2. Convert DOCX to HTML by using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCX to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input DOCX document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOCX to JSON in Range via C#" %}}
While you are converting DOCX to JSON, you can also set a range for your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get the CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
