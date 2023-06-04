---
title: Convert PPTM to JSON format via .NET 
description: Convert PPTM to JSON in C# without using Microsoft Excel or Powerpoint
url_ignore: /net/conversion/pptm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPTM to JSON Format via C#" h2="Export PPTM to JSON via C# without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily convert PPTM to JSON format within any .NET, C#, ASP.NET and VB.NET application. This powerful suite of components provides a simple two-step process for converting PPTM to JSON. 

The first step involves using Aspose.Slides for .NET to export the PPTM file to HTML. Aspose.Slides for .NET is a powerful API that enables developers to create, read, write, modify and convert PowerPoint presentations without the need for Microsoft PowerPoint. It supports a wide range of features, including the ability to export presentations to HTML. 

The second step involves using Aspose.Cells for .NET to convert the HTML to JSON. Aspose.Cells for .NET is a powerful Spreadsheet Programming API that enables developers to create, read, write, modify and convert spreadsheets without the need for Microsoft Excel. It supports a wide range of features, including the ability to convert HTML to JSON. 

By using Aspose.Total for .NET, developers can quickly and easily convert PPTM to JSON format within any .NET, C#, ASP.NET and VB.NET application. This powerful suite of components provides a simple two-step process for converting PPTM to JSON, making it an ideal solution for developers who need to convert PPTM to JSON.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PPTM to JSON Format via C#" %}}
1. Open PPTM file using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
2. Convert PPTM to HTML by using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPTM to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input PPTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTM to JSON in Range via C#" %}}
While you are converting PPTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}