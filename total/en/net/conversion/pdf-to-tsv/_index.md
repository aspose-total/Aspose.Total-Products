---
title: Convert PDF to TSV via C# API
description: C# API to Convert PDF File to TSV without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-tsv/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: TSV
otherformats: EXCEL XLTX ODS XLTM XLSB XLT FODS MD XLSM SXC CSV XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PDF to TSV" h2="Export PDF File to TSV via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of APIs that enables developers to easily convert PDF files to TSV within any .NET, C#, ASP.NET and VB.NET applications. The process involves two steps, firstly using Aspose.PDF for .NET to export the PDF to XLSX and then using Aspose.Cells for .NET Spreadsheet Programming API to convert the XLSX to TSV.

Aspose.PDF for .NET is a powerful PDF manipulation API that enables developers to create, read, edit, convert and print PDF documents within their .NET applications. It provides a wide range of features such as document manipulation, text extraction, image extraction, annotation, form filling, and much more. With this API, developers can easily export PDF files to XLSX format.

Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, read, edit, and convert spreadsheets within their .NET applications. It provides a wide range of features such as document manipulation, text extraction, image extraction, annotation, form filling, and much more. With this API, developers can easily convert XLSX files to TSV format.

Using Aspose.Total for .NET, developers can easily convert PDF files to TSV within any .NET, C#, ASP.NET and VB.NET applications. The process involves two steps, firstly using Aspose.PDF for .NET to export the PDF to XLSX and then using Aspose.Cells for .NET Spreadsheet Programming API to convert the XLSX to TSV. This process is simple and efficient, and can be used to quickly convert PDF files to TSV format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to TSV" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to TSV format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Tsv` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to TSV via C#" %}}
If your PDF document is password protected, you cannot convert it to TSV without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to TSV with Watermark via C#" %}}
While converting PDF file to TSV, you can also add watermark to your output TSV file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TSV with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}