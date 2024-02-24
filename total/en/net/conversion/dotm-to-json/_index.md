---
title: Convert DOTM to JSON format via .NET 
description: Convert DOTM to JSON in C# without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM SXC XLTM TSV DIF FODS XLSM XLSX ODS XLTX XLS EXCEL XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTM to JSON Format via C#" h2="Parse DOTM to JSON via C# without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily create, manipulate, convert and render documents in a variety of formats. It provides a wide range of features and capabilities, including the ability to convert DOTM to JSON format. This article will explain how to use Aspose.Total for .NET to convert DOTM to JSON in two simple steps.

The first step is to use Aspose.Words for .NET to export DOTM to HTML. Aspose.Words for .NET is a powerful .NET library that enables developers to create, manipulate, convert and render documents in a variety of formats. It provides a wide range of features and capabilities, including the ability to export DOTM to HTML. To do this, simply open the DOTM file in Aspose.Words for .NET and then use the Save method to save it as an HTML file.

The second step is to use Aspose.Cells for .NET to convert HTML to JSON. Aspose.Cells for .NET is a powerful .NET library that enables developers to create, manipulate, convert and render spreadsheets in a variety of formats. It provides a wide range of features and capabilities, including the ability to convert HTML to JSON. To do this, simply open the HTML file in Aspose.Cells for .NET and then use the Save method to save it as a JSON file.

By following these two simple steps, you can easily convert DOTM to JSON format using Aspose.Total for .NET. Aspose.Total for .NET provides a comprehensive suite of .NET components that enables developers to easily create, manipulate, convert and render documents in a variety of formats. It provides a wide range of features and capabilities, including the ability to convert DOTM to JSON format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOTM to JSON Format via C#" %}}
1. Open DOTM file using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
2. Convert DOTM to HTML by using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTM to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input DOTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTM to JSON in Range via C#" %}}
While you are converting DOTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}