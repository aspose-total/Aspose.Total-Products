---
title: Java API to Render XPS to TXT
description: Export XPS to TXT via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/xps-to-txt/
family: total
platformtag: java
feature: conversion
informat: XPS
outformat: TXT
otherformats: XLSB TSV CSV FODS ODS EXCEL DIF MD XLAM XLSM XLT XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export XPS to TXT via Java" h2="Convert XPS file to TXT by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate XPS to TXT conversion feature in their Java applications. This suite includes Aspose.PDF for Java and Aspose.Cells for Java. Aspose.PDF for Java is a powerful PDF manipulation API that enables developers to render XPS to XLSX. Aspose.Cells for Java is a Spreadsheet Programming API that enables developers to convert XLSX to TXT. 

The process of XPS to TXT conversion involves two steps. In the first step, Aspose.PDF for Java is used to render XPS to XLSX. This API provides a wide range of features that enable developers to manipulate PDF documents in various ways. It supports a wide range of features such as document conversion, text extraction, image extraction, document signing, and more. 

In the second step, Aspose.Cells for Java is used to convert XLSX to TXT. This API provides a wide range of features that enable developers to manipulate spreadsheets in various ways. It supports a wide range of features such as document conversion, text extraction, image extraction, document signing, and more. It also provides support for various file formats such as XLSX, XLS, CSV, HTML, and more. 

By using Aspose.Total for Java, developers can easily integrate XPS to TXT conversion feature in their Java applications. This suite provides a comprehensive set of components that enable developers to manipulate PDF documents and spreadsheets in various ways. It also provides support for various file formats such as XLSX, XLS, CSV, HTML, and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XPS File to TXT via Java" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XPS to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to TXT format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected XPS to TXT via Java" %}}
If your XPS document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to TXT with Watermark via Java" %}}
While converting XPS file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as TXT with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}