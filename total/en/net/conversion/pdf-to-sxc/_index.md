---
title: Convert PDF to SXC via C# API
description: C# API to Convert PDF File to SXC without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: SXC
otherformats: XLTX XLAM TSV DIF TXT XLSB FODS EXCEL MD ODS XLT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PDF to SXC" h2="Export PDF File to SXC via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert PDF files to SXC within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a powerful and efficient way to convert PDF files to SXC without any manual intervention. 

The process of converting PDF to SXC involves two steps. Firstly, Aspose.PDF for .NET is used to export PDF to XLSX. This component provides a wide range of features to manipulate PDF documents, such as creating, editing, converting, and printing PDF files. It also supports a variety of formats, including XLSX, XLS, CSV, HTML, and TXT. 

Once the PDF file is converted to XLSX, Aspose.Cells for .NET is used to convert XLSX to SXC. This component provides a comprehensive set of features to manipulate spreadsheets, such as creating, editing, formatting, and printing spreadsheets. It also supports a variety of formats, including SXC, XLSX, XLS, CSV, HTML, and TXT. 

Using Aspose.Total for .NET, developers can easily convert PDF files to SXC within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a powerful and efficient way to convert PDF files to SXC without any manual intervention. It also supports a variety of formats, making it a great choice for developers who need to convert PDF files to SXC.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to SXC" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to SXC format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Sxc` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to SXC via C#" %}}
If your PDF document is password protected, you cannot convert it to SXC without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to SXC with Watermark via C#" %}}
While converting PDF file to SXC, you can also add watermark to your output SXC file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as SXC with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}