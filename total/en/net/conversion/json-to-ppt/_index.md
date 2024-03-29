---
title: Convert JSON Format to PPT via .NET 
description: Parse JSON to PPT in C# without using Microsoft PowerPoint
url_ignore: /net/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: PPSM POT POTM PPS OTP POWERPOINT PPTM ODP PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to PPT via C#" h2="C# API to parse JSON to PPT without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting JSON to PPT is a simple process that can be done within any .NET, C#, ASP.NET and VB.NET application. It can be done in two steps using the Aspose.Total for .NET package. 

The first step is to parse the JSON to PPTX using Aspose.Cells for .NET. This API is part of the Aspose.Total for .NET package and is designed to help developers create, manipulate and convert spreadsheets. It can be used to parse JSON to PPTX, allowing developers to easily convert JSON data into a PowerPoint presentation. 

The second step is to convert the PPTX to PPT using Aspose.Slides for .NET. This API is also part of the Aspose.Total for .NET package and is designed to help developers create, manipulate and convert presentations. It can be used to convert PPTX to PPT, allowing developers to quickly and easily convert their JSON data into a PowerPoint presentation. 

By using the Aspose.Total for .NET package, developers can easily convert JSON to PPT within any .NET, C#, ASP.NET and VB.NET application. This package provides the necessary APIs to parse JSON to PPTX and then convert PPTX to PPT, allowing developers to quickly and easily create a PowerPoint presentation from their JSON data.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to PPT via C#" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) class and [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) it as PPTX 
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to PPT format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from the command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout and Convert JSON Format to PPT via C#" %}}
While parsing JSON to PPT, you can also set layout options for your JSON format using [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). It allows you to process array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to PPT with Watermark" %}}
Using the API, you can also convert JSON to PPT with watermark. In order to add a watermark to your PPT document, you can first parse JSON to PPTX and add a watermark to it. In order to add a watermark, load the newly created PPTX file using the [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class, select the master presentation, add shape type using AddAutoShape, and add watermark text using AddTextFrame. After adding the watermark, you can save the document to PPT.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}