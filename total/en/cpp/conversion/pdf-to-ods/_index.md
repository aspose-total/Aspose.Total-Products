---
title: C++ API to Convert PDF to ODS
description: Convert PDF to ODS via C++ API without using Microsoft Excel or Adobe Reader
url_ignore: /cpp/conversion/pdf-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: ODS
otherformats: DIF FODS XLSB XLTM SXC XLT XLAM XLSM XLTX MD EXCEL TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to ODS in C++ Applications" h2="Convert PDF to ODS in native C++ applications without requiring Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

PDF is a popular file format for sharing documents, but it is not suitable for editing. ODS is an open document spreadsheet format that is used for editing and storing data in a tabular form. Converting PDF to ODS allows users to edit the data in the PDF document and store it in a more convenient format.

<h2>How Aspose.Total Helps for PDF to ODS Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of file format automation libraries that enables developers to easily convert PDF to ODS. It consists of three components: Aspose.PDF for C++, Aspose.Cells for C++, and Aspose.Total for C++. Aspose.PDF for C++ is used to export PDF to XLSX, and Aspose.Cells for C++ is used to convert XLSX to ODS. The process is simple and straightforward, and it can be completed in just two steps.

First, Aspose.PDF for C++ is used to export the PDF document to XLSX. This component provides a wide range of features for manipulating PDF documents, such as extracting text, images, and annotations, converting PDF to other formats, and more. After the PDF document has been exported to XLSX, Aspose.Cells for C++ can be used to convert the XLSX file to ODS. This component provides a comprehensive set of features for working with spreadsheets, such as creating, editing, and converting spreadsheets, manipulating charts and shapes, and more.

Once the PDF document has been converted to ODS, users can easily edit the data in the document and store it in a more convenient format. Aspose.Total for C++ makes it easy to convert PDF to ODS, and it is a great solution for developers who need to automate the process of converting PDF documents to ODS.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert PDF to ODS" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function
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

{{% blocks/products/pf/feature-page-section  h2="Get or Set PDF File Information via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) also allows you to get information about your PDF document and lets you take informed decisions before your conversion process. In order to get file specific information of a PDF file, you first need to call the [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) method of [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class. Once the DocumentInfo object is retrieved, you can get the values of the individual properties. Furthermore, you can also set the properties by using respective methods of DocumentInfo class.
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