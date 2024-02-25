---
title: Convert PDF to XLSM via C# API
description: C# API to Convert PDF File to XLSM without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XLSM
otherformats: EXCEL XLSB ODS FODS MD TXT XLT XLAM XLTM CSV TSV SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PDF to XLSM" h2="Export PDF File to XLSM via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert PDF files to XLSM within any .NET, C#, ASP.NET and VB.NET applications. The process involves two steps, both of which are made simple by the use of Aspose.Total for .NET. 

The first step is to export the PDF file to XLSX format. This can be done using Aspose.PDF for .NET, a powerful PDF manipulation API. It allows developers to convert PDF documents to a variety of other formats, including XLSX. It also provides a range of features for manipulating PDF documents, such as adding, deleting, and extracting pages, as well as merging and splitting documents. 

The second step is to convert the XLSX file to XLSM format. This can be done using Aspose.Cells for .NET, a powerful spreadsheet programming API. It allows developers to create, manipulate, and convert spreadsheets in a variety of formats, including XLSM. It also provides a range of features for manipulating spreadsheets, such as adding, deleting, and formatting cells, as well as inserting and deleting worksheets. 

By using Aspose.Total for .NET, developers can easily convert PDF files to XLSM within any .NET, C#, ASP.NET and VB.NET applications. It provides a simple and efficient way to convert PDF documents to XLSM format, without the need for any additional software or libraries.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to XLSM" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to XLSM format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Xlsm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to XLSM via C#" %}}
If your PDF document is password protected, you cannot convert it to XLSM without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to XLSM with Watermark via C#" %}}
While converting PDF file to XLSM, you can also add watermark to your output XLSM file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as XLSM with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}