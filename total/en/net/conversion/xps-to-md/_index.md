---
title: Convert XPS to MD via C# API
description: C# API to Convert XPS File to MD without using Microsoft Excel or Adobe Reader
url_ignore: /net/conversion/xps-to-md/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: MD
otherformats: EXCEL CSV XLTM TXT XLSM XLSB SXC XLT FODS XLAM XLTX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# API to Render XPS to MD" h2="Export XPS File to MD via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of components that enables developers to easily convert XPS files to MD within any .NET, C#, ASP.NET and VB.NET applications. This suite of components provides a powerful and efficient way to convert XPS to MD without any manual intervention. 

The process of converting XPS to MD involves two steps. Firstly, Aspose.PDF for .NET is used to export XPS to XLSX. This component provides a wide range of features that enable developers to manipulate PDF documents in a variety of ways. It also provides the ability to convert XPS to XLSX with ease. 

Once the XPS file has been converted to XLSX, Aspose.Cells for .NET can be used to convert XLSX to MD. This component provides a comprehensive set of features that enable developers to manipulate spreadsheets in a variety of ways. It also provides the ability to convert XLSX to MD with ease. 

Overall, Aspose.Total for .NET provides a powerful and efficient way to convert XPS to MD within any .NET, C#, ASP.NET and VB.NET applications. It enables developers to quickly and easily convert XPS to MD without any manual intervention. Furthermore, the components provided by Aspose.Total for .NET are highly reliable and provide a wide range of features that enable developers to manipulate documents and spreadsheets in a variety of ways.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to MD" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XPS to MD via C#" %}}
If your XPS document is password protected, you cannot convert it to MD without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to MD with Watermark via C#" %}}
While converting XPS file to MD, you can also add watermark to your output MD file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as MD with Watermark. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}