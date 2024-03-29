---
title: Convert XPS to ODS via C# API
description: C# API to Convert XPS File to ODS without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/xps-to-ods/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: ODS
otherformats: EXCEL XLTX XLT MD XLTM XLSM TSV SXC XLAM TXT DIF FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render XPS to ODS" h2="Export XPS File to ODS via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily create, convert, and manipulate documents within any .NET, C#, ASP.NET and VB.NET applications. It provides a wide range of features and capabilities that make it an ideal choice for developers who need to work with documents in their applications.

One of the most useful features of Aspose.Total for .NET is its ability to convert XPS files to ODS. This can be done in two steps. Firstly, Aspose.PDF for .NET can be used to export XPS to XLSX. This component provides a wide range of features and capabilities that make it an ideal choice for developers who need to work with PDF documents in their applications. It can be used to convert XPS to XLSX with just a few lines of code.

Once the XPS file has been converted to XLSX, Aspose.Cells for .NET can be used to convert the XLSX to ODS. This component provides a powerful Spreadsheet Programming API that enables developers to easily create, manipulate, and convert spreadsheets within their applications. It can be used to convert XLSX to ODS with just a few lines of code.

By using Aspose.Total for .NET, developers can easily convert XPS files to ODS within any .NET, C#, ASP.NET and VB.NET applications. It provides a wide range of features and capabilities that make it an ideal choice for developers who need to work with documents in their applications. It is a comprehensive suite of components that enables developers to easily create, convert, and manipulate documents within their applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to ODS" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to ODS format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Ods` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XPS to ODS via C#" %}}
If your XPS document is password protected, you cannot convert it to ODS without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to ODS with Watermark via C#" %}}
While converting XPS file to ODS, you can also add watermark to your output ODS file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as ODS with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}