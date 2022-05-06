---
title: Convert MD to TXT via C# API
description: C# API to Convert MD File to TXT without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/md-to-txt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TXT
otherformats: ODS CSV XLT XLTM XLAM XLTX DIF EXCEL XLSB TSV XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render MD to TXT" h2="Export MD File to TXT via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily convert MD file to TXT within any .NET, C#, ASP.NET and VB.NET applications. Firstly, by using [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can export MD to XLSX. After that, by using [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, you can convert XLSX to TXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert MD to TXT" %}}
1. Open MD file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert MD to XLSX by using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to TXT format using [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Txt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected MD to TXT via C#" %}}
If your MD document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD File to TXT with Watermark via C#" %}}
While converting MD file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TXT with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}