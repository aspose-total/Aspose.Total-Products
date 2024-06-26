---
title: Convert PDF to MD via C# API
description: C# API to Convert PDF File to MD without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-md/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MD
otherformats: XLSB TXT TSV XLAM SXC CSV XLT DIF FODS EXCEL XLSM XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PDF to MD" h2="Export PDF File to MD via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily convert PDF files to MD within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a wide range of features and capabilities that make it easy to create powerful and efficient applications. 

The process of converting PDF to MD begins with Aspose.PDF for .NET, which is a powerful PDF manipulation API that enables developers to export PDF to XLSX. This API provides a wide range of features and capabilities that make it easy to manipulate PDF documents, including the ability to convert PDF to other formats such as XLSX. 

Once the PDF has been converted to XLSX, Aspose.Cells for .NET can be used to convert the XLSX to MD. Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, manipulate, and convert spreadsheets. This API provides a wide range of features and capabilities that make it easy to create powerful and efficient applications. 

By using Aspose.Total for .NET, developers can easily convert PDF to MD within any .NET, C#, ASP.NET and VB.NET applications. This comprehensive suite of components provides a wide range of features and capabilities that make it easy to create powerful and efficient applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to MD" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to MD format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Md` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to MD via C#" %}}
If your PDF document is password protected, you cannot convert it to MD without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to MD with Watermark via C#" %}}
While converting PDF file to MD, you can also add watermark to your output MD file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as MD with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}