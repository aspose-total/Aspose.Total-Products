---
title: Convert PCL to TXT via C# API
description: C# API to Convert PCL File to TXT without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pcl-to-txt/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: TXT
otherformats: XLTM SXC DIF XLAM FODS MD XLT TSV ODS CSV XLTX XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PCL to TXT" h2="Export PCL File to TXT via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert PCL files to TXT within any .NET, C#, ASP.NET and VB.NET applications. The process involves two steps. Firstly, Aspose.PDF for .NET is used to export the PCL file to XLSX. This is done by using the PDF to XLSX conversion feature of the API. After that, Aspose.Cells for .NET is used to convert the XLSX file to TXT. This is done by using the Spreadsheet Programming API of the API. 

The Spreadsheet Programming API of Aspose.Cells for .NET provides a wide range of features that enable developers to easily manipulate spreadsheets. It allows developers to create, read, write, modify, and convert spreadsheets in various formats. It also provides features such as data validation, data sorting, data filtering, and more. 

The PDF to XLSX conversion feature of Aspose.PDF for .NET enables developers to easily convert PCL files to XLSX. It supports a wide range of features such as page range selection, page orientation, page size, page margin, and more. It also supports a wide range of image formats such as JPEG, PNG, TIFF, and more. 

Using Aspose.Total for .NET, developers can easily convert PCL files to TXT within any .NET, C#, ASP.NET and VB.NET applications. It provides a comprehensive suite of components that enable developers to easily manipulate spreadsheets and convert PCL files to XLSX. It also provides features such as data validation, data sorting, data filtering, and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to TXT" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PCL to TXT via C#" %}}
If your PCL document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PCL File to TXT with Watermark via C#" %}}
While converting PCL file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TXT with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}