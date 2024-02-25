---
title: Convert PDF to Excel via C# API
description: C# API to Convert PDF File to Excel without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pdf-to-excel/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: EXCEL
otherformats: MD XLTX DIF ODS SXC TXT XLTM XLSM FODS CSV TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to Excel with .NET Core" h2="Export PDF to Excel via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Why Convert PDF to Excel formats via .NET Code?</h2>

Converting PDF files to Excel formats via .NET serves several important purposes. Firstly, Excel is a powerful tool for data analysis, organization, and manipulation. By converting PDFs to Excel, you can transform static PDF data into dynamic and editable spreadsheets, allowing for advanced calculations, charting, and deeper data insights. Secondly, it enhances data compatibility by enabling the seamless transfer of information from PDFs into the versatile Excel format. This compatibility ensures that data can be easily integrated into various applications, databases, and reporting tools, making it more accessible and functional. Finally, .NET libraries and APIs simplify the conversion process, allowing developers to automate the extraction and transformation of data, saving time and improving workflow efficiency.

<h2 class="heading-border">How to Convert PDF to Excel Offline with Aspose.Total?</h2>

[Aspose.Total for .NET](https://products.aspose.com/total/net/) provides an efficient solution for converting PDF files to Excel formats using .NET, C#, ASP.NET, and VB.NET applications. The conversion process is simple and involves two API's from the Aspose product suite, namely [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) and [Aspose.Cells for .NET](https://products.aspose.com/cells/net/).<br><br>

To begin, Aspose.PDF for .NET allows the export of PDF files to XLSX format. This API provides a range of options and settings for exporting PDF files to Excel, enabling developers to control the conversion process. Once the PDF file is exported to XLSX format, the Aspose.Cells for .NET Spreadsheet Programming API can be used to convert the XLSX file to Excel format. This API offers comprehensive functionality to manipulate and convert Excel files, allowing for a seamless conversion process.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to Excel with .NET?" %}}
1. Load PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to XLSX by using [Document.Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class 
4. Save the document to CSV format using [Workbook.Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Csv` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PDF to Excel Converter Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to Excel via C#" %}}
If your PDF document is password protected, you cannot convert it to Excel without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Excel with Watermark via C#" %}}
While converting PDF file to Excel, you can also add watermark to your output Excel file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as Excel with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}