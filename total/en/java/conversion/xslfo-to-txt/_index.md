---
title: Java API to Render XSLFO to TXT
description: Export XSLFO to TXT via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/xslfo-to-txt/
family: total
platformtag: java
feature: conversion
informat: XSLFO
outformat: TXT
otherformats: EXCEL SXC XLTX XLAM XLSM CSV TSV MD XLTM XLT XLSB ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export XSLFO to TXT via Java" h2="Convert XSLFO file to TXT by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate XSLFO to TXT conversion feature in their Java applications. This suite includes Aspose.PDF for Java and Aspose.Cells for Java, which are two powerful APIs that can be used to render XSLFO to XLSX and convert XLSX to TXT respectively. 

The process of converting XSLFO to TXT involves two steps. In the first step, Aspose.PDF for Java can be used to render XSLFO to XLSX. This API provides a wide range of features that can be used to create, manipulate, and convert PDF documents. It also supports XSLFO to XLSX conversion, which enables developers to convert XSLFO documents to XLSX format. 

In the second step, Aspose.Cells for Java can be used to convert XLSX to TXT. This API provides a comprehensive set of features that can be used to create, manipulate, and convert spreadsheets. It also supports XLSX to TXT conversion, which enables developers to convert XLSX documents to TXT format. 

By using Aspose.Total for Java, developers can easily integrate XSLFO to TXT conversion feature in their Java applications. This suite provides a comprehensive set of features that can be used to render XSLFO to XLSX and convert XLSX to TXT. It also offers a wide range of features that can be used to create, manipulate, and convert PDF and spreadsheet documents.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XSLFO File to TXT via Java" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XSLFO to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to TXT format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XSLFO to TXT via Java" %}}
If your XSLFO document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XSLFO File to TXT with Watermark via Java" %}}
While converting XSLFO file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as TXT with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}