---
title: Convert JSON Format to CHM via .NET 
description: Parse JSON to CHM in C# without using Microsoft Word
url_ignore: /net/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: OTT FLATOPC PS DOTX RTF WORDML ODT WORD EPUB DOC DOT PCL MOBI DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to CHM via C#" h2="C# API to parse JSON to CHM without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of components that enables developers to parse JSON to CHM within any .NET, C#, ASP.NET and VB.NET application. This process can be completed in two simple steps. 

The first step is to use Aspose.Cells for .NET to export JSON to PDF. Aspose.Cells for .NET is a powerful library that enables developers to create, manipulate and convert spreadsheets in various formats. It supports a wide range of features such as creating and editing worksheets, formatting cells, adding charts and images, and more. With Aspose.Cells for .NET, developers can easily export JSON to PDF with just a few lines of code. 

The second step is to use Aspose.Words for .NET to convert PDF to CHM. Aspose.Words for .NET is a powerful library that enables developers to create, manipulate and convert documents in various formats. It supports a wide range of features such as creating and editing documents, formatting text, adding images, and more. With Aspose.Words for .NET, developers can easily convert PDF to CHM with just a few lines of code. 

By using Aspose.Total for .NET, developers can easily parse JSON to CHM within any .NET, C#, ASP.NET and VB.NET application. This process can be completed in two simple steps, using Aspose.Cells for .NET to export JSON to PDF and Aspose.Words for .NET to convert PDF to CHM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to CHM via C#" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) class and [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) it as PDF 
3. Load PDF document by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to CHM format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout and Convert JSON Format to CHM via C#" %}}
While parsing JSON to CHM, you can also set layout options for your JSON using [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). It allows you to process Array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Parse JSON Format to CHM with Watermark" %}}
Using the API, you can also convert JSON to CHM with watermark. In order to add a watermark to your CHM document, you can first parse JSON file to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/net/aspose.words/document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.SetText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to CHM.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}