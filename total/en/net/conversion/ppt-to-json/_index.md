---
title: Convert PPT to JSON format via .NET 
description: Convert PPT to JSON in C# without using Microsoft Excel or Powerpoint
url_ignore: /net/conversion/ppt-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPT to JSON via C# .NET Core" h2="Export PPT to JSON via C# without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Why Convert PPT to JSON via .NET?</h2>

Converting PPT to JSON via .NET is valuable for extracting structured data from PowerPoint presentations, enabling easy data analysis, integration, and sharing, enhancing accessibility and versatility for various applications and systems that require JSON format.

<h2 class="heading-border">How Aspose.Total can help in PPT to JSON Conversion?</h2>

With [Aspose.Total for .NET](https://products.aspose.com/total/net/), PPT to JSON conversion in any .NET, C#, ASP.NET, or VB.NET application is a straightforward two-step process. First, employ Aspose.Slides for .NET to export PPT to HTML. Then, use Aspose.Cells for .NET Spreadsheet Programming API to convert HTML to JSON, simplifying the entire conversion.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPT to JSON Format via C#" %}}
1. Open PPT file using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
2. Convert PPT to HTML by using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tools Required for PPT to JSON Conversion" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPT to JSON Format via C#" %}}
Using the API, you can also open the password-protected document. If your input PPT document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to JSON in Range via C#" %}}
While you are converting PPT to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, get CellsCollection of the Worksheet containing the data, create a range from CellsCollection by specifying row & column indices, and call ExportRangeToJson method with references to Range & ExportRangeToJsonOptions objects. Finally, you can save the JSON data to file via File.WriteAllText method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}