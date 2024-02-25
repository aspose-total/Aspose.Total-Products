---
title: C++ API to Convert PDF to TSV
description: Convert PDF to TSV via C++ API without using Microsoft Excel or Adobe Reader
url_ignore: /cpp/conversion/pdf-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: TSV
otherformats: EXCEL DIF MD XLTM ODS XLTX CSV XLSM XLSB XLAM SXC FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to TSV in C++ Applications" h2="Convert PDF to TSV in native C++ applications without requiring Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PDF to TSV?</h2>

PDF is a popular file format for sharing documents, but it is not suitable for data analysis and manipulation. TSV (Tab Separated Values) is a text-based format that is used to store tabular data. It is a simple and efficient way to store data in a structured format, which makes it ideal for data analysis and manipulation. Therefore, it is often necessary to convert PDF to TSV in order to make the data more accessible and easier to work with.

<h2>How Aspose.Total Helps for PDF to TSV Conversion?</h2>

Aspose.Total for C++ is a comprehensive file format automation library that provides a wide range of features for manipulating various file formats. It includes APIs for PDF, XLSX and TSV, which makes it an ideal choice for converting PDF to TSV. The process is simple and straightforward, and can be completed in two steps. 

In the first step, you can use Aspose.PDF for C++ to export PDF to XLSX. This API provides a wide range of features for manipulating PDF documents, including the ability to convert PDF to XLSX. 

In the second step, you can use Aspose.Cells for C++ to convert XLSX to TSV. This API provides a comprehensive set of features for manipulating spreadsheets, including the ability to convert XLSX to TSV. 

Overall, Aspose.Total for C++ makes it easy to convert PDF to TSV in C++. It provides a simple and efficient way to convert PDF documents to a format that is more suitable for data analysis and manipulation.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert PDF to TSV" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function
3. Load XLSX document by using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference
4. Save the document to TSV format using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get or Set PDF File Information via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) also allows you to get information about your PDF document and lets you take informed decisions before your conversion process. In order to get file specific information of a PDF file, you first need to call the [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) method of [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class. Once the DocumentInfo object is retrieved, you can get the values of the individual properties. Furthermore, you can also set the properties by using respective methods of DocumentInfo class.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save TSV File Format to Stream via C++" %}}
 [Aspose.Cells for C++](https://products.aspose.com/cells/net/) allows saving TSV file format to stream. To save files to a stream, create a MemoryStream or FileStream object and save the file to that stream object by calling the [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object’s [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) method. Specify the desired file format using the [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) enumeration when calling the Save method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-csv-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}