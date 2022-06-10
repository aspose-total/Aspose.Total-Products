---
title: Convert JSON Format to PCL via .NET 
description: Parse JSON to PCL in C# without using Microsoft Word
url_ignore: /net/conversion/json-to-pcl/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PCL
otherformats: PS DOC DOTX DOCM RTF MOBI EPUB CHM OTT WORD ODT FLATOPC WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to PCL via C#" h2="C# API to parse JSON to PCL without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
By using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can parse JSON to PCL  within any .NET, C#, ASP.NET and VB.NET application in two simple steps. Firstly, by using [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), you can export JSON to PDF. After that, by using [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can convert PDF to PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to PCL via C#" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) class and [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) it as PDF 
3. Load PDF document by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PCL format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout and Convert JSON Format to PCL via C#" %}}
While parsing JSON to PCL, you can also set layout options for your JSON using [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). It allows you to process Array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Parse JSON Format to PCL with Watermark" %}}
Using the API, you can also convert JSON to PCL with watermark. In order to add a watermark to your PCL document, you can first parse JSON file to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/net/aspose.words/document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.SetText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to PCL.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}