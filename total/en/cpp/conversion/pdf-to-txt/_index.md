---
title: C++ API to Convert PDF to TXT
description: Convert PDF to TXT via C++ API without using Microsoft Excel or Adobe Reader
url_ignore: /cpp/conversion/pdf-to-txt/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: TXT
otherformats: ODS EXCEL SXC MD CSV XLSM XLT TSV XLTX DIF XLSB XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to TXT in C++ Applications" h2="Convert PDF to TXT in native C++ applications without requiring Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

PDF to TXT conversion is a common requirement for many applications. Text files are easier to read and process than PDFs, and can be used for a variety of purposes such as text analysis, data extraction, and document comparison. Converting PDF to TXT also allows for easier editing and manipulation of the text content.

<h2>How Aspose.Total Helps for PDF to TXT Conversion</h2>

Aspose.Total for C++ is a comprehensive file format automation library that provides a wide range of features for PDF to TXT conversion. It includes the Aspose.PDF for C++ library, which can be used to export PDF to XLSX, and the Aspose.Cells for C++ library, which can be used to convert XLSX to TXT. This two-step process is simple and efficient, and can be used to quickly and easily convert PDF to TXT. Aspose.Total for C++ also provides a wide range of other features for file format automation, such as the ability to convert PDF to HTML, DOCX, and other formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert PDF to TXT" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to XLSX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) member function
3. Load XLSX document by using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference
4. Save the document to TXT format using [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) member function
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

{{% blocks/products/pf/feature-page-section  h2="Save TXT File Format to Stream via C++" %}}
 [Aspose.Cells for C++](https://products.aspose.com/cells/net/) allows saving TXT file format to stream. To save files to a stream, create a MemoryStream or FileStream object and save the file to that stream object by calling the [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object’s [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) method. Specify the desired file format using the [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) enumeration when calling the Save method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-csv-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}