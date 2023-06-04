---
title: Convert MD to CSV via C# API
description: C# API to Convert MD File to CSV without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/md-to-csv/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: CSV
otherformats: EXCEL ODS XLAM SXC FODS XLT DIF XLSB XLSM XLTM TSV TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render MD to CSV" h2="Export MD File to CSV via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert MD file to CSV within any .NET, C#, ASP.NET and VB.NET applications. The process involves two steps. Firstly, Aspose.PDF for .NET can be used to export MD to XLSX. This component is a powerful PDF manipulation API that enables developers to create, read, edit, convert and print PDF documents without using Adobe Acrobat. It also provides features such as document conversion, text extraction, document signing, form filling, document assembly, and much more. 

The second step involves using Aspose.Cells for .NET Spreadsheet Programming API to convert XLSX to CSV. This component is a powerful spreadsheet programming API that enables developers to create, manipulate, convert and render spreadsheets without using Microsoft Excel. It also provides features such as data import/export, formula calculation engine, pivot tables, charting, and much more. With Aspose.Cells for .NET, developers can easily convert XLSX to CSV and other popular formats such as XLS, HTML, PDF, ODS, and more. 

In conclusion, Aspose.Total for .NET is an ideal solution for developers who need to convert MD file to CSV within any .NET, C#, ASP.NET and VB.NET applications. It provides two powerful components, Aspose.PDF for .NET and Aspose.Cells for .NET, that enable developers to easily export MD to XLSX and then convert XLSX to CSV.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert MD to CSV" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert MD to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to CSV format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Csv` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected MD to CSV via C#" %}}
If your MD document is password protected, you cannot convert it to CSV without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD File to CSV with Watermark via C#" %}}
While converting MD file to CSV, you can also add watermark to your output CSV file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as CSV with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}