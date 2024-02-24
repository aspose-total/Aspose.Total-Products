---
title: Convert DOC to JSON format via .NET 
description: Convert DOC to JSON in C# without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: CSV XLAM SXC TSV XLT EXCEL DIF XLSM XLTM XLSX XLSB FODS ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOC to JSON Format via C#" h2="Parse & Convert DOC to JSON via C# without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Why Convert DOC to JSON format?</h2>

There are several reasons why someone might want to convert a DOC file to JSON. One reason is that JSON is a more flexible and versatile format than DOC. DOC files are designed for storing text documents, whereas JSON can store a wide range of data types, including text, numbers, and objects. Another reason why someone might want to convert a DOC file to JSON is that JSON is a more web-friendly format. JSON can be easily read and processed by web applications, whereas DOC files can be more difficult to work with in a web context. Additionally, converting DOC to JSON can make it easier to integrate the content of a Word document with other web-based tools and services. For example, if you want to extract data from a Word document and display it on a website, converting it to JSON can make the process more efficient and less error-prone.

<h2 class="heading-border">How Aspose.Total can help in DOC to JSON Conversion?</h2>

By using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can convert DOC to JSON format within any .NET, C#, ASP.NET and VB.NET application in two simple steps. Firstly, by using [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can export DOC to HTML. After that, by using [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, you can convert HTML to JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOC to JSON via C#?" %}}
1. Load DOC file using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
2. Convert DOC to HTML by using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tools Required for DOC to JSON Conversion" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert Protected DOC to JSON via C#?" %}}
Using the API, you can also open the password-protected document. If your input DOC document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert DOC to JSON in Range via C#?" %}}
While you are converting DOC to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}