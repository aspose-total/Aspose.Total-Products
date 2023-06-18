---
title: Convert PPSX to JSON format via .NET 
description: Convert PPSX to JSON in C# without using Microsoft Excel or Powerpoint
url_ignore: /net/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPSX to JSON Format via C#" h2="Export PPSX to JSON via C# without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily convert PPSX to JSON format within any .NET, C#, ASP.NET and VB.NET application. This powerful suite of components provides a simple two-step process for converting PPSX to JSON. 

The first step is to use Aspose.Slides for .NET to export the PPSX file to HTML. Aspose.Slides for .NET is a powerful API that enables developers to create, read, write and modify PowerPoint presentations in a variety of formats, including PPSX. It provides a wide range of features, such as the ability to add, delete, and modify slides, as well as the ability to add text, images, shapes, and other objects to slides. 

The second step is to use Aspose.Cells for .NET to convert the HTML file to JSON. Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, read, write, and modify spreadsheets in a variety of formats, including JSON. It provides a wide range of features, such as the ability to add, delete, and modify cells, as well as the ability to add formulas, charts, and other objects to spreadsheets. 

By using Aspose.Total for .NET, developers can quickly and easily convert PPSX to JSON format within any .NET, C#, ASP.NET and VB.NET application. This powerful suite of components provides a simple two-step process for converting PPSX to JSON, making it an ideal solution for developers who need to quickly and easily convert PPSX to JSON.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PPSX to JSON Format via C#" %}}
1. Open PPSX file using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
2. Convert PPSX to HTML by using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPSX to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input PPSX document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSX to JSON in Range via C#" %}}
While you are converting PPSX to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}