---
title: Convert PDF to TXT via C# API
description: C# API to Convert PDF File to TXT without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-txt/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: TXT
otherformats: FODS XLTM DIF XLTX XLSB EXCEL ODS XLSM TSV MD XLAM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PDF to TXT" h2="Export PDF File to TXT via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert PDF files to TXT within any .NET, C#, ASP.NET and VB.NET applications. This suite of components is designed to provide developers with a comprehensive set of tools for working with PDF documents. 

The process of converting PDF to TXT begins with Aspose.PDF for .NET. This component enables developers to export PDF documents to XLSX format. Once the PDF document has been exported to XLSX, the next step is to use Aspose.Cells for .NET Spreadsheet Programming API to convert the XLSX file to TXT. This API provides developers with a powerful set of features for working with spreadsheets, including the ability to read, write, and manipulate data in XLSX files. 

Once the XLSX file has been converted to TXT, developers can then use the TXT file in their applications. This makes it easy to integrate PDF documents into existing applications, as well as to create new applications that can work with PDF documents. Aspose.Total for .NET also provides developers with a range of other components for working with PDF documents, such as the ability to create, edit, and manipulate PDF documents. 

Overall, Aspose.Total for .NET provides developers with a comprehensive suite of components for working with PDF documents. With this suite of components, developers can easily convert PDF documents to TXT within any .NET, C#, ASP.NET and VB.NET applications. This makes it easy to integrate PDF documents into existing applications, as well as to create new applications that can work with PDF documents.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to TXT" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to TXT via C#" %}}
If your PDF document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to TXT with Watermark via C#" %}}
While converting PDF file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TXT with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}