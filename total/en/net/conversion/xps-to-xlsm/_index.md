---
title: Convert XPS to XLSM via C# API
description: C# API to Convert XPS File to XLSM without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/xps-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: XLSM
otherformats: EXCEL XLSB ODS DIF SXC CSV FODS TSV XLAM TXT XLTX MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render XPS to XLSM" h2="Export XPS File to XLSM via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert XPS files to XLSM within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a powerful set of features that allow developers to quickly and easily create, manipulate and convert documents.

The process of converting XPS to XLSM involves two steps. Firstly, Aspose.PDF for .NET can be used to export XPS to XLSX. This component provides a wide range of features that allow developers to create, manipulate and convert PDF documents. It also provides the ability to export XPS documents to XLSX format.

Once the XPS document has been exported to XLSX, Aspose.Cells for .NET can be used to convert XLSX to XLSM. This component provides a powerful set of features that allow developers to quickly and easily create, manipulate and convert spreadsheets. It also provides the ability to convert XLSX documents to XLSM format.

By using Aspose.Total for .NET, developers can easily convert XPS files to XLSM within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a powerful set of features that allow developers to quickly and easily create, manipulate and convert documents. It also provides the ability to export XPS documents to XLSX and convert XLSX documents to XLSM format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to XLSM" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XPS to XLSM via C#" %}}
If your XPS document is password protected, you cannot convert it to XLSM without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to XLSM with Watermark via C#" %}}
While converting XPS file to XLSM, you can also add watermark to your output XLSM file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as XLSM with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}