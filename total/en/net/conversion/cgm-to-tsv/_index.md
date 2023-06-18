---
title: Convert CGM to TSV via C# API
description: C# API to Convert CGM File to TSV without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: CSV FODS XLSM EXCEL TXT SXC XLAM ODS DIF XLSB XLT MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render CGM to TSV" h2="Export CGM File to TSV via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert CGM files to TSV within any .NET, C#, ASP.NET and VB.NET applications. The conversion process involves two steps. 

The first step is to use Aspose.PDF for .NET to export the CGM file to XLSX. Aspose.PDF for .NET is a powerful library that enables developers to create, read, edit, and convert PDF documents within .NET applications. It supports a wide range of features, including the ability to export CGM files to XLSX. 

The second step is to use Aspose.Cells for .NET to convert the XLSX file to TSV. Aspose.Cells for .NET is a powerful spreadsheet programming API that enables developers to create, read, edit, and convert spreadsheets within .NET applications. It supports a wide range of features, including the ability to convert XLSX files to TSV. 

Using Aspose.Total for .NET, developers can easily convert CGM files to TSV within any .NET, C#, ASP.NET and VB.NET applications. The conversion process involves two steps: exporting the CGM file to XLSX using Aspose.PDF for .NET, and then converting the XLSX file to TSV using Aspose.Cells for .NET. Both components are included in the Aspose.Total for .NET suite, making it easy for developers to quickly and easily convert CGM files to TSV.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert CGM to TSV" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert CGM to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected CGM to TSV via C#" %}}
If your CGM document is password protected, you cannot convert it to TSV without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM File to TSV with Watermark via C#" %}}
While converting CGM file to TSV, you can also add watermark to your output TSV file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TSV with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}