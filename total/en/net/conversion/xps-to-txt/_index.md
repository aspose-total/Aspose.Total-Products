---
title: Convert XPS to TXT via C# API
description: C# API to Convert XPS File to TXT without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/xps-to-txt/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: TXT
otherformats: XLTM EXCEL XLSM DIF SXC XLAM FODS TSV XLT CSV ODS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render XPS to TXT" h2="Export XPS File to TXT via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert XPS files to TXT within any .NET, C#, ASP.NET and VB.NET applications. The conversion process is simple and straightforward, and requires two steps. 

The first step is to use Aspose.PDF for .NET to export the XPS file to XLSX. Aspose.PDF for .NET is a powerful PDF manipulation API that enables developers to create, read, edit, and convert PDF documents without any external dependencies. It also provides the ability to export XPS files to XLSX, allowing developers to easily convert XPS files to other formats. 

The second step is to use Aspose.Cells for .NET to convert the XLSX file to TXT. Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, read, edit, and convert spreadsheets without any external dependencies. It also provides the ability to convert XLSX files to TXT, allowing developers to easily convert XPS files to other formats. 

Using Aspose.Total for .NET, developers can quickly and easily convert XPS files to TXT within any .NET, C#, ASP.NET and VB.NET applications. The two-step process is simple and straightforward, and requires no external dependencies. Aspose.PDF for .NET is used to export the XPS file to XLSX, and Aspose.Cells for .NET is used to convert the XLSX file to TXT. With Aspose.Total for .NET, developers can quickly and easily convert XPS files to TXT with minimal effort.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to TXT" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to TXT format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Txt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XPS to TXT via C#" %}}
If your XPS document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to TXT with Watermark via C#" %}}
While converting XPS file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TXT with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}