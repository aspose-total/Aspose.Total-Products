---
title: Convert PCL to SXC via C# API
description: C# API to Convert PCL File to SXC without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/pcl-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: SXC
otherformats: FODS DIF MD ODS XLTM CSV EXCEL XLAM XLTX XLSM TSV TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render PCL to SXC" h2="Export PCL File to SXC via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert PCL files to SXC within any .NET, C#, ASP.NET and VB.NET applications. The process of conversion involves two steps. Firstly, Aspose.PDF for .NET is used to export PCL to XLSX. This component provides a wide range of features to manipulate PDF documents. It enables developers to create, edit, convert, render, print and split PDF documents. It also allows developers to add annotations, watermarks, signatures, bookmarks, headers and footers to PDF documents. 

Once the PCL file is converted to XLSX, Aspose.Cells for .NET is used to convert XLSX to SXC. This component provides a comprehensive set of features to manipulate spreadsheets. It enables developers to create, edit, copy, convert, render, print and split spreadsheets. It also allows developers to add formulas, charts, images, hyperlinks, comments, shapes, autofilters, data validation, conditional formatting and many more features to spreadsheets. 

Using Aspose.Total for .NET, developers can easily convert PCL to SXC within any .NET, C#, ASP.NET and VB.NET applications. Aspose.PDF for .NET is used to export PCL to XLSX and Aspose.Cells for .NET is used to convert XLSX to SXC. Both components provide a wide range of features to manipulate PDF documents and spreadsheets respectively. This makes it easier for developers to convert PCL to SXC quickly and efficiently.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to SXC" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PCL to SXC via C#" %}}
If your PCL document is password protected, you cannot convert it to SXC without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PCL File to SXC with Watermark via C#" %}}
While converting PCL file to SXC, you can also add watermark to your output SXC file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as SXC with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}