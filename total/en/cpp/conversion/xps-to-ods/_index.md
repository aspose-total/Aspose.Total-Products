---
title: C++ API to Convert XPS to ODS
description: Convert XPS to ODS via C++ API without using Microsoft Excel or Adobe Reader
url_ignore: /cpp/conversion/xps-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: ODS
otherformats: XLSB XLAM XLT CSV EXCEL XLTX TSV DIF XLTM TXT XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to ODS in C++ Applications" h2="Convert XPS to ODS in native C++ applications without requiring Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to ODS</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft that is used to store documents in a fixed layout. It is similar to PDF, but it is not as widely used as PDF. ODS (OpenDocument Spreadsheet) is an open standard for spreadsheets, developed by the Open Document Format for Office Applications (ODF). It is an open source format, which means that it is freely available for anyone to use. Converting XPS to ODS can be beneficial for users who need to share their documents with others who may not have access to the XPS format.

<h2>How Aspose.Total Helps for XPS to ODS Conversion</h2>

Aspose.Total for C++ is a file format automation library that makes it easy to convert XPS to ODS. It is a two-step process. In the first step, you can export XPS to XLSX by using Aspose.PDF for C++. After that, by using Aspose.Cells for C++ Spreadsheet Programming API, you can convert XLSX to ODS. This process is simple and efficient, and it allows users to quickly and easily convert their XPS documents to ODS. Aspose.Total for C++ also provides a wide range of other features, such as the ability to create, edit, and convert documents, as well as the ability to manipulate images and text.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert XPS to ODS" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XPS to XLSX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function
3. Load XLSX document by using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference
4. Save the document to ODS format using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get or Set XPS File Information via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) also allows you to get information about your XPS document and lets you take informed decisions before your conversion process. In order to get file specific information of a XPS file, you first need to call the [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) method of [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class. Once the DocumentInfo object is retrieved, you can get the values of the individual properties. Furthermore, you can also set the properties by using respective methods of DocumentInfo class.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save ODS File Format to Stream via C++" %}}
 [Aspose.Cells for C++](https://products.aspose.com/cells/net/) allows saving ODS file format to stream. To save files to a stream, create a MemoryStream or FileStream object and save the file to that stream object by calling the [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object’s [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) method. Specify the desired file format using the [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) enumeration when calling the Save method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-csv-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}