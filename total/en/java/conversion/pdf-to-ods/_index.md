---
title: Java API to Render PDF to ODS
description: Export PDF to ODS via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/pdf-to-ods/
family: total
platformtag: java
feature: conversion
informat: PDF
outformat: ODS
otherformats: SXC TSV DIF EXCEL XLT XLTX XLSM MD FODS XLSB TXT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export PDF to ODS via Java" h2="Convert PDF file to ODS by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for Java is a comprehensive suite of APIs that enables developers to integrate PDF to ODS conversion feature in their Java applications. This two-step process starts with Aspose.PDF for Java, which is a powerful PDF manipulation API that allows you to render PDF to XLSX. Once the PDF is converted to XLSX, the second step involves using Spreadsheet Programming API Aspose.Cells for Java to convert XLSX to ODS. 

Aspose.PDF for Java is a feature-rich API that enables developers to create, read, edit, and convert PDF documents without any external dependencies. It supports a wide range of features such as document manipulation, text extraction, image extraction, annotations, form filling, and more. It also supports a variety of output formats such as XLSX, HTML, and SVG. 

Aspose.Cells for Java is a powerful spreadsheet programming API that enables developers to create, read, edit, and convert spreadsheets without any external dependencies. It supports a wide range of features such as document manipulation, text extraction, image extraction, annotations, form filling, and more. It also supports a variety of output formats such as ODS, XLSX, HTML, and SVG. 

By using Aspose.Total for Java, developers can easily integrate PDF to ODS conversion feature in their Java applications. The two-step process starts with Aspose.PDF for Java to render PDF to XLSX and then Aspose.Cells for Java to convert XLSX to ODS. This comprehensive suite of APIs provides developers with the tools they need to create powerful and efficient applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PDF File to ODS via Java" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to ODS format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to ODS via Java" %}}
If your PDF document is password protected, you cannot convert it to ODS without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to ODS with Watermark via Java" %}}
While converting PDF file to ODS, you can also add watermark to your output ODS file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as ODS with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}